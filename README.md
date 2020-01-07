# jada [![Netlify Status](https://api.netlify.com/api/v1/badges/ab389147-4a61-4967-967c-a2d3c0020f98/deploy-status)](https://app.netlify.com/sites/gridsome-jada/deploys)

A practical blog starter for [Gridsome](https://gridsome.org/)

## Demo

<https://gridsome-jada.netlify.com>

[![Deploy to netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Microflash/jada)

## Features

- [x] Accessible and responsive design
- [x] Support for blogging with markdown content
- [x] Table of contents for blog posts
- [x] Tags for blog posts
- [x] Pagination for blog posts
- [x] Search with [Fuse.js](https://fusejs.io/) and [vue-fuse](https://github.com/shayneo/vue-fuse)
- [x] Automated blurb generation for posts
- [x] GitHub URL generation for blog posts
- [x] Syntax highlighting with [Shiki](https://github.com/octref/shiki)
- [x] [Sass](https://sass-lang.com/) integration
- [x] Theme Switcher for Dark and Light modes
- [x] Support for RSS, Atom and JSON feeds
- [x] Custom 404 page
- [x] Sitemap in XML

## Installation

### Using Gridsome CLI

```sh
npx gridsome create my-blog https://github.com/Microflash/jada.git
```

Gridsome will remove `.git` directory and install dependencies for you.

### Using Git

Clone this repository.

```sh
git clone https://github.com/Microflash/jada.git my-blog

# navigate to the directory
cd my-blog

# remove the git folder
rm -rf .git

# install dependencies
npm install
```

### Using GitHub Templates

You can directly [generate](https://github.com/Microflash/jada/generate) a new project from this repository on GitHub.

## Documentation

### Gridsome

For Gridsome configurations and docs, check [Gridsome docs](https://gridsome.org/docs/).

## License

Licensed under [MIT](./LICENSE.md).

---

## Footnotes

### Acknowledgements
 
This project would not have been possible without the open-source community, in general, and the following projects and people, in particular (not in any specific order):

- [Gridsome](https://gridsome.org/): a modern Vue.js framework for static websites (and more)
- [Gridsome Portfolio Starter](https://github.com/drehimself/gridsome-portfolio-starter): a simple portfolio starter for Gridsome 
- [Fuse.js](https://fusejs.io/): a lightweight fuzzy-search library
- [Shiki](https://github.com/octref/shiki): a beautiful syntax highlighter
- [Feather Icons](https://feathericons.com/): beautiful open-source icons
- [Remarkability](https://mflash.dev/remarkability/): the baseline css for HTML generated from markdown
- [Hamburgers](https://github.com/jonsuh/hamburgers): a collection of tasty CSS-animated hamburger icons
- [Grid By Example](https://gridbyexample.com/): a collection of examples and references on CSS Grid maintained by [Rachel Andrews](https://rachelandrew.co.uk/)
- [Leonardo](https://github.com/adobe/leonardo): an adaptive color scale generator developed by Adobe
- [Happy Hues](https://www.happyhues.co/): a collection of color palettes by [Mackenzie Child](https://www.mackenziechild.me/)

### Postscript

- `jada` is based on [Microflash](https://github.com/Microflash/microflash.github.io).
- Illustrations are from [Lively Panoramas](https://github.com/Microflash/lively-panoramas), an up-and-coming open-source vector illustrations pack.
