# Tayyn Hyzmat

A delivery dispatch system for restaurants, flowers, and parcel orders in Aşgabat.

Dispatchers enter phone orders, eligible drivers receive short offers for their region, and the first valid claim wins. The driver app is distributed privately to pilot drivers. The system is designed for weak mobile connections and uses synthetic balances during the pilot. No payment provider is connected and no real money moves through the wallet.

## Stack

- Vue 3, Vite, strict TypeScript, and shadcn-vue
- Capacitor Android driver app
- Express, Prisma, PostgreSQL, and Socket.IO
- Docker and versioned database migrations

## Public source

This repository is a reviewed public source release. It contains product code, tests, architecture notes, and synthetic fixtures. Private operational material, deployment credentials, client documents, production exports, and monitoring configuration are kept outside this repository.

Start with [product scope](docs/product.md), [architecture](docs/architecture.md), and [testing](docs/testing.md).
