---
published: true
title: How to do sessions
layout: post
---
The development of the Reddit app goes slowly. I'm very new to this TDD and I;m spending way too much time trying to make tests. As we speak, I'm still looking for a way to simulate authorised requests in Mocha.

I had an internal debate on cookie-sessions vs JWTs a little while back. Should I use cookie-sessions to save session variables and other data or should I be using JWTs to store keys and user data for further requests? I've held off on implementing JWTs as it's going to be a chore to have to store the JWTs in the client side so I'm currently using a Mongo strategy session storage. Now how to test the goddamn things...