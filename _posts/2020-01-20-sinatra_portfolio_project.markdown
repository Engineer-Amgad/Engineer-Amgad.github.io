---
layout: post
title:      "Sinatra Portfolio Project"
date:       2020-01-20 21:15:26 -0500
permalink:  sinatra_portfolio_project
---

##Craigslist Web app

###I have created a craigslist like web app. this app allows users to post ads cars and other items online. 
##The database:
###There are two database tables. the first table is for users and the second table is for ads. Users have a username and a password. The password is encrypted. The encryption is done through use of the bcrypt gem. 
the ads data table has a title, description, image, price, contact, and user_id. 
##Active Record and Data Associations:
###I have used active record to associated users and ads databases. this done by inheriting ActiveRecod::base for the user and ad classes. To associate the users and ads databases, I have mapped the database structure so the the user has many ads and ads belongs to users. 
This data structure allows the user of the web app to create ads. those ads belongs to that user/creater. Other user will have the ability to view the ads. However, the ad creater is the only user that is allowed to edit or delete those ads. 
##CRUD:
###I have use the CRUD princeple for this project. the user has the ability to create, read, update, and delete ads. Again, I have placed logic in the RESTful routes so that only the creater of an ad has the ability to updated or deleted.
##RESTful Routes:
This web app follows the restful routes for the most part and where it makes sense. The only two places where I have chosen to break the restful routes rules are in the sign-up and log-in routers. This is because it make better user expericance to set routes in a way a user would understand. So instead of '/user/new' the routes show as '/signup' and '/login'. 
##conclusion
###This been a comprehensive project. It required the use of many concepts and programming skills. To list a fiew of those areas I could mention the web app directroy stucture, ruby if statments and loops, data structure and migration, active record and model assoication, Sinatra routes, Restful routes, password encryption, the use of sessions, and user data protection.

