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
* [WebVR](#webvr)
* [Libraries](#libraries)
* [Community](#community)

## WebGL

> All things dealing with WebGL

### WebGL sub-categories
* [Articles](#articles)
* [Blog Series](#blog-series)
* [Books](#books)
* [Bug Reporting](#bug-reporting)
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
* [WebGL Insights](https://github.com/WebGLInsights/WebGLInsights.github.io/releases/download/v1.0/WebGL.Insights.-.Patrick.Cozzi.pdf) by **Patrick Cozzi** - Presents real-world techniques for intermediate and advanced WebGL developers by assembling contributions from experienced WebGL engine and application developers, GPU vendors, browser developers, researchers, and educators.
  * [Book's Personal Site](http://www.webglinsights.com/)
* [WebGL Programming Guide: Interactive 3D Graphics Programming with WebGL](https://www.amazon.com/WebGL-Programming-Guide-Interactive-Graphics/dp/0321902920) by **Kouichi Matsuda** and **Rodger Lea** - WebGL Programming Guide will help you get started quickly with interactive WebGL 3D programming, even if you have no prior knowledge of HTML5, JavaScript, 3D graphics, mathematics, or OpenGL.

### Bug Reporting

> Reporting bugs helps everyone in long run

* [Chrome Bug Report](https://bugs.chromium.org/p/chromium/issues/list) - Chrome related bugs
* [Khronos BugZilla](https://www.khronos.org/bugzilla/buglist.cgi?product=WebGL&query_format=advanced) - Spec or Conformance related bugs
* [Mozilla BugZilla](https://bugzilla.mozilla.org/enter_bug.cgi?alias=&assigned_to=nobody%40mozilla.org&blocked=&bug_file_loc=http%3A%2F%2F&bug_severity=normal&bug_status=NEW&cf_blocking_191=---&cf_blocking_193=---&cf_blocking_fennec=---&cf_status_191=---&cf_status_192=---&comment=&component=Canvas%3A%20WebGL&contenttypeentry=&contenttypemethod=autodetect&contenttypeselection=text%2Fplain&data=&dependson=&description=&flag_type-203=X&flag_type-270=X&flag_type-271=X&flag_type-325=X&flag_type-369=X&flag_type-37=X&flag_type-370=X&flag_type-385=X&flag_type-388=X&flag_type-4=X&flag_type-422=X&flag_type-479=X&flag_type-480=X&flag_type-485=X&flag_type-486=X&flag_type-5=X&flag_type-543=X&flag_type-555=X&flag_type-556=X&flag_type-557=X&flag_type-565=X&flag_type-566=X&flag_type-567=X&form_name=enter_bug&keywords=&maketemplate=Remember%20values%20as%20bookmarkable%20template&op_sys=All&priority=--&product=Core&qa_contact=canvas.webgl%40core.bugs&rep_platform=All&short_desc=&status_whiteboard=&target_milestone=---&version=Trunk) - Firefox related bugs
* [WebKit Bugzilla](https://bugs.webkit.org/enter_bug.cgi?assigned_to=cmarrin%40apple.com&attachurl=&blocked=&bug_file_loc=http%3A%2F%2F&bug_severity=Normal&bug_status=NEW&comment=&component=WebGL&contenttypeentry=&contenttypemethod=autodetect&contenttypeselection=text%2Fplain&data=&dependson=&description=&flag_type-1=X&flag_type-3=X&form_name=enter_bug&keywords=&maketemplate=Remember%20values%20as%20bookmarkable%20template&op_sys=Mac%20OS%20X%2010.5&priority=P2&product=WebKit&rep_platform=PC&short_desc=&version=528%2B%20%28Nightly%20build%29) - Safari related bugs

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
* [GLSLbin](http://glslb.in) - Fragment shader sandbox supporting [glslify](https://github.com/glslify/glslify).
* [Shader Toy](https://www.shadertoy.com) - Most popular live editor for fragment shaders.
* [ShaderFrog](https://shaderfrog.com/) - WebGL Shader Editor and Composer.
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

* [Khronos Dev Tools](https://github.com/KhronosGroup/WebGLDeveloperTools) - Useful WebGL developer tools, intended to be used as an ES6 module.
* [Spector.js](http://spector.babylonjs.com/) - Agnostic JavaScript framework for exploring and troubleshooting your WebGL scenes.
* [WebGL Inspector](http://benvanik.github.io/WebGL-Inspector/) - Tool inspired by gDEBugger and PIX with the goal of making the development of advanced WebGL applications easier.
* [WebGl Playground](http://jessevdk.github.io/webgl-play/) - The editor lets you work on the JavaScript code and the GLSL vertex/fragment shaders (if you have any) at the same time in a convenient way. Everything is organized, formatted and highlighted properly, just as you would like.
* [WebGL Report](http://webglreport.com/?v=1) - Way to view the details of what your browser supports for WebGL.
* [WebGL Support Stats](http://webglstats.com/) - Interactive dashboard showing the support for WebGL features in different browsers and devices.
* [WebGL Texture Tester](http://toji.github.io/texture-tester/) - Attempts to load one of every texture format supported by WebGL, intended to quickly show which formats your browser/device supports.
* [Web Tracing Framework](http://google.github.io/tracing-framework/index.html) - Set of libraries, tools, and visualizers for the tracing and investigation of complex web applications.

#### Chrome Specific Tools/Debugger

* [GLSL Shader Editor Extension](https://github.com/spite/ShaderEditorExtension) - Chrome DevTools extension to help you edit shaders live in the browser.
* [Spector.js Extension](https://chrome.google.com/webstore/detail/spectorjs/denbgaamihkadbghdceggmchnflmhpmk) - Explore and Troubleshoot your WebGL and WebGL2 scenes easily.
* [Webgl Insight](https://github.com/3Dparallax/insight) - Chrome extension WebGL debugging toolkit providing a variety of capabilities.

#### Firefox Specific Tools/Debugger

* [Canvas Debugger](https://hacks.mozilla.org/2014/03/introducing-the-canvas-debugger-in-firefox-developer-tools/) - Quick tutorial how to use Firefox's developer tools to debug WebGL Shaders.
* [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools) - The offical list of all of Firefox's debugger tools.
* [Shader Editor](https://hacks.mozilla.org/2013/11/live-editing-webgl-shaders-with-firefox-developer-tools/) - Quick tutorial how to use Firefox's developer tools to debug WebGL Shaders.

### Tutorials

> Online WebGL Tutorials (non-video)

* [Directional Shadow Mapping](http://chinedufn.com/webgl-shadow-mapping-tutorial/) - Concepts behind real time directional light shadow mapping.
* [Get Started Tutorial](https://www.khronos.org/webgl/wiki/Tutorial) - Khronos' tutorial how to get up and running with WebGL.
* [Getting Started with WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL) - Mozilla Foundation guide to getting started with WebGL.
* [Learn WebGL](https://www.tutorialspoint.com/webgl/index.htm) - Tutorials Point set of article to get you familiar with WebGL terms.
* [Learning WebGL](http://learningwebgl.com/blog/?page_id=1217) - Tutorials from the author of _WebGL Up and Running_.
* [Multitexturing using a Blendmap](http://chinedufn.com/webgl-multitexture-blend-map-tutorial/) - How to use a blendmap to multitexture a terrain.
* [Particle Effects via Billboards](http://chinedufn.com/webgl-particle-effect-billboard-tutorial/) - Create particle effects by applying a technique called billboarding.
* [The Book of Shaders](http://thebookofshaders.com/) - Gentle step-by-step guide through the abstract and complex universe of Fragment Shaders.
* [WebGL Academy](http://www.webglacademy.com/) - Simplified online IDE with automatic indentation, syntax highlighting for HTML, Javascript, GLSL and Python. You can run your code and download your projects.
* [WebGL Fundamentals](https://webglfundamentals.org/) - Series of online tutorials with code samples and live demonstrations.
* [WebGL Workshop](http://webgl-workshop.com/) - Interactive workshop to get you up and running with WebGL.

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
* [What's Coming in WebGL 2.0](https://blog.tojicode.com/2013/09/whats-coming-in-webgl-20.html) - Look into the upcoming features of WebGL 2.
* [WebGL 2 SIGGRAPH Asia 2015](https://docs.google.com/presentation/d/1Orx0GB0cQcYhHkYsaEcoo5js3c5-pv7ahPniIRIzzfg/edit#slide=id.p) - Presentation by Zhenyao Mo, Ken Russell of Google during SIGGRAPH Asia 2015.
* [WebGL 2 Lands in Firefox](https://hacks.mozilla.org/2017/01/webgl-2-lands-in-firefox/) - Information the support for WebGL 2 starting with Firefox 51.
* [WebGL 2 Basics](http://www.realtimerendering.com/blog/webgl-2-basics/) - Blog post about getting started with WebGL 2.
* [WebGL 2 New Features](http://www.realtimerendering.com/blog/webgl-2-new-features/) - Blog post about whats new and cool in WebGl 2.

### References

> WebGL 2 references

* [WebGL 2 Spec Sheet (Editor Draft)](https://www.khronos.org/registry/webgl/specs/latest/2.0/) - All the detailed information about WebGL 2.
* [WebGL 2 Reference Card](https://www.khronos.org/files/webgl20-reference-guide.pdf) - WebGL 2.0 API Quick Reference Card for printing.
* [WebGL 2 Compatible Chart](https://caniuse.com/#feat=webgl2) - Chart to show current browsers supporting WebGL 2

### Tutorials
* [WebGL 2 Fundamentals](https://webgl2fundamentals.org/)- Series of online tutorials with code samples and live demonstrations.
* [WebGL 2 Samples](http://webglsamples.org/WebGL2Samples/) - Great source of many different WebGL 2 work with very good commenting.
* [WebGL 2 Examples](https://github.com/tsherif/webgl2examples) - Rendering algorithms implemented in raw WebGL 2.

### Videos

> WebGL related Videos

* [Fun with WebGL 2.0](https://www.youtube.com/playlist?list=PLMinhigDWz6emRKVkVIEAaePW7vtIkaIF) - Video tutorial series on getting started with WebGL 2, still actively adding videos.
* [WebGL 2.0 is Here: What You Need To Know](https://www.youtube.com/watch?v=Xf65duJ_QFs) - Khronos Webinar April 2017.
    * [Slides](https://www.khronos.org/assets/uploads/developers/library/2017-webgl-webinar/Khronos-Webinar-WebGL-20-is-here_What-you-need-to-know_Apr17.pdf)

## WebVR

> Information about different parts of the new and upcoming WebVR ecosystem
>
> All items related to more developers and less on where to find WebVR content as entertainment

### WebVR sub-categories

* [Articles](#articles-2)
* [Blog Series](#blog-series-1)
* [Platforms](#platforms)
* [References](#references-2)

### Articles

> WebVR articles and/or blog posts (non-tutorials)

### Blog Series

> Maintained blog series of WebVR focused topics

* [Mozilla VR Blog](https://blog.mozvr.com/) - WebVR focused blog from makers of Firefox.

### Platforms

> WebVR designed platforms to experience

* [JanusVR](https://janusvr.com/) - Webpages as collaborative 3D webspaces interconnected by portals.

### References

> WebVR references

* [Browser Support](https://webvr.rocks/) - Shows support by browser, headset, and OS.
* [Mozilla VR](https://mozvr.com/) - Mozilla's offical WebVR page.
* [UX of VR](https://www.uxofvr.com/) - Curated list of resources to help create good UX in WebVR.
* [WebVR Spec](https://w3c.github.io/webvr/) - The offical W3C WebVR specs.
  * [How to read WebVR Specs](https://dassur.ma/things/reading-specs/)

## Libraries

> [More detailed information about the different libraries can be found in the Libraries directory.](https://github.com/sjfricke/awesome-webgl/tree/master/Libraries)

### 2D
* [p2.js](https://github.com/schteppe/p2.js) - 2D rigid body physics engine written in JavaScript.
* [Phaser](https://phaser.io/) - Open source HTML5 2D game framework for Canvas and WebGL, supports mobile web browsers.
* [PixiJS](http://www.pixijs.com/) - powerful 2D Javascript renderer based on WebGL.
* [Planck.js](https://github.com/shakiba/planck.js) - 2D physics engine for cross-platform HTML5 game development.
* [Stage.js](https://github.com/shakiba/stage.js) - 2D Library for cross-platform HTML5 game development.

### Maps and Visualizations
* [Cesium](https://cesiumjs.org/) - Open-source library for world-class 3D globes and maps.
* [Deck.gl](https://uber.github.io/deck.gl/) - WebGL overlay suite for React providing a set of highly performant data visualization overlays.
* [Luma.gl](https://uber.github.io/luma.gl/) - WebGL2 powered framework for GPU-powered data visualization and computation.
* [xeogl](http://xeogl.org/) - Data-driven 3D visualization engine on WebGL.

### Math
* [glMatrix](http://glmatrix.net/) - Javascript matrix and vector library for high performance WebGL apps.
* [Sylvester](http://sylvester.jcoglan.com/) - Sylvester is a vector, matrix and geometry library for JavaScript.
* [TWGL](http://twgljs.org/) - Sole purpose is to make using the WebGL API less verbose.

### Rendering
* [GLBoost](https://github.com/emadurandal/GLBoost) - Rendering library for 3D graphic geeks.
* [GrimoireGL](https://grimoire.gl/) - Bridge between Web engineers and CG engineers.
* [Hilo3d](https://github.com/hiloteam/Hilo3d) - WebGL rendering engine for 3D games.

### Physics
* [Ammo.js](https://github.com/kripken/ammo.js/) - Direct port of the Bullet physics engine to JavaScript using Emscripten.
* [Cannon.js](http://schteppe.github.io/cannon.js/) - Lightweight and simple 3D physics engine for the web.

### WebGL 2
* [PicoGL.js](https://tsherif.github.io/picogl.js/) - Minimal WebGL 2-only rendering library.

### WebVR
* [A-Frame](https://aframe.io/) - Web framework for building virtual reality experiences.
  * [Awesome-AFrame](https://github.com/aframevr/awesome-aframe)
* [Hologram](https://hologram.cool/) - Desktop app that let you create and prototype WebVR in interactive way needing no previous coding knowledge.
* [LÖVR](https://lovr.org/) - Simple framework for creating VR with Lua.
* [ReactVR](https://facebook.github.io/react-vr/) - Build VR websites and interactive 360 experiences with React.
* [Primrose](https://www.primrosevr.com/) - Rapidly prototype VR applications in your browser.

### Others
* [Babylon.js](https://www.babylonjs.com/) - Complete JavaScript framework for building 3D games with HTML5, WebGL and Web Audio.
* [Blend4Web](https://www.blend4web.com/en/) - Tool for interactive 3D visualization on the Internet.
* [ClayGL](http://claygl.xyz/) - WebGL graphic Library for building scalable Web3D applications.
* [CopperLicht](http://www.ambiera.com/copperlicht/index.html) - JavaScript library and WebGL 3D engine for creating games and 3D applications.
* [GLGE](http://www.glge.org/) - Javascript library intended to ease the use of WebGL.
* [Lightgl.js](https://github.com/evanw/lightgl.js) - Lightweight and explict library to help prototype.
* [OSG.js](http://osgjs.org/) - WebGL framework based on OpenSceneGraph concepts to interact with WebGL.
* [Pex-gl](http://vorg.github.io/pex/) - JavaScript libraries for computational thinking in Plask/Node.js and WebGL.
* [PlayCanvas](https://playcanvas.com/) - Game engine platform to build interactive experiences.
* [Pocket.gl](http://pocket.gl/) - Fully customizable webgl shader sandbox to embed in your pages.
* [QTEK](https://github.com/pissang/qtek) - Library with many features.
* [Regl](http://regl.party/) - Light declarative and stateless library, functional abstraction for WebGL.
* [Scene.js](http://scenejs.org/) - Extensible WebGL-based engine for high-detail 3D visualisation.
* [Three.js](https://threejs.org/) - Aimed to create an easy to use, lightweight, 3D library.
* [Turbulenz](https://github.com/turbulenz/turbulenz_engine) - Modular 3D and 2D game framework for making HTML5 powered games for browsers, desktops and mobile devices.
* [Whitestorm.js](https://whs.io/) - Framework for developing 3D web apps with physics.

## Community
* [Stack Overflow](https://stackoverflow.com/questions/tagged/webgl)
* [Reddit](https://www.reddit.com/r/webgl/)
* [Facebook](https://www.facebook.com/groups/webgl/about/)
* [Twitter](https://twitter.com/webgl)
* [Freenode IRC](http://webchat.freenode.net/?channels=webgl)
* [Khronos Forum](https://forums.khronos.org/forumdisplay.php/92-WebGL)
* [Google Group](https://groups.google.com/forum/#!forum/webgl-dev-list)
* [Google Plus](https://plus.google.com/communities/114915309361980512257)
* [Public Mailing List](https://www.khronos.org/webgl/public-mailing-list/)
* [WebVR Slack](http://webvr-slack.herokuapp.com/)
* [WebVR Public Mailing List](https://lists.w3.org/Archives/Public/public-webvr/)

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
