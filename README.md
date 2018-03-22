# Brunch on Speed

This is a skeleton (or boilerplate) for [Brunch](http://brunch.io), a fast and easy to configure building tool for modern Web development. The skeleton is intended to be a foundation for a long-scroll, single, static Web page.

[![dependencies Status](https://david-dm.org/jfilter/brunch-on-speed/status.svg)](https://david-dm.org/jfilter/brunch-on-speed)
[![devDependency Status](https://david-dm.org/jfilter/brunch-on-speed/dev-status.svg)](https://david-dm.org/jfilter/brunch-on-speed#info=devDependencies)

## Installation

Clone this repo manually or use `brunch new DIRECTORY -s jfilter/brunch-on-speed`

## Features

* [Twitter Bootstrap 4.0](https://getbootstrap.com/docs/4.0/getting-started/introduction/)
* [jQuery](http://jquery.com)
* Compilation of ECMAScript 2015 (ECMAScript 6) files with [Babel](https://babeljs.io)
* Uglification and concatenation of Javascript files with [UglifyJS](http://lisperator.net/uglifyjs/)
* Extending CSS with [Sass](http://sass-lang.com)
* Autoprefixing, concatenation, minification (and more) of CSS files with [Pleeease (PostCSS)](http://pleeease.io)
* Auto reload of development server
* [ESLint](http://eslint.org) with [AirBnB Javascript Style Guide](https://github.com/airbnb/javascript)
* Ready to format your code with [Prettier](https://prettier.io)
* index.html with essential meta tags for SEO and Social Media

## Recommendation

To complete the development environment, make sure to integrate [ESLint](https://eslint.org/docs/user-guide/integrations) and [Prettier](https://prettier.io/docs/en/editors.html) into your text editor.

## Getting started with Brunch

* Install (if you don't have them):
  * [Node.js](http://nodejs.org): `brew install node` on OS X
  * [Brunch](http://brunch.io): `npm install -g brunch`
  * Brunch plugins and app dependencies: `npm install`
* Run:
  * `npm start` — watches the project with continuous rebuild. This will also launch HTTP server with [pushState](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Manipulating_the_browser_history).
  * `npm run build` — builds minified project for production
* Learn:
  * `public/` dir is fully auto-generated and served by HTTP server. Write your code in `app/` dir.
  * Place static files you want to be copied from `app/assets/` to `public/`.
  * [Brunch site](http://brunch.io), [Getting started guide](https://github.com/brunch/brunch-guide#readme)
