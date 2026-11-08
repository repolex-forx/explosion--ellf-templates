# Repolex Knowledge Graph of explosion/ellf-templates

RDF knowledge graph data for [explosion/ellf-templates](https://github.com/explosion/ellf-templates), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/ellf-templates
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── da035be10624e0c992a9990d522f70d8e6cd67ef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── da035be10624e0c992a9990d522f70d8e6cd67ef
│           └── chunk-001.nq.gz
├── blob
│   ├── 052a9a06f06e4f264b9351d2445e8351403ad83f.nq.gz
│   ├── 0a4d3a8c6bf4e32e580138415e5e9a8c0433968a.nq.gz
│   ├── 0f1856df6b538146938348beb63e66f719c83ca4.nq.gz
│   ├── 11e1a2bcdf0cfafe90c0ca9ca73b251a08847a49.nq.gz
│   ├── 1d19a2d9a8512c7ea21c32d00e5db2bd74acb2ff.nq.gz
│   ├── 1fdb20deacb30814df82b61ff6727f8b0e8120bf.nq.gz
│   ├── 21413ff01d23e9ee1e6bf1e0fe5ddb708a3b6a99.nq.gz
│   ├── 2292038c24487d1bd927a72f8417ac2843ee035e.nq.gz
│   ├── 28ac23b36e609500dc43957f71cbd883e9b0d4b6.nq.gz
│   ├── 2d4c9b5196e1613b05f14308c6052128837f4142.nq.gz
│   ├── 2ebf1f92e8a12d6b633ab23d93a7fb2100c275a3.nq.gz
│   ├── 36e47796012ad181d9003f3e30c05723695c1697.nq.gz
│   ├── 382b44c1beb595dee2a1dc02e5e96dd68d9486c3.nq.gz
│   ├── 3e1586b7ad49d0f7bdac309fc7539fb22aa8c39f.nq.gz
│   ├── 3e56bf6555f64f6011f6cda0aea778ccdaba81c1.nq.gz
│   ├── 4381bc233fefb277f0c3b250f14cb06bf5033274.nq.gz
│   ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
│   ├── 4642a806e0d3ffc5e7ed7633484761d4d8bfef26.nq.gz
│   ├── 47c486380536593ce10e7408a2ee7f50bc2a3fe1.nq.gz
│   ├── 4a5da542bab8c6a40db609176be2619011240762.nq.gz
│   ├── 4e73e2060ebfb41df19d57f923ed5c1ddcc596ad.nq.gz
│   ├── 4f6659648dae7dd4df69b34b7a994a26338479fd.nq.gz
│   ├── 52a55805d1141ebea2a172b4ce4fd97484598d7d.nq.gz
│   ├── 5dfc6d930b63a4081641db780bcee4937f6f1cff.nq.gz
│   ├── 65f3950690c82f32074324bda70e56775a6df9af.nq.gz
│   ├── 6950ce15becc958f830e484ee31a41e246c27c8b.nq.gz
│   ├── 712ee573885fe30349a75066d5a8109e28495ec5.nq.gz
│   ├── 79e168443cd7565093d7773c4c058cd169545aaa.nq.gz
│   ├── 87d88e306e30913e1ce74d6403207be6a398d568.nq.gz
│   ├── 8b16106ac132d63b9c03520b2088ae73660445a1.nq.gz
│   ├── 979597c47ffe269b803c717045ee90ee660216a0.nq.gz
│   ├── a67dfe3cf4aeedfba92c6b8e9be7bd7a6e4396d8.nq.gz
│   ├── aa43dcb60ead873db65d2ec70b0ad320e95f7e67.nq.gz
│   ├── aa8441c11a4c72d4e0306cf0704a37eca81d2c31.nq.gz
│   ├── af3da373f8dec9f89fb707323df22a481ac0e7ef.nq.gz
│   ├── b6e9f1dfa7b0c8921d2c954915554a991ecaec4d.nq.gz
│   ├── bde3d06f6326d3b1586aa2237e2c88ef1cdf9333.nq.gz
│   ├── c447450fdfb7afeefbcbed6ae4c8e42d4724e02c.nq.gz
│   ├── c454e7a8c80eb93069ed209342dda869fa91bc91.nq.gz
│   ├── c66a28510660f82aca4d52c3b6702711e820b87e.nq.gz
│   ├── c6b0732278afea8b7cdddf95f28415d9e7244f4f.nq.gz
│   ├── c8fa61dfc48ac13f523de3f128b16f7d7bde6411.nq.gz
│   ├── ca95377cb8ee645c1584a4d0a034643f120688e0.nq.gz
│   ├── d22794dcfafa8302b131da09914c9c8e40455172.nq.gz
│   ├── d7f50519f879d29fac2b5fcc61de7a3e5de8b043.nq.gz
│   ├── ded0ac4d431a6b2e9af5d6aa45fbe6f25f01c8a0.nq.gz
│   ├── e079f8a6038dd2dc8512967540f96ee0de172067.nq.gz
│   ├── e5b95051f3ec78cd2e13f6ad72610100cb71feeb.nq.gz
│   ├── e658e5163edd21bc3a3c0b0946de860a5efbbb4a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7dc1df9389a39086918de9d0b1805f930f41cf8.nq.gz
│   ├── edd3a51a81e375130d950a27c9d86246d1f5ad6b.nq.gz
│   └── f635fff0cf2ef3e77f0fd347727323ade1a41dc7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── da035be10624e0c992a9990d522f70d8e6cd67ef.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 60 files
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

[explosion/ellf-templates](https://github.com/explosion/ellf-templates)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
