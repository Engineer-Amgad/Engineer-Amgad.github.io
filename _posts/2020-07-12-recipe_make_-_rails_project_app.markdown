---
layout: post
title:      "Recipe Make - Rails Project App"
date:       2020-07-12 18:57:52 +0000
permalink:  recipe_make_-_rails_project_app
---


This project has two main feathures Authincation and has many through assoication.

Authintication: The app allows the users to sign up directrly to the app using a user name and passward. the user information is stored in the database with a secure passwared using "bcrybt". the app also allows the users to log in via thier google account. once the user is signs up or signs in, the user can create view recipes by other user as well as create his or her own recipe. 

Assoication: To make this app works a has many through assoication was created. this is due to the many to many reraltionship between recpes and their ingredients. A recipe may have many ingredients and an ingredient may have many recipes assoicated with it. To make this assoication works, I have used a third database table called recipe_ingredients. this table has a recipe_id, an ingredient_id as well as the amount of the ingredient.

This app has been a great learning experiance. those main features in the app are found in many web apps today. I'm sure the leason leaned here will be very useful in my future projects. 

#### GitHub link to the app: https://github.com/Engineer-Amgad/recipe-maker
