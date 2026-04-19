# Repolex Knowledge Graph of webpack-contrib/mini-css-extract-plugin

RDF knowledge graph data for [webpack-contrib/mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin), parsed by [repolex](https://repolex.ai).

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
lexq download webpack-contrib/mini-css-extract-plugin
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d50f981f3ffee8ffd668ca712a9e4d904ed1c5a9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d50f981f3ffee8ffd668ca712a9e4d904ed1c5a9.nq.gz
│   └── repolex
│       └── d50f981f3ffee8ffd668ca712a9e4d904ed1c5a9
│           └── chunk-001.nq.gz
└── blob
    ├── 006df2e26ba99e65f4d9c0fa004444bfcebd5bec.nq.gz
    ├── 00fb6ed3d5e4085c489a701df2a2bbfc83526eec.nq.gz
    ├── 015a99a7ec11d659f56108779d84a3232cd27ba1.nq.gz
    ├── 018a5e2f194adefb2b8e688fb53decc892a6fff8.nq.gz
    ├── 01e55e2750661f9a0c1dfa2de85332b83a78dde0.nq.gz
    ├── 02961362905f5a86607ae7c458197bf710f494c0.nq.gz
    ├── 03203eac05a78d2f7188f0f56df29ec8a1981a06.nq.gz
    ├── 038004c6256301ee6c97417c3729b767731fd051.nq.gz
    ├── 03a68dc29b26002b9cf5e9a5b241ca5bc64f9d69.nq.gz
    ├── 04a660b0c772702f0057ecbbe273cf3c10bf1768.nq.gz
    ├── 0637e6003f016d9d2818e9dc3b077c18370b60b2.nq.gz
    ├── 06958ee2393b4ce6e295070e0f3dc6f6c513ec94.nq.gz
    ├── 06a88a33572a10fec0c8161c2f691fe1409134aa.nq.gz
    ├── 06b02cfd2da8301f6250887e4792fc76d686e233.nq.gz
    ├── 06e4b18833450bafbd5c55da1f01bfefd175ca45.nq.gz
    ├── 06e9cbbbce96001683fb913a4b4b44f5658d92ef.nq.gz
    ├── 072aeac1592067d75f16053e794d67db40b7aa41.nq.gz
    ├── 082f3979b1999c565acff13163466de8d1eb12d9.nq.gz
    ├── 08bc0aaa4b56e59fa6b4e3ae5b52d33845e18b6b.nq.gz
    ├── 08c770b63c691c1e67097f4cb66c9455c2ecee27.nq.gz
    ├── 08e2283ebd721fc780ee135a0a42956fcc646295.nq.gz
    ├── 08e919698df87d68ea136d3a2bfa2a9b4a2d0ef4.nq.gz
    ├── 0a8dcf637dd370ee412d2fb23abe86fd28b06e56.nq.gz
    ├── 0ab5682fef40728e4d22bb5c49b60e79635216df.nq.gz
    ├── 0b88269805172dc5ba369a3819df77ca033b66e7.nq.gz
    ├── 0bfb08d3bbe69167d7f9f05fa6e58d0fc86205e0.nq.gz
    ├── 0c13bc98845339f1dbe46abb8780e95673f3782f.nq.gz
    ├── 0c2b3fadac023f2b7dc1fc7da9f83e6cdac42598.nq.gz
    ├── 0c56c95b5ebd31c6c9e6946333da8b7aa531c1cb.nq.gz
    ├── 0cbc5c9eb8255d2eb3b02b9dfbb8836a445fe63f.nq.gz
    ├── 0d70c763af52808912e27433d276cf11b7fddbe8.nq.gz
    ├── 0d915613a8cc1eb1302b8e50b1ad6a1fcf18e4be.nq.gz
    ├── 0e0da3fdacae9bc1ca099fd252d4fb0cc66d581e.nq.gz
    ├── 0e6f6fe783a96e3cb56e571f73e446412ac278a3.nq.gz
    ├── 0f3fa1e5d2d00a0a2489c1051253385bd7aee424.nq.gz
    ├── 0fb8a8485ae7a6b04db9ae85f6b789d2af3771ba.nq.gz
    ├── 0fcba139861929e681e767fd107b816788980ce4.nq.gz
    ├── 10190b64f55642a9529660b340dd70502374bd0e.nq.gz
    ├── 103c461ee372676715bde5ba5c35beb0cde2c9ea.nq.gz
    ├── 10fdd583d4be9c630944cb89eff2f70bd02cd019.nq.gz
    ├── 119a9749574627ca0cea4f3336da892e25a95838.nq.gz
    ├── 11bc26095e72a5bc9c6d4e994769bc5e8b56bc45.nq.gz
    ├── 11f889619a1c0cc1b6647aa52ec898f3ff755d27.nq.gz
    ├── 1227633cfe4ca2d29149a4a4a6c82714885a0d86.nq.gz
    ├── 1310d8833b532418f963ca46817c7e0b86e5d01b.nq.gz
    ├── 1323e35dedae0490c8189b76fd40ae344a1fc03b.nq.gz
    ├── 139597f9cb07c5d48bed18984ec4747f4b4f3438.nq.gz
    ├── 14073c2dccbdcd2bdefc4abf741948f99f94a668.nq.gz
    ├── 140d28ec70a79a511f1d1a35650f6f7bbaeb1b17.nq.gz
    ├── 161da41569f15e67e17cb3203efbefc3a2e80952.nq.gz
    ├── 16322ad9d54b2098fa236a67a6de0c45bdd3506a.nq.gz
    ├── 16502c4537bf9f39d0db3b5870430b16ba54cd9a.nq.gz
    ├── 16518354cb0c521bb9fb077f45d6732a525bfa00.nq.gz
    ├── 1652c1f66cb5d4526e8d5e9888cf90ffaa0735ec.nq.gz
    ├── 1682f548ffa200ec010bbe0bf858fd392808761e.nq.gz
    ├── 171269b8e9077ac305a561d0e64556a8748bc5f2.nq.gz
    ├── 17727ef95fd79a073aa96d492bb1c5fc37429c52.nq.gz
    ├── 17eb927b09b6c4c853b2c400b16279f596563a1b.nq.gz
    ├── 18c06fae0ef0b5e6b866a0f1157f90d3ae84da52.nq.gz
    ├── 18dae071a9ee6babc928baf2ff55770d13ad7de3.nq.gz
    ├── 19f9965277ac8bb61e21b8cbe1f806289e4c397a.nq.gz
    ├── 1a4074dd230e8a94469293e00c539741eb8fe1fa.nq.gz
    ├── 1b9d3ae61a677c3c1b6f308b8ab342ca2b3c7d08.nq.gz
    ├── 1bebc0ca7a6d3bc6b07d085a6d920653c8d76d08.nq.gz
    ├── 1c52ccbb6603f7514e73bf8664ab20da61738fb4.nq.gz
    ├── 1c8966823e246fff05290b8ae0646b736eb5ac9a.nq.gz
    ├── 1cf3facd4bf3ea2131ed0a086967634af9295769.nq.gz
    ├── 1cf799c71f5b88da294910a2867f72c83cc613d7.nq.gz
    ├── 1d3869c4b89366fd913172a304e2784528b912f4.nq.gz
    ├── 1d76b708f6a8156fb4a115090b2df0e656d086cf.nq.gz
    ├── 1d835e13228b2fa64efaa696d9ff995b1d88736e.nq.gz
    ├── 1dc01d87b49506ddaa8a3cce5648cca5d75cb370.nq.gz
    ├── 1e09c7ac7d563b1794dd129336361a0749054fdf.nq.gz
    ├── 1e8530eba82f26b296669334ca207d858c6b494a.nq.gz
    ├── 20ddebe29128ca56b35deddfddfc32b9212efc43.nq.gz
    ├── 21b1b65d871a58241d703fd813f84c025c41c0a9.nq.gz
    ├── 22b75b91d795f16d88a8b9cc6abbfc6a646c6953.nq.gz
    ├── 22d01e87ed3b24feeb07b2b1f2909d4094f1d721.nq.gz
    ├── 232dd5bda63a4f4626b0c8695b6ba90e76789d08.nq.gz
    ├── 235bfe1ddce43c7ff754fe88cd86e4b9671e75fe.nq.gz
    ├── 23768a7a638529d9e7b290c34a0a3765388b1875.nq.gz
    ├── 23a87d579eae83c7273dee096470034ff1b72aba.nq.gz
    ├── 23f2a9f74fb361177c835b88f0991dcd91720c37.nq.gz
    ├── 24e5b2ceb428b47a217d460c3c9ee3fcfb7a5117.nq.gz
    ├── 253ded4bcebafe4b489ce99d9ea4ae83f779c968.nq.gz
    ├── 254b176ddab86793d2a199e9efeb303b7556eb04.nq.gz
    ├── 254f81b4a2e5a37b07dc13fc869298d4c98cc443.nq.gz
    ├── 25e350d149ed7cc91b24206f68f44f297e55e5b1.nq.gz
    ├── 2742013da744d41d2253987b37f084fecb0b780c.nq.gz
    ├── 28b0c8a2afc9486ea22cf6318503702864533b61.nq.gz
    ├── 292bfd37320d14e7313504991502d206ff9a687f.nq.gz
    ├── 295b4a8f01079d80fb499713c52cfa45e20745df.nq.gz
    ├── 2abe50c6c301a53bacff60abbbf0c4aec3ef6aaa.nq.gz
    ├── 2b7fc03012a1d0375716b7baa05718178b56cbd1.nq.gz
    ├── 2cbb9676458d43082f9a24180f2d23e74f93b3f6.nq.gz
    ├── 2e113d33834419b32844dd2c9cd3e923db4102a3.nq.gz
    ├── 2f78afe7ff08a0d23b46d6d2a1ecb9205d09bdda.nq.gz
    ├── 2f87399852a0dd0ab98ae4beb86afec04dd40f66.nq.gz
    ├── 2fa9e2cb967e7813bbe6a6063a6d12bc059461db.nq.gz
    ├── 30c5a4fbe6bccb9ee1312ca90d7b306aa47e0718.nq.gz
    ├── 312d2fe56b2dd81e3e8fd8ea641f2861008d6f0a.nq.gz
    ├── 3131ef8d3fd4d95b6e6228bb15c344fe6d051d89.nq.gz
    ├── 32ae31530fa6318d2a90c05aaffe1703017139dc.nq.gz
    ├── 332c82b03585ae4cd8b1dd84ac1608f156060d58.nq.gz
    ├── 34d6b334612435177fafd229f5b56daa02f21037.nq.gz
    ├── 356917034412202ff01933ec90c5b4eef35fcb0e.nq.gz
    ├── 356d5138ebaacc2dbb1670334fd380d9cbf37f60.nq.gz
    ├── 357f8bcb23da94b5aa796887a8fb59a393c74d80.nq.gz
    ├── 35cc00ff3033361b1e5d8f2df3ede373ddb9031c.nq.gz
    ├── 36f1d36908c44d51ac8f61f403c570874e9382c4.nq.gz
    ├── 37a9c167ea33b792c864b708ae104aaf05ed64b0.nq.gz
    ├── 38240d394c143b346ab6cb05f66df004b3bed1aa.nq.gz
    ├── 387b19f43d2b00d71a93df175c51ad3546522efd.nq.gz
    ├── 38e6c26e0ec6a4eac0746c299f05b4059c1b3a20.nq.gz
    ├── 394fd463508e7f47702256648c2c4a5636c72683.nq.gz
    ├── 3a76068821673f779d83c2a8b3a392a056d1f521.nq.gz
    ├── 3acedadce0b47769b8a4762a9de8fed76f7f2465.nq.gz
    ├── 3b4bcabe8b812444cbb55c654ff8694f8e861947.nq.gz
    ├── 3b529e8a100513cdf8408b2c3024045b6bff2bc2.nq.gz
    ├── 3bbe1838d0d938aa429e7d1ef770cbe9d6ab53e5.nq.gz
    ├── 3bc21aa14020809f69dd1353bcbc7db7e6e454cb.nq.gz
    ├── 3bc4fc4e5a616cc8b9a637a88df56ebe3aada9f0.nq.gz
    ├── 3bcd55cf15d59ca1117933bab923e7aad0d37729.nq.gz
    ├── 3c05a023608a8cf93af873388f3872a43da591d5.nq.gz
    ├── 3ca33756354480bffcbd628ce3a76c266ae47c8e.nq.gz
    ├── 3d87a6ed0d86d766a68e46c2876e8a1ab6d4dcbb.nq.gz
    ├── 3dd844df60719aa7f8accd4587710680a2364c48.nq.gz
    ├── 3e45a4cacf88166db4e9c101510d28e11e378770.nq.gz
    ├── 3e4c4d81a31e66a66e4492f32853363107b24515.nq.gz
    ├── 3e7d1c112d29869fb921f38f5c957ccd05ce3b54.nq.gz
    ├── 3edbc7a6894ad5113f46c74bd1cc91d01b48be40.nq.gz
    ├── 3fb0e3387dd3870c0d880cd51d35c09ae32f02f5.nq.gz
    ├── 3fea942b504df14e503976728f11accccb948b14.nq.gz
    ├── 404fdef2230e722e4c2d564f2c6f4e621e52f9f6.nq.gz
    ├── 4071103dc9212c044a141a39d136c9088879c5cc.nq.gz
    ├── 410b31d8da263d6e4b847d26b6e9963522ecee63.nq.gz
    ├── 414d12e5f8d448d6e4b59c0ff9f25a2321450a7d.nq.gz
    ├── 41ae9f3747c758c25638ce8dd8f10a751ef6b358.nq.gz
    ├── 42710aa3b011ec57c822d12ec183303bda65fc0c.nq.gz
    ├── 42721dd6fe65d6398366a30f99eefa39ef2cfa9c.nq.gz
    ├── 43479c3dd2c48c0ded5b5bd7d805521c3a7036f0.nq.gz
    ├── 434b8007e5daf3cd941b31f08e05186f6abe46f9.nq.gz
    ├── 479edbac4b7fde94e807cdef33dfba51b2c3bc7a.nq.gz
    ├── 49156322e93982fe1add5b270f8637fd3eb9466a.nq.gz
    ├── 4997095818f4487cad45a1191d9496643e0ca056.nq.gz
    ├── 49a5626c8561e29d2cfd1f4bcd3ed1bc03ad4800.nq.gz
    ├── 49f0c3c656c0e9b563bd85f38870358d2d512f0b.nq.gz
    ├── 49fa513e14544a8751db4ef689f6ab5a4cfd2b69.nq.gz
    ├── 4b76a9cabdc03bc7a2d17b6167056c0216fb0841.nq.gz
    ├── 4b9c949cde9e2e929ea121efed1fba3ef07f3436.nq.gz
    ├── 4ba3041c637e60bee3838151864313b49d115b0b.nq.gz
    ├── 4cc245e5622032fdd61ff27b4e3c7c8be7415842.nq.gz
    ├── 4ce2857d6f006cf152ca09805443c465a8dbfb32.nq.gz
    ├── 4d3a45ae4fff064a12caf0eefdb189556cf29ded.nq.gz
    ├── 4dd03532c7adfb48bfaa03e6375c3b1296d63621.nq.gz
    ├── 4ddb75eec59210180222083770d8334cc394fbb3.nq.gz
    ├── 4e07e687cd68c186211c014a46707ca140681b37.nq.gz
    ├── 4eecda407ae980242b2a2a616582781623bebcf7.nq.gz
    ├── 4f22121496d7f5f56907a334d7b3aa62263e2969.nq.gz
    ├── 4fcc117d4533e3eea1b802421f327c51d1b83d6d.nq.gz
    ├── 4fe51c72d641f29700c88b1dd15b641cac1b5ec5.nq.gz
    ├── 5039f88febd7898aaeb2eb9a5bc8005c15b5cb5b.nq.gz
    ├── 505dc441b731bef4d2ff5f52483496cf648aa34f.nq.gz
    ├── 506b2a5712f40dcc211d6576706de2803086ffc6.nq.gz
    ├── 507bea5df35c4bcd19d946647224739ecfd0d88f.nq.gz
    ├── 51aa94f5dcfa10bc32335e549d21ee05bf4ed898.nq.gz
    ├── 51e707b6719f9d5f298b67100514daee4b50026c.nq.gz
    ├── 527afee7142b0826b08b62d8ff05978d4c6eb137.nq.gz
    ├── 52a8abd6879f538bd6ae0963a1091041de84e95d.nq.gz
    ├── 52bd1ff4b63d7a0edc1915bdb6416bda4d90ae78.nq.gz
    ├── 52c2b3e40436b09c6492b2f1ce7753dfa61667b7.nq.gz
    ├── 52c33c89c343abc24d402e3725a106c33151c5f6.nq.gz
    ├── 52c5845a7c3803f313d8905ee2f83ac20a5bc9b3.nq.gz
    ├── 5337afb9acb6b87115524abd5653fb88ea07bc89.nq.gz
    ├── 53eaaab9f0a2a0cf90bd4ff8aa3f3000f8989d23.nq.gz
    ├── 54227c4953be04cdc0a2a6192d8e86dced73148d.nq.gz
    ├── 5451a331f9cea48685352ed1a64b5d211c631ccd.nq.gz
    ├── 545562eacc28ae6e16d636b8016bc636c6f62a78.nq.gz
    ├── 54a7697f7cf2766d9a0eb3a81c6d211a0724f13a.nq.gz
    ├── 54c5fddca51516878d5638e89fe80403e6692afc.nq.gz
    ├── 55223ca50b0cf249c1d803010dd8fd158ba4b943.nq.gz
    ├── 56d4d16df8b23de86917d29bf9f242890da49d88.nq.gz
    ├── 56ffd112dda59b936a4a022069d0f4a2b706f9e7.nq.gz
    ├── 5763ca17679428c3662704513faefdb784d380ae.nq.gz
    ├── 5780fe7ea3c07b0c091f7907b0e0591d44507224.nq.gz
    ├── 585cdf7cb46e5a8593eccb86bf7e1b1140eac2b8.nq.gz
    ├── 58c979cda9b094d95a1f4c1d85a05788b1e14639.nq.gz
    ├── 58f1494343475d7098b7803af98af65a1a7cb98c.nq.gz
    ├── 59116df9c8f69d4d29dd3fd18e4c4e4c5bc69386.nq.gz
    ├── 59681eefad4a331db6679db084357257f04e14ae.nq.gz
    ├── 59c99aa9bab62a51ed16eb3446d5cbd581435e5c.nq.gz
    ├── 5a71f1b51e6968eaaf398949e7cb657c426005e9.nq.gz
    ├── 5b1b9ce488c634bc791ede2db5a9df37a51ac039.nq.gz
    ├── 5b3b22a45f06a0df95748bbc1194bb4b86bfcf46.nq.gz
    ├── 5c3eacc9fcac618ee309506ae340c043686887e3.nq.gz
    ├── 5c86ca87a83e60414047933d8079dc9324b5e502.nq.gz
    └── 5cf619e1aadc144b8af5ce69c028b6a14664f40f.nq.gz

8 directories, 200 files
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

[webpack-contrib/mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
