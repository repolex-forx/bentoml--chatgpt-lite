# Repolex Knowledge Graph of bentoml/chatgpt-lite

RDF knowledge graph data for [bentoml/chatgpt-lite](https://github.com/bentoml/chatgpt-lite), parsed by [repolex](https://repolex.ai).

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
rlex download bentoml/chatgpt-lite
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4b4d64102b24506f1f7110741e85b20407f96d7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e4b4d64102b24506f1f7110741e85b20407f96d7
│           └── chunk-001.nq.gz
├── blob
│   ├── 024287e20909105928e46aa5a46fc4524221301b.nq.gz
│   ├── 04b5f0a43ee6514051107e71b4c1dc8157d31a90.nq.gz
│   ├── 0aba7a90a00067033b41c8a6adcb12a03152fda8.nq.gz
│   ├── 0eb831fd3f83deadb29cb4fc846e9feb919a61c2.nq.gz
│   ├── 11484e8c2830064e85df71b00507a2498c7d595b.nq.gz
│   ├── 15277cd5d27f1cb59ae50fe978255f3196319bb5.nq.gz
│   ├── 1697a9912b7f5bf383c48375b98eabf5cb713959.nq.gz
│   ├── 1b3d5dbbfd9cd95787d9a167e39554cc502aac78.nq.gz
│   ├── 1b7b5ab2bc5266b2e25dc26aa2355a018bf70cd3.nq.gz
│   ├── 214e0992ddef28ea547b7842dd4a4b5bd607a641.nq.gz
│   ├── 2a6a0ad4bff31353d13db5f9dcdd1fc6844c1b6c.nq.gz
│   ├── 2c588a9349524a353d0c0125ff605c971d98e5cd.nq.gz
│   ├── 2faee9ec3530908f39c453f209027aa2f0e187bf.nq.gz
│   ├── 379a6b93cc13505e231d35bafff591f51604f171.nq.gz
│   ├── 3a433c86b57767318cf61ad22c6f680ba8a10290.nq.gz
│   ├── 400bde250ea09a1d4f3605d2ace05d5988b35412.nq.gz
│   ├── 46fef46e4644a36b0bf9291a46da7a13e2aad864.nq.gz
│   ├── 48b2f42e001c01a2c6c87055fd9c9467f0c7fac0.nq.gz
│   ├── 4ca73f764010c580b700216c1ec831bb8204320f.nq.gz
│   ├── 4cc2134e63140c58b430686310a3cd49460d11bd.nq.gz
│   ├── 4e05ba34cb3ac3b6b098d6737448ebe431849c94.nq.gz
│   ├── 4eceb681dcd81c6d2f6b7a25f4aa4e30cc29ca87.nq.gz
│   ├── 570e3e50bdfa175a54d01f46c8bb84ac59e227da.nq.gz
│   ├── 620c7d81f90b455bd9a8ee5a37d4d4f335443076.nq.gz
│   ├── 6a520ec88284911bea17c35e7d1876b7dc738bf9.nq.gz
│   ├── 70732dd504af4d44fcb101f853e2eb1e04e008c7.nq.gz
│   ├── 7452b5dc69b2a634c86779ee4cd4c13319549b43.nq.gz
│   ├── 76a341706ea27d9e4d51f043b9722d3f062b3a90.nq.gz
│   ├── 7e61c3546e36153c6387e71637c980cf5d54a2e0.nq.gz
│   ├── 85f717cc09ecb1153d6a4c0962284e09e4b8d6a9.nq.gz
│   ├── 8dcbfa043c9414725a5d6de8286a81e73e3702b1.nq.gz
│   ├── 907df283cc814acccab03c5f6cb166d44e8b8d2f.nq.gz
│   ├── 97fe40c5c94b0ed5e373d65185e6664cacd9d192.nq.gz
│   ├── 9f1d29a95ac09b38f3f4623f2a1c09d09a63470c.nq.gz
│   ├── 9f27cafd7aa3645f5942ced0177c162d47f8b4bb.nq.gz
│   ├── a28d6071c209611d06b3a423285f26d49ab7a920.nq.gz
│   ├── b3d6ebc92d75b4b194ec7d6d37d5a523252f1657.nq.gz
│   ├── b6ea752e3807ee8d34858c5012646831a44a2ed9.nq.gz
│   ├── bc5ee5adb371b6347c8767f1a28097b892ade754.nq.gz
│   ├── bf83fae6c6c86a229e65d867953f1e68402ad7e0.nq.gz
│   ├── c476c0eb5b08947947e3c8db6eaf65043e33059e.nq.gz
│   ├── c9d3c05b63b0a979b4bbdf0dabf6e333f12de36d.nq.gz
│   ├── d1ae10dc1491af03f523a7cc0a1b467731536a1b.nq.gz
│   ├── d5f7f5c8391b28c10c35b73a459700cd7adec449.nq.gz
│   ├── dae199c31e31b10b5b0cea28accebe1f839fcd53.nq.gz
│   ├── db5ddae553c9a7729c442e4eb375e3461b5825fb.nq.gz
│   ├── e00c13cb5e548e41b955083747c4d4555b6afa28.nq.gz
│   ├── e55eea98e315d0c511836d48b3ca40de84cffa62.nq.gz
│   ├── e5cf66295e21e30778bfeff2fc7e550c581b1459.nq.gz
│   ├── e94a359130c88b63ec072247a7b52080abc6dfca.nq.gz
│   ├── eabd5a9a8b7e1f91bd55f629e695d419d6d75882.nq.gz
│   ├── ee55bfb6d6edbb8248ea7f12cc5b175411184946.nq.gz
│   ├── f2d79f4d4fbcc76f432e2e9de6583942b370ce8f.nq.gz
│   ├── f4cc252ae6deb40a202468990358df10964306b0.nq.gz
│   ├── f8879953f9b98f4441345d0c33330ff2104dc5c0.nq.gz
│   └── fe76121209d2eca7df9e7f6a76aaff4d6af6767f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e4b4d64102b24506f1f7110741e85b20407f96d7.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 63 files
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

[bentoml/chatgpt-lite](https://github.com/bentoml/chatgpt-lite)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
