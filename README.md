# Edgelord

Edgelord is a configurable router that runs as a Cloudflare worker.

## Development

To build the WASM module:

```shell
wasm-pack build
```

To preview the Worker (this will also continually rebuild the WASM module as changes are made):

```shell
wrangler preview --watch
```

To publish the Worker:

```shell
wrangler publish
```
