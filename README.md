##NY Mag Ooyala Test
Implementation of Ooyala's v4 player

To run: 
```
cd ooyala-static
python -m SimpleHTTPServer
```

Then navigate to 0.0.0.0:8000 in your browser

You can also see this in action (http://byronhulcher.github.io/ooyala-static)[here].

We use a custom skin.json file based on (https://github.com/ooyala/skin-config)[ooyala/skin-config].
We use a forked copy of (https://github.com/ooyala/html5-skin)[ooyala/html5-skin] located at  (https://github.com/byronhulcher/html5-skin)[byronhulcher/html5-skin] to add support for the loadingImage option.