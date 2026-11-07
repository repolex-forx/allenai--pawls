# Repolex Knowledge Graph of allenai/pawls

RDF knowledge graph data for [allenai/pawls](https://github.com/allenai/pawls), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/pawls
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1a201c6cbb1b35fe39db4708cf70f08c00b7867c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1a201c6cbb1b35fe39db4708cf70f08c00b7867c
│           └── chunk-001.nq.gz
├── blob
│   ├── 00120c13de3c884b52005cff103d3a9aa3776097.nq.gz
│   ├── 027268f8bdd0a1a2734dd8db25aec5c036c2f1bf.nq.gz
│   ├── 05962f6db20801bbcb6e45957acbebb4ef2651de.nq.gz
│   ├── 0ea6ccf589f1e5e475299536c008a38f335ddfb0.nq.gz
│   ├── 109e11b3a08861ec904aabb76179b6a59cda7983.nq.gz
│   ├── 19f8fc28f7e696998145e0b229efcc65f8c131ab.nq.gz
│   ├── 1cdb467a516a2cfd0740dd505f467eb3f4a144a3.nq.gz
│   ├── 2194320e378f5943d8bf628e8089ef44d6640163.nq.gz
│   ├── 22daff3c8370c2f268bb39564409956801a47843.nq.gz
│   ├── 232db3d739ba5ad5c7963c1c4548f4c494b6c279.nq.gz
│   ├── 29b41acfe5b069beba138d575889b0f14d295972.nq.gz
│   ├── 2b3d35d2a208fadf3dbac0e33874c169d7fd5341.nq.gz
│   ├── 2ba4f87b2fb062007fcc1b5f1ebc4fa0521bfd00.nq.gz
│   ├── 2c8e1a84122b6510c89ea27be4145fac7aef00ed.nq.gz
│   ├── 2d9c2a7bda9da5d466efba5e204feadf5faa43f7.nq.gz
│   ├── 2f3e6d9639f447b0f62d729eb4a39c27ef7c1ccf.nq.gz
│   ├── 2fd6bacb8b6851d559b5ea6f1a909c57cdb7521d.nq.gz
│   ├── 378e0487909986fec30429fa13ab5a31b4f5d09a.nq.gz
│   ├── 3a3df3d908ed597690b3d90b251249a8d585a603.nq.gz
│   ├── 3ac27759bc0548c07ffacfe2c6c86f035aaed697.nq.gz
│   ├── 40f009ea286dd409e70ddb8cfd7b3ca0ef4fcc20.nq.gz
│   ├── 48286f7caaa7807bcc5d6fe26b0bcfb966b9c0fe.nq.gz
│   ├── 49300403c7fa5ae2eb7b495731d40831cb9eacd6.nq.gz
│   ├── 4b4677e1a9de2ec7df90cdc32d8caebf1a32b071.nq.gz
│   ├── 4fecb601a2e579ce412ae1cea0483b83ce76f86d.nq.gz
│   ├── 5025f90eb8431d52157870775e38192b6e65f526.nq.gz
│   ├── 503139ac11dd2cacb3d90c013a7882adbb82fa89.nq.gz
│   ├── 5cf4d46d22f9307aa27685ffcf9158c3b80e4288.nq.gz
│   ├── 5f04472eb8c5bf7d7aed28a06b712a8fc54348b0.nq.gz
│   ├── 62638b5ade2ee58b276c929833ac03561f3b7f1d.nq.gz
│   ├── 6431bc5fc6b2c932dfe5d0418fc667b86c18b9fc.nq.gz
│   ├── 6a1d2feb35651d9dda6738093dcc73d7b33cb0fd.nq.gz
│   ├── 6cb3fe0709ca19f03a5c617a3c0406af516965f3.nq.gz
│   ├── 6f6e961109cfe080e1074fb4fb957b034dcf9958.nq.gz
│   ├── 6ff424996b0d7bae151a4963b25b49ec658c36cc.nq.gz
│   ├── 7259cd8b4fddc15410c1a926d24a1c2c7c435154.nq.gz
│   ├── 79cf0a00a796e97ed50f2bbf9dd81a5ea60a5728.nq.gz
│   ├── 7a7ff6d2e31d1f34b2db267ed28571cef7b21a40.nq.gz
│   ├── 7b24c896a4c99cce8db3dc50fbff255fa92680e2.nq.gz
│   ├── 848da249bd5f1eaa5cd2cc64b0a3b19ef8afd294.nq.gz
│   ├── 85756040c5879bc89b960fa11a1ddc11cb0d60bd.nq.gz
│   ├── 85c3aa6abcc51f036b54c62d8bcdbe01a28a7aa0.nq.gz
│   ├── 8a5bdc7c54081a0bc26cde64759eaa9aa9e64166.nq.gz
│   ├── 8c76f7e7d106c4cc223ffff3cea5f4de04ec09d3.nq.gz
│   ├── 8feeb76b44872c86daf6edaf6e4213fe9827105c.nq.gz
│   ├── 905ee00c21aa25d19e9c53fa6e1c51352891d2ed.nq.gz
│   ├── 984512c43d41f80922edc5b6d6f31068b49711c9.nq.gz
│   ├── 9b259bdfcf9022e7f4999a318ab7261300644e11.nq.gz
│   ├── 9bef1b177d4d8a7f8ecb6f7dac23bd93f0aaf256.nq.gz
│   ├── 9e4201ea0ca3dc6a127813f3fbb699495ee7704f.nq.gz
│   ├── 9e65da028b161bf3674dfcf845503df4439f65e0.nq.gz
│   ├── b0cb1051b88ee2d58ae8aeb74607507f022c1a05.nq.gz
│   ├── b18e156eeeabbc079b17b5bb328a510b2273741f.nq.gz
│   ├── b1b395c1df4239c5b76d6a9d3bbe1b054129a43b.nq.gz
│   ├── b25d96d9b11a144d38edc396bc2fa6e8fed8ba43.nq.gz
│   ├── b6085537c6ea481680f3b8997772a2b68b0df439.nq.gz
│   ├── b7eb2b03eee2db3db70c3a2a35009b5108c79f54.nq.gz
│   ├── b903d310d4f60a1b2267602af033eb33405588ba.nq.gz
│   ├── b92594512d600460fd7d430988bac1ad953e3c2d.nq.gz
│   ├── bdebc298ab30ccb5649c87e1687ea240b699947d.nq.gz
│   ├── c1800108a8fa5170757258a007f3fc43a8f14def.nq.gz
│   ├── c2dc002ca5127392646accb2564010b27284abd5.nq.gz
│   ├── c343d8933f94497694ce43423077cc76c1607b82.nq.gz
│   ├── c7e74b6aef369bfd87ca4f317958205976032d22.nq.gz
│   ├── cb50ea68e21a5fa410790630fde24df049b33f3d.nq.gz
│   ├── cc3a61688a3f0930e278ac6dbc26e7510dcacbd8.nq.gz
│   ├── d0bd49b2152c8b22efbcd45f198c8078fc31e07e.nq.gz
│   ├── d3331a042a4d6869e7d2c628c824fcc4ee21dd6f.nq.gz
│   ├── d369ffb1634dc9e5e1cf75bc75ac38b171ececc0.nq.gz
│   ├── d5e3711208bc975eb3c537b16250efe49fd8ec40.nq.gz
│   ├── d88e4bcd37c84141c64450c276a8076a11149eb4.nq.gz
│   ├── df350767492834bc5e3628daf22a67c9da90eba7.nq.gz
│   ├── e17167e93e2175f9bb1220cd48bbb9aea8300ce0.nq.gz
│   ├── e1f75ab8cdfb876c338b9a348d9e999f2d4e9d51.nq.gz
│   ├── e4fe6d277bbbd796b04db2d940523b3b27bc3145.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9d35a5325af253837eb8505fead68bacdd26a3c.nq.gz
│   ├── eb8f7dcf717ddc37b2276814f4658a9f64ab44d4.nq.gz
│   ├── ebb4370f0964bd23857018ea33b85ec72bebf409.nq.gz
│   ├── ec4e5c4ebbe2223d6b493824405aa84326d4593a.nq.gz
│   ├── ed317007aceb6911e5175f81b3c345a9e96ea185.nq.gz
│   ├── eda9a1d455911480812ac4c4493cee4f960ec71f.nq.gz
│   ├── ef251db8b038549fa424803753510a321248c130.nq.gz
│   ├── f02d77f29d256741b8d839287ef8bd5f753dc040.nq.gz
│   ├── f081b9b9e10f62093158d6312120fa854df46c1b.nq.gz
│   ├── f0b358a5c4bccb02f57b8924a7936b8fecede39f.nq.gz
│   ├── f17d8215cbc5a5b6e847340b988f81063e59376a.nq.gz
│   ├── f3e02605f6248307cf892673a065b259dd51d373.nq.gz
│   ├── f4636f6f550c6a35bb495011edffc627848582f7.nq.gz
│   ├── f6a4bbd08df25a5706ce995f521d4596954044ba.nq.gz
│   ├── f91b4d8cce8b9273d0df7f578045dd7e74750178.nq.gz
│   ├── fd49db4e08210ae5b8ffb80e470519b472cc4e46.nq.gz
│   └── ffc5791da023a42f5e61d40486d1e7390ae629fc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1a201c6cbb1b35fe39db4708cf70f08c00b7867c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 101 files
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

[allenai/pawls](https://github.com/allenai/pawls)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
