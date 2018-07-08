# Coming Soon Webpage
A free open-source 'coming soon' webpage you can use for your project. I've used it for quite a few of my projects. It has a countdown timer to the project release date.  
You can preview it here: https://comingsoonwebpage.jam-es.com

### Installing
To host it yourself all you need is static website hosting. If you do not already have this, you can use Google App Engine (https://cloud.google.com/appengine/) for free.

## Built With

* [MaterializeCSS Framework](https://materializecss.com/) - A great CSS framework, I highly recommend. I used version 1.0.0-rc.2. The index.html file links to the required CSS/Js files which are hosted on a CDN.
* [FlipClock.js](https://flipclockjs.com/) - Countdown clock with nice animations. All CSS/Js required is included.

## Breakdown of files/folders
* readme.md - This readme markdown file
* app.yaml - Specifies how URL paths correspond to request handlers and static files when hosting with Google App Engine. If you are not using GAE you do not need it.
* index.html - The webpage where all the fun happens :)
* css/flipclock.css - CSS file used by FlipClock.js
* js/flipclock.js & js/flipclock.min.js - JavaScript files used by FlipClock.js
* js/sidenav.js - JavaScript code for initializing a mobile sidenav.

## License

You may download/use/distribute/modify/host/sell the code however you like. There are no restrictions.