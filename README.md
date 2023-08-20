# Test of nuxt running on cloudflare module workers with lazy loaded chunks

___

Nitropack code from [nitro#1172](https://github.com/unjs/nitro/pull/1172)

Wrangler code (prerelease) from [wrangler#3726](https://github.com/cloudflare/workers-sdk/pull/3726)

___

## Instructions

```sh
$ npm i
```

then
```sh
$ npm run worker:dev
```
to locally run the worker

and
```sh
$ npm run worker:deploy
```
to deploy it

The above should just work since I have committed the `.output` directory

to rebuild the directory/worker code:
```sh
$ npm run build
```