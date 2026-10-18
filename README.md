# Repolex Knowledge Graph of holoviz/holoviews

RDF knowledge graph data for [holoviz/holoviews](https://github.com/holoviz/holoviews), parsed by [repolex](https://repolex.ai).

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
rlex download holoviz/holoviews
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4168fd4b99446003bda9b219421b7422f8b50d0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e4168fd4b99446003bda9b219421b7422f8b50d0
│           └── chunk-001.nq.gz
└── blob
    ├── 001c6b22f2f065668c5758ac49484cd978c623e3.nq.gz
    ├── 008081ca337d8d36698974105a1dd676145fd04f.nq.gz
    ├── 00b43a31a52bd780c7ca77356b965fe6ef6e832f.nq.gz
    ├── 01c1aa42485a93ec056c2d0100db21b2fefae93c.nq.gz
    ├── 029500fd9744596b493693dad4bf25cc78c44486.nq.gz
    ├── 03b12f38ea8c7ab2965fae1fd80697b435625aba.nq.gz
    ├── 043a5f76c96cf8aefe09a74c2a43e34474a88d5f.nq.gz
    ├── 046e5405ef3983481192a8d93c9bd11ab362c2bd.nq.gz
    ├── 04988c628f0632a01e5793eb64bf683773aa32e9.nq.gz
    ├── 04ed32a1be1e133c942e41fa736d4c56bc2f4aae.nq.gz
    ├── 0506d65394d87470846841499cc71db04375f513.nq.gz
    ├── 0511e947d1aeb0499b82267886368476cb776f4b.nq.gz
    ├── 0529bbb2ae8eaf059603b4e215607a965000a571.nq.gz
    ├── 05a29a82743727e312e5fc79ee74ddb2c8610ffc.nq.gz
    ├── 075593b5e4cf2989163a66f75d436167cc222f4b.nq.gz
    ├── 079298ec50734aaa40dcd8f0fd12857653da26f7.nq.gz
    ├── 0849ce5320d10fa9bdcb7af9137767f510d93281.nq.gz
    ├── 08c57b048168103060c0e6504114f6c569d44ae9.nq.gz
    ├── 08e01e517009cfd4fbee5899a4dda9b5f1061112.nq.gz
    ├── 0a2b558f7a81cb5fa1f023b75aea086d99e41b21.nq.gz
    ├── 0a9058bccba228470cd651f2ee9f87602dc4c938.nq.gz
    ├── 0a96fdd0f7c637628c806734fab4818e8800881a.nq.gz
    ├── 0b3f44044e480fb65d9984f012ec9fd85d35eb25.nq.gz
    ├── 0b447655eb1382e8cfe9a4b1fbe0910c5b74a222.nq.gz
    ├── 0b84119e4e5b8f2efda948cc8251577d781fd30f.nq.gz
    ├── 0bd9152a7657c50396b14fb187a7bfdea6353907.nq.gz
    ├── 0c1a36d0ae227415b03d85da7984dc95e01aa4aa.nq.gz
    ├── 0c50660cc34b13f43d982d14273bc964050f9edc.nq.gz
    ├── 0c8124de0ad0ad020e53e9b8c8865b3071590540.nq.gz
    ├── 0cddc4c6daaf6644d5ad7f514eb75ee9a630c07f.nq.gz
    ├── 0d0206df49a16d06bf77e69bdad583d15378e82d.nq.gz
    ├── 0d2dd9474e558b1c1616d640519c5d8fdf0c4352.nq.gz
    ├── 0e43d94fad6ab1bdfeab987dec97e4ac16ed51ff.nq.gz
    ├── 0e79898b39c4e64fb180e5345eff5d4f128a1e8b.nq.gz
    ├── 0e81c02bcd824361fb92ec85c1afc365f38567f9.nq.gz
    ├── 0f85256ee08419cfae06e7cc994657b65238c97c.nq.gz
    ├── 0fdb7c292a0e433a8025488f98104b1df1e70e87.nq.gz
    ├── 10143440efbf5ed7be7f91706e522465c3ea301e.nq.gz
    ├── 10353e10f448c9dac515b72d11a53e234486571d.nq.gz
    ├── 111112c8201b5619b2d20dabf9c1e804233ed96a.nq.gz
    ├── 117278ebbbc3c314998654856ed0d65c3eff3164.nq.gz
    ├── 12105681386934367cb229a39003acd40e34b85b.nq.gz
    ├── 124d675832f5470d9a25846a101811a51e712945.nq.gz
    ├── 12905d5233be7d31ae50bd60bb6fc1bc7fe6dde2.nq.gz
    ├── 143c1b2780a692688adb1d9303ed42a83bb5223f.nq.gz
    ├── 14869bc125b073d734cf6d56596cdab553814ba8.nq.gz
    ├── 1570ff9967328e5f9d077e6a5af0b784d72e9c3e.nq.gz
    ├── 16065ec034da273f68cb4873511ff271c4e80c09.nq.gz
    ├── 174acb88ef5bc0cf75fc41167588c22b7f141e2d.nq.gz
    ├── 185aaf82442e80355bc5fc7d25f4946dbdc6b529.nq.gz
    ├── 1a1a3802b8b7e0740a48a7cb3d0db8827b583d6a.nq.gz
    ├── 1b0272761d2312741de0c4ec6ba470b0f12cc220.nq.gz
    ├── 1b7502aa81fee02b4d4ca59320c5b43ffcd47b19.nq.gz
    ├── 1bd08c642591e2ee1ce62d280436710e91d9b5b0.nq.gz
    ├── 1be4e6edc617ef443c72cd9f8aaec352cfe2c29e.nq.gz
    ├── 1c7804f23ce6c7023be6591c637cde7ff52b9d6b.nq.gz
    ├── 1c977542dc559aecaf3efa3a6de6709726438e82.nq.gz
    ├── 1ce715650219342daa66441a4765e8a947200b0c.nq.gz
    ├── 1d0e65021c96de2de65d8bac5c5a84e0446f1d14.nq.gz
    ├── 1d7fc14db327472afef9bb136553b29ac7d379b3.nq.gz
    ├── 1d99b36c08c7e7ffe2158708a2a1bf951f93b033.nq.gz
    ├── 1db78b7054c73b72d9ff98edfae785d117529215.nq.gz
    ├── 1e0c3576b81627e01ab021d3bcaa80c41583ee65.nq.gz
    ├── 1e5836212b9ffb7409ae177b97fd132f6b1c7429.nq.gz
    ├── 1ee3430ee983d89e53e872d96866b418760dc4c2.nq.gz
    ├── 1ef76953bd58fcb6b4ac6607161e3e630798e706.nq.gz
    ├── 1fc87f62e4f4a720d7b16af6cd1a4d12295fe139.nq.gz
    ├── 1fce8da3e42cfaa3c4b26bb13e098e105948d345.nq.gz
    ├── 1fd8ba6958b6f047a04f387c74066ab5c924f251.nq.gz
    ├── 20b3562c873e67ad15d361dc8d7da1671db23e69.nq.gz
    ├── 217b43d6e6e6c233a43da1f63aec5b13330d2683.nq.gz
    ├── 229f1cc4b689770660dc8abcf9754a723ab148d1.nq.gz
    ├── 232d824045d1aafe8624a45a4bdd5b4c9a866036.nq.gz
    ├── 2360f9a22ba99943c8c643bb0cedee5f17c7a03b.nq.gz
    ├── 252b32bf6feac96158beb5eaa65b120bea4fe5a7.nq.gz
    ├── 252db86a92b171ab1daa96b78eb67c518dfb9dee.nq.gz
    ├── 258ffa72243db0afbeb840ddae68f85409b92e1f.nq.gz
    ├── 26cca4d52a9ef8051332746ca067b1be57924926.nq.gz
    ├── 278ed4a61a6960046ae283e3f43ec48328a4b40c.nq.gz
    ├── 27b6b4f768d59b66c222013406b803e531980559.nq.gz
    ├── 27cfa4a33cd1f0210334c9e1309453c95abc454a.nq.gz
    ├── 27eaf70132d254f26f03b6a87188099ff9f3aa65.nq.gz
    ├── 27eea9285d5e7b94cda270995eef7fca255406a2.nq.gz
    ├── 27f165e2ad938661ab70b0b4b44b544fb0da5fed.nq.gz
    ├── 296286af54a01c0e8cc131f9372329db5831d377.nq.gz
    ├── 29aa8305814554fd926769da9e588b6ba47b9efe.nq.gz
    ├── 29c4f806670cf64bf1e4f2ae2114dea4b1e18948.nq.gz
    ├── 29d56496093ae4c575f3be215d5fe1cea4851ebb.nq.gz
    ├── 2b0dca71b751da28199e5281320c7a31a9113d56.nq.gz
    ├── 2b292a9385b4b6c76e31e49f783b2f372065c737.nq.gz
    ├── 2b780f746d2fed0e0097784d42b28d84197b544e.nq.gz
    ├── 2b89bdbeaf9904641c2b913b9527fd20d212465a.nq.gz
    ├── 2cae06f35c12a8aee4571221cda98b51c3f966c4.nq.gz
    ├── 2d21a5d45ec8c2c544e193c8a50175c6d983d5df.nq.gz
    ├── 2d559f3d4d047ce45f088cdbb4e7f6313905afc2.nq.gz
    ├── 2dafff39291dda80da840c757790467579a1acef.nq.gz
    ├── 2e2caa49d797e85d07ba91000c55173403de6108.nq.gz
    ├── 2e6dd57e7c5eb6849d42fda16f0cf8582ee1b2e1.nq.gz
    ├── 2edf321ccbc82a73b2136fc85f58694f169ca98c.nq.gz
    ├── 2fa0dd80e6a402b28bf6771d5e417ddaaaad93d8.nq.gz
    ├── 307e6affcc7afc39cfad6d890feecf9106be011b.nq.gz
    ├── 307ed160d7f5ac5a3c690166cabee185a7e20b36.nq.gz
    ├── 3099f86e275056857dbfcbace9c8148669758f9b.nq.gz
    ├── 310b7f207157e23a47a6ab5328e0eaf200b2a7ea.nq.gz
    ├── 31acaaffd6e39d3ac756894a952223fdb851df6b.nq.gz
    ├── 31d6f7d0dabaab8f6077749145023a686e466a8b.nq.gz
    ├── 3210b8f6c53dc0757619fc9c948e10b4b8bc7a6f.nq.gz
    ├── 32162dd750913307774908f22a546c8cf4bd4bce.nq.gz
    ├── 3228f18e07eff6dcacb5a92c7acfe9818492e3a3.nq.gz
    ├── 3359bbb216bc63f7b49967bc5075dd385857c105.nq.gz
    ├── 33ef5b0ddd7f567405c8435621f38f79d09db4c0.nq.gz
    ├── 33f8b7ae1e075f103207676874ba8e5496256022.nq.gz
    ├── 347056ab7a099c0fe8086e319a87669cec34d1a5.nq.gz
    ├── 34b687a8c28d954f60738ee51de74b1f3bd188f9.nq.gz
    ├── 34f3a15514c8aa28a6cbaf6604ea16e7f8924a2c.nq.gz
    ├── 350f65a3b7c937eb2fd195b7f56afc0c2471c132.nq.gz
    ├── 35ee1c017b46a3e6f3653f0a555f3355a9906777.nq.gz
    ├── 368fbd1846fbb9ccdab67dcf4f6ec2ac3080efaa.nq.gz
    ├── 36c5bd8d9f56b0ee88761dfc6c9abf15e4c0c5eb.nq.gz
    ├── 376ad1946f6f4cc7b1012e8562af5cca147d19ad.nq.gz
    ├── 37c1b4c12aaf8d13bc04241843176ca3262008a0.nq.gz
    ├── 38428d0fa20d6502c272b4fcf43cee5c2c341411.nq.gz
    ├── 39f0e0b2f82b49d81db8e92632edf8ed3fe9127a.nq.gz
    ├── 3a08fabc62fefc085d3a6b7c5337a6e36f05119c.nq.gz
    ├── 3aaa2d4e3abaced2d91a394e301127a912b91752.nq.gz
    ├── 3b3fa7f3a2850118fd2c2a7766c36ddd055ae1de.nq.gz
    ├── 3be81392288dd1ab943f6ff06bd8309c6aad42b1.nq.gz
    ├── 3bf5df7e22facba9dbe9b7f0020689b7230fb486.nq.gz
    ├── 3c033f8cb075a23908cf68715f02b4c0e4ce98e0.nq.gz
    ├── 3c0fc1499c8c80a23c41b16fdc902bfe2f635058.nq.gz
    ├── 3c3dfa8fe6104b94781d7731c0454aa5757779e4.nq.gz
    ├── 3cbde48882c4956d66be040a8a55b5234e32bece.nq.gz
    ├── 40deff049a0f239afa81914f78ab6f04e7654c7f.nq.gz
    ├── 40f337de898937f4676e483830467de2104d6513.nq.gz
    ├── 411d87aaeff0c61e5ea15ecb5095230a2f1fec15.nq.gz
    ├── 41a55040e5ca077482338620263c4a53664c8baa.nq.gz
    ├── 41e16f5bef013ac16c7f062d3bbf4589f09c3b3c.nq.gz
    ├── 422165fa5131a234a353e28230e6abe80a8a7766.nq.gz
    ├── 422d14e275be0e6635471a777d772663a071065b.nq.gz
    ├── 430bfb1cf07487ebe372474c2de8ee8c74a26071.nq.gz
    ├── 436442aadf25a9a305d439d634679d6238928f46.nq.gz
    ├── 436d0821fe8101da91301cfe2f1d9c3c55ed9786.nq.gz
    ├── 442b4e076c5494304548e7885b9ae774bf97b596.nq.gz
    ├── 44e3dd2e157943a12cd065b27e62974cab437747.nq.gz
    ├── 4646a4c81bf15df310cec17e9c37e3ead740eb76.nq.gz
    ├── 466759d3b94e97fdd8835fb69eae10b5bc38fdef.nq.gz
    ├── 46758d5320d058221547e24646a36aff7b1fe5e0.nq.gz
    ├── 46c22f6f4c8198394bd4d5b728c6f71ae2ade9f4.nq.gz
    ├── 477e4eb751796cf7c0565cbf54dcdafccbd6fc96.nq.gz
    ├── 47c87881c9cd7f06b967dd8cd986338f0a76caf3.nq.gz
    ├── 483779008d80485733c1ae21e5b51793f8d727d2.nq.gz
    ├── 483dac41e3e416b57507d0e52aed78f59be62583.nq.gz
    ├── 48d19503c6d297f7fefe349f43b8b85ec300407f.nq.gz
    ├── 49e88f150f17dbefdf88e367693d89fcf0b3a816.nq.gz
    ├── 4a3ed9c1e2b1eb7ef1ee4a2aa27a71e57f69cae5.nq.gz
    ├── 4a4b64cbe2003db554a8c85e594e2c68da5c20b5.nq.gz
    ├── 4a7a2b6a4b0a8c9f6358f88374883319d5f4c8f3.nq.gz
    ├── 4aaece9b22c1bc153db2ba0b7e8dc6bb0c2b29fc.nq.gz
    ├── 4b0d6711ca6aaf2f44dfdc607e08f0fe56e81323.nq.gz
    ├── 4b679d0629f7e795f29f08536ebe45842b268bf5.nq.gz
    ├── 4bc217092f417d8067f0bd654dad86c4db7eeb57.nq.gz
    ├── 4bc9d468597cdf26aea20f09135ed34834c2421e.nq.gz
    ├── 4d0426a36da773563747bdb9b32260bf774246f1.nq.gz
    ├── 4e810a681c069134d9f46c67eea6b39f309fed59.nq.gz
    ├── 4eaa2cfc6600e43b5f4890891d2467a122020e5d.nq.gz
    ├── 4fc19c5dfb55cde145321f8068093f7f61b6aefc.nq.gz
    ├── 50271e0d6ca1a768df3a7fed771250b7fff94cc0.nq.gz
    ├── 50e990497e52f34db3924133b381a7d1847c78ad.nq.gz
    ├── 50fcaa391e84239d0bf9e7eb3fb2708c1672814a.nq.gz
    ├── 511a0baf430b3bf189beaaec2a1434bc0cc7d77f.nq.gz
    ├── 51342768202d59fc5148581f3c18c934537e4289.nq.gz
    ├── 52207d921da83f63c4e88d3dc27376c74eb01591.nq.gz
    ├── 52669333b6c7906d7ad6a3a489ef6d8888fa6f33.nq.gz
    ├── 542791d83f1e52bf1540c1f7b4f1282b003cdb4c.nq.gz
    ├── 543c134cb50797f1ef9c5f7cd70070637447a194.nq.gz
    ├── 552e6b0ca78e62d9e8cb0b7166c1f81b61081a83.nq.gz
    ├── 554e904ec2898ca75a5e52edbdb5ba6ce4261e56.nq.gz
    ├── 557a806d38bb5596542be849d1da14ee9be3f640.nq.gz
    ├── 55ab88cc22bcdf9132049f98517d183b91265fb6.nq.gz
    ├── 5655530cca4241ef5f486d7adcae61888fa81e1f.nq.gz
    ├── 57629bb7db089eb379c52575f658e5a36374900d.nq.gz
    ├── 584003af4d34f8993ce3626bdaa007ddf0503117.nq.gz
    ├── 5aeb840ded5b8ff95088a2554810b9c1a17cf4cc.nq.gz
    ├── 5b0d8d88098018d5f65bb1c023a367b8b04892e4.nq.gz
    ├── 5b27c23897492b729d574eb066d2e4397af35397.nq.gz
    ├── 5b2882030f78a6c5d1beec3df219aa7b1d4166fa.nq.gz
    ├── 5bd63107fb75c2c74365557ed744aecd72e27d10.nq.gz
    ├── 5c555854fc89eb2401a381055fecbe3a779109f4.nq.gz
    ├── 5ca9dd82407ec8a71da2d71cbfda5f8f8121dd4a.nq.gz
    ├── 5f657d2dd15bf63d6db1d32a9032aeaf1e65de01.nq.gz
    ├── 5fd715f5c1d352fd22c5ea6f6a81d746f5ffa79c.nq.gz
    ├── 5ff68bc88cf4ff0b17b407bad3d2ff1750cbb97f.nq.gz
    ├── 603f515b6f319192d0ae2ad6a54c537bd61f60bc.nq.gz
    ├── 606c9805662b3809e4edf1d5f5cde320dbfb1554.nq.gz
    ├── 614c1bab853760ddee3c6dd046665d1cab80f460.nq.gz
    ├── 61b0d9c3bc27695c18bbe70271cb835796c21652.nq.gz
    ├── 61d0bf66999785eb8b36b1262c33f10157baf478.nq.gz
    └── 635cf8b871df52209143041a5514a1eb8e425591.nq.gz

7 directories, 200 files
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

[holoviz/holoviews](https://github.com/holoviz/holoviews)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
