# Hydrogen

Hydrogen is a React framework and SDK that you can use to build fast and dynamic Shopify custom storefronts.

[Check out the docs](https://shopify.dev/custom-storefronts/hydrogen)

## Getting started

**Requirements:**

- Node.js version 16.5.0 or higher
- Yarn

```bash
yarn
yarn dev
```

## Building for production

```bash
yarn build
```

Then, you can run a local `server.js` using the production build with:

```bash
yarn serve
```

### Changing the `base` URL

If you'd like to change Vite's [public base path](https://vitejs.dev/guide/build.html#public-base-path), you may do so by setting the `VITE_BASE_URL` environment variable.

```bash
VITE_BASE_URL=https://my-cdn.example/ yarn build
```

You can check your `dist/client/index.html` to ensure that the URLs now point at the provided URL.
