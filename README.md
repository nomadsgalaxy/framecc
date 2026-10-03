# framecc.nomadsgalaxy.com

The website for [Command Center](https://github.com/nomadsgalaxy/Command-Center), the Steam
Frame's VR desktop. It's one static page plus the install script, published with GitHub Pages.

- `index.html` is the page. The scene at the top is WebGL (three.js), with a CSS version as the
  fallback, and it opens in a headset through WebXR when the browser supports it.
- `install` is what `curl -fsSL https://framecc.nomadsgalaxy.com/install | sh` runs.

Same license as Command Center (see its NOTICE.md).
