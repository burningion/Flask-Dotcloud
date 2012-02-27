# Flask-DotCloud

Minimum project example to get you up and running with Flask and dotCloud.

## Installation

Checkout the code, change to the project directory, and then run the following to get started:
     
     $ dotcloud create projectname
     $ dotcloud push projectname

And you'll see a bunch of text, and at the very end will be your custom url.


## Killing Running Server

When you're done running your server:
     
     $ dotcloud destroy projectname

## Gotchas

Don't ever have a git repo in the root directory of your project. DotCloud freaks out silently.

Wrap everything in a directory instead, like this project.

Oh, and have fun!