# Repolex Knowledge Graph of pydantic/datafusion-variant

RDF knowledge graph data for [pydantic/datafusion-variant](https://github.com/pydantic/datafusion-variant), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/datafusion-variant
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9e1c84698150eaef7b640f50f907dd8e585174f5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9e1c84698150eaef7b640f50f907dd8e585174f5
│           └── chunk-001.nq.gz
├── blob
│   ├── 068023a0db4b7e162b97c88e16c8970941492e84.nq.gz
│   ├── 09e683bde3c26245687948541743e881a0023994.nq.gz
│   ├── 0a3d58f8e5f880ab0c75a1a4b34554838c38e2d3.nq.gz
│   ├── 0ae00f303c10a3d6dc78994e8116b648567ae64d.nq.gz
│   ├── 0f378310785054d4fe809f222c3a8a9188cc40fb.nq.gz
│   ├── 110b9d9d646581f09888efdd7c21b28fb35e30e3.nq.gz
│   ├── 14dd5f2dab8af75eb38d80f678d4fe2434d3c654.nq.gz
│   ├── 16d9e3f9035285d70ac2de39c0feb5644fdec4f1.nq.gz
│   ├── 18d7e05bd5b7b4cc7417a3d4e19c37b00250be2e.nq.gz
│   ├── 1a4a27657c6e1822e7c79805256b24b06f675a79.nq.gz
│   ├── 1f9672e0b23e5393d8f497690a1b03832dd1d26e.nq.gz
│   ├── 205e6dfe908d8a5cc40ce433d027d68898569fd4.nq.gz
│   ├── 208e1931cf3e95060a004f83b05e60182e0c5bea.nq.gz
│   ├── 25df15de1f907509c79374a8caee3490ff0b6e06.nq.gz
│   ├── 32acae788dda92f06ce0266f78695dea46bb7ea7.nq.gz
│   ├── 39de766cc2f148cbad6e09c4bdd75ff896630fe9.nq.gz
│   ├── 42a0bccead3322572120895bec89b4b900b44a8e.nq.gz
│   ├── 4e346024e830897b66e8c980e33cf025ac007bfd.nq.gz
│   ├── 542cdedb01e2040e8fbde30063aa55d3f6b06b7d.nq.gz
│   ├── 5a18acda68fb46efe1c94994c905ad2a7cc68af8.nq.gz
│   ├── 5ff38d7748ddcd0753ab55f610c9ea020bac6645.nq.gz
│   ├── 6aecc5eb41c73338de951a5927724519a8c7adea.nq.gz
│   ├── 6afa33f0b7f9860998f7ded01dfe39784b5e7a22.nq.gz
│   ├── 7de604b844328fd8b21bffa4b8ae44ee74b05a69.nq.gz
│   ├── 8f544793a7f13b42393e953d0f695628d9a0995f.nq.gz
│   ├── 90cda28a48d488df391db85b9489e7e1152bf6d1.nq.gz
│   ├── 911aa3338b8ca6c79a82f8569c636c098ec8276c.nq.gz
│   ├── 948bb321579e76f12aa4531702a12b587c0c4fc3.nq.gz
│   ├── b29c114ece15ffedb6ca2d219bacfd6cf5feb587.nq.gz
│   ├── b311db32e53e78175c2d64c1c16b8e3c5856a3e1.nq.gz
│   ├── b76d4ebba28238bc13a3677d679e601f11b8501c.nq.gz
│   ├── b8c4ad4c75eab19c49a19cc8049972125ecd7d00.nq.gz
│   ├── bd9c7e682ca684a4d8b91de52a06cab85deb8826.nq.gz
│   ├── c5a7c2883f9f7382401f085604b422dc4c307987.nq.gz
│   ├── d4e2f6417d512674dde9050e0dfabc85c367c541.nq.gz
│   ├── d582d72ea99236d69838d66c41d20a5e81f66279.nq.gz
│   ├── d74c6b599d2ae5eb8cbc226c1d2ae310198cc2df.nq.gz
│   ├── e0578e1fe8db8f17f4a5b93e1b00b9b214faba02.nq.gz
│   ├── e6724cd80e84f9df1a749689242d6d83906eeaa1.nq.gz
│   ├── ec0e2476a55216901be8f50d75c382ff2268e463.nq.gz
│   ├── ec232f6eabaa04ac4dd606c8a413ea7f9be244f8.nq.gz
│   ├── ee231e4726c80a9d0d0ce0182a45d60ae10364e9.nq.gz
│   ├── ee380313b4cef83e4a2a20a06f585a25b41ab0e6.nq.gz
│   ├── ef7ddcae912044c1f9bc6cd0b9603202f51bbc46.nq.gz
│   ├── fcb972afa205e3a33975074827f769ac0152ff4a.nq.gz
│   └── fdb407b926713aec7e5c4e76e9d9399d5fa46b68.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9e1c84698150eaef7b640f50f907dd8e585174f5.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 53 files
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

[pydantic/datafusion-variant](https://github.com/pydantic/datafusion-variant)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
