---
id: integration
title: Scanblue 3D player integration
sidebar_label: 3D player integration
---



## Ways to integrate a 3D model into your website or webshop

For easy integration of 3D models you have hosted in our 3D Cloud we provide the Scanblue **3D Player**. Based on the capabilities of the user's device the player offers a 3D experience or an AR view.

### Option 1: Embed the Scanblue Player directly inside your page

The 3D model will directly be shown inside your page. Best way to impress your customers with an interative version of your product directly inside your product presentation page.

>Note: Avoid loading multiple 3D models this way into one page. This may cause memory overflow on the clients device. 

```
<iframe
    src="https://webview.scanblue.cloud/ar/[YOUR-ASSET-ID-CODE]"
    style="height: 500px; width: 100%; border: none"
    frameborder="0"
    allowvr
    allowfullscreen
    mozallowfullscreen="true"
    webkitallowfullscreen="true"
    scrolling="no"
    >
</iframe>
```

See  [live code example.](http://docs.scanblue.cloud/_examples/player-integration/example-embed-iframe/)

### Option 2: Embed the Scanblue Player with preloading

By using the preload option, the user first needs to click or touch the preview image to initiate the loading of the Scanblue Player.

```
<iframe
    src="https://webview.scanblue.cloud/ar/[YOUR-ASSET-ID-CODE]?mode=embedded-img"
    style="height: 500px; width: 100%; border: none"
    frameborder="0"
    allowvr
    allowfullscreen
    mozallowfullscreen="true"
    webkitallowfullscreen="true"
    scrolling="no"
    >
</iframe>
```

See  [live code example.](http://docs.scanblue.cloud/_examples/player-integration/example-embed-iframe-preload/)
