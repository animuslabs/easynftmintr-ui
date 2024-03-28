# Quasar App (meow-nfts-ui)

A Quasar Project

## Install the dependencies
```bash
yarn
# or
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```


### Lint the files
```bash
yarn lint
# or
npm run lint
```


### Format the files
```bash
yarn format
# or
npm run format
```



### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.config.js](https://v2.quasar.dev/quasar-cli-webpack/quasar-config-js).


# to change network
anchor.ts --> line no.6 --> const client = new APIClient({ url: endpoints[1][1] })

atomic.ts --> line no.50 --> const client = new APIClient({ url: endpoints[1][1] })
and collections change

config.ts --> change networks
