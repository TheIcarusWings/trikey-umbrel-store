# Trikey Umbrel community app store

The [Umbrel](https://umbrel.com) community app store for **Trikey Guardian**: key 3 of a
[Trikey](https://github.com/TheIcarusWings/trikey) 2-of-3 bitcoin wallet, running on your own node.

> **Pre-alpha, not audited.** Use it on signet, testnet or regtest only. Don't use it with real funds.

## Install

1. On your Umbrel, open **App Store**, then the **⋯** menu, then **Community App Stores**.
2. Paste `https://github.com/TheIcarusWings/trikey-umbrel-store` and add it.
3. Open the **Trikey** store and install **Trikey Guardian**. It needs the **Bitcoin Node** and
   **Electrs** apps; Umbrel installs them if they are missing.

The app installs `v0.1.6-alpha`, pinned by digest.
Pre-alpha and not audited: on mainnet, use only an amount you can afford to lose.

## Where this comes from

This repository is generated from
[`packaging/umbrel/`](https://github.com/TheIcarusWings/trikey/tree/main/packaging/umbrel) in the
main repo. Each release copies it here with the image pinned by digest, so please send changes there.
The image is built reproducibly; see
[`packaging/VERIFY.md`](https://github.com/TheIcarusWings/trikey/blob/main/packaging/VERIFY.md) to
check it yourself.

## License

MIT, like Trikey.
