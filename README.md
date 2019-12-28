# Svelte Template Hot

This is a copy of official [Svelte template for Webpack](https://github.com/sveltejs/template-webpack) with added HMR support.

This template aims to remain as close to the official template as possible. Please refer to official docs for general usage. For HMR specific stuff, see bellow!

**:warning: Experimental :warning:**

This HMR implementation relies on Svelte's private & non documented API. This means that it can stop working with any new version of Svelte.

Progress of Svelte HMR support can be tracked in [this issue](https://github.com/sveltejs/svelte/issues/3632).

**NOTE** The template pins the major version of Svelte, using the [tilde comparator](https://docs.npmjs.com/misc/semver#tilde-ranges-123-12-1) because, in practice, HMR breakages tend to only happen with new major versions of Svelte. In your app, you can change this to your liking -- because you might be more interested in last version of Svelte than working HMR, or be wise and pin the exact versions of all you dependencies.

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
