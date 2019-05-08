# Blogger
![alt text](https://github.com/dartmouth-cs52-19S/lab4-ziruihao/blob/master/img/full.png)

I built a blog platform with material-ui.

https://blogger-cs52.surge.sh/

https://blogger-error-cs52.surge.sh/ (showcasing error-handling)

## Tech Stack
React, Express, and MongoDB.

## Features
### Client

#### Filter Posts by Tags
You can filter posts by tags either by clicking the tag nodes:

![alt text](https://github.com/dartmouth-cs52-19S/lab4-ziruihao/blob/master/img/tags.png)

Or you can use the search bar up top (make sure to type tags in the format of '#tag').

![alt text](https://github.com/dartmouth-cs52-19S/lab4-ziruihao/blob/master/img/searchbar.png)

#### Redux Error-handling
I handled all errors coming from the connection to the Heroku server by making an `error-reducer.js` and creating error states. To try error handling, go to this link:

![alt text](https://github.com/dartmouth-cs52-19S/lab4-ziruihao/blob/master/img/error.png)

#### Input Validation
If you try to make a blank post, my app will automatically fill 'Untitled post' as its default title, so that we can query them.

![alt text](https://github.com/dartmouth-cs52-19S/lab4-ziruihao/blob/master/img/untitled.png)

#### Markdown
Support for markdown in post-writing.

![alt text](https://github.com/dartmouth-cs52-19S/lab4-ziruihao/blob/master/img/markdown.png)

### Server
#### C-R-U-D MVC Structure
Complete with controllers to create, read, update, and delete database documents.

#### MongoDB and Heroku
Deployed database via mLab dyno in Heroku.
