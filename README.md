# Repolex Knowledge Graph of certifi/python-certifi

RDF knowledge graph data for [certifi/python-certifi](https://github.com/certifi/python-certifi), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download certifi/python-certifi
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 015cba9d2492a4cddaf5efe40666c18a2b259c93.nq.gz
│   │   ├── 04f5882b59f1dc80b8019f6be767c95751502cd0.nq.gz
│   │   ├── 088f93122ea7c91cfdaeea7fa76ab2f850b8064d.nq.gz
│   │   ├── 10a1f8a56c9675fa87c42abad25183adbc3bc783.nq.gz
│   │   ├── 124f4adf171e15cd9a91a8b6e0325ecc97be8fe1.nq.gz
│   │   ├── 21abb9b9bbf4c0cfecf652fadafee3eb9615d553.nq.gz
│   │   ├── 258de09f05f0096432bfb751612bb7b6b68d9107.nq.gz
│   │   ├── 2669f7bdbdf4dd35fb739babfcbf197c687462b1.nq.gz
│   │   ├── 275c9eb55733a464589c15fb4566fddd4598e5b2.nq.gz
│   │   ├── 325c2fde4f8eec10d682b09f3b0414dc05e69a81.nq.gz
│   │   ├── 341e59d1fb3d526d3e7f2b63de3ffb7ba1d1d74b.nq.gz
│   │   ├── 38502797954603558ebf5f2c93f3645279e18158.nq.gz
│   │   ├── 401100fe95e8a807ab096e767b7d42fe86bdd1ee.nq.gz
│   │   ├── 45a64658872a94a83c4b70fce02a96f0f29895e6.nq.gz
│   │   ├── 45eb6113c0cff15293611eedf237f7345dcf24bd.nq.gz
│   │   ├── 4ba39005afa1958ee24af51a11b64299fba61025.nq.gz
│   │   ├── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   │   ├── 4f35e3529c78ced74040cf5d80bf8ec4aac9a190.nq.gz
│   │   ├── 515962b01a24501c912c26ccced7ef8b47f81553.nq.gz
│   │   ├── 6f0b77146602bde85c0225b3aea99d94b702a7e8.nq.gz
│   │   ├── 8110050d8441d363c8057d5ad187c8ad5a862fc2.nq.gz
│   │   ├── 84dc7666c2a09d5a428755b02eb7830c86bb9caa.nq.gz
│   │   ├── 8b3d7bae85bbc87c9181cc1d39548db3d31627f0.nq.gz
│   │   ├── 8be9f899232acbf9cf32822e861964dbb27e44ed.nq.gz
│   │   ├── 8eab47bb64c659749cd0295b2b47ef1ef9f586d0.nq.gz
│   │   ├── 8effc0d8fd3e14e3db1f04c915246b82bb8c6107.nq.gz
│   │   ├── 8fb96ed81f71e7097ed11bc4d9b19afd7ea5c909.nq.gz
│   │   ├── 9d514b4cad79357071c89d7dc4dc1b4df72bb997.nq.gz
│   │   ├── 9e9e840925d7b8e76c76fdac1fab7e6e88c1c3b8.nq.gz
│   │   ├── 9f9dc30f1d9e46b3ae6f9b29ee4d2e433010ff33.nq.gz
│   │   ├── b81bdb269f1edb791bcd4ec8a9d0c053758f961a.nq.gz
│   │   ├── b8595f24d2299af67057d5c66cf36e5de77628fc.nq.gz
│   │   ├── b9edccc6183cfb2f4e8bb04a920bcbb1e13f9fbe.nq.gz
│   │   ├── bd8153872e9c6fc98f4023df9c2deaffea2fa463.nq.gz
│   │   ├── bf1224e31f12c9bde8d83ac5c8d2c2360ad5640b.nq.gz
│   │   ├── e22525313129970e8b8623fca8c9ab7137dc2e8f.nq.gz
│   │   ├── e62c737f2e89f04e49ab21f551c1725dd6b75e31.nq.gz
│   │   ├── e71328216bff7cb51c8682b092316e7aab132f1b.nq.gz
│   │   ├── f3bb7957567af5b278de5fe043e571c93cf14eb4.nq.gz
│   │   └── f7e30d82841ef508158da706b7743b2d34018fb1.nq.gz
│   ├── dataflow
│   │   ├── 015cba9d2492a4cddaf5efe40666c18a2b259c93.nq.gz
│   │   ├── 04f5882b59f1dc80b8019f6be767c95751502cd0.nq.gz
│   │   ├── 088f93122ea7c91cfdaeea7fa76ab2f850b8064d.nq.gz
│   │   ├── 10a1f8a56c9675fa87c42abad25183adbc3bc783.nq.gz
│   │   ├── 124f4adf171e15cd9a91a8b6e0325ecc97be8fe1.nq.gz
│   │   ├── 21abb9b9bbf4c0cfecf652fadafee3eb9615d553.nq.gz
│   │   ├── 258de09f05f0096432bfb751612bb7b6b68d9107.nq.gz
│   │   ├── 2669f7bdbdf4dd35fb739babfcbf197c687462b1.nq.gz
│   │   ├── 275c9eb55733a464589c15fb4566fddd4598e5b2.nq.gz
│   │   ├── 325c2fde4f8eec10d682b09f3b0414dc05e69a81.nq.gz
│   │   ├── 341e59d1fb3d526d3e7f2b63de3ffb7ba1d1d74b.nq.gz
│   │   ├── 38502797954603558ebf5f2c93f3645279e18158.nq.gz
│   │   ├── 401100fe95e8a807ab096e767b7d42fe86bdd1ee.nq.gz
│   │   ├── 45a64658872a94a83c4b70fce02a96f0f29895e6.nq.gz
│   │   ├── 45eb6113c0cff15293611eedf237f7345dcf24bd.nq.gz
│   │   ├── 4ba39005afa1958ee24af51a11b64299fba61025.nq.gz
│   │   ├── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   │   ├── 4f35e3529c78ced74040cf5d80bf8ec4aac9a190.nq.gz
│   │   ├── 515962b01a24501c912c26ccced7ef8b47f81553.nq.gz
│   │   ├── 6f0b77146602bde85c0225b3aea99d94b702a7e8.nq.gz
│   │   ├── 8110050d8441d363c8057d5ad187c8ad5a862fc2.nq.gz
│   │   ├── 84dc7666c2a09d5a428755b02eb7830c86bb9caa.nq.gz
│   │   ├── 8b3d7bae85bbc87c9181cc1d39548db3d31627f0.nq.gz
│   │   ├── 8be9f899232acbf9cf32822e861964dbb27e44ed.nq.gz
│   │   ├── 8eab47bb64c659749cd0295b2b47ef1ef9f586d0.nq.gz
│   │   ├── 8effc0d8fd3e14e3db1f04c915246b82bb8c6107.nq.gz
│   │   ├── 8fb96ed81f71e7097ed11bc4d9b19afd7ea5c909.nq.gz
│   │   ├── 9d514b4cad79357071c89d7dc4dc1b4df72bb997.nq.gz
│   │   ├── 9e9e840925d7b8e76c76fdac1fab7e6e88c1c3b8.nq.gz
│   │   ├── 9f9dc30f1d9e46b3ae6f9b29ee4d2e433010ff33.nq.gz
│   │   ├── b81bdb269f1edb791bcd4ec8a9d0c053758f961a.nq.gz
│   │   ├── b8595f24d2299af67057d5c66cf36e5de77628fc.nq.gz
│   │   ├── b9edccc6183cfb2f4e8bb04a920bcbb1e13f9fbe.nq.gz
│   │   ├── bd8153872e9c6fc98f4023df9c2deaffea2fa463.nq.gz
│   │   ├── bf1224e31f12c9bde8d83ac5c8d2c2360ad5640b.nq.gz
│   │   ├── e22525313129970e8b8623fca8c9ab7137dc2e8f.nq.gz
│   │   ├── e62c737f2e89f04e49ab21f551c1725dd6b75e31.nq.gz
│   │   ├── e71328216bff7cb51c8682b092316e7aab132f1b.nq.gz
│   │   ├── f3bb7957567af5b278de5fe043e571c93cf14eb4.nq.gz
│   │   └── f7e30d82841ef508158da706b7743b2d34018fb1.nq.gz
│   ├── lsp
│   │   ├── 015cba9d2492a4cddaf5efe40666c18a2b259c93.nq.gz
│   │   ├── 04f5882b59f1dc80b8019f6be767c95751502cd0.nq.gz
│   │   ├── 088f93122ea7c91cfdaeea7fa76ab2f850b8064d.nq.gz
│   │   ├── 10a1f8a56c9675fa87c42abad25183adbc3bc783.nq.gz
│   │   ├── 124f4adf171e15cd9a91a8b6e0325ecc97be8fe1.nq.gz
│   │   ├── 21abb9b9bbf4c0cfecf652fadafee3eb9615d553.nq.gz
│   │   ├── 258de09f05f0096432bfb751612bb7b6b68d9107.nq.gz
│   │   ├── 2669f7bdbdf4dd35fb739babfcbf197c687462b1.nq.gz
│   │   ├── 275c9eb55733a464589c15fb4566fddd4598e5b2.nq.gz
│   │   ├── 325c2fde4f8eec10d682b09f3b0414dc05e69a81.nq.gz
│   │   ├── 341e59d1fb3d526d3e7f2b63de3ffb7ba1d1d74b.nq.gz
│   │   ├── 38502797954603558ebf5f2c93f3645279e18158.nq.gz
│   │   ├── 401100fe95e8a807ab096e767b7d42fe86bdd1ee.nq.gz
│   │   ├── 45a64658872a94a83c4b70fce02a96f0f29895e6.nq.gz
│   │   ├── 45eb6113c0cff15293611eedf237f7345dcf24bd.nq.gz
│   │   ├── 4ba39005afa1958ee24af51a11b64299fba61025.nq.gz
│   │   ├── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   │   ├── 4f35e3529c78ced74040cf5d80bf8ec4aac9a190.nq.gz
│   │   ├── 515962b01a24501c912c26ccced7ef8b47f81553.nq.gz
│   │   ├── 6f0b77146602bde85c0225b3aea99d94b702a7e8.nq.gz
│   │   ├── 8110050d8441d363c8057d5ad187c8ad5a862fc2.nq.gz
│   │   ├── 84dc7666c2a09d5a428755b02eb7830c86bb9caa.nq.gz
│   │   ├── 8b3d7bae85bbc87c9181cc1d39548db3d31627f0.nq.gz
│   │   ├── 8be9f899232acbf9cf32822e861964dbb27e44ed.nq.gz
│   │   ├── 8eab47bb64c659749cd0295b2b47ef1ef9f586d0.nq.gz
│   │   ├── 8effc0d8fd3e14e3db1f04c915246b82bb8c6107.nq.gz
│   │   ├── 8fb96ed81f71e7097ed11bc4d9b19afd7ea5c909.nq.gz
│   │   ├── 9d514b4cad79357071c89d7dc4dc1b4df72bb997.nq.gz
│   │   ├── 9e9e840925d7b8e76c76fdac1fab7e6e88c1c3b8.nq.gz
│   │   ├── 9f9dc30f1d9e46b3ae6f9b29ee4d2e433010ff33.nq.gz
│   │   ├── b81bdb269f1edb791bcd4ec8a9d0c053758f961a.nq.gz
│   │   ├── b8595f24d2299af67057d5c66cf36e5de77628fc.nq.gz
│   │   ├── b9edccc6183cfb2f4e8bb04a920bcbb1e13f9fbe.nq.gz
│   │   ├── bd8153872e9c6fc98f4023df9c2deaffea2fa463.nq.gz
│   │   ├── bf1224e31f12c9bde8d83ac5c8d2c2360ad5640b.nq.gz
│   │   ├── e22525313129970e8b8623fca8c9ab7137dc2e8f.nq.gz
│   │   ├── e62c737f2e89f04e49ab21f551c1725dd6b75e31.nq.gz
│   │   ├── e71328216bff7cb51c8682b092316e7aab132f1b.nq.gz
│   │   ├── f3bb7957567af5b278de5fe043e571c93cf14eb4.nq.gz
│   │   └── f7e30d82841ef508158da706b7743b2d34018fb1.nq.gz
│   └── repolex
│       ├── 015cba9d2492a4cddaf5efe40666c18a2b259c93.nq.gz
│       ├── 04f5882b59f1dc80b8019f6be767c95751502cd0.nq.gz
│       ├── 088f93122ea7c91cfdaeea7fa76ab2f850b8064d.nq.gz
│       ├── 10a1f8a56c9675fa87c42abad25183adbc3bc783.nq.gz
│       ├── 124f4adf171e15cd9a91a8b6e0325ecc97be8fe1.nq.gz
│       ├── 21abb9b9bbf4c0cfecf652fadafee3eb9615d553.nq.gz
│       ├── 258de09f05f0096432bfb751612bb7b6b68d9107.nq.gz
│       ├── 2669f7bdbdf4dd35fb739babfcbf197c687462b1.nq.gz
│       ├── 275c9eb55733a464589c15fb4566fddd4598e5b2.nq.gz
│       ├── 325c2fde4f8eec10d682b09f3b0414dc05e69a81.nq.gz
│       ├── 341e59d1fb3d526d3e7f2b63de3ffb7ba1d1d74b.nq.gz
│       ├── 38502797954603558ebf5f2c93f3645279e18158.nq.gz
│       ├── 401100fe95e8a807ab096e767b7d42fe86bdd1ee.nq.gz
│       ├── 45a64658872a94a83c4b70fce02a96f0f29895e6.nq.gz
│       ├── 45eb6113c0cff15293611eedf237f7345dcf24bd.nq.gz
│       ├── 4ba39005afa1958ee24af51a11b64299fba61025.nq.gz
│       ├── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│       ├── 4f35e3529c78ced74040cf5d80bf8ec4aac9a190.nq.gz
│       ├── 515962b01a24501c912c26ccced7ef8b47f81553.nq.gz
│       ├── 6f0b77146602bde85c0225b3aea99d94b702a7e8.nq.gz
│       ├── 8110050d8441d363c8057d5ad187c8ad5a862fc2.nq.gz
│       ├── 84dc7666c2a09d5a428755b02eb7830c86bb9caa.nq.gz
│       ├── 8b3d7bae85bbc87c9181cc1d39548db3d31627f0.nq.gz
│       ├── 8be9f899232acbf9cf32822e861964dbb27e44ed.nq.gz
│       ├── 8eab47bb64c659749cd0295b2b47ef1ef9f586d0.nq.gz
│       ├── 8effc0d8fd3e14e3db1f04c915246b82bb8c6107.nq.gz
│       ├── 8fb96ed81f71e7097ed11bc4d9b19afd7ea5c909.nq.gz
│       ├── 9d514b4cad79357071c89d7dc4dc1b4df72bb997.nq.gz
│       ├── 9e9e840925d7b8e76c76fdac1fab7e6e88c1c3b8.nq.gz
│       ├── 9f9dc30f1d9e46b3ae6f9b29ee4d2e433010ff33.nq.gz
│       ├── b81bdb269f1edb791bcd4ec8a9d0c053758f961a.nq.gz
│       ├── b8595f24d2299af67057d5c66cf36e5de77628fc.nq.gz
│       ├── b9edccc6183cfb2f4e8bb04a920bcbb1e13f9fbe.nq.gz
│       ├── bd8153872e9c6fc98f4023df9c2deaffea2fa463.nq.gz
│       ├── bf1224e31f12c9bde8d83ac5c8d2c2360ad5640b.nq.gz
│       ├── e22525313129970e8b8623fca8c9ab7137dc2e8f.nq.gz
│       ├── e62c737f2e89f04e49ab21f551c1725dd6b75e31.nq.gz
│       ├── e71328216bff7cb51c8682b092316e7aab132f1b.nq.gz
│       ├── f3bb7957567af5b278de5fe043e571c93cf14eb4.nq.gz
│       └── f7e30d82841ef508158da706b7743b2d34018fb1.nq.gz
└── blob
    ├── 02123695d01e8b7776994129cff8b99f0dd85fcc.nq.gz
    ├── 031bd4b53043c099111faa7adfdab15f63569c11.nq.gz
    ├── 051d61af474225858ab2f7f76dafcc8fe94f9e38.nq.gz
    ├── 062a2e17b7959d64977a8be136992aad603263ab.nq.gz
    ├── 06d6150be3050066330ac9d5276cb53a8cb10989.nq.gz
    ├── 0a64774eabe6b51f6fec2eeaf9875fc0f5e668e6.nq.gz
    ├── 0a65d1a61bcd7052b043408788357cf7f55678ff.nq.gz
    ├── 0c2dbd4475d889566826951585579f33df12744d.nq.gz
    ├── 0c4963ef6050d85f50925ff2d0108ca50a1f232d.nq.gz
    ├── 0c9e0fc1447e98b7f63ae8c9eb552c2af7b83f45.nq.gz
    ├── 0d59a05630e7ff963947b2596194d12248a41863.nq.gz
    ├── 0fd855f46465b1ba48d8490c912196ce0590bfb3.nq.gz
    ├── 101ac98fa42d9eb4b27836e122cc81d495e33c21.nq.gz
    ├── 108f9d631a376e4e1057f9c11df3e95c3908eb62.nq.gz
    ├── 1717aebc5b9787ddee8807f1484dde4201e7b68d.nq.gz
    ├── 177082e0fb151364bf7ff5e801eadabf8734acfc.nq.gz
    ├── 17aaf900bdafc6e09392f741f0ee19ea228d651b.nq.gz
    ├── 17efb80afda14662bf7549ac780318b112aeb726.nq.gz
    ├── 182b5112a5a4542175505fd9513d45330909f26a.nq.gz
    ├── 1a9cec08d5f81d46ceac597d7e05b9143d40ac69.nq.gz
    ├── 1ac3f61c63b08c475f36ddcc00de31b5f26e5bbf.nq.gz
    ├── 1b6157d262b83de3ad916b12c3d518c2a018352e.nq.gz
    ├── 1ba5f7e306b64a521e40e13678e2cf4892583f47.nq.gz
    ├── 1c91f3ec932d465dece996df658b92880772a077.nq.gz
    ├── 1e53cecc167b1f0493f9485cf326848787400b68.nq.gz
    ├── 1f47154cde38dff79359526d068fc6eb4fabf780.nq.gz
    ├── 213e8215368965a8b0c81f190775d26e44991527.nq.gz
    ├── 2245a4d3939619042279447c42f8bd9f7410c78a.nq.gz
    ├── 2498174f6bc1aa8b89a327a0a9649f889c20f85f.nq.gz
    ├── 2541a69e807af821ecc8ed481631274714fdf631.nq.gz
    ├── 25be1608e7c9e8444f3ec86d2188df70d3e7e7ad.nq.gz
    ├── 2713f541c44982d22ed24d8d2bf10a0f40f2e0a6.nq.gz
    ├── 28c414bdc0480128a666dba4ff0df88bec5201ef.nq.gz
    ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
    ├── 2beb68997ff29e5147e0d278b80b0c51b386571b.nq.gz
    ├── 2c20c269f649bfa0a7339daf8aa05ca31c2d4186.nq.gz
    ├── 2c3ceb045e909997919e8a78bcb4eca58fc7a40b.nq.gz
    ├── 2cef691c5ab7c1cb8a45ea54c1f5bf50be595360.nq.gz
    ├── 2d02ea44c40b8e2e5c625a10573ae5b4ff7a6eae.nq.gz
    └── 2fa23f4b4f7e08a3acc756bd900b23b684a3a301.nq.gz

7 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[certifi/python-certifi](https://github.com/certifi/python-certifi)

---
*Parsed on 2026-03-18 by [repolex](https://repolex.ai)*
