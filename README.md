# Quasar App with Pug (quasar-pug)

A template for Quasar App development with Pug enabled

## Install Quasar CLI
Do not use any Node version higher than 14+. Webpack 4 does not support any
Node version higher than this and we cannot move to Webpack 5 without making breaking changes.
However, we will support Webpack 5 in a future release.
Do not use uneven versions of Node i.e. 13, 15, etc.
These versions are not tested with Quasar and often cause issues due to their experimental nature.
We highly recommend always using the LTS version of Node.

```bash
yarn global add @quasar/cli
```
or
```bash
npm install -g @quasar/cli
```
If you are using Yarn, make sure that the Yarn global install location is in your PATH:

in ~/.bashrc or equivalent
```bash
export PATH="$(yarn global bin):$PATH"
```

## Install the dependencies
```bash
yarn
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

### Lint the files
```bash
yarn run lint
```

### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).
