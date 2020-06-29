# Fixed GPL version 7.0.0 theme-base

This package is the base for all the themes under classic.

Sencha GPL version shows the `Ext JS Trial` watermark. They just forgot to remove it. This package fixes this error.
(See [this question](https://stackoverflow.com/q/61817778/1951708) on Stack Overflow.)

## Usage
In your `package.json` add this line under `dependencies`:

    "@sencha/ext-classic-theme-base": "https://github.com/lmeyer1/ext-classic-theme-base/tarball/master",

This will replace @sencha's original faulty package with this corrected one.

You can force an update of this package with `npm install -f @sencha/ext-classic-theme-base`. You might need this
because this is not a versioned package.

## Licencing

The code contained in this repository is licensed under the GPL 3.0 licencing terms according to
[Sencha GPL Licensing](https://www.sencha.com/legal/gpl/) and [GNU GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

The removal of the watermark in this code cannot be assimilated with the defended removal of the watermark in software
distributed under the [Trial Licence](https://www.sencha.com/legal/sencha-software-license-agreement/) (paragraph 2.2 of the
Sencha Software License Agreement), because this present source code has been obtained under the GPL 3.0 software license.
Furthermore, the presence of the *Ext Js Trial* watermark in the *Ext Js GPL* version cannot be explained other than as
an oversight.
