# <img src="https://fireproof.storage/static/img/flame.svg" alt="Fireproof logo" width="25"> Fireproof

Live data the easy way. **Write features first, access your data anywhere.** Fireproof is a realtime document ledger that adds collaboration to any app with zero configuration.

## Quick Start

```js
import { fireproof } from "@fireproof/core";
const db = fireproof("my-app");
await db.put({ _id: "first", hello: "world" });
```

📚 [Read the Docs](https://use-fireproof.com/docs) | 🚀 [React Tutorial](https://use-fireproof.com/docs/react-tutorial) | 💬 [Join Discord](https://discord.gg/cCryrNHePH)

## Why Fireproof?

- **Network aware** - encrypted and multi-writer safe
- **Real-time collaboration** - built on CRDTs
- **Web-native** - small package size, no WASM
- **Zero config** - write features first, add sync later

## Featured Projects

- [Core Ledger](https://github.com/fireproof-storage/fireproof) - The main database engine
- [React Hooks](https://github.com/fireproof-storage/fireproof/tree/main/packages/react) - Live data hooks for React
- [Connect](https://github.com/fireproof-storage/fireproof/tree/main/packages/connect) - Real-time sync between browsers and backends
- [Examples](https://github.com/fireproof-storage/fireproof/tree/main/examples) - Sample apps and integrations

## Latest Updates

- 📝 [Blog](https://fireproof.storage/blog/)
- 🗺️ [Roadmap](https://use-fireproof.com/docs/architecture)
- 📦 [NPM Packages](https://www.npmjs.com/org/fireproof)

## License

Dual-licensed under [MIT or Apache 2.0](https://github.com/fireproof-storage/fireproof/blob/main/LICENSE.md)
