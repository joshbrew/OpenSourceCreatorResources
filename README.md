# Open Source Creator Resources
A smattering of mostly free and open source software, or at least software with sufficient free versions that I use on the regular. Good starting place for anyone's computer career or if you never want to pay a dime and still be all-powerful. The communities around this software are awesome, too.  Made this mostly just so I don't forget.

## Digital Art

#### Blender 3
3D Art, Rendering, 2D/3D Animation, 2D/3D CAD mods, video editing, sequence scripting, and lots more.

https://blender.org 

Alternatively use bforartists for better UX

https://bforartists.de

#### Krita
Drawing and Image Editing. Great for printmaking or drawing icons.

https://krita.org 

#### GIMP
Drawing and Image Editing, I use it for basic post-processing or turning images into icons after scanning.

https://gimp.org

#### InkScape
Vector graphics editor.

https://inkscape.org

#### Materialize
Material/texture editor. Visual node-based workflow. Super robust

http://boundingboxsoftware.com/materialize/

#### Meshroom
Free and open source photogrammetry software. It's pretty much the coolest.

https://alicevision.github.io/#meshroom

#### Canva (web based, mostly free tools)
Great print editor for posters, pamphlets, infographics, etc. 

https://canva.com

Need to mention Autodesk's 3DsMax and Maya, which have free licenses for educational purposes, but require a subscription for commercial use.

## Video
Blender has some great features for this.

#### OpenShot
Open source video editing, lots of free effects libraries and stuff.

https://openshot.org

#### Da Vinci Resolve
Professional software with a really great free version

https://resolve.org

## Audio

#### Audacity
Ye olde audacity

https://audacityteam.org

#### LMMS
Really smooth software

https://lmms.io/

#### Ardour
Free source, pay-what-you-want build

https://github.com/Ardour/ardour

# Coding

## Code Editors
Sure you could do everything through command line and notepad, but that kind of sucks and precludes a lot of potential for better, more creative work. Github and sourceforge are loaded with examples in any coding language. https://stackoverflow.com is an oracle for coding problems.

## VSCodium
Tracker-free VSCode. You really don't need anything else now, I do all my microcontroller and app programing in VSCode with some simple environment configuraiton. https://vscodium.com/

#### Visual Studio
Omni editor, great package manager, I use this mainly for C++

https://visualstudio.microsoft.com

#### Visual Studio Code
Lite editor, can add pretty much any library known to man to it and edit and debug anything.

https://code.visualstudio.com

#### Anaconda
Python launcher, provides a great user-friendly UI layer to make life easier. Great for RPi programming.

https://www.anaconda.com/distribution/

#### Eclipse
Omni editor, I use it mainly for Java or C

https://eclipse.org

#### Arduino
Arduino microcontrolller libraries. Tons of free templates and examples. Open hardware (tons of cheap competitors, 5 dollar BT/WiFI ESP32 for example, or a 1 dollar Arduino Nano)

https://arduino.cc

#### nRF Connect via VSCode (plus Zephyr)
State of the art microcontroller coding and RTOS support. It's production quality stuff.

Extension Info: https://www.nordicsemi.com/Products/Development-tools/nRF-Connect-for-VS-Code
With Zephyr: https://zephyrproject.org/getting-started-with-nrf-connect-for-visual-studio-code/

#### Android Studio
The main industry mobile app editor for Android. It's not the easiest to learn but lets you do anything with an Android phone.

https://developer.android.com/studio

