# Progressive Web Application

This text editor application features a number of methods that are useful for storing and retrieving data. Users are able to create nodes or code snippets with or without internet connection. 

## Table of Contents:

- [Overview](#Overview)
- [The Challenge](#The-Challenge)
- [What is a PWA?](#what-is-a-PWA?)
- [What I Learned](#What-I-Learned)
- [Credits and Achknowledgements](#Credits-and-Acknowledgements)


# Overview

## The Challenge:

The goal of this project was to develop an application UI style clean, intuitive and easy to navigate. Understanding how to add logic to a method and build a database to create functionality was challenging because the structure of `content` meant an `id` of 1 to render back in the text editor, and I didn't learn that until I kept testing it. This is an assingment we had walked through in class together, I looked back into the mini project with similar functionality and code that was useful in creating this text editor application.

## What is PWA?

A Progressive Web App (PWA) is a type of web application that is designed to work offline and to provide a user experience that is similar to native mobile apps. PWAs are built using web technologies such as HTML, CSS, and JavaScript, and they can be installed on a user's device using a browser.

PWAs are becoming increasingly popular because they offer a number of advantages over traditional web applications. For example, PWAs are:

* Fast and reliable: PWAs are cached on the user's device, which means that they can load quickly and can be used even when there is no internet connection.
* Accessible: PWAs can be accessed from any device with a web browser, including mobile phones, tablets, and computers.
* Engaging: PWAs can provide a rich user experience, with features such as push notifications, offline access, and native app-like features.

## What I learned

What I learned in building this application is using a WebpackPwaManifest plug-in, using the developer tool to create service worker with workbox that Caches statis assets, using IndexedDB to create an object store that includes both GET and PUT methods. 

## Credits and Acknowledgements

This was an assignment we walked-through together in class. I used the knowledge I learned outside of class to impliment code in the database.js file, and deploy to heroku. I also looked into week 19 mini-project that was useful in completing this application.

Heroku deployed: https://heather-pwa-app-bcb16d20426d.herokuapp.com/

GitHub Repository: https://github.com/codingprincess111/progressive-web-application