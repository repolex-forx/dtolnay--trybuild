# Repolex Knowledge Graph of dtolnay/trybuild

RDF knowledge graph data for [dtolnay/trybuild](https://github.com/dtolnay/trybuild), parsed by [repolex](https://repolex.ai).

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
rlex download dtolnay/trybuild
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 56587f36d1931557ea3baf3ea329da9c59ba92bb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 56587f36d1931557ea3baf3ea329da9c59ba92bb.nq.gz
│   └── repolex
│       └── 56587f36d1931557ea3baf3ea329da9c59ba92bb
│           └── chunk-001.nq.gz
├── blob
│   ├── 02feb33f6fd1c9f6ce523eebc730263e80f9eeb4.nq.gz
│   ├── 0913b94828eb90aa9e6d7b461da39e7b7a7473fb.nq.gz
│   ├── 0eea6cc8b4ce4f7b496562a612be1867db97f966.nq.gz
│   ├── 0ff0cacd0c83b231d99851599d442875b7ea774b.nq.gz
│   ├── 12f3e931c9ce3cfb7fac2b555730a5d17d4fb2bb.nq.gz
│   ├── 17270e338ea738c0a29f39f194fb510c8e1eab5d.nq.gz
│   ├── 175e8f2d40890d2fb11f05964522e2f7f1bfb436.nq.gz
│   ├── 1a386551c98553f9efdc9828097d58e094d730f3.nq.gz
│   ├── 1b0693ea9001bae64c9b1ae59f4bdea116a02b20.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 1c55c6b476eb64874356aaf3303af4228686a57f.nq.gz
│   ├── 221ebaa5a8c8e3c2b0e6f0649749b1174152ea6f.nq.gz
│   ├── 22814c5ef67ecdbae6f077a8116249e96da9d316.nq.gz
│   ├── 24ba5068004f9dc851f50a9fe47fcd1756103f16.nq.gz
│   ├── 29b5c416eaa4dbe4802a573f0f2ecddab65860a8.nq.gz
│   ├── 29d7d8dbb67872f770efd858814e0da1f0f4683f.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 352d9d0ff7c0ded61500315de9d27ce6a3124e07.nq.gz
│   ├── 39626ff00f45d9bd28d8c814fe3375cd69cfd0c9.nq.gz
│   ├── 3c2a49895d5ef61e63f6e6c644cb711477a90f66.nq.gz
│   ├── 420f9b93060fcd94d172a41d6428542d259947d2.nq.gz
│   ├── 4bc31dc394135fc1aa166b499d5f346bc0abfc2d.nq.gz
│   ├── 4db4c184a38685b346ef2d6d1df7d48bf54b626a.nq.gz
│   ├── 4ebf813196ee554e16f6978a46972044ac2cbb4d.nq.gz
│   ├── 53adc42ba39383ba2925587d1ead050a30425628.nq.gz
│   ├── 5573efbad08845bec4179d4ba272eeed15dd8b6b.nq.gz
│   ├── 64725b04ab44445f6949f9ce8d2033c0d596f9ba.nq.gz
│   ├── 6b62a8f7084895620be5ff2aa23925fef77a3ea0.nq.gz
│   ├── 6d9830732db5893069091ff5917a3cb775d270a7.nq.gz
│   ├── 7143195436db7afa30938d26076ab003a8cc6527.nq.gz
│   ├── 71e687a8fd2e30a33d0df754d3e3b128d30e1f08.nq.gz
│   ├── 750707701cdae985156601cc906195021ba6a6e5.nq.gz
│   ├── 77678828f33efd3562cdf0be1237ab2662a2d0a3.nq.gz
│   ├── 7fc2291696ce7f5caa6ff02ffe5b1b8cff3c8983.nq.gz
│   ├── 812c8a6b0b7cbe76bb6e714fcbe7984e849b342b.nq.gz
│   ├── 8480ca2993eac4e47ea1969e0ac5fb3f76b02ce5.nq.gz
│   ├── 848e815ca9a14a8076c39c0e7f680fad1d094c8d.nq.gz
│   ├── 866c575df412e60c9b0c455a314d4e946cc83e2a.nq.gz
│   ├── 87909683bbd58bc6c52927382b88cb75dce7d285.nq.gz
│   ├── 8a709d5b862e603410153e11e19fd3212ab9dd28.nq.gz
│   ├── 8d21ebfd21b34a8b0c5cc01a7a12531b5a747416.nq.gz
│   ├── 93002978a3a37e913656ebc2222d0645f9ccc428.nq.gz
│   ├── 963ab64f1fa6f3eb6f8af6fcdf6d2bc86ba891ba.nq.gz
│   ├── 9d1ae3c07b14cf72125aab2cb40737316a60d878.nq.gz
│   ├── a3bdf912a4b3e3118668cb1f97047cfc2cb699ca.nq.gz
│   ├── a4340f179530f5d9f76a34ff5b4730cc7623bed4.nq.gz
│   ├── a49c1580fb04f4e1baf7aaa8f0dfd83cf45d07e5.nq.gz
│   ├── a52a4ce4e06092a2f663e51f1bc7b661bde9245e.nq.gz
│   ├── a8c7fecd65a0f3a04cc04f0520f99f85ab4a3620.nq.gz
│   ├── b1eb6f48e9b2356aa360da43e4b7efa51907eb7c.nq.gz
│   ├── b315213545c3cb1252a39b05538b1b9f326e11d6.nq.gz
│   ├── b71a05dc630d97b01a517edfc11acb1a340d28b5.nq.gz
│   ├── b7f10dd504cd74ef1bc7854bb4e62f6a25955857.nq.gz
│   ├── b9ae62d5d07ed4e498805b9aa1d90c8739aceda8.nq.gz
│   ├── bccc718fb9452d5aab8d057958372e6d4765fc28.nq.gz
│   ├── c680aed818cc9c7a774fe29e7695fe15d7e809e6.nq.gz
│   ├── d0ecf7abeeff1f96548891a19297d838bbe4281c.nq.gz
│   ├── d34b0efba5174b2c9cc4bd0d9cdbc261c63a019b.nq.gz
│   ├── e2253ddf9807044267f3e0e36e06982681a29ad7.nq.gz
│   ├── e4211d821899a6f492ccf527b889fc7b3622303b.nq.gz
│   ├── e9e21997b1aca0707f8749ea13c09aec66c899d2.nq.gz
│   ├── ea4bf42b4ced83708908f9ca1a10bf030d7611d8.nq.gz
│   ├── f0d1147dc93d2ab3f9023cd89adc3e575d96d93b.nq.gz
│   ├── f1a7cf80de3a4257ffc62acdea392d2b4559ce5d.nq.gz
│   ├── f328e4d9d04c31d0d70d16d21a07d1613be9d577.nq.gz
│   ├── f8b9845db3fa18564c56f9d0d88059d393745b15.nq.gz
│   └── fe075822bc3edd7e90bac8efb2919804418dddb4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 56587f36d1931557ea3baf3ea329da9c59ba92bb.nq.gz
├── filetree
│   └── 56587f36d1931557ea3baf3ea329da9c59ba92bb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 77 files
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

[dtolnay/trybuild](https://github.com/dtolnay/trybuild)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
