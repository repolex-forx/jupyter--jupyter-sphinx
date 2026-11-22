# Repolex Knowledge Graph of jupyter/jupyter-sphinx

RDF knowledge graph data for [jupyter/jupyter-sphinx](https://github.com/jupyter/jupyter-sphinx), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter/jupyter-sphinx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0d6b26c677334dbbd0f4d1935f50dcf3888c82c1
│   │   │   └── chunk-001.nq.gz
│   │   └── bd4c85dc8cc08eab5251ffee2a94ec25a669c5bb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0d6b26c677334dbbd0f4d1935f50dcf3888c82c1.nq.gz
│   └── repolex
│       ├── 0d6b26c677334dbbd0f4d1935f50dcf3888c82c1
│       │   └── chunk-001.nq.gz
│       └── bd4c85dc8cc08eab5251ffee2a94ec25a669c5bb
│           └── chunk-001.nq.gz
├── blob
│   ├── 008559447664f6f5b7ffc10845005cac6e33be16.nq.gz
│   ├── 05ada482aff7724cc7701d5339498d128e22a903.nq.gz
│   ├── 0aa9969b2bb4441966b09b0dce110fe030552bb6.nq.gz
│   ├── 106feabbca234db9a447a0f9a8c49be90f0bf91c.nq.gz
│   ├── 149c5171ed42532d6e6e8f320f43067077430953.nq.gz
│   ├── 1880af96a54b2575fb70803a357ee1bece68109a.nq.gz
│   ├── 207bdb2f60b58cc8e84257a633f70cd6b506f427.nq.gz
│   ├── 23b47cff451e88fa5e2b70e54cdae6c0078889d7.nq.gz
│   ├── 2ea0c860f478698b0bb481cee45a5479377195d5.nq.gz
│   ├── 32a3db7f76803d851333671b17f9f29559e66e3f.nq.gz
│   ├── 336c8a7ede92fb7c79389b7397084fc1a5434300.nq.gz
│   ├── 34af884fa307c44d4ea19d786026e962786b7d8b.nq.gz
│   ├── 48ff4ad8e05be1dcfda8f10fedd2132bbf327cf1.nq.gz
│   ├── 4e85b16396ad1cf7ec33cf36a52198fc6d0abc19.nq.gz
│   ├── 50888921ea6eeebedf0c8c4a10733d289b256e87.nq.gz
│   ├── 51e1a0f6f93fcfba16e360c70612a7634d1bc446.nq.gz
│   ├── 53f554b622ae6330037d18630749e7106812a79a.nq.gz
│   ├── 562b0837a35aa73abe80b33e9a6e2fce1d717788.nq.gz
│   ├── 568aed75f5a7cdaa56a71952e3a488a210ac2047.nq.gz
│   ├── 57a19658ca525144aa7c4915131aabe229690696.nq.gz
│   ├── 5a38af2f69c21d4eefe7717cc9c0646eabada4fe.nq.gz
│   ├── 5b824189611d5d7eca04a7a5311f4217bbd4dc0b.nq.gz
│   ├── 5dc3cb55326e20e07a97f2f75667d781ab691859.nq.gz
│   ├── 60645b6550152101526e6f7e3e17b83cb996cca1.nq.gz
│   ├── 6372f7655f0c1a2222c73508ce478f49af45a8af.nq.gz
│   ├── 64eec78f941d487008a5c9117c6e0518dc6f6be2.nq.gz
│   ├── 66f0cab3c3bd17881165697a463e0829be3bd481.nq.gz
│   ├── 68bc17f9ff2104a9d7b6777058bb4c343ca72609.nq.gz
│   ├── 6c8b93167c8ee405f9e4aba04ae2451391040a68.nq.gz
│   ├── 70cee8f1a33561f907fbe798fe6af7867e5988dd.nq.gz
│   ├── 73a839af9851d0f2bcb6d1345338a66319759509.nq.gz
│   ├── 87724dfccda01c9f00932fdda6123ec755a32da1.nq.gz
│   ├── 9093fc53dc2c4b4ee1162d787188a1796f0ddc5e.nq.gz
│   ├── 96bdf5a3b6df043c23dfcc36a6a1de3bf1a0cba9.nq.gz
│   ├── a25bf695239c49b25b7cb6661aa34f3a238aefda.nq.gz
│   ├── a7a13a7660256d17931e193ca16760912f00debb.nq.gz
│   ├── aab20ea9d2e605db868c75985b58686a453cb2f0.nq.gz
│   ├── af56cc25709c1a2cca0636f98fd573feddee5cb8.nq.gz
│   ├── b4b15e98bd647e979d0a3de8d5eb892cffc2e967.nq.gz
│   ├── b71f282431aeb7c3b6438c6fab7a5af26c3519ba.nq.gz
│   ├── c6486e0a094aabb7f6a8049bef437e7445414792.nq.gz
│   ├── cb473cff6e85cc4c4111e251dac077b09aeae335.nq.gz
│   ├── cfc006c738ff9182b2f75f3945e16fa407b50eb3.nq.gz
│   ├── d44cc6a077e85027909c79fcab15b8d0a6a044cf.nq.gz
│   ├── d5b5baf89c8237a4bac72d170b1525069dd45e0a.nq.gz
│   ├── e7f1cd200d7e1dab91b4c3ffd5d44fa2f725531b.nq.gz
│   ├── ea38e5e847be37c9e2d44ddf2305e613d149e8c7.nq.gz
│   ├── ebe1f4bcdd656a4727013813b9483e422bab346b.nq.gz
│   ├── ec30328343fbf20fe4236543f1531a9f620325cc.nq.gz
│   ├── f35428fc14ef56b26cd2e9bbdd6543aec7cc5b1a.nq.gz
│   ├── f516e56ded8bcde21bdc890d8e8f6ef71a3b766e.nq.gz
│   ├── f8d0c224b6286c1aeb3820bdd2ddcbd0fc7a294f.nq.gz
│   ├── fb7dc682bed1802f5a0eedd84679320eaf9babdb.nq.gz
│   └── fd51ed37f7ea2f3d231d54941d05bae5a3b9b5f6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 0d6b26c677334dbbd0f4d1935f50dcf3888c82c1.nq.gz
├── filetree
│   ├── 0d6b26c677334dbbd0f4d1935f50dcf3888c82c1.nq.gz
│   └── bd4c85dc8cc08eab5251ffee2a94ec25a669c5bb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 67 files
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

[jupyter/jupyter-sphinx](https://github.com/jupyter/jupyter-sphinx)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
