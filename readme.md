# MentorCub Tailwind CSS

We use Tailwind CSS to style our applications. Tailwind CSS is a utility-first CSS framework for rapidly building custom user interfaces that is highly customizable.

This repository contains Tailwind CSS configuration, `tailwind.config.js`, that we will probably use in most of our applications and Post CSS configuration, `postcss.config.js` which is required by Tailwind CSS. The reason we create this repository is to prevent copy-pasting these Tailwind related files in case we change it in the future.

## Installation

To have this package set up properly, you need to have installed Tailwind CSS. Please refer to [Tailwind CSS Installation](https://tailwindcss.com/docs/installation/using-postcss). After that, you can install this package by running the command below:

```bash
npm i @mentorcub/tailwindcss
```

After installing the package, add a `tailwind.config.js` file in the root of your project. Write the line below inside of the config file.

```js
module.exports = require("@mentorcub/tailwindcss/tailwind.config");
```

After that, we also need to setup the `postcss.config.js` file with the configuration that is required by Tailwind CSS.

```js
module.exports = require("@mentorcub/tailwindcss/postcss.config");
```

We are all set!