#### Nativescript Sidekick
Mobile app creator, 100 free cloud builds per month (meaning you don't have to download 30+ GB of packages). Not the biggest community but it's improving every year. Has templates and a library browser.

https://www.nativescript.org/nativescript-sidekick

## Webapp Editing/Debugging

#### Chrome
Chrome's built-in debugging and editing interface is my favorite for web debugging, including live editing and detailed performance monitoring. Just open your html files with chrome and hit ctrl+shift+J to start editing. Works on any web page, too.

https://google.com/chrome

#### Chromium
FOSS base of Chrome, Brave, Edge, etc. It's a lot of stuff but it has the latest chrome engine features.

https://www.chromium.org/

## Game Design
Game design is one of the best ways to internalize coding logic and hierarchical programming. It's also a straightforward way to learn about performance and low level programming as the results are immediately obvious by what happens your screen.

#### Godot Engine
Great starting place, the most recent updates make it a very viable way to make performant 2D or 3D games rapidly with a growing community. You can alternate between 3 programming languages at will including a custom scripting engine. It's fun to use and has tons of tutorials plus a browser of free projects you can use to remix mechanics.

https://godotengine.org

#### Unreal Engine
Pretty much the ultimate game/simulation engine. They have major investors on top of a decade of development made free and open source, with small royalties if a certain profit margin is made. Use it for games, simulations, CGI, putting the final touches on CAD projects, 2D and 3D animation, etc. Owned by Epic Games, subsidized by Tencent in China, but still the most powerful digital art software out there. Sign up for Nvidia's developer community, too, regardless of your hardware.

https://unrealengine.com

#### Unity Engine
Bigger community than UE (for now), some things are easier, but it's also less intuitive with less free tools available.

https://unity.com

## PCB Design
It's cheaper than ever to prototype manufacture circuit boards and even flexible circuits. I have to recommend https://pcbway.com for their services and the vast open source design libraries people are sharing.

#### KiCAD
Nasa-published full free and open source PCB editor.

https://kicad.org

#### Autodesk EAGLE
The free version is great, much more user friendly than KiCAD but limited for non-education purposes without paying.

https://www.autodesk.com/products/eagle/overview

#### CircuitMaker (Altium)
Free version of Altium, which is a very expensive software otherwise.

https://www.altium.com/circuitmaker

## Coding API Highlights
Here's APIs that are very current in their philosophy and optimization. I'm still learning how to use most of these but they're freakin sweet. There are obviously dozens of popular free distibuted APIS (database APIs, visual APIs, etc) but these are a few I enjoy in particular.

#### Shameles plug

#### Tinybuild
Do you want to program in the most convenient language and be able to scale in the most convenient possible way to create web, desktop, and mobile applications with a single build setup? Well that's not as easy as it should be, but we put together a bundler system that gets you as close as possible and using the easiest most scalable dependencies with ESBuild and options for Tauri or Electron for Desktop and Capacitor for Android and IOS.

https://github.com/joshbrew/tinybuild

We are going on 100 repositories now, check it out to find more web and microcontroller resources. 


#### ThreeJS or BabylonJS
We are web devs so we like having a primitive 3D rendering system. ThreeJS gives you good control over simple 3D scenes and about a decade of free support, BabylonJS gives you a more professional suite suitable for game development and a similarly long legacy of community engagement. WebGPU with WebGL2 fallbacks to ensure decent performance, we are confident in the future of graphics on the web.

https://threejs.org/

https://www.babylonjs.com/



#### Tensorflow
Google's machine learning and data analytics libraries. Super optimized, based on Nvidia hardware. Unreal Engine compatible via a plugin (omg). This covers the other really useful python libraries like pandas or numpy, and also Nvidia's dev tools.

https://tensorflow.org

UE4 Plugin

https://github.com/getnamo/tensorflow-ue4

#### OpenCV
Open Computer Vision library. O.G. C++ and C libraries for all things machine learning or image and video editing/filtering. Huge community, tons of resources.

https://opencv.org

#### NodeJS
Package and library manager for Javascript projects. Pretty essential for any applications and lets you access tens of thousands of packaged libraries and share work.

https://nodejs.org

#### Quart
Flask is a python server library, Quart is the asyncio and multithreading-based upgrade to it, which enables 4X or more server performance. Reddit used to be based on Flask, for an example of how just how much traffic you can already handle with simple libraries. It also enables seamless data streaming between coding languages, like to HTML applications via websockets, opening up many possibilities.

https://gitlab.com/pgjones/quart

etc...



