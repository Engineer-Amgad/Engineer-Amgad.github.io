---
layout: post
title:      "Greenville Schools CLI App"
date:       2019-11-03 14:39:07 +0000
permalink:  greenville_schools_cli_app
---


This is my first ruby project. in this project I am creating an app that scrape the web and give the user a list of all public schools in Greenville, NC area. All the labs I have done so far were made so that all I have to do is write code. This is the first time where I had to build an app from scratch. to accomplish this monumental task I have broken the project in 5 steps to make more manageable. 
#### Setting up the project and repo
In this step I worked on setting up the project. there are a few steps to be followed careful to set up the project files and repo currently. I had to perform this task several time to make it do what I needed to do. the most important lesson here is to name the project currently. the first time I have named may cli "Greenville-Schools-Cli". this created a problem because the gem install created a file named "Greenville" in the lib folder. Then it created a folder "schools" inside of the Greenville folder and then a "Cli" file inside of that. on top of this, all the other supporting file were named or refer to these file in a way I did not intend. I have learn from this experience that naming the project is critical as all you dependencies will use this name to refer to the project folders and files. 
#### The scrapper
I have focused on getting the scraper to work. I have created an array of hashes to collect the data needed. this step was necessary to make sure I have collect the information I needed before moving forward with the rest of the project.
#### The School class
once I have collect the schools in the area from the web, I went to turning the schools into objects. this accomplished through the use of the School class. Then I went back and modified the scraper method to create School objects and assign all the schools information to those objects. At this point I remove all the code I used earlier to create the array of hashes as that was just used to test the scraper method.
#### The CLI
The cli class is what helps the user interact with the rest of the app and navigate the schools objects. this part was not difficult. all it has to do is collect input from the user and display information accordingly. however I found my code was getting ugly and disorganized, and because of that I was getting unexplained error. this issue lead me to the next step in the project.
#### Refactoring
In this step I went back and broken most of the method into smaller methods that are called upon when needed. this made the code much cleaner and easier to read and understand. I have realized that writing short methods make easy to spot error.
#### Adding color
As I was testing my cli I have noticed I was not easy to distinguish between the options the cli is displaying to the user and the information given afterward. for this reason I have added color to the cli. I have colored the cli options green and the schools info blue. this made a create visual impact and clarity 

This project as been a great experience in many ways. I have learned about creating gems from scratch, setting up a repo on github, learning git commands, scraping the web, creating objects, and creating clis. 
