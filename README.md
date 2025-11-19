# README

## Pear by Holepunch

> Pear loads applications remotely from peers and allows anyone to create and share applications with peers.

Pear by Holepunch is a combined Peer-to-Peer (P2P) Runtime, Development & Deployment tool.

Build, share & extend unstoppable, zero-infrastructure P2P applications for Desktop, Terminal & Mobile.

Welcome to the Internet of Peers

_– Holepunch, the P2P Company_

***

### Table of Contents

#### Guides

Step-by-step guides for building and deploying Pear applications.

* Getting Started
* Starting a Pear Desktop Project
* Making a Pear Desktop Application
* Starting a Pear Terminal Project
* Making a Pear Terminal Application
* Sharing a Pear Application
* Marking a Release
* Making a Bare Mobile Application
* Debugging a Pear Terminal Application
* Creating a Pear Init Template
* Best Practices

#### Runtime

Core runtime references and utilities.

* Command-Line Interface (CLI)
* Application Programming Interface (API)
* Configuration
* Migration
* Troubleshooting
* Frequently Asked Questions

> The Pear Runtime uses [Bare](https://github.com/holepunchto/bare), a small and modular JavaScript runtime for desktop and mobile. See the Bare Reference for more.

#### How-tos

Concise walkthroughs of essential peer-to-peer features.

* Connect Two Peers with HyperDHT
* Connect to Many Peers with Hyperswarm
* Replicate and Persist with Hypercore
* Manage Many Hypercores via Corestore
* Share Append-only Databases with Hyperbee
* Create a Full P2P Filesystem

#### Building Blocks

Fundamental primitives for powerful P2P applications.

| Name       | Description                                                        | Stability  |
| ---------- | ------------------------------------------------------------------ | ---------- |
| Hypercore  | Distributed, secure append-only log for scalable P2P applications. | **stable** |
| Hyperbee   | B-tree built on Hypercore for ordered key-value storage.           | **stable** |
| Hyperdrive | Real-time distributed file system.                                 | **stable** |
| Autobase   | Virtual Hypercore over many peer-owned cores.                      | **stable** |
| HyperDHT   | Peer-to-peer Distributed Hash Table.                               | **stable** |
| Hyperswarm | Topic-based peer discovery and connection layer.                   | **stable** |

#### Helpers

Utilities to enhance and simplify application building.

| Name             | Description                                            | Stability  |
| ---------------- | ------------------------------------------------------ | ---------- |
| Corestore        | Manages multiple Hypercores via factory.               | **stable** |
| Localdrive       | Filesystem interoperable with Hyperdrive.              | **stable** |
| Mirrordrive      | Mirrors drives across environments.                    | **stable** |
| Secretstream     | Secure peer-to-peer stream encryption.                 | **stable** |
| Compact-Encoding | Binary encoding for performance-focused serialization. | **stable** |
| Protomux         | Multiplex message protocols over one stream.           | **stable** |

#### Tools

CLI utilities for development and operations.

| Name       | Description                             | Stability  |
| ---------- | --------------------------------------- | ---------- |
| Hypershell | CLI for encrypted P2P shell sessions.   | **stable** |
| Hypertele  | Multipurpose proxy powered by DHT.      | **stable** |
| Hyperbeam  | Encrypted one-to-one internet pipe.     | **stable** |
| Hyperssh   | SSH over P2P using DHT.                 | **stable** |
| Drives     | CLI for managing Hyperdrive/Localdrive. | **stable** |

#### Apps

* Keet: Encrypted P2P video and chat platform.

#### Examples

* Bare on Mobile
* React App using Pear

***

### Stability Index

| Stability        | Description                                 |
| ---------------- | ------------------------------------------- |
| **stable**       | Actively maintained and used in production. |
| **experimental** | New or rapidly evolving.                    |
| **deprecated**   | Will be phased out or replaced.             |
| **unstable**     | May change or be removed without notice.    |
