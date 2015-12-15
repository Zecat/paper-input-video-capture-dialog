# paper-input-video-capture-dialog

This element give you the ability to import a video from your local disk, and then open it in a dialog where you can play it and take a snapshot of the current frame. Once captured, you can confirm the dialog.

To use, just bind to the attributes it provides, and call 'search()'.

This is just a wrapper arrount an input type file and [iron-video-capture](https://github.com/Zecat/iron-video-capture).

## Demo & doc

See the [component page](http://zecat.github.io/paper-input-video-capture-dialog) for more information.

## Todo

- support multiple videos & multiple capture per video using neon-slideshow.
- use paper-tile-rename to display capture and update they name in the blob file.
- implement iron-form-element-behavior
- change the logic to extend the native input ?