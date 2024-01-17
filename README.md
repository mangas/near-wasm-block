# Example NEAR Blocks Subgraph

An example to help you get started with NEAR indexing with The Graph. For more information see the
docs on https://thegraph.com/docs/supported-networks/near.

## Quick Start

Have `pnpm` available globally, then:

```
pnpm install
pnpm run codegen
pnpm run build

# Deploy to a local `graph-node` instance
pnpm run create-local
pnpm run deploy-local

# Or deploy to a The Graph network
pnpm run create
pnpm run deploy
```