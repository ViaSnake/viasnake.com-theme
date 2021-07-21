# viasnake.com-theme

[viasnake.com](https://viasnake.com)で使用されているGhostのテーマリポジトリです。元リポジトリは[TryGhost/Ruby](https://github.com/TryGhost/Ruby)です。

# Ruby

A multi-column theme with a unique card layout. Share your posts with contemporary style. Completely free and fully responsive, released under the MIT license.

**Demo: https://ruby.ghost.io**

&nbsp;

# Instructions

1. [Download this theme](https://github.com/TryGhost/Ruby/archive/master.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
yarn zip
```

# PostCSS Features Used

- Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.

# Copyright & License

> This repository has been forked. Any code added in this repository is an MIT Licence.

Copyright (c) 2013-2021 Ghost Foundation - Released under the [MIT license](LICENSE).
Copyright (c) 2021 viasnake - Released under the [MIT license](LICENSE).
