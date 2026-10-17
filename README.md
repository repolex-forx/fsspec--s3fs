# Repolex Knowledge Graph of fsspec/s3fs

RDF knowledge graph data for [fsspec/s3fs](https://github.com/fsspec/s3fs), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download fsspec/s3fs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0cdfb8108c204dbf2d10c2f9977f85260220975e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0cdfb8108c204dbf2d10c2f9977f85260220975e
│           └── chunk-001.nq.gz
├── blob
│   ├── 05d5b70b8c9b5aaad44cc1b40b9877a89da7e5ad.nq.gz
│   ├── 10cd3a8a6c162ed8faf0ae29dd7c9409d7e43083.nq.gz
│   ├── 118649092b04e6cd1fb6c766cdf10f6943b1090c.nq.gz
│   ├── 16fffc59dc4381614b90acd9bc2875116bc9774d.nq.gz
│   ├── 1917891d0ec2af43454e37b7e0dbb155973a280b.nq.gz
│   ├── 243ac8c6c3f45a5e674f8ad27462f3cbfcf5ed4b.nq.gz
│   ├── 2e537615263641006cbed9d3f9593654ae04e600.nq.gz
│   ├── 2faeb79b9729f3704a07110955209f45f6d5f13f.nq.gz
│   ├── 3699cfb5b0af677b321b70c15a569c3e76ecd985.nq.gz
│   ├── 3dc3d25d18e07b80dc58a2f8d81a90b0ecff4ada.nq.gz
│   ├── 4e317f847ee0775f795e9ae5f80c6250a2e29bb7.nq.gz
│   ├── 54a024fb365c86a8c3ea48db7dfb9892e8479b87.nq.gz
│   ├── 577c968f41ae5d8a53271e3ba8f461b17ac30ccd.nq.gz
│   ├── 5d0152496e3dd3ae3dedec21e9a7b69ca82c05d0.nq.gz
│   ├── 62a1029d30467d00d9678cc01db1486e3c2d7f41.nq.gz
│   ├── 62a97e38c9c89565e7931024723e0c65ffe1d093.nq.gz
│   ├── 6db533e5e99f5995423ab088c1cc328cefb79217.nq.gz
│   ├── 852093f81021efd302430811ec06b7ee18ef2daf.nq.gz
│   ├── 86b02896255c07d0d6577f72212c094fc0bb1a4a.nq.gz
│   ├── 8d9804c97c7c8d249f5ad421291e34aea213079e.nq.gz
│   ├── 90cacd86dc67457a37cbc79dcb34006081bc8f6c.nq.gz
│   ├── 9578469ded9364212d9b8b8012f54d5fc2e511a2.nq.gz
│   ├── a32ad1e5310d02378930e55138e2709ff351ea51.nq.gz
│   ├── a5a06e1748c6e2f1a0892b4513339c6a0de0584c.nq.gz
│   ├── ae8cb6556ccef7f135988b3f3ed442ab4c22d56f.nq.gz
│   ├── af51ee5598fd6d3d9c91da656fd1bd271beb4147.nq.gz
│   ├── b20d02184714fc75c6043ad15fd162b6486cdd9e.nq.gz
│   ├── b2f64ce287372576248bec17ad273eec5c69484b.nq.gz
│   ├── b462c9791452194e5037d8bdc0aa9350c4786309.nq.gz
│   ├── c37380f6223bd92030c4fe38561708694c9f4775.nq.gz
│   ├── c3e21d2b77cc8d8e2652bc07f98a6a68ed96293a.nq.gz
│   ├── d2c7757f6c2827e87b6b7ffe89665c28ce6489a2.nq.gz
│   ├── d95c363670c52d29938c9824db677f450f57006b.nq.gz
│   ├── dd188ebff593e2bce91d6330ce727dab8bd70a69.nq.gz
│   ├── de97d9042ce12adc2594b401834611427d3fb1aa.nq.gz
│   ├── e5054bd5f0793dd1ff72f5f2d44392604342ba74.nq.gz
│   ├── e574d2b24e07d018f09f22222088bd7efbaaec96.nq.gz
│   ├── e67c7e73f08a4d706bc9afa62c470638fad1d8a7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f44c84ca8581a218b706aff06e03cb4b558e4742.nq.gz
│   ├── f6cc212e7b0c54a80a7e01a4dc00c8e523ae8534.nq.gz
│   ├── f74d0a4d67ac651137d8c66efd1ba43917d13e83.nq.gz
│   ├── f8a42f9a965391ae5287576e043d398f821e2774.nq.gz
│   └── ff29c2bc0ef11ae9ada47ffc104aac48dd4684bc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0cdfb8108c204dbf2d10c2f9977f85260220975e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[fsspec/s3fs](https://github.com/fsspec/s3fs)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
