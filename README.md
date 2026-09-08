# Kaspa Mining Suite 2.0 — package source

This repository is retained as the package source for **Kaspa Mining Suite
2.0**. It is no longer the canonical NoillioN Labs community app store.

Add the consolidated store URL under **App Store → Community App Stores** on
Umbrel:

https://github.com/NoillioN-Labs/umbrel-community-app-store

Open this community store and install or update **Kaspa Mining Suite 2.0** to **0.3.0**. This community preview opens without an additional in-app password prompt. The dedicated Kaspa node must synchronize before miners can connect.

Version 0.3.0 turns Analytics into a visual dashboard with a cumulative realised-reward graph, verified composition donut, colour-coded DAG resolution and block outcomes, a statistical mining-outlook gauge, an event timeline, and a compact recent-rewards view. The full evidence ledger remains available on demand. Unresolved and Red discoveries remain visible but are excluded from realised rewards.

UI: **5560** · miner Stratum: **55556** · node P2P: **16121**. Existing data directories and ports are retained. Both services use the same immutable multi-platform container image digest. Download a database backup before updating; this version upgrades the reward schema.

This is a development preview for Umbrel testing. Physical mining acceptance is still pending. Never enter wallet seeds or private keys.

The Kaspa icon is supplied unmodified from [Kaspa's official website](https://kaspa.org/icon.svg). Logo use follows the [official brand guidelines](https://kaspa.org/wp-content/uploads/2023/08/Kaspa-Brand-Guidelines-Final.pdf); the mark belongs to its respective rights holders.

Future package changes made here are copied into the consolidated store through
an exact deployment-file allowlist. Do not add credentials, personal data,
wallet information, production configuration, logs, diagnostics, or real user
data to this repository.
