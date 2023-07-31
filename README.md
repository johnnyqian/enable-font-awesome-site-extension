[![MyGet Build Status](https://www.myget.org/BuildSource/Badge/enable-font-awesome-site-extension?identifier=0aeb3391-cee8-4132-926c-9419d0b31d91)](https://www.myget.org/feed/Packages/enable-font-awesome-site-extension)

# Enable web fonts for Azure App Service

By default files with .woff2, .woff and .ttf extensions are not served by IIS in Azure App Service. This extension simply add MIME types for these font files.

This will work with:

* Font Awesome
* Simple Line Icons
* IconMoon
* And any more static .woff2, .woff and .ttf files in your project

# How to add this extension

Locate your **App Service** in Azure portal, in the blade, you'll find the "Extensions" tab, in the right pane, click "Add", find "Enable Static Web Fonts", click OK. Then **restart App Service**, that's it.

![Enable Static Web Fonts](https://raw.githubusercontent.com/johnnyqian/enable-font-awesome-site-extension/master/enable-static-web-fonts.png)
