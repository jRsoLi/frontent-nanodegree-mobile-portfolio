# README

## PageSpeed Score

### Changes:

* Minifed style.css and put it inline (took mobile out of it)
* Created, minified and put inline the style-mobile.css
* Minified print.css
* Google Font at end of page
* Added pictures locally and compressed them

## Getting Rid of Jank

### Changes:

* Removed declarations from the loops and put them beforehand
* Made declerations more specific by using "getElemtById" and "getElementsByClassName"
* Compressed Pizza Image

## Instructions to run locally:

Open the command prompt at the repository root and use pythons SimpleHTTPServer to create a local Server
```
python -m SimpleHTTPServer 8000
```
Open a second command prompt at the repository root and run ngrok to make your server accessible from the web
```
ngrok http 8000
```
