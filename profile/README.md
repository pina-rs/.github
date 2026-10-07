# Pina

Rust libraries and tools for building on Solana, from on-chain programs to browser clients and wallet connections.

The main framework, [Pina](https://github.com/pina-rs/pina), is built on [Pinocchio](https://github.com/anza-xyz/pinocchio). It provides account validation, zero-copy data access, macros, and tools for building and testing programs.

## Repositories

| Repository                                                    | What it does                                                                                                                                                                                        |
| ------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [pina](https://github.com/pina-rs/pina)                       | The on-chain framework, CLI, client generators, security lints, and program examples.                                                                                                               |
| [pinapod](https://github.com/pina-rs/pinapod)                 | Validated, zero-copy types for account and instruction data. Supports fixed and compact layouts in `no_std` programs. A Pina-maintained fork of [ZeroPod](https://github.com/blueshift-gg/zeropod). |
| [wasm_solana](https://github.com/pina-rs/wasm_solana)         | A Rust Solana RPC client for WebAssembly, with an in-memory test wallet, testing utilities, and browser examples.                                                                                   |
| [wallet_standard](https://github.com/pina-rs/wallet_standard) | Rust implementations of the Solana Wallet Standard, including browser wallet discovery, connection, and signing.                                                                                    |
| [lootbox](https://github.com/pina-rs/lootbox)                 | A random-reward program built with Pina. Includes funded prize bundles, generated clients, and a local web playground.                                                                              |

## Where to start

- **Write a program:** read the [Pina Book](https://pina-rs.github.io/pina/) and work through the [examples](https://github.com/pina-rs/pina/tree/main/examples).
- **Define account data:** see the [PinaPod guide](https://pina-rs.github.io/pinapod/).
- **Build a Rust browser app:** start with the [WebAssembly examples](https://github.com/pina-rs/wasm_solana/tree/main/examples) and [Wallet Standard documentation](https://pina-rs.github.io/wallet_standard/).
- **See Pina used in a project:** explore [Lootbox](https://github.com/pina-rs/lootbox).

Pina is still hardening, and Lootbox is experimental. Read each project's release status and security notes before using it with real funds.

For bugs and feature requests, open an issue in the relevant repository. Report security issues using that repository's security policy; Pina's is [here](https://github.com/pina-rs/pina/blob/main/SECURITY.md).

This organisation profile is maintained in [`.github`](https://github.com/pina-rs/.github).
