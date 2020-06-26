# Fixed GPL version 7.0.0 theme-base

This package is the base for all the themes under classic.

Sencha GPL version shows the `Ext JS Trial` watermark. They just forgot to remove it. This package fixes this error.
(See [this question](https://stackoverflow.com/q/61817778/1951708) on Stack Overflow.)

##Usage
In your `package.json` add this line under `dependencies`:

    "@sencha/ext-classic-theme-base": "https://github.com/lmeyer1/ext-classic-theme-base/tarball/master",

This will replace @sencha's original faulty package with this corrected one.

You can force an update of this package with `npm install -f @sencha/ext-classic-theme-base`. You might need this
because this is not a versioned package.
