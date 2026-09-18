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
│   │   ├── 4764395431c8f2a0b4fe18b816ab1fc966a45837
│   │   │   └── chunk-001.nq.gz
│   │   ├── 48a67a2831005f49c48ec29a5837640e23e54e6b
│   │   │   └── chunk-001.nq.gz
│   │   ├── abd9adc758f5ba7f5db567d70a61e0929b69c3c1
│   │   │   └── chunk-001.nq.gz
│   │   └── e4b3efb449ccb994d39230eb6e8440d267471f4a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 4764395431c8f2a0b4fe18b816ab1fc966a45837.nq.gz
│   │   ├── 48a67a2831005f49c48ec29a5837640e23e54e6b.nq.gz
│   │   ├── abd9adc758f5ba7f5db567d70a61e0929b69c3c1.nq.gz
│   │   └── e4b3efb449ccb994d39230eb6e8440d267471f4a.nq.gz
│   └── repolex
│       ├── 4764395431c8f2a0b4fe18b816ab1fc966a45837
│       │   └── chunk-001.nq.gz
│       ├── 48a67a2831005f49c48ec29a5837640e23e54e6b
│       │   └── chunk-001.nq.gz
│       ├── abd9adc758f5ba7f5db567d70a61e0929b69c3c1
│       │   └── chunk-001.nq.gz
│       └── e4b3efb449ccb994d39230eb6e8440d267471f4a
│           └── chunk-001.nq.gz
└── blob
    ├── 000224e78409d7460542ff5967ea32e5316be3ee.nq.gz
    ├── 001d003687c1386a51bf904b2ab995a34e1f4839.nq.gz
    ├── 02df6c33f44c155bf617db2a33b6382afda74e7a.nq.gz
    ├── 0575b1d925a32cf249ce97ba38ce095f5daeff9e.nq.gz
    ├── 05d96f646ae25011cec486bf76f5bccbec8ba33e.nq.gz
    ├── 064325a902eba80a0af1c0619bef49ce42c3789a.nq.gz
    ├── 0a1e3a536fcbf0e45a7c5727e44a330b55054a01.nq.gz
    ├── 0b1288a161780ac0601773bf878cd83303082bf1.nq.gz
    ├── 0be3c05d2b1f1a6461288a3f760a4cec62a5bcfc.nq.gz
    ├── 0c77c6c0c18ce155b4fcb639d8ce504a74957f91.nq.gz
    ├── 0d46fa6e13d633f35db6e057712078ed5034c726.nq.gz
    ├── 12f972c8586d7860a832ab98a7bb15f9aad78250.nq.gz
    ├── 13c6674ef1b0ff15a7b720565396c4b8826ffc32.nq.gz
    ├── 147dd77d1b9e35d40988ec9f26998651d9b763cc.nq.gz
    ├── 15661344299e813f200d7474c1d87518bc6f76dd.nq.gz
    ├── 171fd73110cb3a156eb6949c92a16575f6914b0a.nq.gz
    ├── 179d185143064fee37557edabbc9f6b4424592bf.nq.gz
    ├── 1a81ab50dfd8c631438fcbed3caf25cbd5348d81.nq.gz
    ├── 1b27b96fadf3878ab984dc64c64fcb163fd08d29.nq.gz
    ├── 1ca336f211afc56677e8a95e0f7aae9a0a581ec1.nq.gz
    ├── 1d5a211145f32fcb8369a9ae984c2c4c4cb010b3.nq.gz
    ├── 1f61f69ed08827cd4ae9bddd46c5b446b0ff2724.nq.gz
    ├── 1faa3e79032ff8a7b97ff4b79270ea85e092bef3.nq.gz
    ├── 2000300f786c7308fd9443a1a792de7bc79d5acd.nq.gz
    ├── 2055c5e4b2de9507df6c76092e7d93b9b49648d5.nq.gz
    ├── 20de6395ef84a25ce4a402b415e573caf61491e1.nq.gz
    ├── 215c563e49c32f550084447f402557525706ac1b.nq.gz
    ├── 2169c4e08e289ce21b91b131398fdf21eec3a3b8.nq.gz
    ├── 21ea5f24615e0c337d25ba5bee3bc7f8c7640a77.nq.gz
    ├── 2346fbef8b40d6b13e53f24f9fb9f21b880ebf70.nq.gz
    ├── 249d6838d6bc689442b1d6523e0fb9728a67b371.nq.gz
    ├── 24aa49970631baae31d6a46fffa22b407a80233e.nq.gz
    ├── 259b68b2cf7c0febd472bc2a9746d798f9abdc97.nq.gz
    ├── 267abc7e1f3f63150044ab3c98d8129f76dc16de.nq.gz
    ├── 27b8637cdbd8cd4ea7fa57c2fe79a6da899d6408.nq.gz
    ├── 2aa918d6162fa5308c1168322961f0d429e34406.nq.gz
    ├── 2ad6327f1850a7991bf4f5fe82a1851f0c2e2529.nq.gz
    ├── 2bd049161a1ac55e2bc6fdf0fcde433723b54090.nq.gz
    ├── 2c73fc45ac61a9f9e181b976dfee8a65a2aecb65.nq.gz
    ├── 2cbb88596441e3a3286fe0c2e939b9781bf39ad8.nq.gz
    ├── 2d7885cf17a7d6933742fc3ab27f61a087a14ce6.nq.gz
    ├── 30b515da68e61efbf5659f86ffa9b4dd4b1d5db6.nq.gz
    ├── 315847829a5b695e656fcdd25e871cbe2583cc34.nq.gz
    ├── 33b89b96d03ecfca352571ebe0b572bf0d64a9fb.nq.gz
    ├── 3434753469b08984611278249aec34fefb7e74d4.nq.gz
    ├── 34dc3a4f8cadd9668d39e9fad070656756eb5686.nq.gz
    ├── 354ab56396085c2725738b35222892ee51545537.nq.gz
    ├── 38476dcdf63b114c5360199c0e81aae90c29ecc2.nq.gz
    ├── 3891d2295d77f03fc85655e4072a12838056131a.nq.gz
    ├── 3981fc3a59e00b6c18dab1e6448384a6b35f0a39.nq.gz
    ├── 39f4aff0fd716414a1b03b38f407cf7977466692.nq.gz
    ├── 3a9a9266fb8540e99f912a3db7a87007893764eb.nq.gz
    ├── 3b2d59a3cbc06797aaddbda147d750f0ef98d1cf.nq.gz
    ├── 3b8b833c02931cd8cf0de55785ac5d3f5e94b6e8.nq.gz
    ├── 3c48fb0cd2a499061978305300434682065a02f0.nq.gz
    ├── 3f69f15727b6225594d9cc1129e38253a1bd6789.nq.gz
    ├── 3fb14f1953afa7926f725eb9c9b6614a9de9bda5.nq.gz
    ├── 4070fa2a153c4e968e8a529286ca414a849f4f4a.nq.gz
    ├── 408fe6ae56b3b849a5b762644784277c7481edab.nq.gz
    ├── 409bf0ff7c96f7b6b11a47b50a4fbf64c1dc926d.nq.gz
    ├── 42514a852549f3a0a84999c911f59d600881ce55.nq.gz
    ├── 428856567706798f8fc9a1d021ef92c32f520914.nq.gz
    ├── 46854e8254110c4dc66658029effb49f7c92ed0f.nq.gz
    ├── 47a6a0cae0352dcf0b64d9782178dea9a4fd7fb0.nq.gz
    ├── 47ff61e38ff420d12727374f11318126dbf21896.nq.gz
    ├── 48568ac36c143650e0af5e20877a7d7987113111.nq.gz
    ├── 486e3ea097988058923244075e9b28d5ee9ee295.nq.gz
    ├── 4c2e5fa337c07b31238c26a54944a63cc5aad4b6.nq.gz
    ├── 4da74a6f552999bb49a31f61c5b50f1eeb94c6f6.nq.gz
    ├── 4deb06c50dff71108409d39b4ae53f75427bb255.nq.gz
    ├── 4fa76eefcc96d794607d62eb5fca2bce336242f7.nq.gz
    ├── 4ffcdec36791f3e16a35bb654934c5d8e107344f.nq.gz
    ├── 5417cc11a4c9cc0f5b6113d28936ce98142825c3.nq.gz
    ├── 55d1769d56fa9f33af8e9f79b4bcfe93df0dbcf0.nq.gz
    ├── 56e1ff5fb315a7ebc7835d8c059b1ee4e9d4f237.nq.gz
    ├── 57636287a09a7959bee77ac169a362f7893175be.nq.gz
    ├── 57fc8bae03b548d6106e7ff56f949a6de9b98a16.nq.gz
    ├── 5829ea8a9ba9c866c42ef77c62b25d736b4fdc30.nq.gz
    ├── 5980f59bde1bf7243c6c6a5202d20168c07ca06e.nq.gz
    ├── 5b6cf0c9d4cd4dba2975407e3aaef83023d9145f.nq.gz
    ├── 5c39da7a2b1018e368f4c73113ed648b7bd92630.nq.gz
    ├── 5c4f32d05fbfd8bbf30e66f0da6d139c67ec4fd4.nq.gz
    ├── 5cb2179536574ea678a109c892055f518fbf2425.nq.gz
    ├── 5dd62ccb74d6e1bd622dacc67503bbea69787024.nq.gz
    ├── 5fe00216e0223f54c3bd8af1082ccbd4aefa47c5.nq.gz
    ├── 602f9fbff306a8acfaa3add322742cecfbb3ba4c.nq.gz
    ├── 60eae6f0418c4ee853fb734cabb73c04f4af0294.nq.gz
    ├── 60f534418e27e9bfc7fc5065f5491a15fe03c6ad.nq.gz
    ├── 613d6ab8739b91711d65d12fb2c95f9c45a1c54b.nq.gz
    ├── 618d22d2a3c1ba5fcdc8f86984be0e572e5f0cec.nq.gz
    ├── 61f24ef9264f4c16614bb05be2af7d8df8580fa3.nq.gz
    ├── 62101bfea5525875e4d2a5869443bf6434bbacfc.nq.gz
    ├── 62a1f2f6b773c2f6c45a455799f6d387677238af.nq.gz
    ├── 63d42630a7d924950b4af739c452999fca7df94d.nq.gz
    ├── 64017b79c1e5b2c6b1fa47b0b561c3e6726e73a4.nq.gz
    ├── 6638f5f70d520364e8b426725afdd7d2f68d911c.nq.gz
    ├── 665000b63bd621b4329c7632e27380aeef61a4d0.nq.gz
    ├── 67638d7017d0986ea34e68822e750ab4dfac0c04.nq.gz
    ├── 67ca917141c9a801dca71724117edeacfc68823f.nq.gz
    ├── 6940fd171eb750486c0b93c5f75efbd480df520e.nq.gz
    ├── 69736dfca95784df49c9b792f824a3245e02f72c.nq.gz
    ├── 69b6a3cd06831e79ddb9e071c8494085f349e41a.nq.gz
    ├── 6aaede11796ce2600bf0ce7769a238f050ab83ff.nq.gz
    ├── 6c5044c6a7c5e5d8ec356b9470460e924d62d6fe.nq.gz
    ├── 6c777f274df419d5df3324e4709315122f9a0ed6.nq.gz
    ├── 6ce6c2fbf2251ed41537c9f37913b6951b51ee0c.nq.gz
    ├── 6e9f61b4622b2743d4b848bf1e6d87011ab204f9.nq.gz
    ├── 6feb4ef5deed22be07348d8b6babf00c792c3881.nq.gz
    ├── 714eff28c3a71baf9af4b67c5547642754bb9af3.nq.gz
    ├── 71939acea3f1e9f012045a8a5c46f395034713d3.nq.gz
    ├── 73a81a95d26b225ad104a9a666bce4621da8b19a.nq.gz
    ├── 74aeab19a16ef5a1c5e136abee18b90f526e01ac.nq.gz
    ├── 755af5281ac14d1530d6ac3da96e5c49e753b10a.nq.gz
    ├── 75a83f39c9a2b854fe09d2863e59ecf675df2fb2.nq.gz
    ├── 761270f7eb701347aa58ae6cfeaeb18e89d7b022.nq.gz
    ├── 7ac1d2dcee779d4afd46bfa268a81ce00c667605.nq.gz
    ├── 7af6debabbc3cad98e00aa8da10849887f09957a.nq.gz
    ├── 7b6e007725bfec7de2a5be1c45cb8e3d29cb98e2.nq.gz
    ├── 7c8c3638b61b3bba835d48fdb0f1cbda43d84a31.nq.gz
    ├── 7db9e0a5af8bebff3ffae80489ba3b7ec5adf420.nq.gz
    ├── 7e1c2b04042144c2a7dfd09ed5d6cb4ba94d82c8.nq.gz
    ├── 7f7e0eeb6674b0b7730ffe073247dd7555198a42.nq.gz
    ├── 80c03d47d5f71ac69cb4eaa907c4e1398c3446e9.nq.gz
    ├── 818ce77a5d6bd2ec325e9f785e69f0b86a10e4a4.nq.gz
    ├── 8261503668e22e78e28a9c1be8ce6d2cc711091c.nq.gz
    ├── 85d887062e2366b9b857df41b813456dbc6a9eb4.nq.gz
    ├── 862601fa9faf4acdb0fae08a818b0805a8baa3e3.nq.gz
    ├── 87cb67e88407d54c2360aaafbd2e1560c86cb1c3.nq.gz
    ├── 8877d929a9b4f106cebae344933032e4c359ad24.nq.gz
    ├── 8894c79e28c85eaf3f5e72a5ab2d310f9597e3a6.nq.gz
    ├── 89d67398d2e19f9f9337d25a54bee74b829b47c5.nq.gz
    ├── 8b4a8b57174eb4be0e08bec53b203a45d91f5738.nq.gz
    ├── 8b78d4574ecba8de5a8a99b0aedd2a060619a24a.nq.gz
    ├── 8ba7af8d08ea31a3f407e3928999004e5c3e3f90.nq.gz
    ├── 8bd6bb090bb1eaf68755e63c937e07aa664ccafb.nq.gz
    ├── 8be62e9a7fe420d8504fe3109536364cc77dc0db.nq.gz
    ├── 8cad14bb1790c54c8ac4bc0d51bb291298fc341b.nq.gz
    ├── 8d7372411f8d12ae3a4826e45e7f3f8d8ad1f546.nq.gz
    ├── 8e15646352ec1d9a84bbc6504ef6b46e16bf7823.nq.gz
    ├── 8e6af2ebd02b2547b04aca98c7f2544969ed37b2.nq.gz
    ├── 9354debae43b57331d8916117e1f4d73d032aacf.nq.gz
    ├── 9533b7932321c4bf8ebf2b3623b185861adbbbdd.nq.gz
    ├── 9635777ab771dabce1b465ad9fdb8e4c1ca02439.nq.gz
    ├── 98051e10830c59838f59774464cd2a67d1c4fb55.nq.gz
    ├── 983ff404c4ad987a1c6851f29cc8e975f9f03275.nq.gz
    ├── 9886430713c3e88f783dc405f49853927eb0ef63.nq.gz
    ├── 98eb1fa64c28b8f8836dac12b8ca6c217e3d321b.nq.gz
    ├── 98ed85a059f2da0acf2d5c9f3abccd5ea0881c29.nq.gz
    ├── 99ce8bff9ebb83ccbe5a2e917d3a64172fd98887.nq.gz
    ├── 9ba38d9eb1bb065f988fa31784e639bf2fecd3a8.nq.gz
    ├── a366ba90098912b446a6b879d21d2bd178fbb8e8.nq.gz
    ├── a3a480b81e1b7c246ed4cbe76d640d37fbe28ef9.nq.gz
    ├── a3cd3e4428d5569ba2e4b859f7f9629d26bbbd75.nq.gz
    ├── a3db4c85d04d674896ba88b7a0441a92e0e006e8.nq.gz
    ├── a4dc3079c83d54a73d23fe10a68a561b1c0bdb47.nq.gz
    ├── a67b186dedcbd490d9c734bda053c1763fe4459c.nq.gz
    ├── a6a7176527b415b1f0408c614eb3d548f670822f.nq.gz
    ├── aac761e41e8df3478a32fafd0188d440858ac801.nq.gz
    ├── ac0ee3655ca777e13cf876091f65cc09f49c9aaa.nq.gz
    ├── acebb6ae5b13435eb1c1c7cc9f771089c6167926.nq.gz
    ├── af577791583238f95b87cc3f1090dd1e84859963.nq.gz
    ├── b1d18ba82e38618fdb3bec40f4c089a5a0aef7c7.nq.gz
    ├── b2406a5672903f3ce5717ebf005feecca028b50c.nq.gz
    ├── b2fb7a4363d21104475127f6b69dfab5c7e6fe9a.nq.gz
    ├── b4573b425baeca8e2a766ec047d894aa24a04936.nq.gz
    ├── b59ea56bdd27e4e63accb149725eda59a68de65e.nq.gz
    ├── b75476ec889c8bb98442807a6baf2253f95aa3ba.nq.gz
    ├── b75b02165abbd57e4705ce9e0507912d76cdb0bf.nq.gz
    ├── b780220377e0fa5d60baa1458926574aaacfbc4b.nq.gz
    ├── b932a0b25da75ccd29d6319b7adac69fbe92b763.nq.gz
    ├── ba5f1b4ffef7f6e691ccb0ec7ad33703ef426d69.nq.gz
    ├── ba9d1c14bcae1f6e14a6d1154199099858e8a551.nq.gz
    ├── bd609e475be7bef038fe2e3b8aedea4b998e5bd6.nq.gz
    ├── bde07883624b2b25d8e85b846632cb5545b3fe8e.nq.gz
    ├── bf0c16176044501326193afb14128fcca74f592c.nq.gz
    ├── bf172d5b9bdf98e0fa49e4a1affdf2dab1169d14.nq.gz
    ├── bf822e44dd81fdfcbdfa708104cd974af49dfe19.nq.gz
    ├── bfd86638a39624a2e5301f74b8856001e0008ff2.nq.gz
    ├── bfdfac0e885fdf275d8d8d29f31955543d030990.nq.gz
    ├── c11f7162d62a8aeb4b04b8f3b1447f6c63c4fa53.nq.gz
    ├── c27b1741250b8d53f0808b646a65e2d685cf6a82.nq.gz
    ├── c2c8cb2050736b7a8930ae1c4e41521fe163c69a.nq.gz
    ├── c2cb211bc91c378e05d221379302b6ce7558286a.nq.gz
    ├── c3a93df2749d6d0601b82503d06661cb397e984b.nq.gz
    ├── c401d3e4fdc8953592a565e405c656a6d6a271c4.nq.gz
    ├── c42496b39297b01c11841ca59173a3e1c0f360be.nq.gz
    ├── c5157f87d874a219b87a87ce6a318ca9c4353b1c.nq.gz
    └── c580936c413b5929b76c85d75d55fce972304eac.nq.gz

14 directories, 200 files
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
*Parsed on 2026-09-18 by [repolex](https://repolex.ai)*
