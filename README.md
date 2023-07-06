# LinkClipper

## Description

This is just a simple MacOS application that can be used to copy links to the clipboard when opening any link. It's created with 2 main use cases in mind:

To get full potential of this application it's recommended to use LinkClipper with a clipboard manager application in Mac OS like:

- [Alfred](https://www.alfredapp.com/)
- [RayCast](https://raycast.com/)
- [Clipboard Center](https://clipboard.center/)
- [CopyClip](https://fiplab.com/apps/copyclip-for-mac)
- [Pasta](https://getpasta.com/)
- [Paste](https://pasteapp.io/)

### With Passthrough - Copying links from the browser

Adding this version of LinkClipper as your default browser, will make any link you open in your system to get added to your clipboard before it's opened in your browser. Just remember to change your preferred browser by uncommenting it in `apps/withPassthrough/LinkClipper.app/Contents/MacOS/LinkClipper`.

Then you have to set LinkClipper as the default browser in `System Preferences > General > Default web browser`.

Any link follow in your system from now on will be automatically copied into the clipboard. This is useful when you want to copy a link from the browser to another application, but you don't want to open the link in the browser, and then copy from the URL bar.

### Only Copy - Copying links from any application

This version of the application works only as a way to copy links from any application. This is useful used in combination with [Choosy](https://choosy.app/), [Finicky](https://github.com/johnste/finicky) or [Browserosaurus](https://browserosaurus.com/), so when you try to open a link you can select LinkClipper to only copy the link to the clipboard.

## Credits

- The icons used for this application are called `Safari A AppIcon` (for the Passthrough version) and `Clipboard Center AppIcon` (for the created by [BUXBE](https://macosicons.com/#/u/BUXBE) on [macosicons](https://macosicons.com/).
- Basic app structure created with [appify](https://github.com/subtleGradient/tilde-bin/blob/master/appify).
