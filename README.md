# groundhog
##### with Dark Sky up in this beast
___
click it. it's a video

[![weather](https://img.youtube.com/vi/XiAyWYCcAI0/0.jpg)](https://www.youtube.com/watch?v=XiAyWYCcAI0)


Not a big deal, but I finally made a weather app with code stolen from the internet and styling completely ripped off from Google. The cool thing is this a progressive web app with all the service worker bennys for offline usage.

#### quick start (web)

You're going to need a [Dark Sky Api key](https://darksky.net/dev) to include in your `.env` file at the root of your directory.

```terminal
$ git clone git@github.com:MichaelRCruz/groundhog.git
$ cd groundhog
$ npm install
$ node server.js
```

Navigate Chrome to http://localhost:8000 for use on mobile and desktop.

#### iOS installation (pwa)
0. Open Safari and in a new browser tab, navigate to groundhog.
1. Click the Share  button.
2. Scroll right and click on the Add to Home Screen button.
3. Click Add.
4. Launch the Weather PWA from the home screen.

#### Chrome installation (pwa)
0. Open Chrome, and in a new browser tab, navigate to groundhog.
1. Open DevTools and switch to the Console pane.
2. Click the install button in the upper right corner.
3. Click Add.
4. Launch groundhog from the home screen.
