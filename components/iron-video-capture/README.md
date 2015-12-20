# iron-video-capture

An element extending the native video element, make it easy to capture a video frame. Usefull for a user to choose a video's image preview.
For now, it just capture the current frame.

## Demo & doc

See the [component page](http://zecat.github.io/iron-video-capture) for more information.

## Installation

```
bower install --save Zecat/iron-video-capture
```

## Warning: provide the video from your domaine

Internally it use a canvas element, due to CORS, the video can not come from an external domaine, otherwise, you'll receive a "Uncaught SecurityError: Failed to execute 'toDataURL' on 'HTMLCanvasElement': Tainted canvases may not be exported.". Tell me if you find a solution about that !