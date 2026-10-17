# Repolex Knowledge Graph of microsoft/autogen

RDF knowledge graph data for [microsoft/autogen](https://github.com/microsoft/autogen), parsed by [repolex](https://repolex.ai).

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
rlex download microsoft/autogen
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 004749e6b7102c8fd317b9b1499ce5807223c278
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 004749e6b7102c8fd317b9b1499ce5807223c278
│           └── chunk-001.nq.gz
└── blob
    ├── 003e23c2070d505706e61f2f71756089fab9443a.nq.gz
    ├── 01322e0c5ccc65eeed5002d3fdd45661656cc71e.nq.gz
    ├── 015709d2e599fe26da897e00d4ad586435e805d2.nq.gz
    ├── 0176b3faa3e3bc279ff6506a48a738e77fc586d7.nq.gz
    ├── 01fe65f3056b9ddadba0059806de1c5fac622f02.nq.gz
    ├── 029e19fd5a18696b4b7a103626490266770c6c72.nq.gz
    ├── 033c92162658cbe5a3f3f8388e382d2d16348f99.nq.gz
    ├── 034d2dfb104b5e079c8e3f0e61d33df5c5b65011.nq.gz
    ├── 03894e68699eded3a53fcd796d18ab3200dc8ae4.nq.gz
    ├── 03a68735c082b9834956d497bf829d32e692319e.nq.gz
    ├── 04cd1b2287044366b5f0dd8673d2f24297967707.nq.gz
    ├── 04e94121592922454ab11a936f277555818bb5fb.nq.gz
    ├── 055186a233a6b9796ed555ab489749682e01c887.nq.gz
    ├── 05ee0951a2b44214861028f40fa2fa96a6485d27.nq.gz
    ├── 06b2b6d5f2bc9e86af9a019b86fb5318b063ab49.nq.gz
    ├── 06f11836dedb7e59f353d89322e74845032f95f7.nq.gz
    ├── 06f1c9c741e1bb76a1939db43558ab554f8c5852.nq.gz
    ├── 06f3ab01c4306ae493efcbbe5866a13e3be33894.nq.gz
    ├── 073c9f644d0fa6f265598fc64f156fa2396ed3b5.nq.gz
    ├── 076fc48c562090d64b2f32d0607adbea1e35b158.nq.gz
    ├── 083dbef355237c7a32d446ea1aa36a6fe0fb753c.nq.gz
    ├── 0872d754dc4bf28baf10380670ce21e0d62e434e.nq.gz
    ├── 08a537646f93a6eb036da0b350722e18ed94e59d.nq.gz
    ├── 099ae9a440bf10eb4bcb1838fe24b948ad25d3be.nq.gz
    ├── 09c268d73a98cbda2fd388f4aa352f9089c235a6.nq.gz
    ├── 0a086f5fa1c708ef02e6b4b1f09758caf8c3e850.nq.gz
    ├── 0a4e16ff915f57186185cda9b0646059b4076565.nq.gz
    ├── 0a6cec16890eb6c05c834c94f72f1a44dab0990a.nq.gz
    ├── 0a7092acf9edc9a7253ce6e5dc16ef7ed6276b79.nq.gz
    ├── 0bd075c5f6294e6d0269826987f849c85510eb4c.nq.gz
    ├── 0c208ae9181e5e5717e47ec1bd59368aebc6066e.nq.gz
    ├── 0cd4c7cc8ac5e7907855517131c40e1903acb984.nq.gz
    ├── 0ce79cae33a34d4c5c90d7ead59458092f469a8b.nq.gz
    ├── 0ceb2e68a46a47ab2523874709c24c8207713c18.nq.gz
    ├── 0d697fb0494c680a6e8d5e1e31ca58faba8a0080.nq.gz
    ├── 0e26093d19f58f967ebe4a52252fc98fb75a3d6f.nq.gz
    ├── 0e6a0466e5161dfc372f5487b0b2948a1971a682.nq.gz
    ├── 0e9bffd3c75af136224e1380a3e28112eca27382.nq.gz
    ├── 0ee4c4a2e67257b3259704c985b1283bc5d542b4.nq.gz
    ├── 0f1da65612782959000a8ca2be3a61afb47b3c41.nq.gz
    ├── 10b613553451e256abab10426b055de949424339.nq.gz
    ├── 114919558b2015cfdb8d2149e7b98ff810d2cd28.nq.gz
    ├── 11cd32732f38efe884f5a9a4adf88e882c09b5e2.nq.gz
    ├── 12b09e61cae24572dc84dc059600eb0e3aa8127d.nq.gz
    ├── 13107d39442c4efda99f85cf73cb27cd49a33e53.nq.gz
    ├── 138ca8fb460151a64a6ea4aab5957ed3ef15b665.nq.gz
    ├── 1441ed5dd143a922552d3068e55a2138b09c3cd3.nq.gz
    ├── 1510c41bc13bba9b25784df93be3712743a889fe.nq.gz
    ├── 164e5c1cf81c8b9bd7edd0989bc9029a8b7361e9.nq.gz
    ├── 167baa70e4fdc7732ede2602122972df8c714620.nq.gz
    ├── 1690f40b6e289e008972a9b47f7508017a6fc922.nq.gz
    ├── 16f7a78a7be71c0edeeceead56cbff74e37ce2b5.nq.gz
    ├── 171f513087868f87b1841f82f30132894e4b06a9.nq.gz
    ├── 17446552b13bdc6f1d6805a71b845309fd45a344.nq.gz
    ├── 176789257ba792c7b7b0151d002730dacd0bb7b2.nq.gz
    ├── 1797d42f4c037b0ed6a9afbee4505fafa7488f71.nq.gz
    ├── 189b1a8385958913d5a81a103db83f8862d94f1a.nq.gz
    ├── 1963104774a626228864792606e8baf792a8aaf6.nq.gz
    ├── 1a183e19cba04b0a1e8eaeaf666e9cd64bf7d523.nq.gz
    ├── 1aed539683e27d10ecfd8a17770a25debfd8196e.nq.gz
    ├── 1b159da4e91d2f32bafcc32e28fd464b041a0f6b.nq.gz
    ├── 1b6415977ebfbf7f3b348caca5b548f55c001d25.nq.gz
    ├── 1b8898aba34a968bb393c9e2991318bbf8614d92.nq.gz
    ├── 1bd52b381240313347e5a4c6d62bcad0c483fd7d.nq.gz
    ├── 1bddd184e32ef6c7a904ef951c3dc0a0edfea258.nq.gz
    ├── 1c2b43782888b0b722d902ee28152a8267117b01.nq.gz
    ├── 1c41ecb8b4c55670df045e48dc62047fb137a002.nq.gz
    ├── 1c458ed296a29ab241a770e053e360e409f04155.nq.gz
    ├── 1c4b1564b4c8a2872bbfee938c3eb5d904426c13.nq.gz
    ├── 1c76b01a147d6f920c262a62d64afbd42ae5b176.nq.gz
    ├── 1c9262e4345e58273ab87d44e19d1c8e8e3120ee.nq.gz
    ├── 1cad76f6de23c35e294fe9a2456e46feef837cbc.nq.gz
    ├── 1cde42178febc5d42c061fc7daffef2eb5349234.nq.gz
    ├── 1cfc04e42eebb2af2b84cca3ce99536d04976281.nq.gz
    ├── 1ddffad4aa70d0715b755ebe1b175e11eebf45fa.nq.gz
    ├── 1e6accc3f8fdc560db3f28432d0259749f5b1f6a.nq.gz
    ├── 1f018dabf2c35c28a573b0eac072b27cf5a4de75.nq.gz
    ├── 1f0cc20a6cfe78ab3d8a38a410c98e8cc2065efa.nq.gz
    ├── 1fccd7d0657ba5f1ac3faefd4daa5dbaccb873d8.nq.gz
    ├── 1ff72e618d767757c5d0a6d78341ef03ec1f6ef0.nq.gz
    ├── 20ca951c01b71b615d9a8669931384911e96b156.nq.gz
    ├── 20fd981e716bd3287f8d438bfb36b3b6bb55dae8.nq.gz
    ├── 223b610706099f1902a0c8c9d40902e8971f07b3.nq.gz
    ├── 22b1e8b23d9dc31d21c6f68531515cd70dd4fb43.nq.gz
    ├── 22bdf9d075160b3efdfbe5a88a6b7637f974e595.nq.gz
    ├── 22f0118acb688c4737a4049a7ee0a961079a364e.nq.gz
    ├── 2335ebf092b5c753256cb4f9cbcc6cb8660c8394.nq.gz
    ├── 23c09dbe90838a247506b404f7978ad17901c8b3.nq.gz
    ├── 24d890ec6c632266989c4543ad1c862674f604ed.nq.gz
    ├── 25321cbad65d814cf578628b9f843ec7b959769b.nq.gz
    ├── 2599f4cebeae1664d1cbf90026f4b96aef7e152f.nq.gz
    ├── 2700ece240f5a766dee41fbcacf7ede95ac86c1e.nq.gz
    ├── 27b7b91dbc1d90ff58f47c4398667d6edabe4dd9.nq.gz
    ├── 27e52d184bfcae73b91a6fa59cce73d6c662bef5.nq.gz
    ├── 281a7cc300c59c125b87b44e84d99d8e4dd6545b.nq.gz
    ├── 2870568ed6545ce1dacf632fd3dc94e78d59f490.nq.gz
    ├── 28e5b414ef4d266d8a69aec0ce949cf7431d52d5.nq.gz
    ├── 29705194456aab986e4b5951b9560ce747073e28.nq.gz
    ├── 29b1e162979802f095f6b377e7a5fdd02b7a5463.nq.gz
    ├── 29c60ff13f395d88ce98724566b8bfc179a0d0ee.nq.gz
    ├── 2a906c6b150a45e56ba1fc41a5f0625a0e4ef80c.nq.gz
    ├── 2b7a44251bbe83b35ec5f64887ea8566a8d12a03.nq.gz
    ├── 2b9cd91494f94c833042b2248b8d53e6b607a816.nq.gz
    ├── 2cb345bcbac590f49d8459efbe0e01ae624fa8c3.nq.gz
    ├── 2d81c05cadf77cf7f09dca1bcc0f86a79117855b.nq.gz
    ├── 2dc7d4f0fb7b8a81b1eea811f2455e352dcb9f48.nq.gz
    ├── 2dea134f20432607b1e43aab2300c93ed4c2ead1.nq.gz
    ├── 2e4b9de69ab55343e7399c5e0d79061ad7d337ab.nq.gz
    ├── 2f7f29c0a3450feaca90e007d3b8a1dd7ddbbcd9.nq.gz
    ├── 2fbbd7de715daabe625f19e2f147116651eb02ab.nq.gz
    ├── 3040cc194ae34999dc6b835cd5ecefbbb030c7dd.nq.gz
    ├── 30d54bb574dbcb6b7a8754d2eb423e5ec5be8182.nq.gz
    ├── 314dbe15e7baa9ec9eff1524934c35aed75bc776.nq.gz
    ├── 315ac00554faf55ef98a83536787cfff68b880fb.nq.gz
    ├── 3172b51b7523882b178e645225f371ca420df2bf.nq.gz
    ├── 3175817c0eeefe1cd7114737c57fb2a17780eb20.nq.gz
    ├── 33ad091d26d8a9dc95ebdf616e217d985ec215b8.nq.gz
    ├── 34030a8817fb31d7271a2d0ca57cf51148ce7db6.nq.gz
    ├── 35e6c00c4469e7631d2ea2e3e3e712ef21985635.nq.gz
    ├── 36a0ae24dae31dbe2f978dab6c0ed4d0be286da8.nq.gz
    ├── 373e8ddc1753c8c141766047792ba5800b39e18b.nq.gz
    ├── 377bfbdf62d93dbdc344cd049efcaad1d376e441.nq.gz
    ├── 37cf1b752f35ee80c02097833f4e7cefcd9b4692.nq.gz
    ├── 3878eba033461b6238d5c66fdf2a1a0c0eae2487.nq.gz
    ├── 38b27f248d3238d3669c45ff4fa6c5c30087861a.nq.gz
    ├── 38cf34b5378a11ad055c68dbc33d8fd10e33caa9.nq.gz
    ├── 390adb4ab6fc99984d89d2f258ee5ec8465e8244.nq.gz
    ├── 39270486c7962c817e3189102d675816920825e0.nq.gz
    ├── 39272fbaeb1e0521d97900a01170fec3ba5fd715.nq.gz
    ├── 392bd281f394b3dd3bbe1d7537e47ad78dd7ce20.nq.gz
    ├── 399815c4e354f5b26666a1de9a9505c2672d92df.nq.gz
    ├── 3a8e91f35885021993317ebf752c68e25900a55a.nq.gz
    ├── 3b0135d38eb10d45ef30eea3abe7de5095ef0b7a.nq.gz
    ├── 3b783214177464c33d4fee63c80252f0038e3382.nq.gz
    ├── 3bc830adda98fe62aac95e9a4d1361d784d39e1a.nq.gz
    ├── 3bfeb38e931b444bdf78bc22b3332674195b0eed.nq.gz
    ├── 3cb3efa8145d9d8b629a94034fec9088c7e1e69d.nq.gz
    ├── 3d6374b6ed83ccea5657a2ad6fe1583afd1e38fe.nq.gz
    ├── 3d73e502f61178cd583ff2ca93c8e60554543155.nq.gz
    ├── 3db8bfa55857c48301d0864d1fe3685934342413.nq.gz
    ├── 3dca98f48c6d249623cc0c5d2f0d7462dc03e51e.nq.gz
    ├── 3dcf8ce3b621c3f9f1cbbc350bdfb62b47669894.nq.gz
    ├── 3e32c50a3a0f0bde415d10c67b0f7b31f474d214.nq.gz
    ├── 3ea0cb85df02ea80dee519e9c136f774b093bf09.nq.gz
    ├── 3ec12044f6d88b493ded7159a9639a83d564b55f.nq.gz
    ├── 3f30caacdbde66ea19939b17999af556c4c8168b.nq.gz
    ├── 3f4d76dbc2cd30bbfa20f7b5cfa210c04255542f.nq.gz
    ├── 3f529f0c4474811b413a7a11898c50de666dee73.nq.gz
    ├── 3fbe49c3e0fffba098d48184c6fee21e42b4c63a.nq.gz
    ├── 400b5e1ab0bd5a7219de5486574417dc84f4e01f.nq.gz
    ├── 40301863ed20e43b41a5dff9ec3a94a780cfd30e.nq.gz
    ├── 40653b3ee809aeb4072f9087a637712ed625b56b.nq.gz
    ├── 414bd6d5210c4f2852467679e3a2488e240d400e.nq.gz
    ├── 4290c2dc7c166cdc954b65a34b1c2a10c87f8dcc.nq.gz
    ├── 42b98f81625d437001c3790d08e091d9d953d03e.nq.gz
    ├── 431114faede07591d0aae22871bc93f4d90df456.nq.gz
    ├── 459fc36fbd8c219aedb864dc0209b4662b908f14.nq.gz
    ├── 478ba6f5735f7d19d94d8460da3ad94df65296be.nq.gz
    ├── 47f91a16f498b686058c0fa66c3ecf339b81a94d.nq.gz
    ├── 482f50dca311a8b7e1f6c4f14023e6a896b88b90.nq.gz
    ├── 491eb112b4bb518e450fda75c4959d1203ab37a5.nq.gz
    ├── 493b0370433ae5b3af1b80655978bac24088da13.nq.gz
    ├── 49d225461121ab5c757725f754ff2421f1ec5ac1.nq.gz
    ├── 4a4009992c4f91d2536d7fcbb190bd9345cca1aa.nq.gz
    ├── 4a7a9ea56f85dfc58bfddb3aa3e37bc62c6a9709.nq.gz
    ├── 4b9fdb2500f6796c27ab72c331786fee9e400ea0.nq.gz
    ├── 4baae925de3c3e00b2497291e597a3638ed4c2ee.nq.gz
    ├── 4c341ab22a6a0cb57198f572ee7ad41e84029478.nq.gz
    ├── 4cdff7fba9313d400ee818dba12d249af8a8b640.nq.gz
    ├── 4d46ed5f8175a8ebcb7cb62a2e06faaf2caeb7a1.nq.gz
    ├── 4f67d9727829368ecfb994d3fa4c37a3502de0d3.nq.gz
    ├── 4f75dc43a3f0f2be95837cab238e871b137295ef.nq.gz
    ├── 4fe755350dcb3b8f6f49c73c9413060b061624c7.nq.gz
    ├── 503e2ac2a25eb240f8e72401480e141c62402690.nq.gz
    ├── 50f9f1abb71952dfde57497fa4fd8e3f5e412c6b.nq.gz
    ├── 512fe92f3e3e3d2df4cc48d772159b61d282c286.nq.gz
    ├── 527be9fffe66fa3d36c45c4b1858550f7f0545bf.nq.gz
    ├── 52fe809a20c9b3418fd9c39ab6a90f5d2f99dfcd.nq.gz
    ├── 54224e18cb3b45628dcfaab96a777b9ed9e1ec27.nq.gz
    ├── 54570cf4584c48ced22b47fc44fbb8bb99c5571d.nq.gz
    ├── 54bf61da046f66c84d8d035999fcb91f285a6413.nq.gz
    ├── 55f181360d0f60558977b3bc5d399815adca2547.nq.gz
    ├── 56e7c34d4989ce7fee1203525a1090d42dd32eb7.nq.gz
    ├── 58f3ace6c03d093337c9fa417ccbe8bc267b6c69.nq.gz
    ├── 59d9e11f0e2f2401fb8f97549af84a8e0dcf6b6b.nq.gz
    ├── 5add7d0c7940f057f1f50e83aad102ab90436df3.nq.gz
    ├── 5b3efc93d841fe7d4699d564dec2cd73e87ae8a3.nq.gz
    ├── 5bc8e803844a1bdc9a3e12b7a16f0e0865ed1379.nq.gz
    ├── 5c264887856c72d32e604f044ae68605bf78f79a.nq.gz
    ├── 5d3c2033435f2521be7e4fc4265d5feef35fe629.nq.gz
    ├── 5ddc046920c96fd48ec4139a5c32aae25c7f381c.nq.gz
    ├── 5e3850ffae8bf05f2f4d738dbfb959a9352d88d4.nq.gz
    ├── 5ed2a18293638330343f499a72a433a07873f236.nq.gz
    ├── 5f7ecd947f97859a57e89231fc40398f08697b3c.nq.gz
    ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
    ├── 60a85157182e89b9926b01d7a0e25c6b81582ed7.nq.gz
    ├── 60d527b2fa74478980d5e5724a274124f1baa290.nq.gz
    └── 60f222912387d37be37f457ad486d51060255966.nq.gz

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

[microsoft/autogen](https://github.com/microsoft/autogen)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
