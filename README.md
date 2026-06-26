# Anonymous Demo

Static supplementary-material viewer for resume review. The teaser image is stored as `image.png`; result panoramas are stored under `cases/` and loaded on demand by the viewer.

## Video

The demo video uses the GitHub Release asset first and falls back to the COS URL:

```js
const VIDEO_SOURCES = [
  'https://github.com/Anonymous5781/anonymous-demo/releases/download/v1.0.0/Demo.mp4',
  'https://demo-1323834993.cos.ap-guangzhou.myqcloud.com/Demo.mp4'
];
```

`Demo.mp4` is ignored by Git and should stay out of the repository history. Upload it to the `v1.0.0` release as `Demo.mp4`.

## Local preview

Open `index.html` or `Results_Viewer.html` in a browser. The same page works on GitHub Pages after the Release asset is available.