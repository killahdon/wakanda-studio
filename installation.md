---
---

# Hello World: your first Mobile Web App

## Table of contents

- [Install Wakanda](#install-wakanda)
- [Choose : mobile or web app ?](#choose-mobile-or-web-app)
- [Check for dependencies](#check-for-dependencies)
- [Create your data](#data)
- [Code and preview](#code-preview)
- [Run on emulator](#run-on-emulator)
- [Run on device](#run-on-device)
- [Deploy](#deploy)

## Install Wakanda

First, download and install **Wakanda Community Edition**

- On Windows, [x86](https://github.com/Wakanda/wakanda-digital-app-factory/releases/download/v1.1.3/wakanda-community-all_1.1.3_x86.msi "download") or [x64](https://github.com/Wakanda/wakanda-digital-app-factory/releases/download/v1.1.3/wakanda-community-all_1.1.3_x64.msi "download")
- On Mac OS X, [x64](https://github.com/Wakanda/wakanda-digital-app-factory/releases/download/v1.1.3/wakanda-community-all_1.1.3_x64.dmg "download")


Now we can start our **HelloWorld** project.  

## Choose : mobile or web app ?
We can choose the kind of app we want to create : mobile, web or both.

Let’s say we want to create an Android app with Ionic2.

To do that, we're going to use the studio, and click on "Create a new solution":

<img src="img/hp-initial.png"/>

Which opens the template selection page:  

<img src="img/hw-template-selection.png"/>


There, you can name your app (without spaces) and select the ionic2 blank template.

Now, in your **HelloWorld** project, you can find the basic ionic2 file structure :

<img src="img/hw-file-structure.png"/>  

You have 3 folders at the root of your project:

- Database , in which you’ll find your data model(s) and data  
- Mobile, where you’ll find all your front end files  
- Backend, where you’ll find the settings and permissions on your app and your business logic  

For our “Hello world” we’re only going to work in the mobile folder.


## Check for dependencies

For mobile apps, you need to check for any missing dependencies.
Go in the main menu  (_Help_ > _Wakanda Troubleshooting_) and choose Android.

<img src="img/hw-troubleshooting.png"/>

Here you can see I miss Homebrew, Apache And and Android SDK. All is explained there: why I need them, and how to install them.

<<<<<<< HEAD
## Preview   
Once all your dependencies are checked you can preview your app.
=======

## Code and preview  

Once all your dependencies are checked you can preview your app.
>>>>>>> origin/gh-pages
Just click on your project, and then on "Preview".

<img src="img/hw-first-preview.png"/>


Let's have a look to our project structure : the src folder is the classical [ionic2 project structure](http://ionicframework.com/docs/v2/setup/tutorial/project-structure/ "ionic tutorial").

A simple change in `pages/hello-ionic.html` and I have my **HelloWorld** done.   
The preview is automatically reloaded after each saving.

<img src="img/hw-second-preview.png"/>

You can select "Preview in web browser" if you prefer to see the result in your default browser.  

<img src="img/hw-final-preview.png"/>


## Run on emulator  

Now you can run your app on the Android emulator.

<img src="img/hw-run-emulator.png"/>

<img src="img/hw-emulator-view.png"/>

## Run on device  

[Getting Started »](index.html){:class="btn"}
