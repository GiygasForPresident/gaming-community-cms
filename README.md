**Ultimate Game Community Manager**

Ultimate Game Community Manager is a whole website system that people can use to easily make their own gaming community website with a ban management system and donation system built in. It allows a gaming community owner to choose what all they want to install (Just the website, donation system, and ban system or any combination of these), and it all worka together with one theme, one login, and users and admins can link their steam account so they can do everything all in one place. All of the systems are setup using one database with tables so that everything functions together. All database tables and values are cached in a Redis server (if you decide to use one), in case of an API failure.

The main website will have a Content Management System (CMS) where gaming community owners and admins can add pages, elements, and create a whole blog and everything using beautiful Bootstrap elements.

**The Ultimate Ban Manager**

The Ultimate Ban Manager portion automatically houses a forum built in for appeals. Each game server added will have a section on the forum, each time a user is banned, a thread will be created with a case number. The thread can only be seen by the banned user and admins. The admins will have two types of posts that they can make in each thread. The first type of post will be one that can be seen by both the offending party and admins, and the second can only be seen by admins associated with the case of the banned user. Otherwise the thread would be completely private to the public. All functions of the ban system and donation system use expose access to an API (Application Programming Interface) to manage CRUD (Create, Read, Update, Delete) functions from in game, or whereever you decide to implement them.

**The Ultimate Donation Manager**
The donation system will allow admins to make packages, set up events, set coupons, change the currency accepted, and provide the terms of service of donations applicable to a community. All functions of the ban system and donation system use expose access to an API (Application Programming Interface) to manage CRUD (Create, Read, Update, Delete) functions from in game, or whereever you decide to implement them.

**Discord Bot**
The Discord Bot will allow community owners and admins with permissions to warn, mute, ban, kick, and timeout users, which will be stored in the Ultimate Ban Manager. It also allows for calls to the API that sends a message in a specified channel whenever someone is banned, donates, and more!

Read INSTALL.md for instructions on how to install.
