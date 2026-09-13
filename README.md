# Kaspa Mining Suite 2.0 — package source

This repository is retained as the package source for **Kaspa Mining Suite
2.0**. It is no longer the canonical NoillioN Labs community app store.

Add the consolidated store URL under **App Store → Community App Stores** on
Umbrel:

https://github.com/NoillioN-Labs/umbrel-community-app-store

Open this community store and install or update **Kaspa Mining Suite 2.0** to **0.6.0**. This community preview opens without an additional in-app password prompt. The dedicated Kaspa node must synchronize before miners can connect.

Version 0.6.0 adds connected-peer direction states, inline IBD identification, inbound/outbound peer composition, and guidance for supporting the Kaspa network. Reward composition history now plots the exact components of each verified discovered block instead of empty time intervals, and the mobile hashrate graph keeps its range labels and plot readable. Version 0.5.0 ledger retention, effort tracking, worker timing, optional celebrations, resilient live data, component health, and support-development features are retained.

UI: **5560** · miner Stratum: **55556** · node P2P: **16121**. Existing data directories and ports are retained. Both services use the same immutable AMD64 and ARM64 container image digest.

This is a development preview for Umbrel testing. Physical mining acceptance is still pending. Never enter wallet seeds or private keys.

The Kaspa icon is supplied unmodified from [Kaspa's official website](https://kaspa.org/icon.svg). Logo use follows the [official brand guidelines](https://kaspa.org/wp-content/uploads/2023/08/Kaspa-Brand-Guidelines-Final.pdf); the mark belongs to its respective rights holders.

Future package changes made here are copied into the consolidated store through
an exact deployment-file allowlist. Do not add credentials, personal data,
wallet information, production configuration, logs, diagnostics, or real user
data to this repository.
