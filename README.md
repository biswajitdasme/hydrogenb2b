# Hydrogen App

[Live Link](https://hydrogenb2b.herokuapp.com/)

Hydrogen is a React framework and SDK that you can use to build fast and dynamic Shopify custom storefronts.

[Check out the docs](https://shopify.dev/custom-storefronts/hydrogen)

## Getting started

**Requirements:**

- Node v14+
- Yarn

```bash
yarn
yarn dev
```

Remember to update `shopify.config.js` with your shop's domain and Storefront API token!

## Previewing a production build

To run a local preview of your Hydrogen app in an environment similar to Oxygen, build your Hydrogen app and then run `yarn preview`:

```bash
yarn build
yarn preview
```

## Building for production

```bash
yarn build
```

Then, you can run a local `server.js` using the production build with:

```bash
yarn serve
```
