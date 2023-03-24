---
title: Frostr
web: 
git: https://github.com/nickfarrow/frostr
tags:
- tool
platforms: 
progLang:
- Rust
license:
nips:
---

> Use frost to share a nostr account with friends
> 
> Use Flexible Round Optimized Schnorr Threshold (FROST) signatures to create a joint nostr account with your friends.
>
> FROST is a threshold multisignature (t-of-n), so to make a post/event you require t parties to individually sign and contribute signature shares. These signature shares are then combined into a single schnorr signature which is valid under the joint public key.
>
> Extremely unsafe and violently untested
>
> Please do not add this to any nostr client list.