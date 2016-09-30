# Pure Blue
A pelican theme based on [Pure css](http://purecss.io/)

I use this [pure theme](http://purecss.io/layouts/blog/) and change it to match the Pelican structure.

## Features

* Responsive
* CSS minification (optional via [plugin](https://github.com/aslamhadi/pure-blue))
* Once you activate the virtualenv, run `pip install -r requirements.txt`
* Disqus
* Google Analytics
* Font Awesome

## Installation

You can add this theme as a git submodule

```
git submodule add https://github.com/aslamhadi/pure-blue.git themes/pure-blue
```

And then in `pelicanconf.py` add this line to use this theme

```
THEME = 'themes/pure-blue'
```

## Enable CSS minification

Please follow this [https://github.com/getpelican/pelican-plugins](https://github.com/getpelican/pelican-plugins) to install the plugin. 

I recommend adding the plugins as submodules. Once you've done it, enable the plugin by adding this to `pelicanconf.py`

```
PLUGIN_PATHS = ['./plugins']
PLUGINS = ['assets']
```

*NOTE: path depends on where you put the plugins

## Additional Configurations in pelicanconf.py

`SUBNAME` : sidebar configuration. More information below the SITENAME

## Demo

I use this theme personally. Please go to my [blog](http://commitcode.com/).
