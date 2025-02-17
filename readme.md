# hattip-ws

A lightweight wrapper that helps you integrate `crossws` with [Hattip](https://github.com/hattipjs/hattip).

## Usage

Follow the instructions for your server:

- [Node.js](https://github.com/alloc/hattip-ws/tree/main/src/adapters/node)
- [Deno](https://github.com/alloc/hattip-ws/tree/main/src/adapters/deno)
- [Cloudflare Workers](https://github.com/alloc/hattip-ws/tree/main/src/adapters/cloudflare-workers)
- [Bun](https://github.com/alloc/hattip-ws/tree/main/src/adapters/bun)
- [UWS](https://github.com/alloc/hattip-ws/tree/main/src/adapters/uwebsockets)

## Framework Usage

If you're building a framework on top of Hattip, you may find the root entry point useful. It contains generalized types for the adapters, so developers can pass an “adapter factory” to the framework.

```ts
import type {
  WebSocketAdapterFactory,
  WebSocketAdapterOptions,
  WebSocketAdapter,
} from 'hattip-ws'
```
