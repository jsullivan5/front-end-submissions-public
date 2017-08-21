# Jet Fuel Submission Form

[Project Spec](http://frontend.turing.io/projects/jet-fuel.html)

# Basics

#### Link to the Github Repository for the Project
[jetfuel](https://github.com/jsullivan5/jet-fuel)

#### Link to the Deployed Application
[heroku](https://jtfule.herokuapp.com/)

#### Link to your annotated server file
[annotated server file](https://gist.github.com/jsullivan5/79cdcb95e6a3095bcc8f8b495b0d4c2a)

## Completion

#### Were you able to complete the base functionality?

No.  I failed to impliment css transitions.  Everything else is done.

#### Which extensions, if any, did you complete?

# Code Quality

#### Link to a specific block of your code on Github that you are proud of
[happy code](https://github.com/jsullivan5/jet-fuel/blob/master/server/controller.js#L74)

*I like this code because I was able to use a URL that resembled bitly's.  The slashes in it were throwing off the endpoints
and it took some figuring out.

#### Link to a specific block of your code on Github that you feel not great about

* There is no line sepcifically but it's the CSS transition.  I tried to fight the default browser behavior to add the transition class with setTimeOut, focusing and placing the line everywhere and just can't seem to get it.  Default browser behavior wins after 3:00 AM... 

#### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
```
> jet-fuel@1.0.0 test /Users/jamessullivan/Turing/projects/mod4/jet-fuel
> NODE_ENV=test ./node_modules/.bin/mocha

Jet Fuel is running on http://localhost:3000.
  Client Routes
    ✓ should return the home page (47ms)
    ✓ should return a 404 if endpoint not found

  API Routes
    GET /api/v1/folders
done seeding
done seeding
      ✓ should get the folders
    POST /api/v1/folders
done seeding
done seeding
[ anonymous { name: 'beers', id: 3 } ]
      ✓ should create a new folder
done seeding
done seeding
[ anonymous { name: 'beers', id: 3 } ]
      ✓ should return an error if user tries to duplicate folder.
done seeding
done seeding
      ✓ should return 422 if insufficient data is provided
    GET api/v1/folders/:id/links
done seeding
done seeding
      ✓ should get links for a folder
    POST /api/v1/links
done seeding
done seeding
{ long_URL: 'http://www.expedia.com',
  short_URL: 'http://jt.fl/ca2ea3b5',
  folder_id: 1,
  description: 'expedia' }
      ✓ should create a link
done seeding
done seeding
{ long_URL: 'http://www.expedia.com',
  short_URL: 'http://jt.fl/ca2ea3b5',
  folder_id: 1 }
      ✓ should return 422 if insufficient data is provided
    GET /api/*/:charHash
done seeding
done seeding
      ✓ should accept GET request to redirect (43ms)


  10 passing (957ms)
  ```

#### Please feel free to ask any other questions or make any other statements below!

Anything else you wanna say!

-----


# Instructor Feedback (Instructor Name)

## Specification Adherence

**x points**: Lorem ipsum dolor set amet

## User Interface

**x points**: Lorem ipsum dolor set amet

## Data Persistence with SQL Database

**x points**: Lorem ipsum dolor set amet

## Testing

**x points**: Lorem ipsum dolor set amet

## JavaScript Style

**x points**: Lorem ipsum dolor set amet

## Workflow

**x points**: Lorem ipsum dolor set amet


### To get a 3 on this project, you need to score 110 points or higher
### To get a 4 on this project, you need to score 135 points or higher

# Final Score: x / 150
