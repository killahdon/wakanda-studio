---
---

# Installation

## Table of contents

- [Install Wakanda](#install-wakanda)
- [Setup the mobile stack](#setup-the-mobile-stack)
- [Increase your productivity](#increase-your-productivity)
- [Add extensions](#add-extensions)

## Install Wakanda

First, download and install **Wakanda Community Edition**

- On Windows, [x86](https://github.com/Wakanda/wakanda-digital-app-factory/releases/download/v1.1.3/wakanda-community-all_1.1.3_x86.msi "download") or [x64](https://github.com/Wakanda/wakanda-digital-app-factory/releases/download/v1.1.3/wakanda-community-all_1.1.3_x64.msi "download") click on the `wakanda-digital-app-factory-xxx.msi` file to launch the installation wizard.
- On Mac OS X, [x64](https://github.com/Wakanda/wakanda-digital-app-factory/releases/download/v1.1.3/wakanda-community-all_1.1.3_x64.dmg "download") open `wakanda-digital-app-factory-xxx.dmg` file and copy `Wakanda Studio` and `Wakanda Server` in your `Applications` folder:

<img src="img/install-wakanda.png" />

Now we can start our **HelloWorld** project.  

## Choose your app type
We can choose the kind of app we want to create : mobile, web or both.

Let’s say a mobile app in Angular2 for Android. 

To do that, we're going to use the studio (add logo here), and click on "Create a new solution", to open the template selection page.

## Setup the mobile stack

When you create or open a project, your can check in the console for any missing prerequisites: 

<img src="img/install-console-overview.png"/>

For example, you'll need _Xcode_ to create iOS apps or _Android SDK_ for Android apps.

### Troubleshooting

Do you need help? Open the _Mobile Troubleshooting App_ from the console or the main menu (_Help_ > _Wakanda Mobile Troubleshooting_). Then, detect and fix common issues:

<img class="gif" src="img/install-requirements.png">

## Increase your productivity

### Live reload

The following message in the console warns you when live reload is deactivated:

<img src="img/console-livereload-info.png" />
    
If you want the page to reload automatically after any file changes occur, please install [node](https://nodejs.org/){:target="blank_"} and gulp:

    npm install -g gulp
    
Close the web preview panel and click again on [Run Page](create-web-app.html). The Studio will install automatically the live-reload requierements:

<img src="img/console-livereload-requirements.png" />

## Add extensions

Improve your development workflow adding and updating Studio extensions.
To do so, open the _Add-ons_ app from the toolbar. The _Add-ons_ badge notifies you when extension updates are available:

<img src="img/install-extensions.png" />

---

Now, you are ready to build your app!

[Getting Started »](index.html){:class="btn"}
