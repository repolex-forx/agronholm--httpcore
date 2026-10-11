# Repolex Knowledge Graph of agronholm/httpcore

RDF knowledge graph data for [agronholm/httpcore](https://github.com/agronholm/httpcore), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/httpcore
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 76f6e199b6ab92c6d18d3d8c65a9d19dab6d4ecb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 76f6e199b6ab92c6d18d3d8c65a9d19dab6d4ecb
│           └── chunk-001.nq.gz
├── blob
│   ├── 02dfed4b59cc027ca42d68f167758bc574ad3698.nq.gz
│   ├── 0334e308e3287f098170c3699b44f0a57e2e9b0f.nq.gz
│   ├── 0691f4ae6d79e0612fb6c21843dd31c4e548cb57.nq.gz
│   ├── 0b42944fe2298afa599645c04f63f34c21117d2e.nq.gz
│   ├── 0befd6a3032a059a06e0835cf79a259a19882db1.nq.gz
│   ├── 15f02aa6f828a8cb6b8429c898cdb181f566d96c.nq.gz
│   ├── 19bc62c8b734e7191e42715342ec929f6472c34d.nq.gz
│   ├── 1c4a3228288f28c10b8603dc6d5d34c46a5fd4b1.nq.gz
│   ├── 1c80156dba3d43deecccfd2ea19672f519eef750.nq.gz
│   ├── 1e63820587f9a1735915a3a251f54911a462fe13.nq.gz
│   ├── 22ada95fdc4213cdd21487e562a2e11358ad294c.nq.gz
│   ├── 2f9eeba7f0d2cbbd3e4777eaea13a6813466b53a.nq.gz
│   ├── 2ff2bc3788c84ef4517f78d785797a22d0c83407.nq.gz
│   ├── 311b2b56c53f678ab95fc0def708c675d521a807.nq.gz
│   ├── 32f676682f4780986693bf262c97b0641d8e6e53.nq.gz
│   ├── 32f876357e1ee3da95428d40b35bddd89877baeb.nq.gz
│   ├── 341b2ccc142afe2be24fbb6e150dd06bee83b888.nq.gz
│   ├── 3a639f5e01355e1aa474cca90e071a37bf23cd8a.nq.gz
│   ├── 410700beb8bb9eda044fe4992d5541632874191f.nq.gz
│   ├── 4961cab38977b3bf4f76007f87501016b48de25a.nq.gz
│   ├── 49e14ccc8ddce6b1390b122f4a9cdc18cd1a41b4.nq.gz
│   ├── 4ac3beb7a6248488589ae932e29b2d291ca1d55f.nq.gz
│   ├── 4e06775c3c203ac6cc0979b69bc62f3fcd9252c9.nq.gz
│   ├── 4e77dd1c2bc6ea8efe2ab7d16de12e55cc38187c.nq.gz
│   ├── 4f75bd60e7c84a0c4a37b8d61d25f3b03dc3da1c.nq.gz
│   ├── 602eab0a4ab3f8ebfdc34edb5abc0089fcc9779d.nq.gz
│   ├── 60e16e72a792f6e56e296ed8c24b975cdbed25b7.nq.gz
│   ├── 65885a7208961207ed34c9659c21ac5ef0b90314.nq.gz
│   ├── 676e215c07ffa89929360bc454789cb990fa95e5.nq.gz
│   ├── 6e5d919192afbc02540b1259aea0e042617f4788.nq.gz
│   ├── 76b916e6bebb05a1f409950b25cb600238ea0844.nq.gz
│   ├── 7f644b56da973212ecb2f905dc4c584b5b599bd8.nq.gz
│   ├── 84d4d367b4201569d48020f439af0185e3a8c28d.nq.gz
│   ├── 8ff0b4589cc9a590ae5e0da2797030f0c3ceb8cb.nq.gz
│   ├── 93b031181f89bd42db8e6b24aa9e01f296c46129.nq.gz
│   ├── 94c1631d801c06a649542c43a3608c63d86e5017.nq.gz
│   ├── 95ddb526388eeffb8818064898cef84b86b1d733.nq.gz
│   ├── 9b3ab7001c5bb7ceedb90785c170b993a5a43e4d.nq.gz
│   ├── a41fd2bf21e0abc18a42d84fbeda6cae9523766b.nq.gz
│   ├── aa66ec4a5ba64699bc6c911e7aa8f6141ab4bb2c.nq.gz
│   ├── ac5747c3d92db18c59647786191544039336e62e.nq.gz
│   ├── ad5c77501504b3746012cee26c45b02a2e9e950e.nq.gz
│   ├── b2729fb7feca815d3faa2f5949d8a9fd5531bafa.nq.gz
│   ├── b3d6a53586dd47ee8e399070b1456f68268a6c15.nq.gz
│   ├── b41bc6c3ce6b81631f18048f3e4737c75937e59d.nq.gz
│   ├── ba1075cc04b3a769a07242044271eeb076e03caf.nq.gz
│   ├── bc7d1894ea1ba85726baa49c9365c5ee308d3bb9.nq.gz
│   ├── cec56593dcbf3983fc2cc87e727dc6d076e8681d.nq.gz
│   ├── d7b1050088b094ee986a2f8f100ed4cdcaf24b35.nq.gz
│   ├── df930dc0afc32a1876cbcb5f645589735c2d125d.nq.gz
│   ├── dfda00134f58abc1aea9dfa6cf073e7afa34a7fd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8d3c77c3888094f9a3121585af1b6af892b055c.nq.gz
│   ├── e938aaf90c25fdfd837c4c84a473c93b6723186d.nq.gz
│   ├── f124a4c6c47ba796cbf22432a0894cc3cf699958.nq.gz
│   ├── f795b38b55c0cff7199c295a7de87a141275357e.nq.gz
│   ├── f91c4d9580d10337c88618798349722c368da70d.nq.gz
│   └── f9c9917233193a0da905a83467c7e825518e9a84.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 76f6e199b6ab92c6d18d3d8c65a9d19dab6d4ecb.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 64 files
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

[agronholm/httpcore](https://github.com/agronholm/httpcore)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
