<div align="center">

# FluxRPC

### The most performant Solana RPC.

High-performance infrastructure for teams building apps, trading systems,
indexers, bots, and data products on Solana.

[![Start free](https://img.shields.io/badge/Start_free-10GB_bandwidth-14F195?style=for-the-badge)](https://fluxrpc.com/free)
[![Read the docs](https://img.shields.io/badge/Read_the_docs-9945FF?style=for-the-badge)](https://fluxrpc.com/docs)
[![Developer guides](https://img.shields.io/badge/Developer_guides-Build_on_Solana-3B82F6?style=for-the-badge)](https://fluxrpc.com/docs/guides)
[![View pricing](https://img.shields.io/badge/View_pricing-171717?style=for-the-badge)](https://fluxrpc.com/pricing)

</div>

## Infrastructure that keeps up with Solana

FluxRPC gives developers fast, production-ready access to Solana without the
cost and operational overhead of running an RPC fleet.

- **Fast JSON-RPC** — read chain state, simulate transactions, and submit them
  through familiar Solana APIs.
- **Real-time WebSockets** — subscribe to accounts, logs, programs,
  transactions, slots, and blocks.
- **Yellowstone gRPC** — stream filtered, high-volume blockchain data with low
  latency.
- **Predictable pricing** — pay for bandwidth instead of translating every
  request into an opaque credit cost.
- **Built to scale** — start free, then grow from development traffic to
  production workloads on the same platform.

## Start building

Create an account, generate an API key, and make your first request:

```bash
curl --request POST \
  --url "https://eu.fluxrpc.com?key=YOUR_API_KEY" \
  --header "Content-Type: application/json" \
  --data '{
    "jsonrpc": "2.0",
    "id": 1,
    "method": "getBalance",
    "params": ["YOUR_WALLET_ADDRESS"]
  }'
```

## Hands-on Solana developer guides

Go beyond API definitions with detailed, practical walkthroughs. Start with
Solana's account model, learn how to make efficient RPC requests, then build
complete transaction flows for real applications.

### Learn Solana accounts and efficient RPC

| Guide | What you'll build and learn |
| --- | --- |
| **[Read a Solana account](https://fluxrpc.com/docs/guides/get-account-info)** | Use `getAccountInfo`, understand response fields and encodings, parse program data, and reduce bandwidth. |
| **[Batch account reads](https://fluxrpc.com/docs/guides/get-multiple-accounts)** | Use `getMultipleAccounts`, handle missing accounts safely, and cut response sizes with `dataSlice`. |
| **[Query a program's accounts](https://fluxrpc.com/docs/guides/get-program-accounts)** | Use `getProgramAccounts` with `dataSize`, `memcmp`, `changedSinceSlot`, and `dataSlice`. |
| **[Find a wallet's tokens](https://fluxrpc.com/docs/guides/get-token-accounts-by-owner)** | Use `getTokenAccountsByOwner`, decode balances, and check token risk with RugCheck. |
| **[Find a token's largest holders](https://fluxrpc.com/docs/guides/get-token-largest-accounts)** | Use `getTokenLargestAccounts` and compare raw RPC data with a full RugCheck token report. |

### Build real application flows

| Guide | What you'll build and learn |
| --- | --- |
| **[Display a wallet's SOL balance](https://fluxrpc.com/docs/guides/get-balance)** | Use `getBalance`, connect a browser wallet, and protect frontend credentials with Shield keys. |
| **[Analyze token risk in bulk](https://fluxrpc.com/docs/guides/bulk-token-summary)** | Use RugCheck's `bulkTokenSummary` to analyze up to 255 tokens and calculate a wallet-wide risk score. |
| **[Send a Solana transaction](https://fluxrpc.com/docs/guides/send-transaction)** | Build and sign a SOL transfer in the browser, then submit it with `sendTransaction`. |
| **[Confirm a transaction](https://fluxrpc.com/docs/guides/confirm-transaction-websocket)** | Use `signatureSubscribe` in a Web Worker, with an RPC fallback for reliability. |

**[Explore all developer guides →](https://fluxrpc.com/docs/guides)**

## Developer resources

| Resource | Link |
| --- | --- |
| **Account** | [Start free with 10GB of bandwidth](https://fluxrpc.com/free) |
| **Dashboard** | [Manage API keys and usage](https://fluxrpc.com/login) |
| **Getting started** | [Make your first FluxRPC request](https://fluxrpc.com/docs/getting-started) |
| **Developer guides** | [Follow hands-on Solana tutorials](https://fluxrpc.com/docs/guides) |
| **JSON-RPC** | [Browse the RPC method reference](https://fluxrpc.com/docs/rpc) |
| **WebSocket** | [Stream real-time events](https://fluxrpc.com/docs/websocket) |
| **Yellowstone gRPC** | [Set up high-throughput streaming](https://fluxrpc.com/docs/yellowstone) |
| **Pricing** | [Compare plans](https://fluxrpc.com/pricing) |
| **Support** | [Talk to the FluxRPC team](https://fluxrpc.com/contact) |

## More from FluxRPC

- [**Lantern**](https://fluxrpc.com/docs/lantern/introduction) — a self-hosted
  Solana RPC load balancer and failover layer with caching, health monitoring,
  WebSocket support, and Yellowstone gRPC support.
- [**RugCheck API**](https://fluxrpc.com/docs/rugcheck) — Solana token risk
  analysis and on-chain intelligence for applications and automated workflows.
- [**Fogo RPC**](https://fluxrpc.com/docs) — Solana-compatible HTTP,
  WebSocket, and Yellowstone gRPC infrastructure for Fogo.

---

<div align="center">

**Stop managing RPC infrastructure. Start shipping.**

[Website](https://fluxrpc.com) · [Start free](https://fluxrpc.com/free) ·
[Developer guides](https://fluxrpc.com/docs/guides) ·
[Documentation](https://fluxrpc.com/docs) · [Pricing](https://fluxrpc.com/pricing)

</div>
