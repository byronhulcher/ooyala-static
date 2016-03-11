##NY Mag Ooyala Test
Implementation of Ooyala's v4 player

To run: 
```
cd ooyala-static
python -m SimpleHTTPServer
```

Then navigate to 0.0.0.0:8000 in your browser

You can also see this in action [here](http://byronhulcher.github.io/ooyala-static).

We use a custom skin.json file based on [ooyala/skin-config](https://github.com/ooyala/skin-config).
We use a forked copy of [ooyala/html5-skin](https://github.com/ooyala/html5-skin) located at  [byronhulcher/html5-skin](https://github.com/byronhulcher/html5-skin) to add support for the loadingImage option.
