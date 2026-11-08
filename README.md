# Repolex Knowledge Graph of cohere-ai/cohere-megakernel

RDF knowledge graph data for [cohere-ai/cohere-megakernel](https://github.com/cohere-ai/cohere-megakernel), parsed by [repolex](https://repolex.ai).

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
rlex download cohere-ai/cohere-megakernel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 67d0b9ca22ea3652796b715d1d1863459e0e2c3c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 67d0b9ca22ea3652796b715d1d1863459e0e2c3c
│           └── chunk-001.nq.gz
├── blob
│   ├── 04f0aa7bbc864387630944acc89997f9c372b1fa.nq.gz
│   ├── 04f1d4deca1ab817397c022c2bf59a210b0c09c1.nq.gz
│   ├── 0b7585309b6cd0aa41f362374890b8168f49a1d3.nq.gz
│   ├── 0e18d9e29dc63dcd2fc0deba26dd6052f8a09d1d.nq.gz
│   ├── 0ecc83f995dd09c6f5650363a94fda80cdeaba59.nq.gz
│   ├── 128419026f0ae536871e908595db9ce0013d9928.nq.gz
│   ├── 12ac1dff74c25bf6b6028230e17a7afee9b46fde.nq.gz
│   ├── 1c86c39f5dd4cb80fb042bb46b11bf0b38fdae6e.nq.gz
│   ├── 246e6e5e8f9215836ba27a2752afb7ce72053e69.nq.gz
│   ├── 258fe269707a38221172da20bc22bfd2a57e8447.nq.gz
│   ├── 26bf510954b84df740fb869e66533a5c029fa287.nq.gz
│   ├── 272d6b8e2ecd7667b9ce2925a4934e5d52c60b8c.nq.gz
│   ├── 28ea5185c81472641e257d947f209e68d4bd261c.nq.gz
│   ├── 45ff843bfa6b8652dff7ad0f38b2051d3f9dc63a.nq.gz
│   ├── 4878b29d91b4f5b65d132d3f61109800a386d865.nq.gz
│   ├── 49a87b844011b7ce82d453c57437eb2915e01eda.nq.gz
│   ├── 4db361f8d7c78ee4c3c676f68bd5d8377268ebcc.nq.gz
│   ├── 4de3fde3ec5d2ec035e5a56298d7ef6473611e20.nq.gz
│   ├── 51dd3cc2bb4cc97b2e6f209e4a22b434d7510a6a.nq.gz
│   ├── 597eeb33ab08e734a31a5e7e2e2a35c81d9fb55d.nq.gz
│   ├── 60cfabb31d1d0b8e572a288e3813b03f7b11bc54.nq.gz
│   ├── 6281126804f39137d737d5e2cb35a3325a2512b6.nq.gz
│   ├── 657e37ece5815fe5e105452152c1bb6029b260fe.nq.gz
│   ├── 68502f78215e5fe7edd01c219a500be740269d27.nq.gz
│   ├── 7cd62e42c5bdd07aca6d42848b137cc68ccf0709.nq.gz
│   ├── 7eda0aca7fd145edc17323b821f8daba17f5419b.nq.gz
│   ├── 8a14023a026284f1cf4feabf9d47f01e1125d285.nq.gz
│   ├── 93c47d453c5bb2d768478e37ee6dd81ea39be336.nq.gz
│   ├── 9d9040bc137119b82efa823d8090127dad966760.nq.gz
│   ├── 9ee14d39a8935ea07a76fb14c609afa1106c23a6.nq.gz
│   ├── a04a6b2b6ad4d4f40b6f6ad3ab2cb63e87b48241.nq.gz
│   ├── a44d44316b832728f083f010aefd38a08f0a493d.nq.gz
│   ├── a7ebf81fef2159e7b30d7922a187a70f35ac6a5b.nq.gz
│   ├── a8f708915d841e6fe730b3f01650dbb9ad1c61b0.nq.gz
│   ├── ab2caf61ed6b7c1bd37abc66bacc01c86fdd16b2.nq.gz
│   ├── ac3c0cd548bce1fccb5d441e9604f4f412212121.nq.gz
│   ├── c21daa60a111e6d471d954fd7448e3acf2ae6ecb.nq.gz
│   ├── c2a69ea6d4225a52303d2ba75eea350c66684ef0.nq.gz
│   ├── c588632f1829632a828c9d2f985cf014d5c7c0b8.nq.gz
│   ├── cb7a96caeec1f2630711597627ffa0f044f0b477.nq.gz
│   ├── d2165e8ef517f1c2835a33dd9a9f5005a3123def.nq.gz
│   ├── e196f12c1ad4068141cd28646dff9c81662b55a7.nq.gz
│   ├── ef339b9e945df73bf17788263bc6ea375bf5705f.nq.gz
│   ├── f9c6fb39f35194107cd3e6e61fec45cb05bb36a5.nq.gz
│   ├── fa9d659050ac4aa24f8bc51ac2463aca56f47d6b.nq.gz
│   └── fafb008929d24a7ce195205065bd045e3b197411.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 67d0b9ca22ea3652796b715d1d1863459e0e2c3c.nq.gz
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

[cohere-ai/cohere-megakernel](https://github.com/cohere-ai/cohere-megakernel)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
