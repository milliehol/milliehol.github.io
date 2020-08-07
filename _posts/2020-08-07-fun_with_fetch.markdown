---
layout: post
title:      "Fun with Fetch"
date:       2020-08-07 16:39:09 +0000
permalink:  fun_with_fetch
---


     In order to communicate with a backend API, a frontend Javascript application can use Fetch.  Fetch allows the front end part of the application 
   to receive data from a backend.  It works by making an http request, then receiving the data as a promise.

     The structure of the request allows the then() method usage since it receives the response as a promise.  The promise is a reponse from a fetch 
   request.  The promise is resolved into a JSON object if the JSON() method is used.  Other methods available are the text() and formData() method.  
   The Fetch request is performed in an Asynchronous manner so that the web site is not slowed down by the request.  
     
       The asynchronous process allows each portion of the web site to load when it is able instead of loading in the order that the code is presented.  
   The faster portions such as the HTML and CSS elements are loaded before the slower portions such as the fetch request.  After the fetch request is 
   complete, the data is displayed.  
     
     Here is an example of how to use a fetch request within a javascript page:
		 
		post(url, body) {
	return fetch(url, {
		method: 'POST',
		headers: this.headers,
		body: JSON.stringify(body)
	}).then(res => res.json());   }
     
     The last line of the code receives the promise, then converts the response to JSON for usage by the frontend API. 
