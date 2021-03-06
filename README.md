This is a customized [dashing](http://shopify.github.com/dashing) dashboard for [foobugs](http://www.foobugs.com) containing a set of new widget jobs that also can be used in a fresh dashing setup.

## Widgets & Jobs

All of the widgets use public APIs or regexps on scraped website content. So no need fo complicated OAuth Authentification.

* Facebook (Page) Metrics like Likes, Checkins or Talking About Numbers
* Foursquare Venue Metrics Checkins
* GitHub Repository Stats (Forks and Watchers)
* GitHub UserInfo Metrics like followers, following, repos and gists
* Klout Score
* Twitter User Info like Followers, Following and Tweet Count
* Yahoo Stock Quote Value
* Youtube Video Metrics (rating, views, likes, comments, favorites)

## Using Widgets

All widgets can be displayed with the `Number` widget that is part of the dashing setup. Please check the `sample.erb` in this repository to see how to use them.

You also can copy single job files over to your own dashboard and use them there. Just place the according `.rb` file in your `jobs` directory.

## Demo & Screen

There are two demo dashboards installed on heroku right now:

### Default Dashboard

[Standard Dashboard](http://foobugs-dashboard.herokuapp.com)

<img src="https://raw.github.com/foobugs/foobugs-dashboard/master/dashing_foobugs_screenshot.jpg" /></img>

### Stock Market Dashboard

[Stock Market Example](http://foobugs-dashboard.herokuapp.com/stocks)

<img src="https://raw.github.com/foobugs/foobugs-dashboard/master/dashing_foobugs_stocks_screenshot.jpg"></img>