# Repolex Knowledge Graph of modelcontextprotocol/docs

RDF knowledge graph data for [modelcontextprotocol/docs](https://github.com/modelcontextprotocol/docs), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/docs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 573dc60c2e7aab2605b29d0bf27194aa7b02e4fb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 573dc60c2e7aab2605b29d0bf27194aa7b02e4fb
│           └── chunk-001.nq.gz
├── blob
│   ├── 000dbcff054698b13a912c2dae811b9eaac0d03c.nq.gz
│   ├── 03d9f85d32bf343db07e6e472d555d0a7be41c58.nq.gz
│   ├── 05c32c6053c1edd9a2faaf1b6ebf565c6650fa28.nq.gz
│   ├── 08c2768a177eb40b4ece78c37604e25756266849.nq.gz
│   ├── 0997ebcb32b82fd0c4c8e100e49c22055c21d867.nq.gz
│   ├── 0b38523edddf324eed42702f9f682e54300988b0.nq.gz
│   ├── 0bac103069d57411ab6bf814137e62f42dc0381e.nq.gz
│   ├── 1003197ef15c16827d918508d4f8ce8e85649f52.nq.gz
│   ├── 11bfe8d480c8cd6b685c0e22d33f8534ae74cb09.nq.gz
│   ├── 1cf5678da4b8dc95a4fbfc27461270f8d653d56b.nq.gz
│   ├── 297d68fb9bf31625beb18bf820e3760d6ea9c149.nq.gz
│   ├── 2ecc0dd1b08f1eda0e159ea31c364b209f9cb6f3.nq.gz
│   ├── 3847eaa8d214af3437680b7a745972ca602e3312.nq.gz
│   ├── 3b740c5509fc1f0abfdc70aa2af235f77272d319.nq.gz
│   ├── 413131cbe2d8a0a3218df37c03aa9abb0487c5eb.nq.gz
│   ├── 42093fc7414a40678b789078543a96fabc5ad7fd.nq.gz
│   ├── 45eb4ec2b631ef0eee789b5fe6d11f1c0a9b5c9e.nq.gz
│   ├── 4b05ca139ac412b15d4388fd7841e64e79253488.nq.gz
│   ├── 4d01dd98fe258518834611e09dea44bd742f310c.nq.gz
│   ├── 5008ddfcf53c02e82d7eee2e57c38e5672ef89f6.nq.gz
│   ├── 50eb8eb4afe66b0d89894d264cabfe6f859b4730.nq.gz
│   ├── 52fb1f3513c46321bd42466e44387b3402b318f6.nq.gz
│   ├── 52ffc67fea5d4046d9a72ce5acd9f66f7bfbad3c.nq.gz
│   ├── 5b08c738cf89cbf41218a0f6f7ace2dd2355145e.nq.gz
│   ├── 688a2b4ad0f92090bf0033ab5eb3b20fce1a8484.nq.gz
│   ├── 6b0df2f6d5618ac55026c2489b4ffa3d228e8926.nq.gz
│   ├── 72065f5328f5137cb7217d5c6e2e51a07369966f.nq.gz
│   ├── 73b9f9faebe573ef77bb640e29d47ec8b76c67e6.nq.gz
│   ├── 7b440f1abd20f8e1654b255be952de9c99fe41fe.nq.gz
│   ├── 82b1c162f79577b04e106c5ddebed9e220e777c0.nq.gz
│   ├── 87e1c0c6f00e661ae72b4ee3024988a639fb56ab.nq.gz
│   ├── 897c1e3f08b7abdcf4384816048309a189f4f875.nq.gz
│   ├── 89a2b9c6a522565509776a5397ac3e0ce6bc7e17.nq.gz
│   ├── 945c0fb309e265e87a70d6675b60617989f46bb5.nq.gz
│   ├── 94834e8a5f3ca42ea1c9c5ac87c77bbac5a09072.nq.gz
│   ├── 9df6dc56fdef6ad97ee5e656180d55ba4dec1670.nq.gz
│   ├── a90bbb8777a723563f2d92796da7916b9e26de66.nq.gz
│   ├── aa5fdd9240c1e1ee6ac8acf174503006ad38ed0d.nq.gz
│   ├── ada4364ea34401ca98a21117032c021dfe23ba56.nq.gz
│   ├── af71d074d601aa62ba2311e7c544dcc224b8eec4.nq.gz
│   ├── b17149b31b6c79ddb7f0756e3cecabfc2002f75d.nq.gz
│   ├── b337d050c7f982e40637c166bc6960717f83e259.nq.gz
│   ├── b7c427b48bd7d5aab67db5ea891beaf3bb170b1e.nq.gz
│   ├── bb108ed3b79c43d00db977a388135be42978c788.nq.gz
│   ├── c57e7c756477da11be3899f7eabc2ba4c85cf888.nq.gz
│   ├── c6a30e88ba7461b29ce28f9b43c2abfbbc94be87.nq.gz
│   ├── c98984b5c48aa42e430017ed6d67d102bc0a8bf8.nq.gz
│   ├── cd86826abfbb959f7896bd7d3c184489a0ca0d35.nq.gz
│   ├── d1a8b97261a96a4f80a1ccbe668038df2b138f8d.nq.gz
│   ├── d234ac539279c06a2874b9325e9a75672200b767.nq.gz
│   ├── d8e4f803db03d48d6b2d1cf014fccbf330f88553.nq.gz
│   ├── ddfe90a3cab4f45f5ac86bd1377ca8f7401ce738.nq.gz
│   ├── e699ea7a0f887b528f9bc2aec8065a70c8d3f550.nq.gz
│   ├── e8d72673bed988ab2e0b7ed9fdb02594df029c25.nq.gz
│   ├── ec1673ac2cc24c6887d1dfdfb21d0353e94c8fe2.nq.gz
│   ├── ed8b47328d00cb6ba2ba0fcdf48463b32cbde70a.nq.gz
│   ├── f401638d4f1ce6505164b47a3c3c4f8bb71bc367.nq.gz
│   ├── f48d0d39792cac7ca3b604b355074cfab7c5c280.nq.gz
│   ├── f83a586e7b0b8a6c7305472a8179c14e28fe452d.nq.gz
│   ├── f9992be461d3870a4c8fd08dc77d67a5f16676fe.nq.gz
│   └── fd17370502d949a75babd5ac45898974c0d4eff8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 573dc60c2e7aab2605b29d0bf27194aa7b02e4fb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[modelcontextprotocol/docs](https://github.com/modelcontextprotocol/docs)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
