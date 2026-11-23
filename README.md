# Awesome WebGL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

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
* [WebXR / WebVR](#webxr--webvr)
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
* [Optimizing Scenes for Better WebGL Performance](https://www.soft8soft.com/docs/manual/en/introduction/Optimizing-WebGL-performance.html) - optimization techniques that proved to work well for creating WebGL-based interactives.
* [First steps in WebGL](https://dev.to/aralroca/first-steps-in-webgl-385c) - Learn what WebGL is and how it works by drawing a triangle.

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
* [WebGL Beginner's guide](https://www.amazon.com/WebGL-Beginners-Guide-Diego-Cantor/dp/184969172X) by **Diego Cantor** and **Brandon Jones** - For JavaScript developer who wants to take the plunge into 3D web development via WebGL.
* [WebGL Hotshot](https://www.amazon.com/WebGL-Hotshot-Mitch-Williams-ebook/dp/B00KLAJ65Y) by **Mitch Williams** - For web designer looking to expand your knowledge of 3D graphics concepts and broaden your existing skill set.
* [WebGL Insights](https://github.com/WebGLInsights/WebGLInsights.github.io/releases/download/v1.0/WebGL.Insights.-.Patrick.Cozzi.pdf) by **Patrick Cozzi** - Presents real-world techniques for intermediate and advanced WebGL developers by assembling contributions from experienced WebGL engine and application developers, GPU vendors, browser developers, researchers, and educators.
  * [Book's Personal Site](http://www.webglinsights.com/)
* [WebGL Programming Guide: Interactive 3D Graphics Programming with WebGL](https://www.amazon.com/WebGL-Programming-Guide-Interactive-Graphics/dp/0321902920) by **Kouichi Matsuda** and **Rodger Lea** - WebGL Programming Guide will help you get started quickly with interactive WebGL 3D programming, even if you have no prior knowledge of HTML5, JavaScript, 3D graphics, mathematics, or OpenGL.

### Bug Reporting

> Reporting bugs helps everyone in long run

* [Chrome Bug Report](https://issues.chromium.org/issues) - Chrome related bugs
* [Khronos Github Issue Page](https://github.com/KhronosGroup/WebGL/issues) - Spec or Conformance related bugs
* [Mozilla BugZilla](https://bugzilla.mozilla.org) - Firefox related bugs
* [WebKit Bugzilla](https://bugs.webkit.org/enter_bug.cgi?product=WebKit&component=WebGL) - Safari related bugs

### GLSL Editors

> Online GLSL Editors
>
> NOTE: [WebGL must conform to The OpenGL ES Shading Language, Version 1.00](https://registry.khronos.org/webgl/specs/1.0.3/)
>
> [Official Specs for GLSL Version 1.00](https://registry.khronos.org/OpenGL/specs/es/2.0/GLSL_ES_Specification_1.00.pdf)
>
> [Official Specs for OpenGL ES Version 2.0.25](https://registry.khronos.org/OpenGL/specs/es/2.0/es_full_spec_2.0.pdf)

* [Fractal Lab](http://hirnsohle.de/test/fractalLab/) - Online fractal explorer allowing you to explore 2D and 3D fractals.
* [GLSL Sandbox](https://glslsandbox.com) - Online live editor for fragment shaders.
* [Shader Toy](https://www.shadertoy.com) - Most popular live editor for fragment shaders.
* [ShaderFrog](https://shaderfrog.com/) - WebGL Shader Editor and Composer.
* [SHDR Editor](http://shdr.bkcore.com) - Live GLSL shader editor, viewer and validator.
* [ShaderExpo](https://anuraghazra.dev/ShaderExpo/) - Dependency free shader editor featuring inline error logs, auto completions, models and textures loading.
* [WebGL Playground](http://jessevdk.github.io/webgl-play/) - The editor lets you work on the JavaScript code and the GLSL vertex/fragment shaders (if you have any) at the same time in a convenient way. Everything is organized, formatted and highlighted properly, just as you would like.

### References

> WebGL references

* [Google Project ANGLE](https://github.com/google/angle) - Default WebGL backend for both Google Chrome and Mozilla Firefox on Windows platforms.
* [Khronos Official Wiki](https://wikis.khronos.org/webgl/) - The official wiki for WebGL.
* [WebGL Best Practices](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/WebGL_best_practices) - Mozilla's official set of best practices.
* [WebGL Errata](https://wikis.khronos.org/webgl/Errata_to_the_WebGL_Specification) - Known bugs in graphics drivers affect the conformance suite, and consequently, portability of code.
* [WebGL Extensions](https://registry.khronos.org/webgl/extensions/) - List of extensions for WebGL
* [WebGL Reference Card](https://www.khronos.org/files/webgl/webgl-reference-card-1_0.pdf) - WebGL 1.0 API Quick Reference Card for printing.
* [WebGL Source Code](https://github.com/KhronosGroup/WebGL) - Source code to both view and contribute.
* [WebGL Spec Sheet](https://registry.khronos.org/webgl/specs/1.0/) - All the detailed information about WebGL.

### Talks

> WebGL related talks

* [List of Presentations](https://wikis.khronos.org/webgl/Presentations) - List presented by Khronos of various WebGL related presentations.
* [Next-Generation 3D Graphics on the Web](https://www.youtube.com/watch?v=K2JzIUIHIhc) - Talk at Google I/O 19 from Ricardo Cabello (MrDoob).

### Tools/Debugging

> Tools for development and debugging WebGL

* [Khronos Dev Tools](https://github.com/KhronosGroup/WebGLDeveloperTools) - Useful WebGL developer tools, intended to be used as an ES6 module.
* [Spector.js](https://spector.babylonjs.com/) - Agnostic JavaScript framework for exploring and troubleshooting your WebGL scenes.
* [WebGL GLSL Editor](https://marketplace.visualstudio.com/items?itemName=raczzalan.webgl-glsl-editor) - GLSL language support extension for Visual Studio Code.
* [WebGL Inspector](http://benvanik.github.io/WebGL-Inspector/) - Tool inspired by gDEBugger and PIX with the goal of making the development of advanced WebGL applications easier.
* [WebGL Report](https://webglreport.com/?v=1) - Way to view the details of what your browser supports for WebGL.
* [WebGL Support Stats](https://webglstats.com/) - Interactive dashboard showing the support for WebGL features in different browsers and devices.
* [WebGL Texture Tester](http://toji.github.io/texture-tester/) - Attempts to load one of every texture format supported by WebGL, intended to quickly show which formats your browser/device supports.
* [Web Tracing Framework](http://google.github.io/tracing-framework/index.html) - Set of libraries, tools, and visualizers for the tracing and investigation of complex web applications.

#### Chrome Specific Tools/Debugger

* [GLSL Shader Editor Extension](https://github.com/spite/ShaderEditorExtension) - Chrome DevTools extension to help you edit shaders live in the browser.
* [Spector.js Extension](https://chromewebstore.google.com/detail/spectorjs/denbgaamihkadbghdceggmchnflmhpmk) - Explore and Troubleshoot your WebGL and WebGL2 scenes easily.
* [Webgl Insight](https://github.com/3Dparallax/insight) - Chrome extension WebGL debugging toolkit providing a variety of capabilities.

#### Firefox Specific Tools/Debugger

* [Firefox Developer Tools](https://firefox-source-docs.mozilla.org/devtools-user/index.html) - The official list of all of Firefox's debugger tools.

### Tutorials

> Online WebGL Tutorials (non-video)

* [Directional Shadow Mapping](https://chinedufn.com/webgl-shadow-mapping-tutorial/) - Concepts behind real time directional light shadow mapping.
* [Get Started Tutorial](https://wikis.khronos.org/webgl/Tutorial) - Khronos' tutorial how to get up and running with WebGL.
* [Getting Started with WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL) - Mozilla Foundation guide to getting started with WebGL.
* [Learn WebGL](https://www.tutorialspoint.com/webgl/index.htm) - Tutorials Point set of article to get you familiar with WebGL terms.
* [Multitexturing using a Blendmap](https://chinedufn.com/webgl-multitexture-blend-map-tutorial/) - How to use a blendmap to multitexture a terrain.
* [Particle Effects via Billboards](https://chinedufn.com/webgl-particle-effect-billboard-tutorial/) - Create particle effects by applying a technique called billboarding.
* [The Book of Shaders](https://thebookofshaders.com/) - Gentle step-by-step guide through the abstract and complex universe of Fragment Shaders.
* [WebGL Academy](http://www.webglacademy.com/) - Simplified online IDE with automatic indentation, syntax highlighting for HTML, Javascript, GLSL and Python. You can run your code and download your projects.
* [WebGL Fundamentals](https://webglfundamentals.org/) - Series of online tutorials with code samples and live demonstrations.
* [WebGL Image Processing](https://maximmcnair.com/webgl-image-processing) - Covers a range of _Image Processing_ algorithms in WebGL such as Color Correction, Blend Modes, Thresholding, Dithering, Convolution and Film Grain.
* [WebGL Month](https://github.com/lesnitsky/webgl-month) – Daily WebGL tutorial for a month.
* [WebGL Workshop](https://webgl-workshop.com/) - Interactive workshop to get you up and running with WebGL.
* [A tutorial on infinite canvas with WebGL](https://infinitecanvas.cc) - A hands-on tutorial for building a GPU-accelerated infinite canvas in the browser, with first-class WebGL support (and WebGPU) via a unified graphics API—covering ECS, SDF-based 2D primitives, GPU text, and tile-based rendering, by [@xiaoiver](https://github.com/xiaoiver).

### Videos

> WebGL Related Videos

* [An Introduction to WebGL Programming](https://www.youtube.com/watch?v=tgVLb6fOVVc&feature=youtu.be) - 3 hour overview of WebGL by SIGGRAPH University.
* [WebGL Tutorials - YouTube](https://www.youtube.com/playlist?list=PLjcVFFANLS5zH_PeKC6I8p0Pt1hzph_rt) - Series of lecture style video tutorials from Indigo Code on YouTube.

## WebGL 2

> Information about WebGL 2, the OpenGL ES 3.0 based successor to WebGL 1
>
> Anything pertaining to WebGL in general is found in the [WebGL](#webgl) section

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
* [WebGL 2 New Features](http://www.realtimerendering.com/blog/webgl-2-new-features/) - Blog post about whats new and cool in WebGL 2.
* [Zero Bytes of Geometry: A Metal Lattice Sphere-Traced in a 14.9 KB Page](https://dev.to/smirnovartur/zero-bytes-of-geometry-a-metal-lattice-sphere-traced-in-a-149-kb-page-kib) - Ray marching a signed distance field in raw WebGL 2, with an analytic environment in place of an HDR file and resolution adapted against the display refresh period.

### References

> WebGL 2 references

* [WebGL 2 Spec Sheet (Editor Draft)](https://registry.khronos.org/webgl/specs/latest/2.0/) - All the detailed information about WebGL 2.
* [WebGL 2 Reference Card](https://www.khronos.org/files/webgl20-reference-guide.pdf) - WebGL 2.0 API Quick Reference Card for printing.
* [WebGL 2 Compatible Chart](https://caniuse.com/#feat=webgl2) - Chart to show current browsers supporting WebGL 2

### Tutorials

> WebGL 2 tutorials (non-video)

* [WebGL 2 Fundamentals](https://webgl2fundamentals.org/) - Series of online tutorials with code samples and live demonstrations.
* [WebGL 2 Samples](http://webglsamples.org/WebGL2Samples/) - Great source of many different WebGL 2 work with very good commenting.
* [WebGL 2 Examples](https://github.com/tsherif/webgl2examples) - Rendering algorithms implemented in raw WebGL 2.
* [WebGL 2 & GLSL Primer: A Zero-to-Hero, Spaced-Repetition Guide](https://github.com/GregStanton/webgl2-glsl-primer) - Grok WebGL2 and GLSL through a sequence of guided lessons, each chunked into atomic Q&A cards, with hands-on projects and solution code integrated throughout.

### Videos

> WebGL 2 related videos

* [Fun with WebGL 2.0](https://www.youtube.com/playlist?list=PLMinhigDWz6emRKVkVIEAaePW7vtIkaIF) - Video tutorial series on getting started with WebGL 2.
* [WebGL 2.0 is Here: What You Need To Know](https://www.youtube.com/watch?v=Xf65duJ_QFs) - Khronos Webinar April 2017.
    * [Slides](https://www.khronos.org/assets/uploads/developers/library/2017-webgl-webinar/Khronos-Webinar-WebGL-20-is-here_What-you-need-to-know_Apr17.pdf)

## WebXR / WebVR

> Information about immersive web development. WebVR was superseded by the WebXR Device API; the WebVR items below are kept for historical reference.

### WebXR / WebVR sub-categories

* [References](#references-2)
* [Platforms](#platforms)
* [Frameworks](#frameworks)

### References

> WebXR and WebVR references

* [Immersive Web Community Group](https://www.w3.org/community/immersive-web/) - Group whose goal is to help bring high-performance Virtual Reality and Augmented Reality to the open Web.
* [UX of VR](https://www.uxofvr.com/) - Curated list of resources to help create good UX in VR.
* [WebXR Device API](https://immersive-web.github.io/webxr/) - The W3C draft API for WebXR.
* [WebVR Spec](https://w3c.github.io/webvr/) - The official W3C WebVR spec (legacy).
  * [How to read WebVR Specs](https://dassur.ma/things/reading-specs/)

### Platforms

> Platforms to experience immersive web content

* [JanusVR](https://janusvr.com/) - Webpages as collaborative 3D webspaces interconnected by portals.

### Frameworks

* [A-Frame](https://aframe.io/) - Web framework for building virtual reality experiences.
  * [Awesome-AFrame](https://github.com/aframevr/awesome-aframe)
* [Primrose](https://github.com/capnmidnight/Primrose/) - Rapidly prototype VR applications in your browser.

## Libraries

> [More detailed information about the different libraries can be found in the Libraries directory.](https://github.com/sjfricke/awesome-webgl/tree/master/Libraries)

### Engines and Frameworks
* [Babylon.js](https://www.babylonjs.com/) - Complete JavaScript framework for building 3D games with HTML5, WebGL and Web Audio.
* [Blend4Web](https://www.blend4web.com/en/) - Tool for interactive 3D visualization on the Internet.
* [ClayGL](https://claygl.xyz/) - WebGL graphic Library for building scalable Web3D applications.
* [CopperLicht](https://www.ambiera.com/copperlicht/index.html) - JavaScript library and WebGL 3D engine for creating games and 3D applications.
* [Hilo3d](https://github.com/hiloteam/Hilo3d) - WebGL rendering engine for 3D games.
* [PlayCanvas](https://playcanvas.com/) - Game engine platform to build interactive experiences.
* [Scene.js](http://scenejs.org/) - Extensible WebGL-based engine for high-detail 3D visualisation.
* [Three.js](https://threejs.org/) - Aimed to create an easy to use, lightweight, 3D library.
* [Verge3D](https://www.soft8soft.com/verge3d/) - an artist-friendly toolkit for creating 3D web experiences.
* [zephyr3d](https://zephyr3d.org/) - A TypeScript-based 3D rendering engine with WebGPU/WebGL support.

### 2D
* [Phaser](https://phaser.io/) - Open source HTML5 2D game framework for Canvas and WebGL, supports mobile web browsers.
* [PixiJS](https://pixijs.com/) - powerful 2D Javascript renderer based on WebGL.

### Low-level Rendering
* [GLBoost](https://github.com/emadurandal/GLBoost) - Rendering library for 3D graphic geeks.
* [Lightgl.js](https://github.com/evanw/lightgl.js) - Lightweight and explict library to help prototype.
* [Luma.gl](https://luma.gl/) - WebGL2 powered framework for GPU-powered data visualization and computation.
* [PicoGL.js](https://tsherif.github.io/picogl.js/) - Minimal WebGL 2-only rendering library.
* [Pocket.gl](https://github.com/gportelli/pocket.gl) - Fully customizable webgl shader sandbox to embed in your pages.
* [Regl](https://regl-project.github.io/regl/) - Light declarative and stateless library, functional abstraction for WebGL.
* [TWGL](http://twgljs.org/) - Sole purpose is to make using the WebGL API less verbose.

### Math
* [glMatrix](https://glmatrix.net/) - Javascript matrix and vector library for high performance WebGL apps.

### Physics
* [Ammo.js](https://github.com/kripken/ammo.js/) - Direct port of the Bullet physics engine to JavaScript using Emscripten.
* [Cannon.js](http://schteppe.github.io/cannon.js/) - Lightweight and simple 3D physics engine for the web.

### Maps and Visualizations
* [Cesium](https://cesium.com/) - Open-source library for world-class 3D globes and maps.
* [Deck.gl](http://deck.gl/) - WebGL overlay suite for React providing a set of highly performant data visualization overlays.
* [Globedots](https://github.com/swamoth/globedots) - Dot-matrix globe on WebGL2 in 17 kB, with markers, arcs, labels, heat maps, and a day-night line.
* [leaflet-webgl-markers](https://github.com/tang-tc/leaflet-webgl-markers) - Leaflet plugin for rendering millions of point markers on a single WebGL canvas, with FBO picking and zero redraw while dragging.
* [TradeCanvas](https://github.com/bonguynvan/tradecanvas) - Financial charting library that draws candles, indicators and depth heatmaps with WebGL 2, falling back to Canvas 2D.
* [xeokit](https://xeokit.io/) - Web Graphics SDK for AEC/BIM applications with 3D-tiles, real-world coordinates and double precision.

### Computer Vision (GPGPU)
* [GammaCV](https://gammacv.com) - WebGL accelerated Computer Vision library for browser.
* [Speedy Vision](https://github.com/alemart/speedy-vision) - GPU-accelerated Computer Vision library for JavaScript.

### Particles and Effects
* [NixieFX](https://github.com/azakhary/nixie-fx) - Particle and VFX runtime for PixiJS and Three.js, authored in a browser-based editor.
* [Phenomenon](https://github.com/vaneenige/phenomenon) - Very small, low-level WebGL library that provides the essentials to deliver a high performance experience.
* [Sula Designer](https://sula.ink/designer) - Browser editor for animated WebGL shader backgrounds with snippet export for Webflow, Framer, React, Vue, Svelte and HTML.
* [textmode.js](https://github.com/humanbydefinition/textmode.js) - Lightweight, framework-agnostic creative coding library for real-time ASCII and textmode graphics using WebGL2.
* [Vysmo Transitions](https://github.com/vysmodev/vysmo) - Tree-shakable WebGL 2 library of 60 endpoint-correct transitions with mesh and multi-pass support, ~5 KB gzipped.

### WebAR
* [encantar.js](https://github.com/alemart/encantar-js) - GPU-accelerated Augmented Reality library that works on any device (iOS, Android, desktops). Easy to use and requires no WebXR support.

### Legacy / Unmaintained

> Still linked for historical reference; check project activity before starting something new with these.

* [GLGE](http://www.glge.org/) - Javascript library intended to ease the use of WebGL.
* [OSG.js](https://cedricpinson.github.io/osgjs-website/) - WebGL framework based on OpenSceneGraph concepts to interact with WebGL.
* [Pex-gl](http://vorg.github.io/pex/) - JavaScript libraries for computational thinking in Plask/Node.js and WebGL.
* [React 360](https://github.com/facebookarchive/react-360) - Build VR websites and interactive 360 experiences with React (archived by Facebook).
* [Turbulenz](https://github.com/turbulenz/turbulenz_engine) - Modular 3D and 2D game framework for making HTML5 powered games for browsers, desktops and mobile devices.
* [Whitestorm.js](https://whs.io/) - Framework for developing 3D web apps with physics.

## Community
* [Stack Overflow](https://stackoverflow.com/questions/tagged/webgl)
* [Reddit](https://www.reddit.com/r/webgl/)
* [Facebook](https://www.facebook.com/groups/webgl/about/)
* [Twitter / X](https://x.com/webgl)
* [Khronos Forum](https://community.khronos.org/c/other-standards/webgl/17)
* [Google Group](https://groups.google.com/forum/#!forum/webgl-dev-list)
* [Public Mailing List](https://www.khronos.org/webgl/public-mailing-list/)
* [WebVR Public Mailing List](https://lists.w3.org/Archives/Public/public-webvr/)
* Active Meetup Groups
  * [San Francisco, CA](https://www.meetup.com/webgl-developers-meetup/)
  * [Mountain View, CA](https://www.meetup.com/silicon-valley-html5-webgl-meetup/)
  * [London, United Kingdom](https://www.meetup.com/webgl-workshop-london/)
  * [New York, NY](https://www.meetup.com/nyc-webgl-developers/)

## Related lists

> Similar awesome lists

* [awesome](https://github.com/sindresorhus/awesome) - Curated list of awesome lists.
* [awesome-opengl](https://github.com/eug/awesome-opengl) - Curated list of awesome OpenGL libraries, debuggers and resources. Inspired by awesome-... stuff.
* [awesome-vulkan](https://github.com/vinjn/awesome-vulkan) - Curated list of awesome Vulkan projects and ecosystem.
* [gamedev](https://github.com/ellisonleao/magictools) - Awesome list about game development.
* [glTF](https://github.com/KhronosGroup/glTF) - Runtime 3D Asset Delivery designed for the web.
* [graphics-resources](https://github.com/mattdesl/graphics-resources) - List of graphic programming resources.

## Contributing
Please see [CONTRIBUTING](https://github.com/sjfricke/awesome-webgl/blob/master/CONTRIBUTING.md) for details.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Spencer Fricke](https://github.com/sjfricke) has waived all copyright and related or neighboring rights to this work.
