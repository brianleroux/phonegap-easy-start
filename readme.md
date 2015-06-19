# phonegap easy start

everything is here is the bare min req for getting some html on your phone in app form

## install

- install the phonegap developer app for [android](https://play.google.com/store/apps/details?id=com.adobe.phonegap.app), [ios](https://itunes.apple.com/app/id843536693) or [windows phone](http://www.windowsphone.com/en-us/store/app/phonegap-developer/5c6a2d1e-4fad-4bf8-aaf7-71380cc84fe3) (ideally on all three)
- run `npm i` on this repo

## run

1. run `npm start` from the root of this directory
2. open the app(s) on your phone(s) 
3. enter the ip address displayed from running `npm start` into the app(s) on your phone(s)

from here you can make changes and the device will reload. how you want to build your html stuff is up to you.

## api access

plugins you can use are defined in `config.xml` (docs for those and more can be found here)[http://docs.phonegap.com]

### regrets

we don't really love `config.xml` but it is currently required (legacy yay) but there is a deliberately slow plan to move to vanilla `package.json`


## next steps

once you get happy with your app you may wish to compile it and distribute via app stores. this is considerably more involved as you have to install the sdks for the various mobile platforms you wish to target. [all the docs for that are here](http://docs.phonegap.com/en/edge/guide_cli_index.md.html#The%20Command-Line%20Interface)
