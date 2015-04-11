---
published: true
layout: post
title: Building REST API clients for AngularJS
---

I recently lectured about building REST clients for AngularJS.
At this presentation I made an introduction for REST APIs, and showed the disadvantages of using the traditional
service `$resource`, and offered a better solution for building stable and standalone API service for your AngularJS project.

In my opinion, using [Restangular](https://github.com/mgonto/restangular) is one of the best tools for building a REST
client for an AngularJS project, which is entirely separated from server - `client<>server` approach: hybrid applications,
different servers, ionic projects, etc.

Here are the slides of my lecture:

<iframe src="//www.slideshare.net/slideshow/embed_code/46571972" width="100%" height="550" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen></iframe>