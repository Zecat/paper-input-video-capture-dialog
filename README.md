## paper-input-video-capture-dialog

[Demo And API Docs](http://zecat.github.io/paper-input-video-capture-dialog)

This element gives you the ability to import a video from your local disk, and then open it in a dialog where you can play it and take a snapshot of the current frame. Once captured, you can confirm the dialog.

To use, just bind to the attributes it provides, and call 'search()' on it.

It is just a wrapper arround an input type file and [iron-video-capture](https://github.com/Zecat/iron-video-capture), and it implement Polymer.PaperDialogBehavior.

### Installation

```
bower install --save Zecat/paper-input-video-capture-dialog
```

### Todo

- support multiple videos & multiple capture per video using neon-slideshow & Polymer.IronSelectableBehavior.
- use paper-tile-rename to display capture and update they name in the blob file.
- implement iron-form-element-behavior
- change the logic to extend the native input ?
- change the repo's name & logic to paper-video-capture and add it paper-video-capture-dialog &  paper-input-video-capture-dialog
- support drag & drop