# Balloonist
Share your belongings with others. Visit the [project site](https://balloonist.slack.com)
or go directly to the [balloonist](https://balloonist.herokuapp.com/) app.

## Project management
* Join [Slack](https://balloonist.slack.com) for communication

## Development for project site
Run `middleman build` inside the docs_generator folder and push.

## Development for balloonist

    gem install geordi
    geordi setup
    rails server
    
There are rspec and cucumber tests. Be sure to have the current 
[Chromedriver](https://sites.google.com/a/chromium.org/chromedriver/) installed.

    geordi test