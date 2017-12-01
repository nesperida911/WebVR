WebVR

This project is built with "fullPage.js" & Google's VR WebView.

Image must be hosted online and must have 4028x4028 image size.

```javascript
  window.addEventListener('load', onVrViewLoad)
  function onVrViewLoad() {
    var vrView = new VRView.Player('#vrview', {
      width: '100%',
      height:	500, //You can change this height
      preview: '', //TODO ADD PREVIEW IMAGE OPTIONAL
      image: 'ADD HERE YOUR IMAGE LINK', //TODO ADD YOUR 360 IMAGE LINK HERE (4028x4028) IMPORTANT: MAKE SURE YOU UPLOAD YOUR IMAGE FIRST TO IMAGE HOSTING SITES
      is_stereo: true
    });
  }
```
