# Astro Tailwind Config

> NOTE: This package is experimental and is subject to change.
## Installation

* Install 
```bash
npm i @astrouxds/tailwind
```
* If you're not using the Astro Web Components, you'll need to [Install Astro Design Tokens](https://github.com/RocketCommunicationsInc/astro-design-tokens)
	* `npm i @astrouxds/tokens`
	* In your project root: `import '@astrouxds/tokens/dist/css/index.css'`
* [Install Tailwind](https://tailwindcss.com/docs/installation) in your project.
* Add the Astro Tailwind plugin 
```js
//tailwind.config.js
...
 plugins: [require('@astrouxds/tailwind')]
...

```

## Usage

Reference [Demo Site](https://astro-tailwind-config.netlify.app/) for a list of available colors and utilities.

For more detailed information, see our [Design Token Documentation](https://astrouxds.org/design-tokens/system)