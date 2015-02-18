# Stable

ThreeJS - http://threejs.org/

Helps you create webgl applications easily. Had some issues with parts of the library/platform not working 
with other parts due to version conflicts. At the time of this writing the the JSON exporter for Blender
did not work with bone based animations.

Sea3D - https://github.com/sunag/sea3d

A file format and exporter which can be used with ThreeJS. Supports bone animations.

Pixi - http://www.pixijs.com/

A 2D renderer which uses WebGL but fallsback to Canvas. A fantastic library but is a bit bulky. Noticed
some inconsistencies between Graphics (vector style) rendering in WebGL rendering and 2D canvas rendering.
Filters are not compatible when Canvas fallback is used.

Howler - https://github.com/goldfire/howler.js/

A library which helps you add Sounds to websites.

jQuery - http://jquery.com/

Although it's being used less and less from time to time it's being brought on to projects. Adds a lot
functionality from selecting, manipulating the dom, to Ajax loading. jQuery should never be used to 
create animations but instead gsap/TweenLite should be used.



# Experimental

CLMTrackr - https://github.com/auduno/clmtrackr

Facial feature recognition and tracking. Works better with video/webcam than still images. By default
uses WebGL but can fallback to a slower less precise mode using Canvas 2D.

jsfeat - http://inspirit.github.io/jsfeat/

Computer vision.