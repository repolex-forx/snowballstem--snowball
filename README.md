# Repolex Knowledge Graph of snowballstem/snowball

RDF knowledge graph data for [snowballstem/snowball](https://github.com/snowballstem/snowball), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download snowballstem/snowball
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4b3efb449ccb994d39230eb6e8440d267471f4a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e4b3efb449ccb994d39230eb6e8440d267471f4a.nq.gz
│   └── repolex
│       └── e4b3efb449ccb994d39230eb6e8440d267471f4a
│           └── chunk-001.nq.gz
├── blob
│   ├── 000224e78409d7460542ff5967ea32e5316be3ee.nq.gz
│   ├── 001d003687c1386a51bf904b2ab995a34e1f4839.nq.gz
│   ├── 0575b1d925a32cf249ce97ba38ce095f5daeff9e.nq.gz
│   ├── 05d96f646ae25011cec486bf76f5bccbec8ba33e.nq.gz
│   ├── 064325a902eba80a0af1c0619bef49ce42c3789a.nq.gz
│   ├── 0be3c05d2b1f1a6461288a3f760a4cec62a5bcfc.nq.gz
│   ├── 0c77c6c0c18ce155b4fcb639d8ce504a74957f91.nq.gz
│   ├── 12f972c8586d7860a832ab98a7bb15f9aad78250.nq.gz
│   ├── 147dd77d1b9e35d40988ec9f26998651d9b763cc.nq.gz
│   ├── 15661344299e813f200d7474c1d87518bc6f76dd.nq.gz
│   ├── 179d185143064fee37557edabbc9f6b4424592bf.nq.gz
│   ├── 1a81ab50dfd8c631438fcbed3caf25cbd5348d81.nq.gz
│   ├── 1faa3e79032ff8a7b97ff4b79270ea85e092bef3.nq.gz
│   ├── 2055c5e4b2de9507df6c76092e7d93b9b49648d5.nq.gz
│   ├── 20de6395ef84a25ce4a402b415e573caf61491e1.nq.gz
│   ├── 2169c4e08e289ce21b91b131398fdf21eec3a3b8.nq.gz
│   ├── 249d6838d6bc689442b1d6523e0fb9728a67b371.nq.gz
│   ├── 27b8637cdbd8cd4ea7fa57c2fe79a6da899d6408.nq.gz
│   ├── 2bd049161a1ac55e2bc6fdf0fcde433723b54090.nq.gz
│   ├── 30b515da68e61efbf5659f86ffa9b4dd4b1d5db6.nq.gz
│   ├── 315847829a5b695e656fcdd25e871cbe2583cc34.nq.gz
│   ├── 3434753469b08984611278249aec34fefb7e74d4.nq.gz
│   ├── 354ab56396085c2725738b35222892ee51545537.nq.gz
│   ├── 38476dcdf63b114c5360199c0e81aae90c29ecc2.nq.gz
│   ├── 3981fc3a59e00b6c18dab1e6448384a6b35f0a39.nq.gz
│   ├── 3a9a9266fb8540e99f912a3db7a87007893764eb.nq.gz
│   ├── 3b2d59a3cbc06797aaddbda147d750f0ef98d1cf.nq.gz
│   ├── 3b8b833c02931cd8cf0de55785ac5d3f5e94b6e8.nq.gz
│   ├── 4070fa2a153c4e968e8a529286ca414a849f4f4a.nq.gz
│   ├── 408fe6ae56b3b849a5b762644784277c7481edab.nq.gz
│   ├── 428856567706798f8fc9a1d021ef92c32f520914.nq.gz
│   ├── 46854e8254110c4dc66658029effb49f7c92ed0f.nq.gz
│   ├── 47a6a0cae0352dcf0b64d9782178dea9a4fd7fb0.nq.gz
│   ├── 48568ac36c143650e0af5e20877a7d7987113111.nq.gz
│   ├── 486e3ea097988058923244075e9b28d5ee9ee295.nq.gz
│   ├── 4c2e5fa337c07b31238c26a54944a63cc5aad4b6.nq.gz
│   ├── 4deb06c50dff71108409d39b4ae53f75427bb255.nq.gz
│   ├── 5417cc11a4c9cc0f5b6113d28936ce98142825c3.nq.gz
│   ├── 55d1769d56fa9f33af8e9f79b4bcfe93df0dbcf0.nq.gz
│   ├── 56e1ff5fb315a7ebc7835d8c059b1ee4e9d4f237.nq.gz
│   ├── 57636287a09a7959bee77ac169a362f7893175be.nq.gz
│   ├── 57fc8bae03b548d6106e7ff56f949a6de9b98a16.nq.gz
│   ├── 5829ea8a9ba9c866c42ef77c62b25d736b4fdc30.nq.gz
│   ├── 5b6cf0c9d4cd4dba2975407e3aaef83023d9145f.nq.gz
│   ├── 5dd62ccb74d6e1bd622dacc67503bbea69787024.nq.gz
│   ├── 5fe00216e0223f54c3bd8af1082ccbd4aefa47c5.nq.gz
│   ├── 602f9fbff306a8acfaa3add322742cecfbb3ba4c.nq.gz
│   ├── 60eae6f0418c4ee853fb734cabb73c04f4af0294.nq.gz
│   ├── 60f534418e27e9bfc7fc5065f5491a15fe03c6ad.nq.gz
│   ├── 613d6ab8739b91711d65d12fb2c95f9c45a1c54b.nq.gz
│   ├── 618d22d2a3c1ba5fcdc8f86984be0e572e5f0cec.nq.gz
│   ├── 62101bfea5525875e4d2a5869443bf6434bbacfc.nq.gz
│   ├── 67ca917141c9a801dca71724117edeacfc68823f.nq.gz
│   ├── 6c5044c6a7c5e5d8ec356b9470460e924d62d6fe.nq.gz
│   ├── 6c777f274df419d5df3324e4709315122f9a0ed6.nq.gz
│   ├── 6ce6c2fbf2251ed41537c9f37913b6951b51ee0c.nq.gz
│   ├── 6e9f61b4622b2743d4b848bf1e6d87011ab204f9.nq.gz
│   ├── 714eff28c3a71baf9af4b67c5547642754bb9af3.nq.gz
│   ├── 75a83f39c9a2b854fe09d2863e59ecf675df2fb2.nq.gz
│   ├── 7c8c3638b61b3bba835d48fdb0f1cbda43d84a31.nq.gz
│   ├── 7f7e0eeb6674b0b7730ffe073247dd7555198a42.nq.gz
│   ├── 818ce77a5d6bd2ec325e9f785e69f0b86a10e4a4.nq.gz
│   ├── 862601fa9faf4acdb0fae08a818b0805a8baa3e3.nq.gz
│   ├── 8877d929a9b4f106cebae344933032e4c359ad24.nq.gz
│   ├── 8894c79e28c85eaf3f5e72a5ab2d310f9597e3a6.nq.gz
│   ├── 8b4a8b57174eb4be0e08bec53b203a45d91f5738.nq.gz
│   ├── 8bd6bb090bb1eaf68755e63c937e07aa664ccafb.nq.gz
│   ├── 8be62e9a7fe420d8504fe3109536364cc77dc0db.nq.gz
│   ├── 8d7372411f8d12ae3a4826e45e7f3f8d8ad1f546.nq.gz
│   ├── 9354debae43b57331d8916117e1f4d73d032aacf.nq.gz
│   ├── 983ff404c4ad987a1c6851f29cc8e975f9f03275.nq.gz
│   ├── 9886430713c3e88f783dc405f49853927eb0ef63.nq.gz
│   ├── 98ed85a059f2da0acf2d5c9f3abccd5ea0881c29.nq.gz
│   ├── 99ce8bff9ebb83ccbe5a2e917d3a64172fd98887.nq.gz
│   ├── a3a480b81e1b7c246ed4cbe76d640d37fbe28ef9.nq.gz
│   ├── a3cd3e4428d5569ba2e4b859f7f9629d26bbbd75.nq.gz
│   ├── a4dc3079c83d54a73d23fe10a68a561b1c0bdb47.nq.gz
│   ├── aac761e41e8df3478a32fafd0188d440858ac801.nq.gz
│   ├── af577791583238f95b87cc3f1090dd1e84859963.nq.gz
│   ├── b1d18ba82e38618fdb3bec40f4c089a5a0aef7c7.nq.gz
│   ├── b2406a5672903f3ce5717ebf005feecca028b50c.nq.gz
│   ├── b4573b425baeca8e2a766ec047d894aa24a04936.nq.gz
│   ├── b59ea56bdd27e4e63accb149725eda59a68de65e.nq.gz
│   ├── b75476ec889c8bb98442807a6baf2253f95aa3ba.nq.gz
│   ├── b75b02165abbd57e4705ce9e0507912d76cdb0bf.nq.gz
│   ├── b780220377e0fa5d60baa1458926574aaacfbc4b.nq.gz
│   ├── ba9d1c14bcae1f6e14a6d1154199099858e8a551.nq.gz
│   ├── bde07883624b2b25d8e85b846632cb5545b3fe8e.nq.gz
│   ├── bf822e44dd81fdfcbdfa708104cd974af49dfe19.nq.gz
│   ├── bfd86638a39624a2e5301f74b8856001e0008ff2.nq.gz
│   ├── c11f7162d62a8aeb4b04b8f3b1447f6c63c4fa53.nq.gz
│   ├── c2c8cb2050736b7a8930ae1c4e41521fe163c69a.nq.gz
│   ├── c42496b39297b01c11841ca59173a3e1c0f360be.nq.gz
│   ├── c5157f87d874a219b87a87ce6a318ca9c4353b1c.nq.gz
│   ├── c580936c413b5929b76c85d75d55fce972304eac.nq.gz
│   ├── cb894877a5eda3ba2991aba0575aca38e592763b.nq.gz
│   ├── ccbfce8f192ad4428b5a42d8cc32f8bee5eac539.nq.gz
│   ├── cde0b42b11d5f9b001b177fdd7f3dc8fd3cee32b.nq.gz
│   ├── d1cd95034ffeaf19298accd0c68b300ff7fefa5d.nq.gz
│   ├── d452050fba4941a7cb23c22da6902d1d8a30cc78.nq.gz
│   ├── d58c5852854d2e2d955a8cba02394060ecd0d21a.nq.gz
│   ├── d72922157e75b3cc9e2fbf1d9dcc156de5b72250.nq.gz
│   ├── d8a48b038f8be303b871498fb08bab2ca496c7bd.nq.gz
│   ├── d8d45d1b2d0ac379a00faf6e80d66912f4d5c90b.nq.gz
│   ├── db6def041b5dea804562ebad6076c2b94ba1363b.nq.gz
│   ├── df38631024a2fbbed24d28d36e48ff579bd63881.nq.gz
│   ├── e0e5486fc638d3dd58069826e0ddc6385dd70a71.nq.gz
│   ├── e1403be3c85b4a844aa87422293d6ca75269c4e4.nq.gz
│   ├── e2b22961edfe76ee38c2c10697fea651880968d1.nq.gz
│   ├── e4c1bb2b6a5b3b5848a0a624258c4c80c9cbd0f8.nq.gz
│   ├── e5e3bbeaf7b69bd3ea9f3c18fa7e742641436878.nq.gz
│   ├── ec601f0d6b7e26fbd02369827418cdf3195ee28f.nq.gz
│   ├── ecc4480df84bc5b61f845cca637b0f272b676b36.nq.gz
│   ├── ed0785096028d1c4813ce6f526b63ef533334dc2.nq.gz
│   ├── efed253fd1f70e923862248b5d0a25755734a7d0.nq.gz
│   ├── f0ce991447274666276bafe22f8044cafdc65ce4.nq.gz
│   ├── f1d8e9df735f69a5df3f2d5f20f6db6a5a22a261.nq.gz
│   ├── f25e6a206e38599e0766182a86dd13cc3d97a438.nq.gz
│   ├── f2be5f322d804820f2b461b684b2e002ba58e334.nq.gz
│   ├── f36607f9e93f335177eb162099a7b46821ba2382.nq.gz
│   ├── f6647239c9755df74b811c89d5b0411c5d4b7f2e.nq.gz
│   ├── f701bbe161df4f53ad68a71ae445ffbc3d36db6a.nq.gz
│   ├── f7772d35fe004b69e8352ea2452f821eb89a106b.nq.gz
│   ├── f98ac855e8776a3694251c3dc3be952091dbb69c.nq.gz
│   └── fc49da80e6c19f22bb784fbda949b3a89027af48.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e4b3efb449ccb994d39230eb6e8440d267471f4a.nq.gz
├── filetree
│   └── e4b3efb449ccb994d39230eb6e8440d267471f4a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 135 files
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

## Source repository

[snowballstem/snowball](https://github.com/snowballstem/snowball)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
