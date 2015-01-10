---
layout: post
title:  "Create your own static blog with Jekyll"
date:   2015-01-10
categories: jekyll
excerpt: Hi everyone, today I decided to start my own blog to share about technology. For this first post I decided to talk about how I created this blog.
---

Hi everyone, today I decided to start my own blog to share about technology.

For this first post I decided to talk about how I created this blog. I wanted it to be fast, stable and easy to maintain. After some research I finally chose to use Jekyll, an open source software to generate static websites. But what is a static website and why is it so great to build little blogs like this one?

A static website is a website without any dynamic content, it means that the content served for one url is always the same (unlike on a forum for instance).

There is some advantages to that:

- It's super fast because the pages are always ready to be served without any additional server side computation.
- It's very stable and it avoids you the headaches of a server side to debug and maintain.
- It's easy to find free hosting and you can host your website on [Github Pages](https://pages.github.com/) along your source repository.


Jekyll also supports [Markdown](http://en.wikipedia.org/wiki/Markdown) and [Liquid](https://github.com/Shopify/liquid) two markup languages that allow you to easily write new articles.


Sounds awesome, let's do this!
------------------------------

To kickstart my new blog with a set of best practices (contatenation, minification, files revving, etc.) I decided to use [yeoman](http://yeoman.io/) with the [jekyllrb generator](https://github.com/robwierzbowski/generator-jekyllrb) but you can choose to skip this step and follow the regular installation process on [this page](http://jekyllrb.com/docs/installation/).

To install yeoman, just install [Node.js](http://nodejs.org/) and run the following command with [npm](https://www.npmjs.com/): `npm install -g yo`.
Then install our jekyllrb generator with `npm install -g generator-jekyllrb`.

Ok we now have everything we need to create our blog. Just go into your website root directory and run `yo jekyllrb
` and let the yeoman assistant guide you through this process (if you don't know what to answer, just leave the default value).

Now run `grunt serve` and your blog should appear in your browser, otherwise go to `localhost:9000`.

Great, you now have a brand new shiny static website!

See you soon ;)
