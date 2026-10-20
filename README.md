# Repolex Knowledge Graph of ionelmc/python-redis-lock

RDF knowledge graph data for [ionelmc/python-redis-lock](https://github.com/ionelmc/python-redis-lock), parsed by [repolex](https://repolex.ai).

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
rlex download ionelmc/python-redis-lock
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e448f12f49aa4a07885fe8cd02eae19a7e75fa51
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e448f12f49aa4a07885fe8cd02eae19a7e75fa51
│           └── chunk-001.nq.gz
├── blob
│   ├── 0070e3e909b1cf06620c397a58c460a7c50cdd8b.nq.gz
│   ├── 08936d99094e1b728f76a1a13bc81ce1cdbe0cb7.nq.gz
│   ├── 150ce95711ee31b168f283da938352ce1e4a8c30.nq.gz
│   ├── 1d5bcae1c0f4567551b7d4ae081682e2157ac8c1.nq.gz
│   ├── 2170539e54470ea3207ba21b765b70924c62f6a5.nq.gz
│   ├── 28cf28d2e4f5619ced0feb6611c574af5f53d104.nq.gz
│   ├── 2aba428cf609aa2e25d13b823d1386fb56bf2fd7.nq.gz
│   ├── 30aac7d6eeac5a0f853eb2537f366650bee72f7d.nq.gz
│   ├── 424c959bd712c8187e689fae1368104820163d0c.nq.gz
│   ├── 466d648d6a9a1b62cade23ce13304cecc12fcf31.nq.gz
│   ├── 470d386bbc7bfc1292b429080eb732647bad5363.nq.gz
│   ├── 49e39a8f77fd6d49094502737913e0a2235b5607.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 57de9ee3dc5158c37f3843cbc4f6881c145346db.nq.gz
│   ├── 590dce183d0b61b4e4f40fb1188008b72c2f817c.nq.gz
│   ├── 640513ce35177babc2c37d877eaba7784d154e0d.nq.gz
│   ├── 67e2fdad9e049e1e98fb48c5bf21a5e379e59724.nq.gz
│   ├── 688f86b864f55fa6c2dbc0d5d1a027309ab5cad1.nq.gz
│   ├── 6a618a9538fc280b971ca15bbe1631a1eae43bf2.nq.gz
│   ├── 715897b3b99c8b0555fe74748992cc4e156d649b.nq.gz
│   ├── 71cdb22c11a2e9fe5d15555645da2d6a9dfa16c2.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 7525972955a296377fef81b74e72e28a3e03bc19.nq.gz
│   ├── 7c2ecfaa7476b4524eca1d59e124c402cc3d9d8f.nq.gz
│   ├── 8b9a2aefb27a9faedf8eabf320a796332bc23797.nq.gz
│   ├── 91f3826011d6020e7b3c1c63b2de7d7bc81e745e.nq.gz
│   ├── 92849f4b3af983459612ec77e9f0be783eb301ab.nq.gz
│   ├── 94e02b11eb81d7c4ce4487e9694ef25e1aa53e8e.nq.gz
│   ├── 9aca3f0dd8cfc2243ecfd70a6300584f22bab199.nq.gz
│   ├── a2d480bb79405d1371da3c20e8fe0f3999995624.nq.gz
│   ├── a52e40ee4b9922be2f83acf0df4c450a4cc89ece.nq.gz
│   ├── a629e09ac149daa611c42a6df20ccdc77913fcea.nq.gz
│   ├── ab47d87f9f9a7b108ce4e2680848d872c17b0c57.nq.gz
│   ├── ad842d51d97d389707466a2f855e895fa0b9f6d6.nq.gz
│   ├── adf6656a2e51d882c66d7413b2b8b6abebaffeda.nq.gz
│   ├── b1f10c166aa3a99ce697799f477abf3969dd2ca7.nq.gz
│   ├── b241854ae6996e5c3f6a4ddfca442113cbaabb69.nq.gz
│   ├── b264c43b1aec76887ebf33bea9123260b942c121.nq.gz
│   ├── bf3c10e6d334082496f66736f278feeefbad29a0.nq.gz
│   ├── c03e307ab39cd6807b9bc0d8f404e716707c2533.nq.gz
│   ├── c1a280731498687c7c31c989352de02af0ada697.nq.gz
│   ├── d12c6a1c46f561705b4a9cfd8a19342616d12eb1.nq.gz
│   ├── d52131fca5b08b4425759f5a314264d169dd588a.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e642211365f960e9478ebf5b353eb9d616705125.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed96ce9f0d75ab6d888244db2351a5d281956649.nq.gz
│   ├── ef4bab48d19cbcf6c1b9398b5f1d09475ed5e8cc.nq.gz
│   ├── f1a6472e3bcb22e071bd484365af599740170477.nq.gz
│   ├── f5d7125db33d02cd8c950fcbf60624f4274cb588.nq.gz
│   ├── f95eb78d8a603b0fe5d17560d0dd04877d55c71c.nq.gz
│   └── f9bc13b2110c91b3f28fe3fe568fdcdc9e1e7b7f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e448f12f49aa4a07885fe8cd02eae19a7e75fa51.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[ionelmc/python-redis-lock](https://github.com/ionelmc/python-redis-lock)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
