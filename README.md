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
│   │   ├── 04f5882b59f1dc80b8019f6be767c95751502cd0.nq.gz
│   │   ├── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   │   ├── b9edccc6183cfb2f4e8bb04a920bcbb1e13f9fbe.nq.gz
│   │   └── e62c737f2e89f04e49ab21f551c1725dd6b75e31.nq.gz
│   ├── dataflow
│   │   ├── 04f5882b59f1dc80b8019f6be767c95751502cd0.nq.gz
│   │   ├── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   │   ├── b9edccc6183cfb2f4e8bb04a920bcbb1e13f9fbe.nq.gz
│   │   └── e62c737f2e89f04e49ab21f551c1725dd6b75e31.nq.gz
│   ├── lsp
│   │   ├── 04f5882b59f1dc80b8019f6be767c95751502cd0.nq.gz
│   │   ├── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   │   ├── b9edccc6183cfb2f4e8bb04a920bcbb1e13f9fbe.nq.gz
│   │   └── e62c737f2e89f04e49ab21f551c1725dd6b75e31.nq.gz
│   └── repolex
│       ├── 04f5882b59f1dc80b8019f6be767c95751502cd0.nq.gz
│       ├── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│       ├── b9edccc6183cfb2f4e8bb04a920bcbb1e13f9fbe.nq.gz
│       └── e62c737f2e89f04e49ab21f551c1725dd6b75e31.nq.gz
├── blob
│   ├── 031bd4b53043c099111faa7adfdab15f63569c11.nq.gz
│   ├── 051d61af474225858ab2f7f76dafcc8fe94f9e38.nq.gz
│   ├── 062a2e17b7959d64977a8be136992aad603263ab.nq.gz
│   ├── 06d6150be3050066330ac9d5276cb53a8cb10989.nq.gz
│   ├── 1ac3f61c63b08c475f36ddcc00de31b5f26e5bbf.nq.gz
│   ├── 2245a4d3939619042279447c42f8bd9f7410c78a.nq.gz
│   ├── 28c414bdc0480128a666dba4ff0df88bec5201ef.nq.gz
│   ├── 2c3ceb045e909997919e8a78bcb4eca58fc7a40b.nq.gz
│   ├── 31ecdfb0b4b73faf5a47ab10c8debd1c51b503c7.nq.gz
│   ├── 3346ab5caed9219a4b75d579f9258da9baccbb5b.nq.gz
│   ├── 33eb736c3a393919224df66e26f44febdc14fa62.nq.gz
│   ├── 551eb9776721762bccab0f040ebe9daaaca47984.nq.gz
│   ├── 5de8fc8ba45321a54ff116a2e98d9b01c2fc705f.nq.gz
│   ├── 5e4090017a9bec5de60a745d17007a9e95f31a43.nq.gz
│   ├── 5f1da0dd0c201e8aedc1552ef82a1780eb37276d.nq.gz
│   ├── 6077b5ff84d2f31c8b6972126a788155c41ed20e.nq.gz
│   ├── 632115883cd20c931a1345c3a9457b90d8ac564a.nq.gz
│   ├── 672fb1febf492bbf60d6d5cfabda56a2cf33067e.nq.gz
│   ├── 802b53ff11e347c9bd2cabebeff5c51f716f1db9.nq.gz
│   ├── 853c08c29a1b23c67c2df03c7236f1816914095a.nq.gz
│   ├── 98018904db4563e77c5e8a8063d9050d0bacd7d1.nq.gz
│   ├── 9bf9b0e69ac010437062a4d6388804a7360eac77.nq.gz
│   ├── a4c80fe03675d60bf68f607b8866ca17c36249e0.nq.gz
│   ├── a6a027f7e0d3735e1b5ed37ac87190e53f597f5f.nq.gz
│   ├── b1822292325605201a54b82c29ca5795d83860b5.nq.gz
│   ├── c6de76ca551261ee39c16618767731d13c9d468b.nq.gz
│   ├── dca94c990184624da1816e2cb8bf31aa2b185da0.nq.gz
│   ├── dcdfdbf83f4feae6d870cfb5652d3dfa93ea11c0.nq.gz
│   ├── df8e152c322144804a7be96054729a9918753f5e.nq.gz
│   ├── dfa23ce2799730774589fff52e3ca80b1df993bc.nq.gz
│   ├── e7ae2eea127b4d868276ce742f665cb692f41e86.nq.gz
│   └── f8a9fe3106a1ac99e8799cf5d19509c4cf48deb6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   ├── 04f5882b59f1dc80b8019f6be767c95751502cd0.nq.gz
│   ├── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   ├── b9edccc6183cfb2f4e8bb04a920bcbb1e13f9fbe.nq.gz
│   └── e62c737f2e89f04e49ab21f551c1725dd6b75e31.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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
