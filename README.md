# Pear by Holepunch

Pear by Holepunch is a combined Peer-to-Peer (P2P) Runtime, Development & Deployment tool.

Build, share & extend unstoppable, zero-infrastructure P2P applications for Desktop, Terminal & Mobile.

Welcome to the Internet of Peers

_– Holepunch, the P2P Company_

***

### Table of Contents

#### Guides

Step-by-step guides for building and deploying Pear applications.

* [Getting Started](tutorials/getting-started.md)
* [Starting a Pear Desktop Project](tutorials/advanced/desktop-project.md)
* [Making a Pear Desktop Application](tutorials/advanced/desktop-app.md)
* [Starting a Pear Terminal Project](tutorials/advanced/terminal-project.md)
* [Making a Pear Terminal Application](tutorials/advanced/terminal-app.md)
* [Sharing a Pear Application](tutorials/advanced/share-app.md)
* [Marking a Release](tutorials/advanced/mark-release.md)
* [Making a Bare Mobile Application](tutorials/advanced/bare-mobile-app.md)
* [Debugging a Pear Terminal Application](tutorials/advanced/debug-terminal.md)
* [Creating a Pear Init Template](tutorials/advanced/init-template.md)
* [Best Practices](tutorials/advanced/best-practices.md)

#### Runtime

Core runtime references and utilities.

* [Command-Line Interface (CLI)](reference/command-line-interface-cli.md)
* [Application Programming Interface (API)](reference/application-programming-interface-api.md)
* [Configuration](reference/application-configuration.md)
* [Migration](reference/migration.md)
* [Troubleshooting](how-to/troubleshooting.md)
* [Frequently Asked Questions](explanation/frequently-asked-questions.md)

#### How-tos

Concise walkthroughs of essential peer-to-peer features.

* [Connect Two Peers with HyperDHT](how-to/connect-two-peers.md)
* [Connect to Many Peers with Hyperswarm](how-to/connect-many-peers.md)
* [Replicate and Persist with Hypercore](how-to/replicate-and-persist.md)
* [Manage Many Hypercores via Corestore](how-to/manage-multiple-hypercores.md)
* [Share Append-only Databases with Hyperbee](how-to/share-append-only-databases.md)
* [Create a Full P2P Filesystem](how-to/create-a-p2p-filesystem.md)

#### Building Blocks

Fundamental primitives for powerful P2P applications.

| Name                                                    | Description                                                        | Stability  |
| ------------------------------------------------------- | ------------------------------------------------------------------ | ---------- |
| [Hypercore](explanation/building-blocks/hypercore.md)   | Distributed, secure append-only log for scalable P2P applications. | **stable** |
| [Hyperbee](explanation/building-blocks/hyperbee.md)     | B-tree built on Hypercore for ordered key-value storage.           | **stable** |
| [Hyperdrive](explanation/building-blocks/hyperdrive.md) | Real-time distributed file system.                                 | **stable** |
| [Autobase](explanation/building-blocks/autobase.md)     | Virtual Hypercore over many peer-owned cores.                      | **stable** |
| [HyperDHT](explanation/building-blocks/hyperdht.md)     | Peer-to-peer Distributed Hash Table.                               | **stable** |
| [Hyperswarm](explanation/building-blocks/hyperswarm.md) | Topic-based peer discovery and connection layer.                   | **stable** |

#### Helpers

Utilities to enhance and simplify application building.

| Name                                                      | Description                                            | Stability  |
| --------------------------------------------------------- | ------------------------------------------------------ | ---------- |
| [Corestore](ecosystem/helpers/corestore.md)               | Manages multiple Hypercores via factory.               | **stable** |
| [Localdrive](ecosystem/helpers/localdrive.md)             | Filesystem interoperable with Hyperdrive.              | **stable** |
| [Mirrordrive](ecosystem/helpers/mirrordrive.md)           | Mirrors drives across environments.                    | **stable** |
| [Secretstream](ecosystem/helpers/secretstream.md)         | Secure peer-to-peer stream encryption.                 | **stable** |
| [Compact-Encoding](ecosystem/helpers/compact-encoding.md) | Binary encoding for performance-focused serialization. | **stable** |
| [Protomux](ecosystem/helpers/protomux.md)                 | Multiplex message protocols over one stream.           | **stable** |

#### Tools

CLI utilities for development and operations.

| Name                                        | Description                             | Stability  |
| ------------------------------------------- | --------------------------------------- | ---------- |
| [Hypershell](ecosystem/tools/hypershell.md) | CLI for encrypted P2P shell sessions.   | **stable** |
| [Hypertele](ecosystem/tools/hypertele.md)   | Multipurpose proxy powered by DHT.      | **stable** |
| [Hyperbeam](ecosystem/tools/hyperbeam.md)   | Encrypted one-to-one internet pipe.     | **stable** |
| [Hyperssh](ecosystem/tools/hyperssh.md)     | SSH over P2P using DHT.                 | **stable** |
| [Drives](ecosystem/tools/drives.md)         | CLI for managing Hyperdrive/Localdrive. | **stable** |

#### Apps

* [Keet: Encrypted P2P video and chat platform.](ecosystem/real-apps/keet.md)

#### Examples

* [Bare on Mobile](ecosystem/examples/mobile-bare.md)
* [React App using Pear](ecosystem/examples/react-app.md)

***

### Stability Index

| Stability        | Description                                 |
| ---------------- | ------------------------------------------- |
| **stable**       | Actively maintained and used in production. |
| **experimental** | New or rapidly evolving.                    |
| **deprecated**   | Will be phased out or replaced.             |
| **unstable**     | May change or be removed without notice.    |
