# Repolex Knowledge Graph of pytest-dev/pytest-selenium

RDF knowledge graph data for [pytest-dev/pytest-selenium](https://github.com/pytest-dev/pytest-selenium), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-selenium
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 98de796ad4f86c983420a9e365b8bc5fe73aa1a8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 98de796ad4f86c983420a9e365b8bc5fe73aa1a8
│           └── chunk-001.nq.gz
├── blob
│   ├── 02362f7d17a9b0eb77f9940dcaa4ea443733f06f.nq.gz
│   ├── 0bda97b3b552acb7377714933db2b9ab34a69dd5.nq.gz
│   ├── 17079368b5560e1e814c471876f15b5a4adbd6d6.nq.gz
│   ├── 1a2db7031d2e85a26f33ecfdb976530459f22772.nq.gz
│   ├── 32531fdb2521056e0321279607fb7247eda1ff75.nq.gz
│   ├── 33fea7c3c08fc7870fe0b19ee41eba6a8c54bd68.nq.gz
│   ├── 348a708b82de79005e29fa4a7c6f6ab033085e74.nq.gz
│   ├── 38e4e0f78067e0fcf60410591ef42c7886b1124f.nq.gz
│   ├── 3a5f9642ab431575caef52748640fd23c50756f4.nq.gz
│   ├── 3c31d92cff5124c9201fe18cff8297ffb4547941.nq.gz
│   ├── 3f5aec83a652e21638e65bb0cd78702dd65d9c2f.nq.gz
│   ├── 3f6e1e6118d0e9c322120f0a4b0642cc92fac228.nq.gz
│   ├── 3fccd3106c43567b8e295828f34ff1b654a6bcb2.nq.gz
│   ├── 4122cfbef596a217269be52128af4b18a0a3655e.nq.gz
│   ├── 41dc2327f1698b99dd397a84f47b9596d0a516b5.nq.gz
│   ├── 4e70480d4f86862d09b8be0179c8f544a7107a1d.nq.gz
│   ├── 51e9d773595beb413b48ab3a9b8c90bd3710ebf4.nq.gz
│   ├── 53f32274d0c4a0579d7feadf45ec3aece016ead2.nq.gz
│   ├── 5b23b9b91aa7a6c4b6dfb59ffd8bc2c8441e043e.nq.gz
│   ├── 5c018993562a1c9f5f80435178e832b422c52a1d.nq.gz
│   ├── 5f5d66e526616389967f440fec69de2a0751f766.nq.gz
│   ├── 66a1b5cad0e66f2a994f2546278db6e178abdeb7.nq.gz
│   ├── 6af032b4e83992cad684081643e5745146491bbb.nq.gz
│   ├── 71f1a49f6a02b1145ea44f678b251163a0a086da.nq.gz
│   ├── 73fb7edf213ab0d88055af0cdb02009602d3e99d.nq.gz
│   ├── 7490c2698ccaad9e911c1d6be6c8ae091902323b.nq.gz
│   ├── 7cbffc54e9e49cb3be70427d9669339897a9eecb.nq.gz
│   ├── 82056528d52abbdcdee1da30853a65fc1fc3730d.nq.gz
│   ├── 832506a0dbc80ccb6f0acd87ed58fde4f628ece7.nq.gz
│   ├── 84dffe023ac2608e7852850a6eee97c3a65d6e7c.nq.gz
│   ├── 89d7c9a2e769c245f3f2c9002183dd6e5866ba9d.nq.gz
│   ├── 8a0b252e66e3191a12e8a2c1dee754f851fe7df1.nq.gz
│   ├── 8d0b3c1c91057f7db5e387e28ac1980869360eb2.nq.gz
│   ├── 8f1a13eecb9f096fc04cc25612e4ec86dc861f1a.nq.gz
│   ├── 99cdaf9527f71fa4057ab4555f9f06495c7ffdfb.nq.gz
│   ├── 9b56d868d5ee0230182c51b5e856f0c5ba5748e6.nq.gz
│   ├── a006d5e654f8d30be2c24c8d3043455c8f257ac9.nq.gz
│   ├── a01892bc1fdb7aad2ba494fd51dfe9ec149645cf.nq.gz
│   ├── a84441bfd41d39aef20c5986d6740f290f9e1e52.nq.gz
│   ├── aa35b920e41ea9ff2bf6c0a639131a11928a1466.nq.gz
│   ├── aa94e1bc6d8dbcce9ee587aeb1054f171e1943e1.nq.gz
│   ├── b615121f8916931de9f87dfc9f37e10338c66f3c.nq.gz
│   ├── bb98449a05b38cd84c2f255c60d9b09298785178.nq.gz
│   ├── bca3c46807e92a0ecd36bdc5b9d881059a03e80d.nq.gz
│   ├── bf19469f7791210852aabde8b2b06bc4ea6adba0.nq.gz
│   ├── bf5279de67953489c31a91613ea5267a905f8f8e.nq.gz
│   ├── c2c09f8038ce8081b8ef81febae21d1883775ced.nq.gz
│   ├── c34a6f46aba9049ab31eee6e19622ba18332e1fa.nq.gz
│   ├── c51a6e1b496dd67c11bed1e2ce77e0ad6aad801a.nq.gz
│   ├── c5a338a318ad50d3cfcd26d4ab42821284dbb60a.nq.gz
│   ├── c8eb13fab0d521af7cf38919e87dd649ec9bd064.nq.gz
│   ├── d47f699a96f7c46a6721ab1e7f57c1e5be2af811.nq.gz
│   ├── e17f1ea587079746668acc8787ab68287056e71f.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── e5b61e4645fa4f1f17134607e0224274eef3f94d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a76a2bb6b3bf45312283ef3c63c8fd421e8c6f.nq.gz
│   ├── eafaf05d8a8f5a2918061842735cf7b1aee5ddf2.nq.gz
│   └── fbae7542d7a7f13edf1b43a4bc2814b60711f6af.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 98de796ad4f86c983420a9e365b8bc5fe73aa1a8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[pytest-dev/pytest-selenium](https://github.com/pytest-dev/pytest-selenium)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
