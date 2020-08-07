---
layout: post
title:      "Fun with Fetch"
date:       2020-08-07 15:32:50 +0000
permalink:  fun_with_fetch
---


In order to communicate with a backend API, a frontend Javascript application can use Fetch.  Fetch allows the front end part of the application to receive data from a backend.  It works by making an http request, then receiving the data as a promise.
The structure of the request allows the then() method usage since it receives the response as a promise.  The promise is resolved into a JSON object if this method is used.  Other methods available are the text() and formData() method.  The Fetch request is performed in an Asynchronous manner so that the web site is not slowed down by the request.  After it is complete, the data is displayed.

