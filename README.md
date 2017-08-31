# GRT Youtube Popup - jQuery Plugin
Lightweight jQuery plugin for playing youtube embed videos in a popup. 

You can checkout the demo here: [grt107.github.io/grt-youtube-popup/](http://grt107.github.io/grt-youtube-popup/)

# Screenshot:
![Alt text](/screenshot.jpg?raw=true "Demo Screenshot")

# How to use in your website:
1- Include the plugin stylesheet grt-youtube.css in your ```<head>```

  ```html
  <link rel="stylesheet" href="grt-youtube-popup.css">
  ```

2- Include the plugin javascript file ```grt-youtube-popup.js``` in your ```<body>```

  ```html
  <script src="grt-youtube-popup.js"></script>
  ```

3- Add a custom class that will be used for the plugin and insert the id of Youtube in data attribite like in the example below:

  ```html
  <span class="youtube-link" youtubeid="yPu6qV5byu4">Open Video</span>
  ```
  
4- Initialize the plugin at the end of all your javascript files with your custom class (after ```jQuery``` and ```grt-youtube-popup.js```)

```html
  <script> $(".youtube-link").grtyoutube(); </script>
  ```

# Advanced Options
- Autoplay Enabled (enabled by default)

```html
<script> $(".youtube-link").grtyoutube({ autoPlay:true }); </script>
```

- Autoplay Disabled

```html
<script> $(".youtube-link").grtyoutube({ autoPlay:false }); </script>
```
