# Repolex Knowledge Graph of samuelcolvin/smokeshow

RDF knowledge graph data for [samuelcolvin/smokeshow](https://github.com/samuelcolvin/smokeshow), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/smokeshow
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6e982a3d08dca518fc27cc6075c0d33916edba56
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6e982a3d08dca518fc27cc6075c0d33916edba56
│           └── chunk-001.nq.gz
├── blob
│   ├── 01fe6077d77c8a34e4e2045df2baea06f5df986b.nq.gz
│   ├── 024f1c0923df4ccb0a2fc798ba228081e9bf5003.nq.gz
│   ├── 028415782432a894e19d43c4511e37b1fd8e23e2.nq.gz
│   ├── 0b8125b54fae9c4c983812c5ea6fe3725f66b868.nq.gz
│   ├── 11ee49cfabf7bb96074ee4ebeaf11c21b84da77a.nq.gz
│   ├── 134470f0b48a1fbc9d669307a332bea8a7ef0ad7.nq.gz
│   ├── 19da74628332b563ac8610603a2f41abf585aae7.nq.gz
│   ├── 20f59ebf837d40b77679a1b2ea9fc5737a274ab7.nq.gz
│   ├── 23e86b6699d41fc270840c8068f7f61353b03e9b.nq.gz
│   ├── 2f9ed075c35bcead08c076e06d6b37c7e258c651.nq.gz
│   ├── 33b7f9c8f9acea776f15537396b3ea77cd0d8d36.nq.gz
│   ├── 36e03f7643e89d8897bd613b879d8cae2f7162d1.nq.gz
│   ├── 37f55f10751c5af9af6e13c66075dbc328acecfe.nq.gz
│   ├── 3b88e6e816c5179d08fdc831ea7243a0bc8159da.nq.gz
│   ├── 3f86c749135add11fce668b89195c4c752cb8ab1.nq.gz
│   ├── 455963f41782c79a8b56535770d474fc3decb00c.nq.gz
│   ├── 486b408daf26f97e11caaeb5bec20acac4b4ca0d.nq.gz
│   ├── 571ca40cd573df64f323528b771ee334eaf36464.nq.gz
│   ├── 575c00ba3f9b4c914f673ecbe730f7f7d4f79698.nq.gz
│   ├── 57a8f405bd01431e8d07cf10dc0a7e2f126be52e.nq.gz
│   ├── 5cdf1fdb4333a0adb0368b078f8a05a130985d4b.nq.gz
│   ├── 67ca20b047716c8a0d0e87124649c202155c7c0c.nq.gz
│   ├── 6c06308a15ef7f512edb71cb5f86849f05bb3385.nq.gz
│   ├── 6df287a19b8d560ae6f4600442ee7f9463683039.nq.gz
│   ├── 719be455c0b50adbbd1491cbf4884c2f0d563681.nq.gz
│   ├── 7d21472f2b61a86e68d005dd40218516c913feb1.nq.gz
│   ├── 877ca5c0f684793702fcdddd6245feb990204d15.nq.gz
│   ├── 8a0f1eab183457a1b6335ab9869018b23407d494.nq.gz
│   ├── 8ae85b47fc18b38fa865d02344abdd9017d80a07.nq.gz
│   ├── 8b2b8ee57dda80a89fa523c91c58d7fbb818a4dc.nq.gz
│   ├── 9875a49cf2e49eff81c5893c0f2a3330bd504e4f.nq.gz
│   ├── 9a97ea93de3c201de7c28b66dbf1accb6009dbd3.nq.gz
│   ├── 9d09b76a473bc56c1fe48361e14b1436438da070.nq.gz
│   ├── 9f0286dfd44bcdab09a8ae788fe9123a0ea1af3a.nq.gz
│   ├── 9f787436af231c8456ddf912be983b1e341e3faa.nq.gz
│   ├── a25ed75300e44d76962262342e7c924fee627b1c.nq.gz
│   ├── ab230767bc04bdf471a0eedf1a813ad83ab64705.nq.gz
│   ├── bede0fafcf887d30e2322ac985ed5cb22c40d418.nq.gz
│   ├── c4bedfa85006754aba7ae950f17e0d0867acbaa6.nq.gz
│   ├── c941bf4c82c82325cbbdef7baa890db0f88f8c70.nq.gz
│   ├── cc67d14f4e61ee79daf6711dc92026aa43da860b.nq.gz
│   ├── d8a2c03056a7181498199d6c73029ba8a8813787.nq.gz
│   ├── da2e22d7ea06f71d1048c016d6290725411f629f.nq.gz
│   ├── e40504cbae7c035695f8fbf6ce6f4f63d81c0052.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee5929c44b7f0139607b038ff558f4bcdc1b900a.nq.gz
│   ├── ef806d9ef243379b54786024dc432de43d0c390d.nq.gz
│   └── f1f5178adc4689ada4ca29f3b434931477d8200a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6e982a3d08dca518fc27cc6075c0d33916edba56.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[samuelcolvin/smokeshow](https://github.com/samuelcolvin/smokeshow)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
