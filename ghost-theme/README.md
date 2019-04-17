## source{d} Ghost Theme

This theme is a customization for source{d} based on a blank template for Ghost.

### All Ghost features

It includes all the [Ghost](https://ghost.org/) functionalities a theme can provide, in a modular implementation so it is easy to customize those functionalities or get rid of them.

Probably you will not want everything [Ghost](https://ghost.org/) shows on a theme, but trust me when I say it is easy to remove those stuff you do not want to see instead of add them if they are missing in the first place.

### Code separated into different .hbs files

While trying to avoid complicating the whole code, still some parts of it are divided into different `.hbs` files for easy understanding of what those specific snippets do, and to easily customize them or remove them.

For example, you might find that `page.hbs` is exactly the same as `post.hbs`. The "logical" thing to do is to omit the `page.hbs` so [Ghost](https://ghost.org/) loads the `post.hbs` for default, but both files are there for the reason that this is a developer ready theme.

### No styles

The point with the Pale Ghost theme is to get a good markup with all the [Ghost](https://ghost.org/) features already there.

For that reason, it does not include any CSS because the idea is that you use this theme as a base for your own creation that will include CSS (or SASS, or LESS) for the styling.

What the Pale Ghost theme does have is a `beautify.css` file that highlights the main elements in the markup for a more easy coding. Keep this in the `head.hbs` file if you don not want to see a mess when loading the theme in your browser.

### AMP ready

With some specific AMP modifications separated into specific `.hbs` files for easy maintenance.


### GScan valid

> GScan is designed to check your theme for various issues that we know cause compatibility problems. Our aim is to allow themes to suggest which versions of Ghost they are compatible with via engines in package.json, but to always know for sure by running various checks.

Read more about it in the [GScan documentation](https://themes.ghost.org/docs/gscan).


## Installation

Simple as uploading the `ghost-blog.zip` file into the `Settings -> Design` section from the Ghost Admin, or moving the `pale-ghost` folder into `content/themes`.

You can fork and/or clone this repo so it is easy for you to work on the code, or you can download the latest stable release from the [Releases](https://github.com/nahuelsanchez/pale-ghost/releases) section.


## Copyright

Customization for source{d} based on Pale Ghost Theme Copyright (c) 2018 [Nahuel Sanchez](https://www.nahuelsanchez.com/)

Original theme released under the [MIT license](LICENCE).

Portions of code were borrowed from [Casper](https://github.com/TryGhost/casper), copyright (c) 2013-2018 Ghost Foundation. Used under the MIT license.