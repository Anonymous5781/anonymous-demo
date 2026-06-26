# Anonymous Demo

Static supplementary-material viewer for resume review. Images are embedded in `Results_Viewer.html`; the teaser image is stored as `image.png`.

## Video

The demo video is loaded from a GitHub Release asset:

```js
const VIDEO_SOURCE = 'https://github.com/Anonymous5781/anonymous-demo/releases/download/v1.0.0/Demo.mp4';
```

`Demo.mp4` is ignored by Git and should stay out of the repository history. Upload it to the `v1.0.0` release as `Demo.mp4`.

## Local preview

Open `index.html` or `Results_Viewer.html` in a browser. The same page works on GitHub Pages after the Release asset is available.