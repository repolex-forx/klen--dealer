# Repolex Knowledge Graph of klen/dealer

RDF knowledge graph data for [klen/dealer](https://github.com/klen/dealer), parsed by [repolex](https://repolex.ai).

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
rlex download klen/dealer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6becc485fd13458ee982265ef8ed9b7e008d808b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6becc485fd13458ee982265ef8ed9b7e008d808b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d27ee56408065d9421a482d74b818f81b56ef58.nq.gz
│   ├── 0e00b4eb0ee81ef2b4e2e80dff724fc6e07c3274.nq.gz
│   ├── 0eb5aa33b61681d333f516a6e19d02cdb56cadfc.nq.gz
│   ├── 12469cd94cdc8100ec0fc71b5c9b2e34300efaf1.nq.gz
│   ├── 182d6c097fde92092571219147a89cb9d461fce2.nq.gz
│   ├── 1a9f4c6cd01bc8aa037dc3f97a75ceb681817f8b.nq.gz
│   ├── 1bac2f1eaec62d9fb0e9b4bf8b3950dd00c6f759.nq.gz
│   ├── 1e0db39aab5c21c638a71b250b7240190a615934.nq.gz
│   ├── 1e8aa82b38632777fd72c41e8bf23a98cb257a6e.nq.gz
│   ├── 236c4165ebe4da733e2e7d2acdf5366b552e683b.nq.gz
│   ├── 23d3bc1c0be60dca5b8516b493ea5538f384ae8a.nq.gz
│   ├── 2431023a17b1e7b5c96e5db8e264c251f39beab0.nq.gz
│   ├── 265de06436575b257fbcde18a7b147b9e38ea167.nq.gz
│   ├── 26b36defa51b5b6dfee612f66b52c586d1ec1880.nq.gz
│   ├── 30b21fba8752a0cb29a2c96d9a92c7622e4038a5.nq.gz
│   ├── 31327ba2e31b81d0ca5dbdbaa46b21753e9e457c.nq.gz
│   ├── 32258e403fad0971f2120a92f44bdc56ed130a66.nq.gz
│   ├── 331d858ce9b12fa6720414196a9dd6e0b6a0faaa.nq.gz
│   ├── 3c136371681ffb589ee82a51b88f3089e622e6ec.nq.gz
│   ├── 4062ba287db9d97fb0007c8b11e821ae279702e3.nq.gz
│   ├── 4aa926387fd93b94c03c494f69487361c2c17139.nq.gz
│   ├── 4ad96d51599fb734101f6229f6c1a8a509bd6255.nq.gz
│   ├── 4c0807b4859f3959edde50de6ce5be5495046016.nq.gz
│   ├── 516d31c2fb5ced1304e81a41fd49e0fa6a83a485.nq.gz
│   ├── 5bf05d5f1330e729b51d22445d62472f0af880f5.nq.gz
│   ├── 5f262cf11d78ab22f8ba255df9cd8e60589d96ca.nq.gz
│   ├── 65728ff0576475644188ea0561ad5e76e65cecf3.nq.gz
│   ├── 66e36b04b3ed7527dee82204c1d4ec4ba8e81bd6.nq.gz
│   ├── 6a825bd77eb1f0213bfb543e82084adcbc13085b.nq.gz
│   ├── 6f8c2d21bd9092859c3e26262399180ba1b732b4.nq.gz
│   ├── 74f25b8acd969a5323c0addf660f7c67f268b73e.nq.gz
│   ├── 7a8743c416dc348796c41e3c5bae9b9f45c038df.nq.gz
│   ├── 7cd18362ce722d9d6c63d48895c5b0513a0caa17.nq.gz
│   ├── 7f513be3357aee4af42a02e7e80f034c8cab0cfa.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 926705d0d9e78b6bbde2eff19825ca60ab74b828.nq.gz
│   ├── 93baab783c13ec7c4135c118494ce0ed25551500.nq.gz
│   ├── 9c109d6c2996df62801e682546c4da5706a02a8e.nq.gz
│   ├── 9c37d13a984243afe1e9a7f122c943f3a5ea7365.nq.gz
│   ├── a054b50ced025395f4b3b3bf8205e027024b0fe3.nq.gz
│   ├── a4ce72dca203e69b3533a884431d83463c0ce249.nq.gz
│   ├── b4840b2114fad945c0c4ddf4de4d327dd8887ac8.nq.gz
│   ├── b4aad6d3b572cdf7d15e4733ed4d97778cf26cca.nq.gz
│   ├── b6d47bc0edb64530c4286d8e115147c7070e9631.nq.gz
│   ├── b72692daf5ddea9d400073caa8004a49e3387503.nq.gz
│   ├── b9afd4aaeb2e24f2190a4c1d0e24d471f5c06491.nq.gz
│   ├── c0feb0cfe375c3f34af440d477caccb6f5a31afa.nq.gz
│   ├── c1674f2dd0ba3560502e19399717d46bc591ea46.nq.gz
│   ├── c843229d88ba9cbfc24efab737e2d4e376aabb4b.nq.gz
│   ├── c89ddca8a4497b1d5a415999ec89ad0b5698fa62.nq.gz
│   ├── ce7447a5d03890200b91c6fb91319b01449d21a2.nq.gz
│   ├── d00491fd7e5bb6fa28c517a0bb32b8b506539d4d.nq.gz
│   ├── d3a8311050e54c57c5be7cfe169e60a95768812c.nq.gz
│   ├── d4bb86e57c8a7698ceb6c678f75bf674ce8725f4.nq.gz
│   ├── d6d9abcf2001e8c7bdc28c0e42f599dfe80489b0.nq.gz
│   ├── d802c9efb6ef09c4c6b42814afa18d13cc583518.nq.gz
│   ├── deba29737390f7fa70693ce59b1cdd3f390baab4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee1124730967f986a6b4d36fadce3df602140703.nq.gz
│   ├── f048e44298f86da6d42b3f4c723bb9b7d3b68c40.nq.gz
│   ├── fc24e949d0b2f43aaa983ee192492431ca1a2057.nq.gz
│   └── ff065de8388e74a375868286370f8e95582b80da.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6becc485fd13458ee982265ef8ed9b7e008d808b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[klen/dealer](https://github.com/klen/dealer)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
