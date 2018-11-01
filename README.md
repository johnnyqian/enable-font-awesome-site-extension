[![enable-font-awesome-site-extension MyGet Build Status](https://www.myget.org/BuildSource/Badge/enable-font-awesome-site-extension?identifier=82f9d693-12d1-45d8-9416-fceeef38b3af)](https://www.myget.org/)

# Enable web fonts for Azure App Service

By default files with .woff2, .woff and .ttf extensions are not served by IIS in Azure App Service. This extension simply add MIME types for these font files.

This will work with:

* Font Awesome
* Simple Line Icons
* IconMoon 
* And any more static .woff2, .woff and .ttf files in your project

# How to add this extension

Locate your **App Service** in Azure portal, in the blade, you'll find the "Extensions" tab, in the right pane, click "Add", find "Enable Static Web Fonts", click OK. That's it.

![Enable Static Web Fonts](https://raw.githubusercontent.com/johnnyqian/enable-font-awesome-site-extension/master/enable-static-web-fonts.png)
