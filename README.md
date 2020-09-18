# VUDRM LG Smart TV with dash.js

This repository will demonstrate how to use [VUDRM](https://vudrm.vualto.com/) with [webOS](http://webostv.developer.lge.com/), it uses the [dashjs](https://github.com/Dash-Industry-Forum/dash.js?) player, [HTML5 MSE/EME](https://developer.mozilla.org/en-US/docs/Web/API/Encrypted_Media_Extensions_API) and [PlayReady](https://www.microsoft.com/playready/). 
If you have any questions please contact support@vualto.com

webOS TV 3.0 and up support HTML5 MSE/EME:
http://webostv.developer.lge.com/discover/specifications/supported-media-formats/

Please follow the App Testing guide from LG: 
http://webostv.developer.lge.com/develop/app-test/

The app *must* be run on a TV because the Emulator does not support DRM playback.

You can set the mpeg dash URL and VUDRM token in the `index.html` file. Playback is set to automatically start.
For more information about VUDRM tokens please see the documentation:
https://docs.vualto.com/projects/vudrm/en/latest/VUDRM-token.html
