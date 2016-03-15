[![Stories in Ready](https://badge.waffle.io/dfst/webgme-chflayout.png?label=ready&title=Ready)](https://waffle.io/dfst/webgme-chflayout)
# webgme-chflayout
A Header-Center-Footer webgme layout with a floating panel

# Installation
CHFLayout can be added to a webgme app with:

```
webgme add layout CHFLayout dfst/webgme-chflayout
```

Then, set it as the default with

```
webgme enable layout CHFLayout
```

# Configuration

The panels in each position (ie, `header`, `footer`, `center`, and `float`) can be specified in `components.json` under the `CHFLayout` key (as shown in `components.json` in this directory.
