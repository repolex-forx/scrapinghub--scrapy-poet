# Repolex Knowledge Graph of scrapinghub/scrapy-poet

RDF knowledge graph data for [scrapinghub/scrapy-poet](https://github.com/scrapinghub/scrapy-poet), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/scrapy-poet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f06d684b6b1a40625eb846680225cb00a67bf7ec
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f06d684b6b1a40625eb846680225cb00a67bf7ec
│           └── chunk-001.nq.gz
├── blob
│   ├── 05009ab97e11e2d5981c58ed4ef7e1335f6a14a1.nq.gz
│   ├── 0d828e030b68fc7b0add82cc9569c390a2679250.nq.gz
│   ├── 0d83899bf4f6ddf379274f36dc5eb24dfdcf3589.nq.gz
│   ├── 13b70036ea18f30d6f576d116aab51248f4fc697.nq.gz
│   ├── 1a1508d4d3267491a608dcfdaa38e23233225680.nq.gz
│   ├── 1e47839a4b510d07eaf5bc023d657d3ee4389a4e.nq.gz
│   ├── 2808e29fc8ae5618aff3fad4f14cac46e9ee117c.nq.gz
│   ├── 2841a0501ad21d1f40715cd8a923e77cdcdaeaa8.nq.gz
│   ├── 2921b9290f73737c3eef0bb5f9ad63cba0ba42d1.nq.gz
│   ├── 29595a301b13276057e9cba98937f31435d23b65.nq.gz
│   ├── 2d832e7d002c49f8d40dab0721075fd065076f44.nq.gz
│   ├── 336b255dcbeec2b1682d86822ea1233a3de51cef.nq.gz
│   ├── 375cd01165f05db8ecfa109db202bdde0aa6ae20.nq.gz
│   ├── 3a145710ff5929507b21dbfd000f8cab0fdc45ee.nq.gz
│   ├── 3a50e08191ea2edc00801205d03a820aa42ded4a.nq.gz
│   ├── 3abd521a848af08953dd575c7cf41ca8aa4eac3a.nq.gz
│   ├── 3b7f19f45d21b132436557cb080dee70ab65afbb.nq.gz
│   ├── 3edc695dcea5c89ff59d72a47fd30323fcfaa016.nq.gz
│   ├── 456b47280442b8108a10ee999e536903840b59da.nq.gz
│   ├── 46265ad618cdc3c8909546d36520399aff4cf5db.nq.gz
│   ├── 474607ffac2ca972131311d6b89a63cdef2312fb.nq.gz
│   ├── 4a04b8907ebc5282a87a301137eb94742413fea6.nq.gz
│   ├── 4b9b2f4538205cd3b97a4a8e20563bd5819c740d.nq.gz
│   ├── 4fc482942ffd66f368597fc3acb5b80c207d0de9.nq.gz
│   ├── 53046c033ef72179e6e8e3c241e58d79b0cfce86.nq.gz
│   ├── 53e7fea39278403665bf21eab3ac709f70f17bf1.nq.gz
│   ├── 54ece9e598cc911e35eb6d88f3cfebdc6dad381c.nq.gz
│   ├── 55e70186434e65bcc467b07722564b85e0020f1b.nq.gz
│   ├── 64758359ab2215a6a72e8852697f696c1e883a97.nq.gz
│   ├── 697ed6924a6241e7333d21179d4284701dc1d023.nq.gz
│   ├── 6a71cc227120cc00fefe6744c8d48094e5c70f52.nq.gz
│   ├── 70d958f03e151942dd5536e46823160a0171930a.nq.gz
│   ├── 71d61817b8d6dd24b837d1551ac0cc69040a90b0.nq.gz
│   ├── 7903ea5c0b3d62e5a2bb9ed03b05bac81afeaf00.nq.gz
│   ├── 7b0ab2fc123cbebceb7fcc731f4143ba6d8cc28d.nq.gz
│   ├── 80f12343fd0d849c8342dbd9e5b661f225bf9d5e.nq.gz
│   ├── 81fbd9dc1332d699371bd941639957311a5474f4.nq.gz
│   ├── 83ca5ad1b771832ecb4be309517678033e30bab4.nq.gz
│   ├── 84309c07b9cac869d64c29ca4150ee3d94379500.nq.gz
│   ├── 85afd743cd8918b022f88c74d7900abe6f0c1b8a.nq.gz
│   ├── 8966ef8813115425886cde5df337f44ba88a7a92.nq.gz
│   ├── 8e1ee2669a233a6f3f470961418b5ad777f79375.nq.gz
│   ├── 8eea31c6cdfbe17afd024b3fa3a23290b45ed48a.nq.gz
│   ├── 92fac027e341b0f4e534afcfc2b3c2943b9ce198.nq.gz
│   ├── 9c8376b246905e0a787247c8fbf9e894a44b97ca.nq.gz
│   ├── 9fe2099beeb1a2e545987bfffe35c62d4b1252da.nq.gz
│   ├── a2773dcf2a915f4d61256ef383aa9f7b1fbf9e8f.nq.gz
│   ├── a93288096a33fead9da7edb948eaa765e1288ff6.nq.gz
│   ├── ac933a6d16564f240791c617cf227bb223b96380.nq.gz
│   ├── ad233a557a4f94a9ccde5a13062a44552158cd20.nq.gz
│   ├── ad8f6e3abfdbfcb86c33918306b1157659442546.nq.gz
│   ├── af356cbe1df6c4feb18eb6c0f2a7e8e803e54b85.nq.gz
│   ├── b0e7563f6379b6e7d95e99dc7a234d8b87904724.nq.gz
│   ├── b29e6e57e078fb2f815074dd4d05acf6c5e829b0.nq.gz
│   ├── b8585c3217630bf58ebadd34962709be1a25f69e.nq.gz
│   ├── c174f48fc17adcb9613517006ebfa6beb76aab11.nq.gz
│   ├── c287d83169e98e22ae84a842d64e1619ad8c277a.nq.gz
│   ├── c95570fd1d75941876975fc3955dd4322f749571.nq.gz
│   ├── ce5d5253e226613b7582debe1920e2b04b5fc4f4.nq.gz
│   ├── d3b8d7890e544739589f13f9e330bd9ab58b5454.nq.gz
│   ├── d51549be4bb656f4abf7a59f42a25898d87564f4.nq.gz
│   ├── d8aa6b984fa2c4c4891f114100d205ad99801b34.nq.gz
│   ├── e04f5488e59bfdb2a629943637cb84a373f9e4c8.nq.gz
│   ├── e0cace55ab91e3458a457f8b9975e1e470a1fef7.nq.gz
│   ├── e185e516b2617c5ac280a5e1a6571401b6720566.nq.gz
│   ├── e22e024abaf5d64f0bc373a7f8daff28be17553f.nq.gz
│   ├── e3f579f33b8f3daea7128c323d68575bc74858c5.nq.gz
│   ├── e41af5ee836c598a7482b29ee31f1cd751320316.nq.gz
│   ├── e647e18078dab05f75dc79df0f716a6d2f8d5e8b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e70aaacee4fc78b8be8abbdcbe22bd2831e6a0ab.nq.gz
│   ├── ea34b118e092dc0d868de7db9057453cb80af4dd.nq.gz
│   ├── ec79596512d76726d28a6a07faea33b0479b0787.nq.gz
│   ├── f47c0027b5da0d633cbe4dc54ef5c88d956ba207.nq.gz
│   └── fc3129570d685090fc75dffbd8d2709713de5951.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f06d684b6b1a40625eb846680225cb00a67bf7ec.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[scrapinghub/scrapy-poet](https://github.com/scrapinghub/scrapy-poet)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
