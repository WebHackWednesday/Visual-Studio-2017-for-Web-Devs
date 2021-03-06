# Visual Studio 2017 for Web Developers
Visual Studio 2017 update 3 was released on 14th August 2017. It has many general improvements but we're going to focus on the key updates for web developers. 

You read more about update 3 here: https://blogs.msdn.microsoft.com/visualstudio/2017/08/14/visual-studio-2017-version-15-3-released/

Much of the content for this episode has been taken from a talk that [Mads Kristensen](https://madskristensen.net/) did at Build 2017 called [Modern front-end web development in Visual Studio 2017](https://channel9.msdn.com/events/Build/2017/B8073?term=Modern%20front-end%20web%20development%20in%20Visual%20Studio%202017).

## Web Essentials
Web Essentials has traditionally been an extension that adds a bunch of functionality for web developer. It has often been the 'proving ground' for feature that eventually find their way into the main product. feature link browser Link started in Web Essentials. At one point it was [announced as being deprecated](https://madskristensen.net/post/long-live-web-essentials) but that decision was reversed and it lives on in Visual Studio 2017

The problem with Web Essentials has always been stability. It is one big extension so it one area had a problem it would crash Visual Studio.

In 2017, Web Essentials has been changed to be an extension that installs all the other extensions and lets you pick and choose which ones you want.

This episode shows some of the Web Essentials 2017 extensions and if you are doing web development in Visual Studio, it is really a 'must have' feature.

Get it from the Visual Studio marketplace here: https://marketplace.visualstudio.com/items?itemName=MadsKristensen.WebExtensionPack2017 

There is also a Google Chrome extension that works with browser link from Chrome: https://chrome.google.com/webstore/detail/web-essentials/mghdcdlpcdiodelbplncnodiiadljhhk

## New Templates
With update 3, we have introduced a new set of templates for ASP.net core with most of the popular front end frameworks such as Angular and React. These SPA templates use the JavaScript Services functionality to embed NodeJS within ASP.NET Core on the server, and compile the JavaScript applications server-side as part of the .NET build process.

The templates are accessible via the [Microsoft.aspnetcore.spatemplates Nuget package](https://www.nuget.org/packages/Microsoft.AspNetCore.SpaTemplates/1.0.0) and add a load of neat features including:
* ClientApp folder inside VS solution
* Server-side pre-rendering which renders view of the server before sending to the client (great for SEO and performance)
* Webpack middleware for bundling and packaging
* Live server reload

![New SPA templates](https://msdnshared.blob.core.windows.net/media/2017/08/2-NewTemplates.png)

We also looked at the [ASP.NET Core Template Pack 2017.3 extension](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.ASPNETCoreTemplatePack20173) which adds some interesting new ASP.net configurations based around the [AspNetCore.StaticSiteHelper Nuget package](https://www.nuget.org/packages/AspNetCore.StaticSiteHelper). 
* Static Web: A completely empty static web page
* MVC Basic: very simple MVC application with no bootstrap, jquery etc
* MVC High performance: Like MVC Basic but tuned for performance using gulp

You can see projects created from most of the new templates under the 'Templates' folder in this repository.

## Editor Improvements
In this episode we looked at just a few of the editor improvements for JavaScript and CSS, including:
* Accessibility and W3C validation checking via Browser Link and the [Web Accessibility Checker](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.WebAccessibilityChecker) extension
* Improved JavaScript Intellisense
* Live JavaScript editing and browser refresh on save
* Surface dial debugging
* Chrome JavaScript debugging via Visual Studio

## Resources
[Visual Studio 2017 Update 3 blog](https://blogs.msdn.microsoft.com/visualstudio/2017/08/14/visual-studio-2017-version-15-3-released/)
[A list of extensions for Visual Studio web developers maintained by Mads Kristensen](http://tinyurl.com/extensionlist)
[Video: Modern front-end web development in Visual Studio 2017](https://channel9.msdn.com/events/Build/2017/B8073?term=Modern%20front-end%20web%20development%20in%20Visual%20Studio%202017)
[Web Essentials 2017](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.WebExtensionPack2017)
[.net Core 2.0 SDK](https://www.microsoft.com/net/core#windowscmd)