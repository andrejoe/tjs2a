# tjs2a
A ThreeJS template which will allow an easy port to Android OpenGL ES and Controls.

The idea of this project is to construct an environment using prodominantly Three.js which will allow the development of OpenGL ES apps which can be easily ported (from Three.js) to Android. The goal is to aviod the middle man situation that would be necessary if a third partly library were used and simutaniouly allow the most flexibility on the device by using the lowest level functions directly. For the opengl es code this is expected to be very simple since webgl (as I understand it) is almost identical to opengl es (2.0 maybe not 3.0). However things like controls and audio will need probably more work than I will contribute, to automate. I think instead I will simply convert these by hand.

Why not just develope directly on the device or in an emulator.

If you need to ask this question you have not yet tried. Its slow and tiresome. Whereas working in Three.js is fast and direct. And since it renders to a webpage its easy to separate the working app from the development space. Also when all is done and the final product is ported to android you also have a webgl version.
