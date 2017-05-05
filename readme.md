# Awesome Gideros [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<h1 align="center">
	<a href="http://giderosmobile.com"><img width="400" src="gideros_logo.png" alt="Awesome Gideros"></a>
	<br>
	<br>
</h1>

> A curated list of awesome resources for the Gideros Game Development Framework that allows you to easily create games and apps for Android, iOS, HTML5, WinRT and Desktop (Windows, OSX). Please feel free to contribute to the list by making a pull request. 

## Contents

- [Download and Getting Started](#starting)
- [Gideros Resources](#resources)
	- [General Tutorials and Tips](#tutorials)
	- [Full game examples](#fullgame)
	- [Publications](#publications)
	- [IDEs and Editors](#ide)
	- [Graphics and Shaders](#gfx)
	- [Scene Managment](#scenes)
	- [Input](#input)
	- [Animation and Tweens](#animation)
	- [Tilemaps](#tilemaps)
	- [Camera](#camera)
	- [Audio](#audio)
	- [Monetization](#monetization)
	- [Saving and Loading](#saveload)
	- [GUI](#gui)
	- [3D](#3d)
	- [Plugins](#plugins)
- [Useful Lua-Libraries](#lua)

## Download and Getting Started

- [Download Gideros](http://giderosmobile.com/download) - get Gideros here (it is free but donations are welcome!)
- [Getting Started Manual](http://docs.giderosmobile.com) - check here first to get an overview of the framework
- [API Reference](http://docs.giderosmobile.com/reference/) - whenever you need to figure out something - this is the first place to go
- [Forum](http://giderosmobile.com/forum/) - join the very friendly and helpful community
- [Online Editor](http://giderosmobile.com/code/) - try Gideros in your browser without installing anything
- [Online Examples](http://giderosmobile.com/examples) - see some of the capabilites of Gideros in your browser
- [Developer Guide](http://giderosmobile.com/guide) - official list of guides and tutorials

## Gideros Resources

*A collection of resources (blog and forum entries, websites, packages etc) for Gideros*

### General Tutorials and Tips
- [Introductory Video Tutorial](https://www.youtube.com/watch?v=IRLxBijIX50) - by one of the maintainers of Gideros
- [Publishing to Android](http://giderosmobile.com/forum/discussion/6894/publishing-tutorial#Item_7) - getting started with publishing to Android
- [Improving performance](http://giderosmobile.com/forum/discussion/4892/software-improve-what-kind-of-skills-do-you-need) - forum thread with hints about improving the performance of Gideros apps
- [Desktop API](http://giderosmobile.com/forum/discussion/5870/new-desktop-api-test/p1) - overview of the Desktop API to manipulate mouse cursor and window decorations

### Full game examples
- [Simple square-dodge game](http://bluebilby.com/2013/05/08/gideros-mobile-tutorial-creating-your-first-game/) - introductory tutorial about creating a simple square-dodge game
- [Top-down roguelike Tutorial](https://programmingbymoonlight.com/roguelike-intro/) - extensive tutorial series about making a turn-based roguelike in Gideros
- [Breakout Clone](http://blog.hotbutteredgames.com/post/143878823915/gideros-tutorial-a-simple-box2d-game-gideros-is-a) - tutorial about creating a Breakout-like game using Gideros and Box2D
- ["Grab the treasure" course](http://www.moosader.com/learn/introduction-to-mobile-game-development/) - a comprehensive getting-started guide to Gideros by developing a small game


### Publications
*Books about Gideros*
- [Gideros Mobile Game Development](https://www.packtpub.com/game-development/gideros-mobile-game-development) - comprehensive book about developing a game for mobile with Gideros
- [Learn Lua for iOS Game Development](http://www.apress.com/us/book/9781430246626) - introducing a variety of Lua-based game development frameworks including Gideros

### IDEs and Editors
*Code editors and plugins that work with Gideros*
- [Using ZeroBrane Studio with Gideros](http://www.indiedb.com/tutorials/gideros-with-zerobrane) - introductory tutorial for using ZBS with Gideros Remote Preview 
- [Live Coding with Gideros and ZeroBrane Studio](https://www.youtube.com/watch?v=wPYvJxFxMkM) - video showing the live coding capabilities of ZBS and Gideros
- [ZeroBrane Studio integration and debugging](https://www.youtube.com/watch?v=GIipyzSpSr0) - video tutorial by the creator of ZBS
- [Visual Studio Code plugin](https://marketplace.visualstudio.com/items?itemName=devCAT.lua-debug ) - with Gideros support (Windows only)
- [Sublime Text 3 plugin](http://giderosmobile.com/forum/discussion/5218/gideros-sublime-text-3-package-for-osx-windows-version-0-10/p1) - adding Gideros support to ST3

### Graphics and Shaders
- [Shaders in Gideros](http://bit.ly/2pkF09m) - an introductory text about shaders in Gideros
- [Shadertoy viewer](http://giderosmobile.com/forum/discussion/6667/shadertoy-viewer-beta-shaders-from-www-shadertoy-com-in-gideros/p1) - check out shaders from Shadertoy using Gideros
- [Intro to clipping and the RenderTarget](http://www.indiedb.com/engines/gideros/tutorials/clipping-in-gideros-with-rendertarget) - text-based tutorial on how to use the RenderTarget class to create a clipping effect

### Scene Management
- [SceneManager](http://appcodingeasy.com/Gideros-Mobile/Manage-Scenes-in-Gideros-Mobile) - easily switch between scenes with or without transitions
- [Passing variables using the SceneManager](http://giderosmobile.com/forum/discussion/1474/passing-variables-with-scene-manager/p1) - passing variables to the next scene when using the scene manager

### Input
- [GidSwipe](https://github.com/stetso/GidSwipe) - easy to use tap and swipe manager for mobile 
- [Gestures](http://appcodingeasy.com/Gideros-Mobile/Detecting-Gestures-in-Gideros) - define and detect complex gestures from points a list of points
- [Accelerometer](http://appcodingeasy.com/Gideros-Mobile/Using-Accelerometer-with-Box2d-in-Gideros) - quick example of how to use the device accelerometer as input
- [Shake detection](http://appcodingeasy.com/Gideros-Mobile/Gideros-Shake-detection) - small snippet to detect device shake

### Animation and Tweens
- [GTween](http://appcodingeasy.com/Gideros-Mobile/Gideros-GTween-with-easing) - tween sprite variables with this library (comes with all the easing functions you need)
- [Animation using MovieClip](http://bluebilby.com/2013/05/12/gideros-mobile-tutorial-animated-movieclips/) - tutorial on how to animate sprites using the MovieClip class
- [Spriteheet animation class](https://github.com/nascode/gideros_animsheet) - class that helps with creating and playing animations from spritesheets


### Tilemaps
 - [Collision with Tilemaps](http://giderosmobile.com/forum/discussion/6353/collision-with-any-object/p1) - examples and suggestions on how to make stuff collide with the tiles in your tilemap

 ### Camera
 - [Smooth camera with Drag and Pinch-to-Zoom](http://giderosmobile.com/forum/discussion/2715/camera-class-with-kinetics-and-pinch-to-zoom/p1) - useful class implementation for a camera in a mobile game

### Audio
- [Intro to using audio with Gideros](http://bluebilby.com/2013/04/18/gideros-mobile-tutorial-playing-music-and-sound-effects/) - tutorial about generating and using sounds with Gideros

### Saving and Loading
- [Using JSON](http://giderosmobile.com/forum/discussion/6918/saving-and-loading-data-files#Item_1) - Loading and saving manually via JSON
- [DataSaver module](http://appcodingeasy.com/Gideros-Mobile/Save-and-load-data-module-for-Gideros-Mobile) - a very user-friendly wrapper to make saving and loading data as easy as possible

### Monetization
- [Admob integration](http://giderosmobile.com/forum/discussion/5801/tuto-video-tutorial-how-to-add-admob-plugin-to-your-app) - video tutorial about integrating Admob into your game
- [Google Service integration](http://giderosmobile.com/forum/discussion/5806/tuto-video-tutorial-how-to-add-google-services-to-your-app) - second part of the Admob tutorial showing Google Play Service integration

### GUI
- [Layout](https://github.com/Nlcke/layout) - the "official" Gideors GUI framework ([forum entry](http://giderosmobile.com/forum/discussion/6651/layout-gideros-gui-framework#Item_23))
- [Button class](http://appcodingeasy.com/Gideros-Mobile/Gideros-mobile-button-class) - a simple class for creating clickable buttons
- [AceSlide class](http://appcodingeasy.com/Gideros-Mobile/Easy-input-for-choosing-packages-or-levels-in-Gideros-Mobile) - a sliding UI-Element that can be used for example for level selection

### 3d
*Note: 3D support is still in development but if you like to play around with it already, here are some starting points*
- [Tutorial using 3D in Gideros](https://www.youtube.com/watch?v=IfHwdJD6ad8) - introduction by one of the maintainers of Gideros

### Plugins
- [SKStoreReview](https://github.com/mertkurum/GiderosStoreReview) - Gideros Plugin for SKStoreReviewController iOS 10.3+
- [C++-plugin development](http://giderosmobile.com/forum/discussion/1025/step-by-step-how-to-write-a-c-plugin-and-deploy-it-to-the-desktop-windows-player) - getting started with Gideros plugin development in C++

## Useful Lua-Libraries
*general Lua libraries that are useful in gamedev but are not Gideros specific*

- [lume](https://github.com/rxi/lume) - great collection of functions that are useful for game development
- [inspect](https://github.com/kikito/inspect.lua) - easily pretty-print your tables to the console in a readable way
- [jumper](http://yonaba.github.io/Jumper/) - super-fast grid-based pathfinding for Lua
- [bump](https://github.com/kikito/bump.lua) - simple, flexible and fast library for collision detection using axis-aligned bounding boxes
- [Bresenham](https://github.com/rm-code/Bresenham) - Bresenham's line algorithm, implemented in Lua

## Related Awesome-Lists
- [awesome-lua](https://github.com/LewisJEllis/awesome-lua)
- [awesome-love2d](https://github.com/love2d-community/awesome-love2d)
- [awesome-gamedev](https://github.com/mbrukman/awesome-gamedev)


## License and contributing
 
Please contribute to the list. Simply read the [contribution guidelines](contributing.md) to get started.

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
