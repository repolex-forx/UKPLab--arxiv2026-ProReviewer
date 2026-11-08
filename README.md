# Repolex Knowledge Graph of UKPLab/arxiv2026-ProReviewer

RDF knowledge graph data for [UKPLab/arxiv2026-ProReviewer](https://github.com/UKPLab/arxiv2026-ProReviewer), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/arxiv2026-ProReviewer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9aa7bc4566441300a329e77b1fb44e22acebe301
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9aa7bc4566441300a329e77b1fb44e22acebe301
│           └── chunk-001.nq.gz
└── blob
    ├── 01d020f1fae1f3eb47b6f51a573fbe1c06dd40e5.nq.gz
    ├── 0267603738b300d98bbd608e59fd0988c3389f05.nq.gz
    ├── 02bce36fd80bde985d49339da0f5091097205588.nq.gz
    ├── 030c3158cafe2b6f35908b4a25f7b39266b3dc27.nq.gz
    ├── 0329a1321473128d6b82b741e53dc8c8b3eb040d.nq.gz
    ├── 035542b7e2bdfb5c147b4297cb0c2f83c897b8c8.nq.gz
    ├── 0444de62a976ff3a3985b7e5d3e8525dcd0f4e85.nq.gz
    ├── 045fd4e5ece0dd1ab00282072c2299ef5087a37d.nq.gz
    ├── 046e1c072a45a363a969e989528376e4d41aadf4.nq.gz
    ├── 04aadd3c9227b95b98ac08886cdf536db7cec732.nq.gz
    ├── 05271d5fe9b0fd0772f39aed94b602721ad23407.nq.gz
    ├── 053c7f97fee495f20910d842de889d0c13a370dc.nq.gz
    ├── 0564dfa628cd4b4dd8d4583494eb6b8bbc2bed6b.nq.gz
    ├── 0593ca54c430812544607578771628ddf9bbebef.nq.gz
    ├── 05a25ae2246548b64a06453a25d7b0b18ca4688c.nq.gz
    ├── 0612a2bb6cf7c1acecca8120a67a09de0496d0f3.nq.gz
    ├── 062b102c512d2bcc553498cb91f72514e51fd6ab.nq.gz
    ├── 06f05cf02c7f480b487b2690e22c7b35cd86c637.nq.gz
    ├── 0789a396fca0ee0785fd093c0296a833e7358679.nq.gz
    ├── 07e872d86f7066413130d0943aa05077fd0cd007.nq.gz
    ├── 081f360af14746b0785fd71b024ee113f0c4dc14.nq.gz
    ├── 084abe43085fcc75490a10aafd1de1e8058c2d10.nq.gz
    ├── 0884f0fe97d6e22e20f73e2330fc17edc0528cc0.nq.gz
    ├── 09b00f05e1f3124b4c5383b2f5ae38c7a5ca8a01.nq.gz
    ├── 09f474948e897b90d7426d3ebc29d850d0c4d4ca.nq.gz
    ├── 0a412931fe17de93c742abed3284a87ad3432b53.nq.gz
    ├── 0b6f6c7ee9bc93c57bf74c5ffc5864d04381f301.nq.gz
    ├── 0c1faa44be64127248814db35f143a496ca4b2db.nq.gz
    ├── 0c8491dbe98faec3ebadaecc15546eb22642153a.nq.gz
    ├── 0ca2782853b738b73da0ce375a81e174de855069.nq.gz
    ├── 0cbbc5735a69d6785650779c46cd85d38fbcce34.nq.gz
    ├── 0ce9953cf569a0c15d72ef8277d8d6c7c17a8d68.nq.gz
    ├── 0cfff5296194bea3acd7cd7a470d5cc257a828c3.nq.gz
    ├── 0d431eca56bef9ada9d47bdf78dd18b5de8f8377.nq.gz
    ├── 0da6333e322200e808d8a802e01c2efb3f52eaf7.nq.gz
    ├── 0dff96596bfe288dd9b60b1f4365d16b0f357553.nq.gz
    ├── 10bad6e7297d7084717f940471a10ef5bfa13871.nq.gz
    ├── 10f6f77583a4f970435ebfc2734c1225f601a76b.nq.gz
    ├── 1115cb5ae57bfcf26918bef9fecb65515023ef45.nq.gz
    ├── 11672614413423a237e0b2303757a245739352de.nq.gz
    ├── 11e1fe0e6982ae6c89c9d1af0b096e1c14392cd7.nq.gz
    ├── 11f4c850e33063f4b1261b58ad5bc0f9a7cf2ae6.nq.gz
    ├── 133e47fc27d0c68d81f49104b9dfe58e081b805a.nq.gz
    ├── 135f09bc3c8734b5c82e36153e6d47d236570e35.nq.gz
    ├── 1387081f80af570017418836e6492fb8fe573733.nq.gz
    ├── 13cbe7f739779bdcc2b7bb95f3db0ac941850389.nq.gz
    ├── 140fd706a4033f992f4cab194c17ea279c05eee5.nq.gz
    ├── 141fe57147ddc525daf7eff800f54537972149a1.nq.gz
    ├── 14a559ad7fdafb604cea82eba87e267d308894b7.nq.gz
    ├── 14ada43cb69a4b7f5e83ba3531f228e9843bbc51.nq.gz
    ├── 169820539fb2b2270e12034320c37e121ef79489.nq.gz
    ├── 16bf74b031fc909f37a654965e7aebf1d2239779.nq.gz
    ├── 16e588898a1194cb205699e1d6166f62d4addbc3.nq.gz
    ├── 179c68f4b62a4547a03dabc2807654786446ec52.nq.gz
    ├── 17a2ea5022808f0c57bf5fdf2caf0f2e0302439e.nq.gz
    ├── 17b80044b4496edceadef83702a060c9714c4105.nq.gz
    ├── 189222fc2fefe871d2a51ce51774d1d91de34766.nq.gz
    ├── 1895779b2e62b65ed3d2521b28b4f83ef1296c8b.nq.gz
    ├── 189915a9f53ead216403cf78826721ad38ccadac.nq.gz
    ├── 193687d71543efad42c3c3d649e114f057a27274.nq.gz
    ├── 19b61b9fb4db98d097cdb822aa556cdc9c69f1cc.nq.gz
    ├── 19c06f2e7e3ecb19ea371bd194a1b066b320819c.nq.gz
    ├── 1a32bf8cac60202275e3c71a1001fd6bc20a63b6.nq.gz
    ├── 1a995b888943c14cbfd1ac10a3f5e51f04ec22c1.nq.gz
    ├── 1acd084e38a694a2738ce57ccd8b1a867ddeced1.nq.gz
    ├── 1ae5b48780fdf6e9a319ada2d01b5b2e399f30ec.nq.gz
    ├── 1b41db8eb4fca3d2ff55e2cda21bdd3f021c3400.nq.gz
    ├── 1c669d2a2bdb414e817b94d77fdafd1545471ef2.nq.gz
    ├── 1daa99cc465249a9dd1de46c3b89bb52bc500c84.nq.gz
    ├── 1db5865d011f07e94b58d10dba91bc72a9db9a72.nq.gz
    ├── 1e11099b4917d7194bf7f444cc23c1d9c0da3238.nq.gz
    ├── 1e3ad1475d1275971eb93a69b227c6091b1ce1db.nq.gz
    ├── 1ee9083f7c3c343e2c89445b8641daad044cb2b6.nq.gz
    ├── 1f694b8a8195d8ae452b387b95d8e236abb1fb47.nq.gz
    ├── 1f6dcffe47229c50d8c489807bca2214f3336444.nq.gz
    ├── 1f7beb3fb1d1e5db69f2b6aeb5f9d10a1a2a222a.nq.gz
    ├── 1fcc1519c5340e9a2470a27e96723b459d125fd5.nq.gz
    ├── 1fd996e3fac2cdc11097b9982c49e0cf940a665c.nq.gz
    ├── 206f678965bfc10f7f2e45095351a059bf1437f6.nq.gz
    ├── 21319e801bb776455a9321c5bf0b7f4760b85b1a.nq.gz
    ├── 22b30195b4c3c808cbead5fb3d151ed4a88dca2f.nq.gz
    ├── 22c649ddaa576dd90905ddc025624e56f1564c4a.nq.gz
    ├── 22df686ca6ad63533de4fa6de76bdd2d26ad776b.nq.gz
    ├── 23db24fc75d177546b402a28f6761b6d4c4429b7.nq.gz
    ├── 242aec1b585a771ac81b89f785bcb6381c685ebd.nq.gz
    ├── 24360b646c5349910489ef47a52cd04feaea9e42.nq.gz
    ├── 245fd237567967c3b65021e6681738899e7837e8.nq.gz
    ├── 249fbda23f6bfa1106cb3ce8470fc19fc67d216f.nq.gz
    ├── 2509d1050bbc34f9a3fb5d42f09aa97a19e61464.nq.gz
    ├── 2511500c3663dbbfd9800986ce61ac75d9e9eae7.nq.gz
    ├── 25d786436e8333af8c17e91e5067e5b32fe87bb8.nq.gz
    ├── 2671d7544f59dc3e1bfa693e225e2f583099b715.nq.gz
    ├── 26a41f9c865d6184ec606b0c7c925b0a1fa519f1.nq.gz
    ├── 26af69740bb0ad69db6ceb9c9b3052fc9ddacb25.nq.gz
    ├── 271713521d64151c7e2f3d3bf623d5ddc7bc2abc.nq.gz
    ├── 274ee41708ae581e2a2ea2e8f03cad113f1d9eae.nq.gz
    ├── 27c978e92ae8b6f741cad9dcf2ba404b8b05af67.nq.gz
    ├── 28338559c30bf4dc86dea851afed54971e22193b.nq.gz
    ├── 28441a96010cfd5f5201b716288d45e419944428.nq.gz
    ├── 2890d5ad1678473285144f383c21ebcddab73d3c.nq.gz
    ├── 29ef46e3e9690f7d6802a69aabe39135ff302740.nq.gz
    ├── 2aa69bddb02870335886921a6e7e101881eb5721.nq.gz
    ├── 2b42e3269e7800dc3b4381463e7e616259e2b426.nq.gz
    ├── 2c8b2999b32cfba7c63a4870ceb468163345f14c.nq.gz
    ├── 2cf3f0648752ffecf42ebf31ebd3e077e3f009db.nq.gz
    ├── 2d4bc82172ac09bd04179ba2f87d5df18dbdb09c.nq.gz
    ├── 2e3a18e904d1fd85e004281407bea1d517b7fd65.nq.gz
    ├── 2e4ed831b809916df7cffd4bc03d1e82cfd5d134.nq.gz
    ├── 2ec202bf7fc5f026f4da3d833737c893b41c2bc5.nq.gz
    ├── 30524e7c75f4826eb77c2ad212ae10727f8ebfde.nq.gz
    ├── 30859e9bc85ea9406871f8d6be7459d90e066656.nq.gz
    ├── 30955dab663649be63e697f2af5e0f9afcf9ea12.nq.gz
    ├── 30a7d89e6a1fa06c8304cef5acc81a45c3f363ce.nq.gz
    ├── 30c2f88b98fcb3fb31de561ef43a949775d9d457.nq.gz
    ├── 3102599ef73fb8f878f036a8de3a438f69b2356e.nq.gz
    ├── 317477d0c1616a73b59a7fa601b3e58ee78b32f7.nq.gz
    ├── 31b27993f5214f4365ba15d55db8bce95f219f62.nq.gz
    ├── 32395597d8d4c73344c37e3a77fde1a9fb4b8827.nq.gz
    ├── 34e4211a6d3fe0e7c1a5bccc40cd50298c3d492f.nq.gz
    ├── 354346b57afcb77449c3082fc6a9ad21f989206a.nq.gz
    ├── 35d3df49cba76dbcde077319698fa7973682e48b.nq.gz
    ├── 366d59f4877384aa99ea22cd4949644c09f05b6a.nq.gz
    ├── 3683c6458e7dc11354c9485bc55de1ca3a843bd2.nq.gz
    ├── 369ff5c171f217482905623444baee117bc4c299.nq.gz
    ├── 3871c092fd85e9898884e8f61df7ebcae4ca95db.nq.gz
    ├── 389375a956aa21ab7e090e8593c525b3855665cc.nq.gz
    ├── 38ab8eaab9de86e54326d692c7553c8b35876b6e.nq.gz
    ├── 396952b667e2c04f464c57ce378fe7072aff4786.nq.gz
    ├── 39b345fa5b1de9653365ca546b5889fa78ca00ed.nq.gz
    ├── 3a200a088f99fba5010584cf7abb8e330153aa4b.nq.gz
    ├── 3af01a31b72d99724870d5d453d26bb4268531ca.nq.gz
    ├── 3c1a91115d9522928e94078169af839c675d9d72.nq.gz
    ├── 3c22c30deceffef9fd12c5d3e5010e899cd0a73b.nq.gz
    ├── 3d8b8d4a68cd2132aa9b4de40ef52774c6aa3ff8.nq.gz
    ├── 3da96b04436cf3feaf3da01b9a189e66380097b2.nq.gz
    ├── 3e97f62918b2995b228d5b5c23c1a5bbf144114e.nq.gz
    ├── 3eb3881c91fa303f7360694419a49694f20eb462.nq.gz
    ├── 3f1c439bd862b49b34596e70daed174ed1fcf46e.nq.gz
    ├── 3f426e7acaea73e3425da45430acdc9da547c15f.nq.gz
    ├── 3ffffbb02532733a0ef4ad0d7af317aec17c046a.nq.gz
    ├── 406695c4718e0df5b03a93f8030772e0cdf15aff.nq.gz
    ├── 410c201d957f370165d66a4f3861b8ff53b933b0.nq.gz
    ├── 41d4d83d99002e64688a7eef86a45cc0ffb9ce21.nq.gz
    ├── 421b0384b603b7d688d8449a69efc5eb2a851971.nq.gz
    ├── 42916fa86347602036e051c837c84d53d4006482.nq.gz
    ├── 42f18ea139b5eeb0332ed07420c5d69e4d9a62eb.nq.gz
    ├── 43420e78ca9a5e95f19005ed51b38ec8463a2e8c.nq.gz
    ├── 43924560d38ec04d66174a1a1229078eda178c93.nq.gz
    ├── 43f18b0261b9e09cddcea6e1aedd042df71c20c7.nq.gz
    ├── 4453aaacfad4f5cf593af366164dd06c5074044f.nq.gz
    ├── 44fd0f75dd2e54a82606b19baf899a933527fc77.nq.gz
    ├── 452b3999d2047d90595dfbf1f2e2820a90a0460b.nq.gz
    ├── 45bd369b225c100a7141cb571f3b31277e06a7d4.nq.gz
    ├── 45d5c385b8328a58cefb86aad1dfee5d62db9ef4.nq.gz
    ├── 45fa5e30be92997afa320c93e61595c7d9ca426e.nq.gz
    ├── 46aaf076d588f1ed2711e4f2f108a46a1c8a0203.nq.gz
    ├── 475ca1e4a1ccd85c1d15a0c8c3da972b35cddb77.nq.gz
    ├── 477694743d916f0fefe5a27a363467e4cad183b0.nq.gz
    ├── 47ccbf91fb46c25c66db6baca91a402d2fa3ae2f.nq.gz
    ├── 4890fe0692f7b04b7ccbc3d84113f4e288a5c381.nq.gz
    ├── 48d900123826a8dc58a3ce47656494a351c15e94.nq.gz
    ├── 48f753938d2de04c81bc09f884759c1be72376a9.nq.gz
    ├── 49452e5eb5fa96a063a30cbb78e7cd0fed37e623.nq.gz
    ├── 49a364ad1878ebe190fcaf4a470dc2cc5e2a3e28.nq.gz
    ├── 4a30a64bfcbd1913c4d58e87e0d12250f5580da4.nq.gz
    ├── 4a4c17bbbea0cd3bc75aedeb67798966cafb9141.nq.gz
    ├── 4ad4db88664ae8052339248994274c9097286749.nq.gz
    ├── 4b3acea012ff2993d65e99dac793f0087abcd526.nq.gz
    ├── 4cbb16ed3527dac3cae1cdcc032dbcac45a56bf3.nq.gz
    ├── 4d6ec5212c39cf001500cbb29f0591c367b8f83f.nq.gz
    ├── 4dbfda8d8fb5f9e430a8c08118767843776e73ce.nq.gz
    ├── 4dc758c817fd0c82aa0b39c9dcbe5127df0d573b.nq.gz
    ├── 4e4b7df59f1cd210a20b281a83b2b996037c76f9.nq.gz
    ├── 4f77a406efe707128d0675cad6adcef351689856.nq.gz
    ├── 504cfd2631282d8d7ed32e166b0ecabc649f7195.nq.gz
    ├── 51538eb42a4f0c472cf45cb368cc115ea3283e9a.nq.gz
    ├── 517263bfb6e218f2cdffd32597466305a90207f3.nq.gz
    ├── 5216e594f871f32d4a6303b14fcecf2134640785.nq.gz
    ├── 53d97fbd648f608a17358b6599972bfe66be2b1c.nq.gz
    ├── 54dd27c01bc3e87440042961313211d61a5efcda.nq.gz
    ├── 552708f8f3e5355f0a30b7d3d091246631cb5cad.nq.gz
    ├── 55c89a97fae6122da5a513a54d3a04cf3ba6d277.nq.gz
    ├── 55d4f326a23549e4ac934d1a932dde0ac31ba082.nq.gz
    ├── 55e46e857b9c4912c53611993d0b845a85c9f4d8.nq.gz
    ├── 5602359f7300e19cffa5cd64bc5dffabf0d321ff.nq.gz
    ├── 56406dc92e0a387e7916bede2201917f832d8de2.nq.gz
    ├── 565801cf924e229bea907fb103e1243cea8f3407.nq.gz
    ├── 56a00027e5d4ccc48fc6ab280a71cffe399eeb2e.nq.gz
    ├── 5911c13ca8a997ae12a6d131ac73906c860d5294.nq.gz
    ├── 59a5c4160dd8123d0e18c0f88c574d98cb2f1019.nq.gz
    ├── 5a19e07c0a7c0907df5b0d778453802810988a22.nq.gz
    ├── 5a296f1ed503de935814aaddb051fae068903f92.nq.gz
    ├── 5affad186c92bccc21dbf0235045e658e030f816.nq.gz
    ├── 5b2b93d9d392d40c3710aa344f732c3e2d012cd6.nq.gz
    ├── 5b871b0fda405e8b465aba2733f3596945854c15.nq.gz
    ├── 5c1a954e247c0e4f99f04622c7bdd24cdeb142e3.nq.gz
    ├── 5dda1919a505e2cd7985716967dcff042d91fd29.nq.gz
    └── 5e33119f78e95b7ff75714f917a47e44c4da6688.nq.gz

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

[UKPLab/arxiv2026-ProReviewer](https://github.com/UKPLab/arxiv2026-ProReviewer)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
