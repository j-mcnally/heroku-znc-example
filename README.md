heroku-znc-example
==================

Run a znc bouncer on Heroku.

See the buildpack for details.

https://github.com/j-mcnally/znc-buildpak

Set the app's ngrok api key

`heroku config:set NGROK_API_KEY=[API_KEY]

Set the app's build pack with

`heroku config:set BUILDPACK_URL=https://github.com/j-mcnally/znc-buildpak`

The easiest way to create a znc.conf is to run

`brew install znc`

and then

`znc --makeconf`

and copy the file from ~/.znc/configs/znc.conf into your project.
