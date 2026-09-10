# Kaspa Mining Suite 2.0 — package source

This repository is retained as the package source for **Kaspa Mining Suite
2.0**. It is no longer the canonical NoillioN Labs community app store.

Add the consolidated store URL under **App Store → Community App Stores** on
Umbrel:

https://github.com/NoillioN-Labs/umbrel-community-app-store

Open this community store and install or update **Kaspa Mining Suite 2.0** to **0.4.0**. This community preview opens without an additional in-app password prompt. The dedicated Kaspa node must synchronize before miners can connect.

Version 0.4.0 keeps the live Overview updating when its event stream or an individual API response is malformed, adds independent recovery polling, and reports clear component health for the node, bridge, and application. It highlights the key hashrate and synchronization metrics, adds the previous-day block comparison, improves the block celebration wording, and adds the validated support-development panel used by the companion solo-mining app. The Umbrel credentials prompt remains disabled while password protection is disabled.

UI: **5560** · miner Stratum: **55556** · node P2P: **16121**. Existing data directories, ports, Analytics dashboard, and reward schema are retained. Both services use the same immutable multi-platform container image digest.

This is a development preview for Umbrel testing. Physical mining acceptance is still pending. Never enter wallet seeds or private keys.

The Kaspa icon is supplied unmodified from [Kaspa's official website](https://kaspa.org/icon.svg). Logo use follows the [official brand guidelines](https://kaspa.org/wp-content/uploads/2023/08/Kaspa-Brand-Guidelines-Final.pdf); the mark belongs to its respective rights holders.

Future package changes made here are copied into the consolidated store through
an exact deployment-file allowlist. Do not add credentials, personal data,
wallet information, production configuration, logs, diagnostics, or real user
data to this repository.
