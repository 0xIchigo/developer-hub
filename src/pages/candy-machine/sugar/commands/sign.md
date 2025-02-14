---
title: sign
metaTitle: Candy Machine - Sugar - sign
description: sign command.
---

The `sign` command allows signing all NFTs with a creator's keypair, to verify that creator in the creators array in the NFT metadata. Each creator can only sign for themself and only one creator can sign at a time with this command. The creator's keypair can be passed in with the `--keypair` option, otherwise it defaults to using default keypair specified in your Solana CLI config.

Running the command with the default keypair:

```
sugar sign
```

And running with a specific keypair:

```
sugar sign -k creator-keypair.json
```