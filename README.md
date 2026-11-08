# Repolex Knowledge Graph of stanford-crfm/EUAIActJune15

RDF knowledge graph data for [stanford-crfm/EUAIActJune15](https://github.com/stanford-crfm/EUAIActJune15), parsed by [repolex](https://repolex.ai).

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
rlex download stanford-crfm/EUAIActJune15
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2adeb78ed2ec26494fb8e6b0a166ad2d037e30c9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2adeb78ed2ec26494fb8e6b0a166ad2d037e30c9
│           └── chunk-001.nq.gz
├── blob
│   ├── 0197859851df39a75bbb833f867a6c42e8b62c19.nq.gz
│   ├── 067f478628e9aaae69f0361956ef3016cd7546b1.nq.gz
│   ├── 07052c19f5743b590aee800c6e9173821ac3eb43.nq.gz
│   ├── 0e50de73245177e5d7fb4691027e597824cd1445.nq.gz
│   ├── 1320432aa4cb528019a20debba73aed0c77e504c.nq.gz
│   ├── 13dd3d971c669afb59cd2b316b6025feb74b4724.nq.gz
│   ├── 15095c84e4732c5ddebb1a5fa3d75c64043076d6.nq.gz
│   ├── 1510a86dca10387a01f3a3fe52eb1da4dc54841e.nq.gz
│   ├── 1e096532fcbf2b77c026726a9d3d827a76467fed.nq.gz
│   ├── 270ce49b68462254ed4bc3f7112da9d4afee76e3.nq.gz
│   ├── 29165616ce3afb00464b2f1b794a10044fe62185.nq.gz
│   ├── 2a807f34f1ff1c51e1fb12b45e0b81fc763f2801.nq.gz
│   ├── 2ddec7e7812e1f3fca02cec75654c39f432b5c15.nq.gz
│   ├── 2f680f6cfe939cb60722758b47464f802d47176f.nq.gz
│   ├── 30335efa34bae56244c61c61710b25608cab6154.nq.gz
│   ├── 3bfc05ca6e539160ed2b52a164f06d58f4e79aea.nq.gz
│   ├── 484b45ae72fb73718baffa76f00a0b01699dce6e.nq.gz
│   ├── 4a33c489f164b9b2b5f0798417949e0e79392805.nq.gz
│   ├── 4d01572112ae28d81eaf6d59fa0e57e0fc5fe1b2.nq.gz
│   ├── 5126c88327e4f05f6efc01f7d45552d9790ba776.nq.gz
│   ├── 52915c5a9a291414600a343b000f03062286acc4.nq.gz
│   ├── 57de8f8f0153d231f97ff38a1be6a6da99fef314.nq.gz
│   ├── 5a5d98ee031f8797a8915fe1fe72345b759832b0.nq.gz
│   ├── 5f889f52135a4a70f6958fffddabd4bc9ff1a516.nq.gz
│   ├── 6cecbdf0b27d6704a5ebf90b507c46a6b34d0d92.nq.gz
│   ├── 75e0e372b339b25d693e8949659dda48c4221aa3.nq.gz
│   ├── 790bf0985669ee035dbdaaefbebdafe75bb96ce3.nq.gz
│   ├── 89d49a11f1348b7cad58d685cc7e6f0f6fbdc79e.nq.gz
│   ├── 8c9949562887662b0f3a3e721117221a587b2a32.nq.gz
│   ├── 8da658dcd9d5486bf7e6cfbda03d701c3708ec4b.nq.gz
│   ├── 9adb23c0fe10a097ed6ed49915f8c6968918b93e.nq.gz
│   ├── a499637442f3a1deec2ac92283b839e66ade5dfa.nq.gz
│   ├── a535de52370eecb125da65af5565649fa6afd081.nq.gz
│   ├── a5c7ccb3a05f9b1df15561ba5b3804ebdcc88964.nq.gz
│   ├── a70124068e5be7903a43b55cfa005ce97fea07cc.nq.gz
│   ├── aec7291712db1e2254346277fe659bce0416ee82.nq.gz
│   ├── b51001579b51117ee452d82611a7fd719afec700.nq.gz
│   ├── b7bea44d3c3498e11ba2d3df04ab949427ba3c25.nq.gz
│   ├── b984ebe175019e26d7ecf8d696b44d123ab94a9b.nq.gz
│   ├── bb160138dd5c3beab594de62298bc998c6f536c3.nq.gz
│   ├── c65dc598a648b5f528d4ed96131f4884ef8328b3.nq.gz
│   ├── d068b5bf5908058735f8dc15e71135a90273b977.nq.gz
│   ├── d09fde50b52572347b9e750aa262e77c234de4ac.nq.gz
│   ├── d27a5686486ac31380ef714e681fbe9673f05606.nq.gz
│   ├── da01cacbe47870c541bbeda06e85f025e4b22ff6.nq.gz
│   ├── e1f5a49bd317b2df2fef363852ff8828b182e0ea.nq.gz
│   ├── e23c2ef34156163ff67888bd0b08bfe33beca749.nq.gz
│   ├── f452bfd04c11a25b0fd2dd6e79494468709d4aa5.nq.gz
│   └── fe8999f9c49d82e3febf7cecfa69839e00befdf5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2adeb78ed2ec26494fb8e6b0a166ad2d037e30c9.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 56 files
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

[stanford-crfm/EUAIActJune15](https://github.com/stanford-crfm/EUAIActJune15)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
