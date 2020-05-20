---
layout: post
title:      "Using BCrypt"
date:       2020-05-20 15:51:55 +0000
permalink:  using_bcrypt
---


     In order to ensure that we can store passwords securely within a database, the authenticate method using Bcrypt is a necessary addition to an application.  It allows us to store encrypted passwords within the database.  Specifically, Bcrypt is a secure hash that stores a cryptographic form of the password in the database.  It attaches strings to varying values when storing the secure information.  

     You can use it by adding the Bcrypt gem to your Ruby gem file.  You will need to re-install all of your gems to ensure that it works.  You will also need to add “password_digest” to your migration file and run rake db:migrate.  Within the User model, you need to add “has_secure_password.”  Then, you need to use the Ruby authenticate code when retrieving the password from the User within the User controller.  

