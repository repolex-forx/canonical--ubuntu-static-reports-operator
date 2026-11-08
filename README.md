# Repolex Knowledge Graph of canonical/ubuntu-static-reports-operator

RDF knowledge graph data for [canonical/ubuntu-static-reports-operator](https://github.com/canonical/ubuntu-static-reports-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/ubuntu-static-reports-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ae8fafd2478e909a2cfc63f04384daeeb26bb718
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ae8fafd2478e909a2cfc63f04384daeeb26bb718
│           └── chunk-001.nq.gz
├── blob
│   ├── 027ebe43bd75e955f0cffdbcec43a358e8e398f3.nq.gz
│   ├── 0285ccaad497ddca5a26f8ca6509911c8478c932.nq.gz
│   ├── 042a8d991466b3b733a05d9cb65f664a5e89d9fd.nq.gz
│   ├── 1482df344e9d611ecf5f7cf6b163ca7aa0894104.nq.gz
│   ├── 20d0ae625d3fe409a3f026e3dac29a74c237119b.nq.gz
│   ├── 213d15c2d19fca5cc275716d9256a2b79bf86977.nq.gz
│   ├── 24c0cd4083497c6bcc94bf65dd8935a45b88ef8d.nq.gz
│   ├── 29952012686b7258e4fed259c70af4b428667428.nq.gz
│   ├── 299efd56c2042808fe10b1c026f6085cef9183b8.nq.gz
│   ├── 2b6e4436125c03b1975f45b24829d98a7aa24a53.nq.gz
│   ├── 2d5e4fe6aa1313cd900c1ee06b0fe463972d8257.nq.gz
│   ├── 317905c0da5eadb140782165238439a7d25ace56.nq.gz
│   ├── 3367d0d890423335b233f9eb320bf7f849795e7f.nq.gz
│   ├── 3689b394c3177860c94db522ded16e472c13244d.nq.gz
│   ├── 371794f379c9a9bf7d09e167d1de52243d248250.nq.gz
│   ├── 395d619b736e1f0fe2227fcdee264e9663db687c.nq.gz
│   ├── 3a8f1c95d44008a2de023dd170bfb32a24dffc39.nq.gz
│   ├── 40c034b000031119632263962783e9418d6d32bb.nq.gz
│   ├── 41db4b33753cce58df318531b1ac31c2289aa8a2.nq.gz
│   ├── 45440263d8127af912a459c42d856873d9388811.nq.gz
│   ├── 46c85449a986084da5995da4df64cfe2faf33e40.nq.gz
│   ├── 47e66c8ba20583f6095756a3ba51c2903ff96dfb.nq.gz
│   ├── 482ba70946a43f799f2e84a6dd77d081d891e1de.nq.gz
│   ├── 4c480141f22bbf60bc7e1b4b3a6860b3693c599b.nq.gz
│   ├── 50463f6b8aaae1d2383846ad59b6f531727b7b7b.nq.gz
│   ├── 5149e7723fbbf9d129fe18559050a88103afba2c.nq.gz
│   ├── 5320952e84206896afeae65e436d81b9ea961c20.nq.gz
│   ├── 56ae0cc360abc004f4dbac3b1f857b6498009eed.nq.gz
│   ├── 5a93e7718b968478d544ea01127552d4c266bc3e.nq.gz
│   ├── 650c008c5e3eb4bb1eea89a4a7eb2c6d2266d086.nq.gz
│   ├── 67f9bac2fed664ad11ce7c947ece0a3b17c48b70.nq.gz
│   ├── 6887744d3633ff02d243ca48ec8310ccab664e2d.nq.gz
│   ├── 6b32d049d82e15f03e76670cb641bee6827b337d.nq.gz
│   ├── 6c4e4e803439512f9cb3d393d03d1e4b8c21fade.nq.gz
│   ├── 6def8e7a366f1c9c84c1499b4603d705ec87a133.nq.gz
│   ├── 72cf8536b9f29b9ce92bd6e817079a84b7922bcf.nq.gz
│   ├── 743edcd0030fb8a0a2b86e3f9cada286fb86b3bf.nq.gz
│   ├── 748053303c4ea417bba571e0134fe4cadd21bc93.nq.gz
│   ├── 7ad36eb905c8cc405aae6b3af605c747b73ff84f.nq.gz
│   ├── 7ff4cebf4f0afe30dc9bcf791b3b1ce5ec1c726c.nq.gz
│   ├── 80c68b7fc8369dd95ea0892a3fc8f076238dfac4.nq.gz
│   ├── 82847ac1e77303281b2d0d89b8658e5d94897e5d.nq.gz
│   ├── 86199f30baf079e60299c238a4fad6637139f6d6.nq.gz
│   ├── 867e31bd4e042a9995eff92bebed4d921d1d9801.nq.gz
│   ├── 8e487206c95496beefabdc9641709420fc754b5c.nq.gz
│   ├── 9d5cda9465fcd810a9d8333d7b047e9beb6af8a0.nq.gz
│   ├── 9ff36ed51ffee2df3525b5e5d14b5bd92eb42fa4.nq.gz
│   ├── a84462edd1672e795e045bfbd5beaf8741ead3df.nq.gz
│   ├── ab59d092288148f0972dfcb10b85762956d24890.nq.gz
│   ├── b465bf89c7d1f86a9212bb0e45c05ca265b2a259.nq.gz
│   ├── b6765f502b021988d496fb3640b25c936e575e8e.nq.gz
│   ├── b9e89a28ef58f0b9702183da9e09c4b546a552b3.nq.gz
│   ├── bb1b39313f044cba8a73b6a3562857762097ee58.nq.gz
│   ├── bb4b0816d987d9722e1f6a0fba125823bfdcce89.nq.gz
│   ├── be87c7b85b6262d60e465432a7d6b8edcac1eb6a.nq.gz
│   ├── bf8a9b01db23031b24cde4ac7c90cdee4d491808.nq.gz
│   ├── c224b9eb23280af717c53887b11b82a91896689c.nq.gz
│   ├── c28dcfe5073c4c7753add016cf63dded9e3ee379.nq.gz
│   ├── c397f59ddfe351c588e48f5be64b9b95c63db3eb.nq.gz
│   ├── c3e0ce94ee1b4801327b526fc4cbec94026a001a.nq.gz
│   ├── c47ffc5fcfd43b63f16f68b97866a275c7d06d39.nq.gz
│   ├── c53da844df01ba2cfdb2f14d9780e253e9ec3488.nq.gz
│   ├── cdcbad6a92958b47d2440bf856ab71a162961242.nq.gz
│   ├── ce3c903fa4308b200d58cba0f0a4852025521651.nq.gz
│   ├── d353ba079df7dd8d35d1e8d75e90dcb181a35000.nq.gz
│   ├── d87a7c05dd1680ad751c77ad20ba47fd4909507e.nq.gz
│   ├── d8f292d00da78f33b72d0efcde17ce863501226e.nq.gz
│   ├── e1779e803f4f778b9cfb6bfa7080d09751c54e45.nq.gz
│   ├── e2de549b1a668deca7c2de67c80b2148953c8b46.nq.gz
│   ├── e7cbb526acec8013561b2bd7adb56a72822efdd2.nq.gz
│   ├── e968447a59e31d9a4362dcfeb2c1a5a5a7af9d51.nq.gz
│   ├── e9ee8a5691e2603e2c2078b08b3dd64d8c42905b.nq.gz
│   ├── f0603da7d668cec27af15b1fa3006b67af4c0796.nq.gz
│   ├── f21ab080def243074161a0c3d7576dc88992765c.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f29e954a84d3bf03f3925afbc5140a8e9a03a6cc.nq.gz
│   ├── f7f95cf7b1c1a3ce59002ffd71138a553744c6da.nq.gz
│   ├── f80840d8159f6b2c6de5068d2fa8e46bd77bf31d.nq.gz
│   ├── f96a83cb997e69c7f58dcec6bf8131eb89c1d12f.nq.gz
│   ├── fa5d7fb4ef7f936b4ffe105ffc32f531f89e37e0.nq.gz
│   ├── fba1b6f5778d20285657a4bad578c5128368112e.nq.gz
│   └── fba3b5a935f676cd243b383887528fe20bbf2bfa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ae8fafd2478e909a2cfc63f04384daeeb26bb718.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 90 files
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

[canonical/ubuntu-static-reports-operator](https://github.com/canonical/ubuntu-static-reports-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
