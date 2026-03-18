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
│   │   └── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   ├── dataflow
│   │   └── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   ├── lsp
│   │   └── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
│   └── repolex
│       └── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
├── blob
│   ├── 031bd4b53043c099111faa7adfdab15f63569c11.nq.gz
│   ├── 051d61af474225858ab2f7f76dafcc8fe94f9e38.nq.gz
│   ├── 1ac3f61c63b08c475f36ddcc00de31b5f26e5bbf.nq.gz
│   ├── 31ecdfb0b4b73faf5a47ab10c8debd1c51b503c7.nq.gz
│   ├── 3346ab5caed9219a4b75d579f9258da9baccbb5b.nq.gz
│   ├── 5e4090017a9bec5de60a745d17007a9e95f31a43.nq.gz
│   ├── 6077b5ff84d2f31c8b6972126a788155c41ed20e.nq.gz
│   ├── 853c08c29a1b23c67c2df03c7236f1816914095a.nq.gz
│   ├── b1822292325605201a54b82c29ca5795d83860b5.nq.gz
│   └── dcdfdbf83f4feae6d870cfb5652d3dfa93ea11c0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4bbd7cee108b348f5829be7e2c35e25e6ac5991f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 20 files
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
