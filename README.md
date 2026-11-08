# Repolex Knowledge Graph of canonical/cos-tool

RDF knowledge graph data for [canonical/cos-tool](https://github.com/canonical/cos-tool), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/cos-tool
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3cbc09cb483d56bfd4083c95c8548964a028996a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3cbc09cb483d56bfd4083c95c8548964a028996a
│           └── chunk-001.nq.gz
├── blob
│   ├── 01b7d8d0ce0df5a718d4a223ff6e8fa1c6c503b7.nq.gz
│   ├── 049d278018619264caf1119f8c0bc7e7b7d16d1b.nq.gz
│   ├── 13e35342f338bb019392010442c6717e6c09a13b.nq.gz
│   ├── 1527248b125dabe30867ea3750b2a727c6797536.nq.gz
│   ├── 1bb45e9085b56696c3b53307f0da6268b4b3d16a.nq.gz
│   ├── 1f08296696a28552faafc5f8d918ebfce9d46b69.nq.gz
│   ├── 24729a3c085649978b038bdc96b7038d6b47417b.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2715ffbb9726fb8d19f8de867162446bddead410.nq.gz
│   ├── 2945a781d90e590dc1bffb6dee79756676620f4d.nq.gz
│   ├── 2f867f93dc305436fd6ea1daba322cf343373ee4.nq.gz
│   ├── 31da30a9973ef8dbbb9ef94a8ee4e1494a3c0332.nq.gz
│   ├── 3237094fa69937ba922c6af0b500413ae3e4e716.nq.gz
│   ├── 36c06d140e1bcdef5b414465e14e3ec27f4e8b52.nq.gz
│   ├── 38063568c398d14f42cdf484aa19e14544ae36ae.nq.gz
│   ├── 3a8b85d92d0b216dbc28310d1043420dfba709dd.nq.gz
│   ├── 3d0c5aaebbee0b3cbad7ab2927d0933e9d1b28c5.nq.gz
│   ├── 4304f1abff132f77d74f2d61e12f843244163eec.nq.gz
│   ├── 47f62bbedc5a62fde087e27637521ae32d848271.nq.gz
│   ├── 4e69b2e68a2c160b853272fcb4b4f9c06c846a7a.nq.gz
│   ├── 5dc68d5d400a506990c82e9faefd8de114a2e882.nq.gz
│   ├── 627a0202fb7d79c8178384707874a7f27321a7c6.nq.gz
│   ├── 62cc380862f77a9a850ec722b5a2cc248c1d9f15.nq.gz
│   ├── 6529f07eec855dfb44e98be07d7cb9d3b1ea4209.nq.gz
│   ├── 652c7d218edf2dc1dcf39f46f745b352c2172801.nq.gz
│   ├── 672166c077993b34604c6033b9d86b50054fa821.nq.gz
│   ├── 6caf59ffd4d5d512043bd43cb5f55d000bb9adf7.nq.gz
│   ├── 7228ce9dca8b2f3fbbf2dd7b54b23d0961075a19.nq.gz
│   ├── 76f4f9eacf8d2e605c94a2553dc3f8b615edb43d.nq.gz
│   ├── 7b1d25467c45abb0be311e444fd740cbe3475be0.nq.gz
│   ├── 7bb38efd883b424ac1c0120685eb200249bcac42.nq.gz
│   ├── 7f91cb357735913034021cf35b7c03b4410446c9.nq.gz
│   ├── 81207e13fd05c8568fae90d257025e4a1a13884c.nq.gz
│   ├── 81f6d9767a4cd2542ba04ae1fe9f99167fd89559.nq.gz
│   ├── 85949ebed998343599dab6b1f44bfa55e6e30f10.nq.gz
│   ├── 8895ef6ed986cff18938c4fae5bb9c99e40c2b15.nq.gz
│   ├── 8af91110b5501dd7e37f1bc30d76a3dea1eebc29.nq.gz
│   ├── 8c0c3240ec422c5d44c192231ef705a249629007.nq.gz
│   ├── 8c152a4a775afb33587cbf577f67d21bc7b1182b.nq.gz
│   ├── 95b1769f987923de3b8d278d1b9e0c1d591562bc.nq.gz
│   ├── 96cbbd6d628dc4b218537e8a665b3ebf222c6980.nq.gz
│   ├── 9ac7caa2a02ef51568e86a23c187134a3b42fd1d.nq.gz
│   ├── 9b5a9dbedcfbff9a580975ee1eaa541861a7baf0.nq.gz
│   ├── 9d14004dcddc196c04bdec18aa7a59fde91eda6d.nq.gz
│   ├── 9e3c29fccb205350a321a5731f045d28502e090a.nq.gz
│   ├── 9fd89006af508026ee9abf23e2c86a00c0bfac04.nq.gz
│   ├── ab2af9d45f67d19856775448fd13d057383a8f99.nq.gz
│   ├── b14117708dd8831b68169086cb1cb8229b833e1e.nq.gz
│   ├── b2348b9fbfdc4eb154566c80f844510446be1d02.nq.gz
│   ├── b4cd8111c334643d62c8337c05daadc542adb54e.nq.gz
│   ├── b76bfcc18668c63c1a520fcfe089eafbf803aaa2.nq.gz
│   ├── bab4015fc59279a8ae1ec0e1f6700bcbb64df351.nq.gz
│   ├── bbd3b33e2beea5ff19325a138e087f8bfc545953.nq.gz
│   ├── c1c65739fb965917714ca0f63d96c585b56d58b9.nq.gz
│   ├── c3c06c827ad45cf02d6593aa1573162729c33165.nq.gz
│   ├── c3dcc6c040a5d8f2a2d321c91945b53d41811152.nq.gz
│   ├── c69463d01e7e8a854d233c7ca69221fd8cc459cf.nq.gz
│   ├── c7f0378fc46998ab3155c1740bd755cd80cf28b8.nq.gz
│   ├── ca51bb5d4f28f3b5acc9265492e07264d9aaef81.nq.gz
│   ├── ca80c6f65e7b0105bac4f336700d6b4120410c10.nq.gz
│   ├── cc279375d79d0c550988c2e4a47ce1f53e102049.nq.gz
│   ├── d0ee099b54f13ed059b706943ac921ef2840aebf.nq.gz
│   ├── d1bc2515c9cb2fadd108ea17590eff520d5e7540.nq.gz
│   ├── d248280948d991dd094ee02e7e828dc822cd5104.nq.gz
│   ├── d31bfe490fe57e8fe5c8839dced36a519eeb8475.nq.gz
│   ├── daf9d4082155721816cf15944fae28e6197c5dbd.nq.gz
│   ├── dc6665bface2e6c3a9de817b76fea375be8795cf.nq.gz
│   ├── dcf793a1d91a8ac0e73aa218dea8a73051130e8f.nq.gz
│   ├── e1fc0dc673e33a867af07b3f8a383fdd19c3ebb2.nq.gz
│   ├── e25bb5fbb76a74f374a06721b87b1769ce1a810a.nq.gz
│   ├── e67d1a680b4a1d589893f5dedaecc63ab4334c45.nq.gz
│   ├── eb7eb33120aa38c839d0811e2242ff8ab43af06a.nq.gz
│   ├── edd3c25368dade20bf26dbf15b5cc3f7b7a5d8f2.nq.gz
│   ├── ee85ca9fa9327f74bd9b9cd0ef07136b417c7b97.nq.gz
│   ├── ef9788599c207d8aa0137b4b664617912c3247c8.nq.gz
│   ├── f6d27926f989a6c0ff10515e63ce83a608c123f9.nq.gz
│   ├── fe1c49e7e37ccb9fa28026964ef2cd6dc7a74bc8.nq.gz
│   └── fe8b4ef2049e7b04999fc002e669c2f62214a024.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3cbc09cb483d56bfd4083c95c8548964a028996a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[canonical/cos-tool](https://github.com/canonical/cos-tool)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
