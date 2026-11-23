# Repolex Knowledge Graph of aldanor/qoi-rust

RDF knowledge graph data for [aldanor/qoi-rust](https://github.com/aldanor/qoi-rust), parsed by [repolex](https://repolex.ai).

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
rlex download aldanor/qoi-rust
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e97077e527618a07413f7895a3792a6859afac59
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e97077e527618a07413f7895a3792a6859afac59.nq.gz
│   └── repolex
│       └── e97077e527618a07413f7895a3792a6859afac59
│           └── chunk-001.nq.gz
├── blob
│   ├── 016086545e864a48ea38c8521912c6a3d3b0d8b2.nq.gz
│   ├── 019dac2df2003cd04f8c82b2be9ae9193baa8370.nq.gz
│   ├── 078918d5aed795b2f6966020c84a7759655e396e.nq.gz
│   ├── 082c762e6f8382bf4d4b23f34188e99eaa979f69.nq.gz
│   ├── 08767d4731b2f2546b34d12ff2bf4d79bd78ea7b.nq.gz
│   ├── 0bafc7c10ad8fa29bdf3fd5e428207269a9bc676.nq.gz
│   ├── 0ed84767e83d9d56af2070f203b6e4892ad44864.nq.gz
│   ├── 11069edd79019f7dafbe3138841cf289209270dd.nq.gz
│   ├── 2027fd9e86cf3258d0dd2359c08d20a823c3529a.nq.gz
│   ├── 2281c24418881987774fe2f8310cc3babf8b6950.nq.gz
│   ├── 2454247b536c757f70ca293fc534b4928f8187bf.nq.gz
│   ├── 2b9063629fdc20798c4a6a29a8b6430c046798f9.nq.gz
│   ├── 2e4b18b6febe51e70afb5ff365ddaebc69fe9e7f.nq.gz
│   ├── 315d006dfc7e9f41eeebcb1199d4cb6a239bd8ac.nq.gz
│   ├── 4388d23d6e8a56a1c86cfedc030c7fc41812b1f8.nq.gz
│   ├── 46a247cd4dd24d58edb778e7416280be5a2a4fc9.nq.gz
│   ├── 56d94c1228b4d81f0a85e81881e39c965b5cb088.nq.gz
│   ├── 59a73159e4341fba488419fcc79b6f223609aad1.nq.gz
│   ├── 62a1c3b749705fab8a26a15ca48996a51440e480.nq.gz
│   ├── 720adf48da802c0212320a5565bae748eda23c35.nq.gz
│   ├── 7246b77bcbe22b6ab6215cf5f7b6403c7910b6c5.nq.gz
│   ├── 7b2477693227d92967b8ac594a4d9baf9e6add3c.nq.gz
│   ├── 81229d4ff87d93472c2525ead3e36e249e0e5250.nq.gz
│   ├── 8417cc7b41f350ba309a5c9ae9af027bf7821455.nq.gz
│   ├── 8b0cf5ff7de25261c85220773363e374d0e5f3dc.nq.gz
│   ├── 8f9f42a653013d7f957073ef5fcc474f8539b879.nq.gz
│   ├── 90eef44febf90aaa1628194d75ba8802d5604c5d.nq.gz
│   ├── 997aed4d9b5631b8bc9828d5556deabf76850dd9.nq.gz
│   ├── aedb0c38a14756281bb1249e7064fa109eed0bc4.nq.gz
│   ├── b94ff691ba18e087f7e643001db735648d8e51a5.nq.gz
│   ├── bbc8154fc8fe3c7ff92103ae1ebd74bdac2ddda7.nq.gz
│   ├── cc1eff1fadae2ef9b6ac925b5af06d3382f26134.nq.gz
│   ├── ccdb1cc1a98025fe2f8364b9b1e23a776b4e2688.nq.gz
│   ├── d0c37a6157487c8bcf23a7159bc15eaa26adfe10.nq.gz
│   ├── d1034944ec50a663e4e18f5904068167dd29c2dd.nq.gz
│   ├── d1a04d64007e787b562ab7a8ac47025054e620ba.nq.gz
│   ├── d465140952a20278b38330019d0d3a6b14888c17.nq.gz
│   ├── d4dc5bb7493105a2953dc601b5d7230cb54aa78a.nq.gz
│   ├── d6fccc92871b97b0c50ccf0f3a72cee03a8d7e33.nq.gz
│   ├── d932d310fa97372a855d319bb1ccf71817d9f877.nq.gz
│   ├── df7063ec6dfdf6d5cf1e67f0f847197a8d28ba6d.nq.gz
│   ├── e7c8dcb35efa9c9d5c37b5526ab3d113a23c47ad.nq.gz
│   ├── e7dbeaa5bb861d9f3b797cc8ae67bacbd8b5aefd.nq.gz
│   ├── eb6f20f53b4a11e423e0387137cb3590af373ddf.nq.gz
│   ├── f69cb6a67c903014897d64283ec68a56b68533bd.nq.gz
│   ├── f77506b16a72a21425954b7b3433eda4bae8a121.nq.gz
│   ├── f9c04dced37c362b1df4e85d2278e310420da41c.nq.gz
│   └── ff22e837372943b79e2b61dec9c16fecb5d0c31f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e97077e527618a07413f7895a3792a6859afac59.nq.gz
├── filetree
│   └── e97077e527618a07413f7895a3792a6859afac59.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 58 files
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

[aldanor/qoi-rust](https://github.com/aldanor/qoi-rust)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
