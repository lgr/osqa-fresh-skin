About osqa-fresh-skin 
======================

This is a custom theme for the famous Q&A system http://www.osqa.net/ that is based on the  Nuxeo Skin (http://github.com/nuxeo/osqa-nuxeo-skin).

## Sample Screenshot ##
![Demo](https://github.com/lgr/osqa-fresh-skin/raw/master/demo.png)


Installation
--------
1. Copy the content of this repository to the directory osqa/forum/skins/fresh/:

```
cd osqa/forum/skins/
mkdir fresh
cd fresh
git clone git://github.com/lgr/osqa-fresh-skin.git
```

2. Change the skin in the settings file. Go to the file `settings.py` (or `settings_local.py`) and change the value of the variable `OSQA_DEFAULT_SKIN`:

```
...
OSQA_DEFAULT_SKIN = 'fresh'
...
```

And it should be working. Enjoy:)