---
title: http-NostrPublisher
web: 
git: https://github.com/getAlby/http-nostr-publisher
instances:
tags:
- tool
platforms:
- Linux
- Windows
license: 
progLang:
- JS
authorNPub: npub1xv8mzscll8vvy5rsdw7dcqtd2j268a6yupr6gzqh86f2ulhy9kkqmclk3x
---

> ## HTTP to Nostr Cloudflare worker
>
> This Cloudflare worker exposes a HTTP interface to publish events to specified Nostr relays. The HTTP request is non-blocking and will immediatelly return. The events will be published asynchronously.
>
> The goal of this worker is to make it easier to integrate publishing events into any application. Using this worker applications do not need to integrate websockets and can publish events through a non-blocking HTTP request.




