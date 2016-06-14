# image-histogram

Quick and dirty histogram viewer for images, created after watching this video: https://www.youtube.com/watch?v=fS2EL4z-NNU

### Demo

https://rawgit.com/danieltian/image-histogram/master/index.html

Only works on modern browsers (preferably Chrome) due to usage of native promises and ES6 arrow functions. Only works on local file system files due to single origin policy not allowing canvas to `.getImageData()` from cross-origin images.
