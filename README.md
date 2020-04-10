
## How to Contribute

### Get the code

Requires [Yarn](https://yarnpkg.com) for monorepo workspaces.

```
git clone https://github.com/samuelmaddock/metastream.git
cd metastream
yarn
```

### Start the dev server

Creates a development web server accessible from [http://localhost:8080](http://localhost:8080)

```
cd packages/metastream-signal-server
yarn build
cd ../packages/metastream-app
yarn start
```

### Build the web app

Produces the web app build which gets deployed to [https://app.getmetastream.com](https://app.getmetastream.com)

```
cd packages/metastream-app
yarn build
```

