# Awesome WebGL [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="webgl_logo.png" align="right" width="175">](https://www.khronos.org/webgl/)

This is a curated list of awesome WebGL libraries, resources and much more.

## What is WebGL

WebGL (Web Graphics Library) is a JavaScript API for rendering interactive 3D computer graphics and 2D graphics within
any compatible web browser without the use of plug-ins. WebGL is integrated completely into all the web standards
of the browser allowing GPU accelerated usage of physics and image processing and effects as part of the web page canvas.

WebGL elements can be mixed with other HTML elements and composited with other parts of the page or page background.
WebGL programs consist of control code written in JavaScript and shader code that is executed on a computer's Graphics
Processing Unit (GPU).

## Contents
* [WebGL](#webgl)
* [WebGL 2](#webgl-2)
* [Libraries](#libraries)
* [Community](#community)

## WebGL

> All things dealing with WebGL

### WebGL sub-categories
* [Articles](#articles)
* [Blog Series](#blog-series)
* [Books](#books)
* [GLSL Editors](#glsl-editors)
* [References](#references)
* [Talks](#talks)
* [Tools/Debugging](#toolsdebugging)
  * [Chrome Specific Tools/Debugger](#chrome-specific-toolsdebugger)
  * [Firefox Specific Tools/Debugger](#firefox-specific-toolsdebugger)
* [Tutorials](#tutorials)
* [Videos](#videos)

### Articles

> WebGL articles and/or blog posts (non-tutorials)

* [Context Loss & Preloading](https://medium.com/@mattdesl/non-intrusive-webgl-cebd176c281d#.gyc6h9mr5) - How to manage WebGL when you run into the dreaded context lost.
* [WebGL Off the Main Thread](https://hacks.mozilla.org/2016/01/webgl-off-the-main-thread/) - How to use Web Workers in WebGL.

### Blog Series

> Blog series of WebGL topics

* [Codeflow](http://codeflow.org/tags/webgl.html) - Many blogs on different tricks and techniques.
* [Real-Time Rendering](http://www.realtimerendering.com/blog/tag/webgl/) - This is the blog for the book _Real-Time Rendering_.
* [WebGL Insights](http://webglinsights.blogspot.com/) - This is the blog for the book _WebGL Insights_.

### Books

> Popular books about WebGL

* [Interactive Computer Graphics: A Top-Down Approach with WebGL](https://www.amazon.com/Interactive-Computer-Graphics-Top-Down-Approach/dp/0133574849) by **Edward Angel** and **Dave Shreiner** - Suitable for undergraduate students in computer science and engineering, for students in other disciplines who have good programming skills, and for professionals interested in computer animation and graphics using the latest version of WebGL.
* [Professional WebGL Programming](https://www.amazon.com/Professional-WebGL-Programming-Developing-Graphics/dp/1119968860) by **Andreas Anyuru** - Everything you need to know about developing hardware-accelerated 3D graphics with WebGL.
* [Programming 3D Applications with HTML5 and WebGL](https://www.amazon.com/Programming-Applications-HTML5-WebGL-Visualization/dp/1449362966) by **Tony Parisi** - Create high-performance, visually stunning 3D applications for the Web, using HTML5 and related technologies such as CSS3 and WebGL—the emerging web graphics standard.
  * [First two chapters online](http://chimera.labs.oreilly.com/books/1234000000802/ch01.html)
* [WebGL Beginner's guide](https://www.amazon.com/WebGL-Beginners-Guide-Diego-Cantor/dp/184969172X) by **Diego Cantor** and **Brandon Jones** - For JavaScript developer who wants to take the plunge into 3D web development via WebGL.
* [WebGL Hotshot](https://www.amazon.com/WebGL-Hotshot-Mitch-Williams-ebook/dp/B00KLAJ65Y) by **Mitch Williams** - For web designer looking to expand your knowledge of 3D graphics concepts and broaden your existing skill set.
* [WebGL Insights](https://www.amazon.com/WebGL-Insights-Patrick-Cozzi/dp/1498716075) by **Patrick Cozzi** - Presents real-world techniques for intermediate and advanced WebGL developers by assembling contributions from experienced WebGL engine and application developers, GPU vendors, browser developers, researchers, and educators.
  * [Book's Personal Site](http://www.webglinsights.com/)
* [WebGL Programming Guide: Interactive 3D Graphics Programming with WebGL](https://www.amazon.com/WebGL-Programming-Guide-Interactive-Graphics/dp/0321902920) by **Kouichi Matsuda** and **Rodger Lea** - WebGL Programming Guide will help you get started quickly with interactive WebGL 3D programming, even if you have no prior knowledge of HTML5, JavaScript, 3D graphics, mathematics, or OpenGL.


### GLSL Editors

> Online GLSL Editors
>
> NOTE: [WebGL must conform to The OpenGL ES Shading Language, Version 1.00](https://www.khronos.org/registry/webgl/specs/1.0.3/#4.3)
> 
> [Offical Specs for GLSL Version 1.00](https://www.khronos.org/registry/OpenGL/specs/es/2.0/GLSL_ES_Specification_1.00.pdf)
>
> [Offical Specs for Open ES Version 2.0.25](https://www.khronos.org/registry/OpenGL/specs/es/2.0/es_full_spec_2.0.pdf)

* [Fractal Lab](http://hirnsohle.de/test/fractalLab/) - Online fractal explorer allowing you to explore 2D and 2D fractal.
* [GLSL Sandbox](http://glslsandbox.com) - Online live editor for fragment shaders.
* [GLSLbin](http://glslb.in) - Fragment shader sandbox supporting [glslify](https://github.com/stackgl/glslify).
* [Shader Toy](https://www.shadertoy.com) - Most popular live editor for fragment shaders.
* [ShaderFrog](http://shaderfrog.com/) - WebGL Shader Editor and Composer.
* [SHDR Editor](http://shdr.bkcore.com) - Live GLSL shader editor, viewer and validator.

### References

> WebGL references

* [Google Project ANGLE](https://github.com/google/angle) - Default WebGL backend for both Google Chrome and Mozilla Firefox on Windows platforms.
* [Khronos Offical Wiki](https://www.khronos.org/webgl/wiki/) - The official wiki for WebGL.
* [WebVR Community Group](https://www.w3.org/community/webvr/) - Group who's goal is to help bring high-performance Virtual Reality to the open Web.
* [WebGL Reference Card](https://www.khronos.org/files/webgl/webgl-reference-card-1_0.pdf) - WebGL 1.0 API Quick Reference Card for printing.
* [WebGL Source Code](https://github.com/KhronosGroup/WebGL) - Source code to both view and contribute.
* [WebGL Spec Sheet](https://www.khronos.org/registry/webgl/specs/1.0/) - All the detailed information about WebGL.


### Talks

> WebGL related talks

* [List of Presentations](https://www.khronos.org/webgl/wiki/Presentations) - List presented by Khronos of various WebGL related presentations.

### Tools/Debugging

> Tools for development and debugging WebGL

* [WebGL Inspector](http://benvanik.github.io/WebGL-Inspector/) - Tool inspired by gDEBugger and PIX with the goal of making the development of advanced WebGL applications easier.
* [WebGl Playground](http://webglplayground.net/) - The editor lets you work on the JavaScript code and the GLSL vertex/fragment shaders (if you have any) at the same time in a convenient way. Everything is organized, formatted and highlighted properly, just as you would like.
* [WebGL Report](http://webglreport.com/?v=1) - Way to view the details of what your browser supports for WebGL.
* [WebGL Support Stats](http://webglstats.com/) - Interactive dashboard showing the support for WebGL features in different browsers and devices.
* [WebGL Texture Tester](http://toji.github.io/texture-tester/) - Attempts to load one of every texture format supported by WebGL, intended to quickly show which formats your browser/device supports.
* [Web Tracing Framework](http://google.github.io/tracing-framework/index.html) - Set of libraries, tools, and visualizers for the tracing and investigation of complex web applications.

#### Chrome Specific Tools/Debugger

* [GLSL Shader Editor Extension](https://github.com/spite/ShaderEditorExtension) - Chrome DevTools extension to help you edit shaders live in the browser.
* [Webgl Insight](https://github.com/3Dparallax/insight) - Chrome extension WebGL debugging toolkit providing a variety of capabilities.

#### Firefox Specific Tools/Debugger

* [Canvas Debugger](https://hacks.mozilla.org/2014/03/introducing-the-canvas-debugger-in-firefox-developer-tools/) - Quick tutorial how to use Firefox's developer tools to debug WebGL Shaders.
* [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools) - The offical list of all of Firefox's debugger tools.
* [Shader Editor](https://hacks.mozilla.org/2013/11/live-editing-webgl-shaders-with-firefox-developer-tools/) - Quick tutorial how to use Firefox's developer tools to debug WebGL Shaders.

### Tutorials

> Online WebGL Tutorials (non-video)

* [Get Started Tutorial](https://www.khronos.org/webgl/wiki/Tutorial) - Khronos' tutorial how to get up and running with WebGL.
* [Getting Started with WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL) - Mozilla Foundation guide to getting started with WebGL.
* [Learn WebGL](https://www.tutorialspoint.com/webgl/index.htm) - Tutorials Point set of article to get you familiar with WebGL terms.
* [Learning WebGL](http://learningwebgl.com/blog/?page_id=1217) - Tutorials from the author of _WebGL Up and Running_.
* [The Book of Shaders](http://thebookofshaders.com/) - Gentle step-by-step guide through the abstract and complex universe of Fragment Shaders.
* [WebGL Academy](http://www.webglacademy.com/) - Simplified online IDE with automatic indentation, syntax highlighting for HTML, Javascript, GLSL and Python. You can run your code and download your projects.
* [WebGL Fundamentals](https://webglfundamentals.org/) - Series of online tutorials with code samples and live demonstrations.

### Videos

> WebGL Related Videos

* [An Introduction to WebGL Programming](https://www.youtube.com/watch?v=tgVLb6fOVVc&feature=youtu.be) - 3 hour overview of WebGL by SIGGRAPH University.
* [WebGL Tutorials - YouTube](https://www.youtube.com/playlist?list=PLjcVFFANLS5zH_PeKC6I8p0Pt1hzph_rt) - Series of lecture style video tutorials from Indigo Code on YouTube.

## WebGL 2

> Information about the upcoming WebGL 2 specs
>
> Anything pertaining to WebGL in general is found in the [WebGL](#WebGL) section

### WebGL 2 sub-categories
* [Articles](#articles-1)
* [References](#references-1)
* [Tutorials](#tutorials-1)
* [Videos](#videos-1)

### Articles

> WebGL 2 articles and/or blog posts (non-tutorials)

* [WebGL 2 What's New](https://webgl2fundamentals.org/webgl/lessons/webgl2-whats-new.html) - Look into the new features added in WebGL 2.
* [What's Coming in WebGL 2.0](http://blog.tojicode.com/2013/09/whats-coming-in-webgl-20.html) - Look into the upcoming features of WebGL 2.
* [WebGL 2 SIGGRAPH Asia 2015](https://docs.google.com/presentation/d/1Orx0GB0cQcYhHkYsaEcoo5js3c5-pv7ahPniIRIzzfg/edit#slide=id.p) - Presentation by Zhenyao Mo, Ken Russell of Google during SIGGRAPH Asia 2015.
* [WebGL 2 Lands in Firefox](https://hacks.mozilla.org/2017/01/webgl-2-lands-in-firefox/) - Information the support for WebGL 2 starting with Firefox 51.
* [WebGL 2 Basics](http://www.realtimerendering.com/blog/webgl-2-basics/) - Blog post about getting started with WebGL 2.
* [WebGL 2 New Features](http://www.realtimerendering.com/blog/webgl-2-new-features/) - Blog post about whats new and cool in WebGl 2.

### References

> WebGL 2 references

* [WebGL 2 Spec Sheet (Editor Draft)](https://www.khronos.org/registry/webgl/specs/latest/2.0/) - All the detailed information about WebGL 2.
* [WebGL 2 Reference Card](https://www.khronos.org/files/webgl20-reference-guide.pdf) - WebGL 2.0 API Quick Reference Card for printing.
* [WebGL 2 Compatible Chart](http://caniuse.com/#feat=webgl2) - Chart to show current browsers supporting WebGL 2

### Tutorials
* [WebGL 2 Fundamentals](https://webgl2fundamentals.org/)- Series of online tutorials with code samples and live demonstrations.
* [WebGL 2 Samples](http://webglsamples.org/WebGL2Samples/) - Great source of many different WebGL 2 work with very good commenting.

### Videos

> WebGL related Videos

* [Fun with WebGL 2.0](https://www.youtube.com/playlist?list=PLMinhigDWz6emRKVkVIEAaePW7vtIkaIF) - Video tutorial series on getting started with WebGL 2, still actively adding videos.

## Libraries

> [More detailed information about the different libraries can be found in the Libraries directory.](https://github.com/sjfricke/awesome-webgl/tree/master/Libraries)

### Math
* [glMatrix](http://glmatrix.net/) - Javascript matrix and vector library for high performance WebGL apps.
* [Sylvester](http://sylvester.jcoglan.com/) - Sylvester is a vector, matrix and geometry library for JavaScript.
* [TWGL](http://twgljs.org/) - Sole purpose is to make using the WebGL API less verbose.

### WebGL 2
* [PicoGL.js](https://tsherif.github.io/picogl.js/) - Minimal WebGL 2-only rendering library.

### Others
* [A-Frame](https://aframe.io/) - Web framework for building virtual reality experiences.
* [Ammo.js](https://github.com/kripken/ammo.js/) - Direct port of the Bullet physics engine to JavaScript using Emscripten.
* [Babylon.js](https://www.babylonjs.com/) - Complete JavaScript framework for building 3D games with HTML5, WebGL and Web Audio.
* [CopperLicht](http://www.ambiera.com/copperlicht/index.html) - JavaScript library and WebGL 3D engine for creating games and 3D applications.
* [Cesium](http://cesiumjs.org/) - Open-source library for world-class 3D globes and maps.
* [Deck.gl](https://uber.github.io/deck.gl/) - WebGL overlay suite for React providing a set of highly performant data visualization overlays.
* [GLGE](http://www.glge.org/) - Javascript library intended to ease the use of WebGL.
* [LumaGL](https://uber.github.io/luma.gl/) - WebGL building blocks enabling high-performance browser-based data visualizations.
* [OSG.js](http://osgjs.org/) - WebGL framework based on OpenSceneGraph concepts to interact with WebGL.
* [Phaser](https://phaser.io/) - Open source HTML5 2D game framework for Canvas and WebGL, supports mobile web browsers.
* [PixiJS](http://www.pixijs.com/) - powerful 2D Javascript renderer based on WebGL.
* [Regl](http://regl.party/) - Light declarative and stateless library, functional abstraction for WebGL.
* [Scene.js](http://scenejs.org/) - Extensible WebGL-based engine for high-detail 3D visualisation.
* [Three.js](https://threejs.org/) - Aimed to create an easy to use, lightweight, 3D library.
* [Whitestorm.js](https://whsjs.io/) - Framework for developing 3D web apps with physics.

## Community
* [Stack Overflow](http://stackoverflow.com/questions/tagged/webgl)
* [Reddit](https://www.reddit.com/r/webgl/)
* [Facebook](https://www.facebook.com/groups/webgl/)
* [Twitter](https://twitter.com/webgl)
* [Freenode IRC](http://webchat.freenode.net/?channels=webgl)
* [Khronos Forum](https://forums.khronos.org/forumdisplay.php/92-WebGL)
* [Google Group](https://groups.google.com/forum/#!forum/webgl-dev-list)
* [Google Plus](https://plus.google.com/communities/114915309361980512257)
* [Public Mailing List](https://www.khronos.org/webgl/public-mailing-list/)

## Related lists

> Similar awesome lists

* [awesome](https://github.com/sindresorhus/awesome) - Curated list of awesome lists.
* [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) - Curated list of awesome computer vision resources.
* [awesome-opengl](https://github.com/eug/awesome-opengl) - Curated list of awesome OpenGL libraries, debuggers and resources. Inspired by awesome-... stuff.
* [awesome-vulkan](https://github.com/vinjn/awesome-vulkan) - Curated list of awesome Vulkan projects and ecosystem.
* [gamedev](https://github.com/ellisonleao/magictools) - Awesome list about game development.
* [graphics-resources](https://github.com/mattdesl/graphics-resources) - List of graphic programming resources.

## Contributing
Please see [CONTRIBUTING](https://github.com/sjfricke/awesome-webgl/blob/master/CONTRIBUTING.md) for details.

## Testing
Travis CI testing automation thanks to [awesome_bot](https://github.com/dkhamsing/awesome_bot)!

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Spencer Fricke](https://github.com/sjfricke) has waived all copyright and related or neighboring rights to this work.
