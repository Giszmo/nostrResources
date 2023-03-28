---
title: blastr
web: 
git: https://github.com/MutinyWallet/blastr
instances:
tags:
- tool
platforms:
- Linux
- Windows 
- macOS
license: MIT
progLang:
- Rust
authorNPub: npub1u8lnhlw5usp3t9vmpz60ejpyt649z33hu82wc2hpv6m5xdqmuxhs46turz 
---

> ## A nostr cloudflare workers proxy relay that publishes to all known online relays.
>
> This takes advantage of the high availabilty of cloudflare serverless workers on the edge that are rust wasm-based with 0ms cold starts. Learn more about cloudflare workers.
>
> This is write only for now and is compatible with nostr clients but also features a simple POST api endpoint at /event. All events get queued up to run in batches by another worker that spins up every 30s if there's any events lined up, or once a certain amount of events are queued up.
>
> This will help ensure that your events are broadcasted to as many places as possible.