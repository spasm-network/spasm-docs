## Features

#### Support for different keys and protocols

Spasm currently supports the following private keys and messaging protocols:
- Ethereum-signed Spasm events
- Ethereum-signed DMP events
- Nostr-signed Nostr events
- Unsigned web2 posts (e.g., RSS items)

#### Supported networks

Spasm-powered forum DegenRocket supports the following networks:
- Spasm network
- Nostr network

#### Multi-signing

In 2024, Spasm V2 went live, enabling groundbreaking multi-signing, which allowed users to simultaneously sign the same message with multiple private keys using different protocols and broadcast the message to different networks.

For example, the post about Session vs SimpleX architectures was multi-signed on [monero.top](https://monero.top/news/spasmid010a70651fc27fb9125f7ea) with Ethereum and Nostr private keys and propagated to other Spasm instances like [degenrocket.space](https://degenrocket.space/news/spasmid010a70651fc27fb9125f7ea).

Since the article was pushed to Spasm and Nostr networks, you can also read it in your [native Nostr app](nostr:note1e94uvd0vx2k9mgdgnzzpqmdh0swkqmkhq6uy4c2g3pganxy96pvqlkvmsz). All native Nostr replies to this post will be shown on Spasm instances that enable the Nostr network in settings.

Multi-signed messages display multiple pubkeys so authors can take advantage of different ecosystems like unique usernames from blockchain-based Ethereum naming services and offchain social graph from Nostr.

#### Federation

Spasm instances are not syncing all the messages from all other instances. Instead, the system is very flexible so an admin of each instance can specify which messages should be synced from which instances at which time intervals. This approach helps preserve the freedom of association and solve scalability issues. It also helps against SPAM.

Think about Spasm-powered forums as subreddits. Some of them might share a lot of similar content, while others might have completely different content.
