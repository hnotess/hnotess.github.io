---
layout: post
title: "Making a Twitter Bot"
description: "Here's how I made a Twitter bot"
category: project
tags: [Git, Python, Heroku, API]
---
{% include JB/setup %}

Although I haven't been writing much about coding lately, I have been doing a variety of different projects and working on a few different skills. I love reading hilarious tweets from bots like [Pentametron](https://twitter.com/pentametron) and [Thinkpiecebot](https://twitter.com/thinkpiecebot) and came across a simple tutorial to create a [https://en.wikipedia.org/wiki/Horse_ebooks](Horse ebooks)-style account that generates random text based on an existing Twitter account or accounts. 

I chose to make a bot commemorating [The Toast](http://the-toast.net), one of my favorite websites, in honor of its shutting down. 

I cloned a [repo](https://github.com/tommeagher/heroku_ebooks) on Github and then deployed it to Heroku, following the instructions in the tutorial. I used the Heroku scheduler to get it to run pseudo-randomly. Now it's tweeting stuff like this:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Owl Faces In Order Of How Bummed Out She Looks |.</p>&mdash; Toastie Bot (@toastiebot) <a href="https://twitter.com/toastiebot/status/765488215256162304">August 16, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

This project was a great opportunity for me to further practice the Git workflow as well as play around with Heroku and Python some more. It might not seem like much, but getting used to typing ```git push origin master``` feels pretty good.