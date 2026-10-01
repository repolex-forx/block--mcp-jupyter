# Repolex Knowledge Graph of block/mcp-jupyter

RDF knowledge graph data for [block/mcp-jupyter](https://github.com/block/mcp-jupyter), parsed by [repolex](https://repolex.ai).

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
rlex download block/mcp-jupyter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cefc875bfdc23660b3d2f79cdcc403f00d94189b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── cefc875bfdc23660b3d2f79cdcc403f00d94189b.nq.gz
│   └── repolex
│       └── cefc875bfdc23660b3d2f79cdcc403f00d94189b
│           └── chunk-001.nq.gz
├── blob
│   ├── 019d0cb773bcfaa947008a0cd9588f9caff18a2e.nq.gz
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 08d1a4b1e63030d319effe8f57ed9707bc2ec1fa.nq.gz
│   ├── 0ca00c428e5b54faa5d13eaf2c9350f8066d6374.nq.gz
│   ├── 0cffddcc0656a3c54042bcfbb8586e03f4f4d9f6.nq.gz
│   ├── 11b0da11631f612c6760d4928fec5ac6a185bf82.nq.gz
│   ├── 1e87365c720430d6f48597596de5b70769324002.nq.gz
│   ├── 2594d49169d42b822d56e7e5ced70530b13ef293.nq.gz
│   ├── 289713975cdf51aa1d37e8ad35023c18f2996a58.nq.gz
│   ├── 2ed0fce2ebdfb1cac7180f40d9bce226abd1fc7d.nq.gz
│   ├── 3755731e06ffa9c64d47be635569d405effcd581.nq.gz
│   ├── 3f19a959cf50d55b084ed6db38432a9493e7cce8.nq.gz
│   ├── 40c0eefd1a20b46e64172bbbff3bf8c4031beb16.nq.gz
│   ├── 44c937f4cba8e10d904e15dcc248fe7a7f0ff084.nq.gz
│   ├── 557e01243b989486ab8e9b9bd9a01fab933f93e4.nq.gz
│   ├── 594b6b970683e4d88ddc910da3963b64716ff9a9.nq.gz
│   ├── 64615f479f9168e70ff1e95466923c1d7848cd30.nq.gz
│   ├── 6bbb0485554a5a7ecb6709a20cd54cd8f2d940b7.nq.gz
│   ├── 6d6d0b2c493172c9c282c85d9837dc90f6149292.nq.gz
│   ├── 7015f827a367b8e0866321ebf3210247a582002b.nq.gz
│   ├── 736337aefcaff5ec65fbd635731c692609074231.nq.gz
│   ├── 79a2c8dd1660b19ce288eba76709b69476f03c6d.nq.gz
│   ├── 7be2e1bcb725d4f1dc1f29482635acedcd803e46.nq.gz
│   ├── 7fb23ffac34203f50b6dea57d43ace2046946107.nq.gz
│   ├── 8119447db172de6647101fcf49e0610e5e11f09e.nq.gz
│   ├── 853e72ff2462b43511ab3075ee9dca432f24006f.nq.gz
│   ├── 87acaadba3d3a97cd17d084637a6cdd94caf2167.nq.gz
│   ├── 8aa0adc9df63e66ce2b4e9ec8409b335cc887020.nq.gz
│   ├── 920d7a6523b879dba941c7d5dcb14938e03b5125.nq.gz
│   ├── 9756c5b6685a7fa67f41e11bc2cb6b990c2b12b2.nq.gz
│   ├── 9f71a5da775bd99379fa5c4d5bb73dc816d78bdd.nq.gz
│   ├── a0b81023b93d59be5fc74729ac1db48423aa27dd.nq.gz
│   ├── a2d4aedb90e6519fa6f41debf33da4f648ae34ee.nq.gz
│   ├── a5fe01223e67a8e5b54a56ff0738fc07c4991e83.nq.gz
│   ├── b248eb2e5dee2c37f58ab867ab87be47ef804386.nq.gz
│   ├── b2d6de30624f651a6c584d4faefafceac6302be1.nq.gz
│   ├── b523e6605c9ea48b07a7bef499fb420cee8e7618.nq.gz
│   ├── c01d54bcd39a5f853428f3cd5aa0f383d963c484.nq.gz
│   ├── c778f573ef8a984c76a0376a6f3ebc0e0e25a3aa.nq.gz
│   ├── c80e1e138cc072225b18dc12969d27a015787ed1.nq.gz
│   ├── c92dc0613d055572b3632d5b5555b1d84f56b430.nq.gz
│   ├── cc17d794d8718ff258b63659cd8931a1cb004e08.nq.gz
│   ├── d3567aca79286c20d602490bdd7bf6b6f4cb2fbd.nq.gz
│   ├── d40a0b907760e1b1210e7023cc9c80881f20dba4.nq.gz
│   ├── d4839a6b14c11e64143d1d200c2d4733595ffc6c.nq.gz
│   ├── d5206cfb748d46eb91e5031c15c491adb9e13df7.nq.gz
│   ├── d63bb7a862b3b08110fe3c8ba573aa944d44c7e8.nq.gz
│   ├── da9b877d2f27af6e9dfe3de80b57348290a4a0d7.nq.gz
│   ├── dbdcdde75256878db577b14fe42926b5139e478c.nq.gz
│   ├── e5207aa520ebc3d445b66d6b7a99f98bcfcce48d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb35dee23caf75e5ea16d75e0d727a479d3036.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── e9b6c2ecfab1fdca849bb57ce02bc82633028a10.nq.gz
│   ├── eb114a2a38eaec1b5d53406e555ddb916dcefc4f.nq.gz
│   ├── f19ffa42d391cb48cb84a5b1d311f94e938001d4.nq.gz
│   ├── fa84de075d9bdd727ef1e3231e801e3816e2177a.nq.gz
│   ├── fbc555c397f3660ab1d439f964884526524ff9a6.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── cefc875bfdc23660b3d2f79cdcc403f00d94189b.nq.gz
├── filetree
│   └── cefc875bfdc23660b3d2f79cdcc403f00d94189b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 69 files
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

[block/mcp-jupyter](https://github.com/block/mcp-jupyter)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
