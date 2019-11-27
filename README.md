# Svelte Template Hot

This is a copy of official [Svelte template for Webpack](https://github.com/sveltejs/template-webpack) with added HMR support.

This template aims to remain as close to the official template as possible. Please refer to official docs for general usage. For HMR specific stuff, see bellow!

**:warning: Experimental :warning:**

This HMR implementation relies on Svelte's private & non documented API. This means that it could stop working with any new version of Svelte.

Pending official support, please report your HMR issues to [svelte-loader-hot's tracker](https://github.com/rixo/svelte-loader-hot/issues) (or in this template, if you feel that's more appropriate).

## Installation

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit rixo/svelte-template-webpack-hot svelte-app
cd svelte-app
npm install
```

Run the build script a first time, in order to avoid 404 errors about missing `bundle.css` in the browser:

```bash
npm run build
```

## Quick start

```bash
npm run dev
```

Navigate to http://localhost:8080. You should see your app running. Edit a component file in `src`, save it, and... Eyeball!

## Usage / Add it to your project

TODO
