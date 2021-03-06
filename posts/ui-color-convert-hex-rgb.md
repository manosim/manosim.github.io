---
title: UIColor.xyz - Converting HEX & RGB colours to UIColor
slug: ui-color-convert-hex-rgb
keywords: uicolor,programming,ios,objective-c,swift,convert,hex,rgb,xcode
cover: ui-color.png
date: 2015-02-15
---

Have you ever developed an iOS mobile application in Objective C or in Swift? Then I guess at some point you have "googled" convert HEX or RGB colors to UIColor or UIColor picker. Same happened with me. So while I was developing "Go Back" - an application written in Swift where you can store your location and find your way back there at any time - I had to use a color converter or a color picker for UI Color.

<!--more-->

UIcolor.xyz is a tiny Angular app, where you can either convert HEX & RGB(A) colors or you can use the color picker and it will generate the code you need to copy & paste to your iOS application.

    # It's obvious that it's not that easy to convert colors without a converter
    HEX: #bd3e3e
    RGB: R-189 G-62 B-62

    Objective C: [UIColor colorWithRed:0.74 green:0.24 blue:0.24 alpha:1.0];
    Swift: UIColor(red:0.74, green:0.24, blue:0.24, alpha:1.0)

I guess after the example above it will all make sense right? The application is hosted on **GitHub Pages** and it is of course open-sourced so feel free to get involved! It's free and easy to use. You can now head to [http://www.uicolor.xyz/](http://www.uicolor.xyz/) and give it a try.
