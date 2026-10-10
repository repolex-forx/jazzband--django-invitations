# Repolex Knowledge Graph of jazzband/django-invitations

RDF knowledge graph data for [jazzband/django-invitations](https://github.com/jazzband/django-invitations), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-invitations
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 378b2f59efde51decb5345450c8c9e9d593cb641
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 378b2f59efde51decb5345450c8c9e9d593cb641
│           └── chunk-001.nq.gz
├── blob
│   ├── 043e2ebe286134274ffbb9493acfab1da3b09229.nq.gz
│   ├── 080042f99bed47d824b77aabce86bbc5e1b595da.nq.gz
│   ├── 0ae251bfacc0a865f0a684d05d904ddb5c0658f3.nq.gz
│   ├── 0df524bd087b040c120b5ebbf1d9990dc953e96f.nq.gz
│   ├── 12943cb39232f75b5c43132798528a8f98862140.nq.gz
│   ├── 1a52989aa291a8080ee5999bb59375ac9f3e4724.nq.gz
│   ├── 1ee36fff190c12ab2f4f7c74e34d5c82fd162b67.nq.gz
│   ├── 23d100b0e0f1bc91dba67665767e0e3a02d09cbe.nq.gz
│   ├── 248d4c2df86be719e982219d67eaaa52a7ada7c1.nq.gz
│   ├── 26065cb9c3a20abf0f88078e7a5330543fb41708.nq.gz
│   ├── 31af68a6a6073b23c9936f97a784cd0b6131c52a.nq.gz
│   ├── 322897e5522680a18a44a2adfffe5ef9053b8240.nq.gz
│   ├── 33b05b45c7cf92c5a96b84fab35de55bac267d47.nq.gz
│   ├── 35ba370a262b7216e5ecbfadfaf41ad4b299758b.nq.gz
│   ├── 37d47055b14c84e132fe897cbb111ca88e87d91a.nq.gz
│   ├── 386a4af7c323c278e1eb3a62c318b0b8d0578080.nq.gz
│   ├── 3adb2f5f78db16797be86195e79ab950c90fd36e.nq.gz
│   ├── 3c2a0081ce62cc548c8feab2156b9b6ddc077fe0.nq.gz
│   ├── 3c3046ff39890bca6fac816ddc6291604e790fd1.nq.gz
│   ├── 3d6dd1e3da7ffe1275269bd6aa58a7510219cd16.nq.gz
│   ├── 3e89941d13e08d2c6b37e6f6ec2e7673fe3066ab.nq.gz
│   ├── 43a735b17e4a13169a409455d9078e0414073b74.nq.gz
│   ├── 4d71b477aaed0a0fa45cb4c3b2b9189468fad685.nq.gz
│   ├── 4da11f1133046dfd36dfd52eaa52e4f4e40d5e11.nq.gz
│   ├── 4dd495af4a1d471e60f832dd09ebd74d26365439.nq.gz
│   ├── 541a4802e3b97e05064d391fdadd13ee759af89d.nq.gz
│   ├── 5a6201ef570e3f0e23dce05ae835e0b071f7bdf6.nq.gz
│   ├── 5c9dd8effb8f786fdce2dc66dfb85da8b05ed50f.nq.gz
│   ├── 6d1bafc2f1342c261f4f0b56850e920521c491cb.nq.gz
│   ├── 721076e995b82d3be65261c9cabde1c3b051c999.nq.gz
│   ├── 73a7a997490cbf9dbf32f7c362932cc3066a5cad.nq.gz
│   ├── 785655889d187950902ada0156656f0bae347985.nq.gz
│   ├── 7bc08485dcf1063a26d1dd8ffaf67c0fb72df370.nq.gz
│   ├── 7f45a33f2123f97ece351643d366b64a4b5cdef6.nq.gz
│   ├── 81cbcc2f4201ee85d4a83b3d2fb8abf6c47920ce.nq.gz
│   ├── 8a7c976ad14f17adb9944cdf10cadfd56778a6ab.nq.gz
│   ├── 8a8dd88e746cc5c1cfdd3000bd54d31a17945854.nq.gz
│   ├── 8b55dd446bd32f64d3ed2faad068ceffdc200c47.nq.gz
│   ├── 92f63be9f3cdf85422f46dd197549e745667af95.nq.gz
│   ├── 9625eccf00362c79875da64f34897a5475e44118.nq.gz
│   ├── 96c2fb6b24adb31f0568b0f405f895e9f4af9376.nq.gz
│   ├── 9baab26bc00679969f3e54d5d31cf860493a1f61.nq.gz
│   ├── a0121ae970517d367fd1e243ab66a92a24fab577.nq.gz
│   ├── a0c263d2fe35c02bf26ac265c0618448cefffe79.nq.gz
│   ├── a5079589b89c221c3bacdee31fee48912423d077.nq.gz
│   ├── a74a7917cfbf7d6e208e7b35a5ea2526c06af82e.nq.gz
│   ├── afbacacdbe43aaa991d9771b4671cfc903dd358e.nq.gz
│   ├── afe8b1e705667fa1cde56dc20e48a3928e309317.nq.gz
│   ├── b20672987835d9db86c8cf03428e4d3283f71c3b.nq.gz
│   ├── bb169dc87a5c716a5fb7ad6f44fd87b3a79afde6.nq.gz
│   ├── cab8b8e9bdd215a1be428a96a47fb2f36418a4a4.nq.gz
│   ├── cd249f443a45a8acb99d6530b984ea531e894c8b.nq.gz
│   ├── cef9c887ce1d777ca171d58690474cd6f9a9ab92.nq.gz
│   ├── d232c49271a7fbcda5db007561564528e280773f.nq.gz
│   ├── d40c558fd76aa32f32abcac8e622e1ea0fa5d126.nq.gz
│   ├── d5ca2227e9edcd880e9832d8b9e2966c6ce91bfa.nq.gz
│   ├── d7a6febc531c971e34475cbe61a39097c4efbcd6.nq.gz
│   ├── da1c3aeaed813ac9100569bb0eb99f218a35378d.nq.gz
│   ├── db114d3541f8fde82bf829b4189802f31a3a150d.nq.gz
│   ├── dcf311a96d13be1f9ff959169978c1b84dff5cd4.nq.gz
│   ├── e097299b709a635dc9b975503fee2b3df3f7ccb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74a25b52c0b010e405415341493e796a4c28080.nq.gz
│   ├── ed828377eed773a354646fef356956c645b745b0.nq.gz
│   ├── ee5219bb0dc53918c6dcaf3d2344b14b437182da.nq.gz
│   ├── ee8bb7c8c8de6aa684b532c5f8c161287ba0bbf5.nq.gz
│   ├── ee998bc140be4f8fc4d9ae89fb58e6a736accf9f.nq.gz
│   ├── ef7e7efc09c9d471c391f05b9567966928085840.nq.gz
│   ├── f5b9726b7965a7929d8a5183ad985d592337adf8.nq.gz
│   ├── f6f6c76d2c7dff1d4081a71930b427b1df0fd005.nq.gz
│   ├── fa5899d2df28580b0a8e1bd00e70303955140576.nq.gz
│   └── fad35d197ab9e103c0d03c9018383335a03db6c2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 378b2f59efde51decb5345450c8c9e9d593cb641.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[jazzband/django-invitations](https://github.com/jazzband/django-invitations)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
