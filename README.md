# Gaming Community CMS (Content Management System)

Gaming Community CMS is a whole website system that people can use to easily make their own gaming community website with a ban management system and donation system built in. It allows a gaming community owner to choose what all they want to install (Just the website, donation system, and ban system or any combination of these), and it all works together with one theme, one login, and users and admins can link their Steam account and Discord account, so they can do everything all in one place. All of the systems are setup using one database with tables so that everything functions together. All database tables and values are cached on the gameserver, in case of an API failure.

The website is made up of three sections, and a Discord bot that is made to work with it. The gameserver portion of Gaming Community CMS works using the application programming interface (API) to communicate with the webserver to manage Create, Read, Update, Delete (CRUD) functions to the database.

## Part 1: Content Management System
The Content Management System (CMS) portion of the website is a sleek and stylish website builder and blog system where users that are given permission to make webpages, edit articles, and manage the CMS settings. The starter pages includes a basic website (Toggleable Landing page, a main webpage, an about us page, a contact us page, a cookie policy page, and a Terms of Service/Terms of Use page, a fully featured forum, a page to register for an account, and a login page). Other pages can be created from a template, or built using Bootstrap assets from a blank canvas.

## Part 2
The Ban Management portion automatically houses a public-hidden forum section for appeals. Each game server added to the Bans Management system will have a section on the forum; each time a user is banned, a thread will be created with a unique case number. The thread can only be seen by the banned user and admins. Each server added or deleted from the Ban Management portion is automatically added or removed from the Donation Management system.

The admins will have two types of posts that they can make in each thread: 
  1. Can be seen by both the offending party and admins. 
  2. Can only be seen by admins associated with the case of the banned user. 

All functions of the ban system and donation system use expose access to an API (Application Programming Interface) to manage CRUD (Create, Read, Update, Delete) functions from in game, or wherever you decide to implement them.

## Part 3: Donation Managment
The Ultimate Donation Manager portion will allow admins to create packages, set up events, set coupons, and change the currency accepted by the community. Each server added or deleted from the Donation Management portion is automatically added or removed from the Ban Management system.

All functions of the ban system and donation system use expose access to an API (Application Programming Interface) to manage Create, Read, Update, Delete (CRUD) functions from in game, or wherever you decide to implement them.

## Part 4: Discord Bot
The Discord Bot will allow community owners and admins with permissions to warn, mute, ban, kick, and timeout users, which will be stored in the Ultimate Ban Manager. It also allows for calls to the API that sends a message in a specified channel whenever someone is banned, donates, and more!

# Installation

Read INSTALL.md for instructions on how to install.

# License

Please see LICENSE.md for more information on the license of Ultimate Gaming Server Manager.

# Security Policy

## Supported Versions

Please make sure you have the latest version of Ultimate Gaming Community Manager. If your version is outdated, please update using the instructions in the Wiki.

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |

## Reporting a Vulnerability

All security vulnerabilities should be sent to security@giygas.site
