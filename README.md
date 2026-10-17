# Repolex Knowledge Graph of Nixtla/statsforecast

RDF knowledge graph data for [Nixtla/statsforecast](https://github.com/Nixtla/statsforecast), parsed by [repolex](https://repolex.ai).

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
rlex download Nixtla/statsforecast
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 61bd26fa11c020ba0b31dcdfef77e99c9d52bb7d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 61bd26fa11c020ba0b31dcdfef77e99c9d52bb7d
│           └── chunk-001.nq.gz
└── blob
    ├── 005d29ab38b41758e8f9f3595c2c15eae341b4a7.nq.gz
    ├── 01a0df5ddfb65739cf61dd9c33f5459b479bff8a.nq.gz
    ├── 02613c7c3993988b6e07cd123f87bd59fb27efb8.nq.gz
    ├── 02f54d609bcc7500590a4a9fe4d38969841c2f62.nq.gz
    ├── 03a5bb410564b042b92b36a122f14d94f5694a72.nq.gz
    ├── 047a4cff5353e74b0c2a29e0185bec0a0c2785f5.nq.gz
    ├── 0509734dc0e378e04d6a87fc07914c8349dd3987.nq.gz
    ├── 05a083c2553a5517e414cf8886374f2020c7408e.nq.gz
    ├── 06473517bf788139d5e9bc9bec2bae3dad21ed94.nq.gz
    ├── 071e9eb3ff7c3937836f616ff7ddbdb49acdbb18.nq.gz
    ├── 07549fb3895d6675d634072f5680ea70e0e06561.nq.gz
    ├── 08378d817377078691be3a4c6dbf2eb8418813d6.nq.gz
    ├── 091faa132afcbe4ec38d5ba6d5096a7bbaf80ea4.nq.gz
    ├── 0969b3673b1c0ee93ddbbb61d196db6a61befd6e.nq.gz
    ├── 09e34f11cc2aa262baebb888a87a865498abf2ad.nq.gz
    ├── 0a802aefde1892bcd926a60584ec851fe7259227.nq.gz
    ├── 0e4858c2d6392e937b1d3a86e0ac57b64c6945a6.nq.gz
    ├── 0ee7017ad9872a2d5033203823fff8cbfe7d84c2.nq.gz
    ├── 1015b687b0515fcdefc78951ea779eb0392d6b9a.nq.gz
    ├── 10533ef5378c8d669ada57bd409a5c6b16bbe0d9.nq.gz
    ├── 1135e546f5f5b198dafef5311f093cf957eef063.nq.gz
    ├── 117aeec0a473cdd88fb8a300c6da805993264622.nq.gz
    ├── 11c79e4a6f556a689215c5018b6c94b6718a09d9.nq.gz
    ├── 132c1ae5b9c5493215415dd0728fd76d07e317fc.nq.gz
    ├── 132fc7f2774211c2b8ee6d2883d6969ba16fe463.nq.gz
    ├── 14062e73b7df396930b06fefa80c0ba963f38e70.nq.gz
    ├── 147cd28321e348e0157da8e16127bb51da3f42c8.nq.gz
    ├── 14816ccb8d173eeecc920affd85f5ec3a097aa75.nq.gz
    ├── 15749e07a821ebdbf49b269b08b09d975d132186.nq.gz
    ├── 168563632e666170f3d8249cc7003389bb51ae8c.nq.gz
    ├── 169bb04c79947a0ea58f7adaed0c5dd12408a448.nq.gz
    ├── 1710e91681b4c382396ac8de625f8e5bb2b9f5ed.nq.gz
    ├── 1783d642c1b0375f8594036625b998735e52a980.nq.gz
    ├── 19daa596705f801624d2062ae59744bc3148a883.nq.gz
    ├── 19eed8b79d071f74ae32e63ab8ce9ab37554f8be.nq.gz
    ├── 1acc642b3ee18592cd1642da3053aa60eecd139e.nq.gz
    ├── 1acf1981a15e9ec3be531d0b02047a19a6eb33a8.nq.gz
    ├── 1b2be91f93ee1be8c9aa8a218988ecf51c899ade.nq.gz
    ├── 1b2c854c24ddc43ef5ee30ac48c4cfac900ed34d.nq.gz
    ├── 1bd3529d61ff5e5b63083eddfc5d93e2b4cef697.nq.gz
    ├── 1ce0df3468474902493a439a46ca373b0aec3519.nq.gz
    ├── 1d25e449c0d0b2a2e631481f21c545f9bfbff198.nq.gz
    ├── 20e1ad23ddd2a11300f30da7bacc09f6776b18cc.nq.gz
    ├── 2130c5828d5b060066ff663aaa7f3514c7ce7475.nq.gz
    ├── 22536e059b491a9cd43843733ea4aded4630506c.nq.gz
    ├── 22d56fd96c5b9695b3fa8a0a6f08e6202e0def5b.nq.gz
    ├── 22f9b14b6e648610967097772e3c33386d6ef9f9.nq.gz
    ├── 2320b365887b917fe2a8ead9d96e1c6cdd1b86c0.nq.gz
    ├── 238bbde3ce7a4fdebbccccca3364061a81c4388c.nq.gz
    ├── 23d4f1651d4d14948bdb7b745976fecfc1d04456.nq.gz
    ├── 247195ff07122f3707ebc42ada3d69caf9ea2209.nq.gz
    ├── 2472d90edc09519617e21c310d2d9d908c4e9c4a.nq.gz
    ├── 2489ef218060f13162e0fbc2a8d3616f5cab111f.nq.gz
    ├── 28aded40238e9644dea5846586b71e287cb2b6ea.nq.gz
    ├── 297dcfb78274cc48df60cda25d8a41404e613048.nq.gz
    ├── 2a0588787700c7be278f4a6d59f296e26e5045e2.nq.gz
    ├── 2a4c1db884863fbc4aa277c20dc3f372f256e790.nq.gz
    ├── 2a5387fa565b5c438117654bf0a81acb7ca7685f.nq.gz
    ├── 2a9014065109d5de72d5e4047e1e1bbd90e6a3b6.nq.gz
    ├── 2b3e7ed6d455ca9379164f34ce7f5bdecf2eb7cd.nq.gz
    ├── 2c039b8c04bdb2b560bd08a6bb003df807a4455f.nq.gz
    ├── 2d50a4742d310a1aec174395f5a959133c180bbd.nq.gz
    ├── 2e58d4f744d14b3cca89d9496c384f47826ce235.nq.gz
    ├── 302a217c53903ed04a0b1df126d28665e1322421.nq.gz
    ├── 31518b59b1bac013ef1a26d0a094ee907680f5cb.nq.gz
    ├── 329df4b466d124777343ec28a77de1a425e48711.nq.gz
    ├── 32d76ec703d382d6f37441a70a20db89fde441f2.nq.gz
    ├── 3386f850fd37282355fece2f6cd66009829a2f77.nq.gz
    ├── 354d51139388aa73d83b29debe4115a50bd8dc0f.nq.gz
    ├── 396763121083b97dc7343b3ee3d61efb23ddee41.nq.gz
    ├── 3a52dd9e4b8c18abd83461d53316b0d1c7a26185.nq.gz
    ├── 3afb872bce65f85a6c1bd3a734eb0eb708fd7bcc.nq.gz
    ├── 3f62bff3190f5798fab1577462cf2c56babfd5ad.nq.gz
    ├── 408d156fcf631c7fa00436ab5a0e15aed861259c.nq.gz
    ├── 4142a0bbde38d8801c80e73a8fa18df0baffb465.nq.gz
    ├── 41a7db314a604239a7e592ae802181212d34e5ec.nq.gz
    ├── 45237f7a478545535b78dae9147a3c886d590a54.nq.gz
    ├── 45f3a8b301abddeaff617a4c9c9770c197714ae2.nq.gz
    ├── 45f4d97972330e3e76b8be2c448d68398e56c39e.nq.gz
    ├── 46ec4136cb0c6afb71f65b723b30d42b51b60d5e.nq.gz
    ├── 47f72c0b591a0a5d9da20cabd7ecf8028a436143.nq.gz
    ├── 482494ea3f8e91fe91c50f19f2f60749a9790147.nq.gz
    ├── 4a455b68ac12dea374708fb6d7a7b2cce9a3c1ac.nq.gz
    ├── 4a9684db576e0e8f920ea02b6dcd45e6603a9776.nq.gz
    ├── 4b0c1c936f26a9c4f98186eb7bd30ad45521c10c.nq.gz
    ├── 4c2c3dd234e975b8481dda534df65d0ad997abf5.nq.gz
    ├── 4da429bd98efc7c579bb44faf49242077681effe.nq.gz
    ├── 4e496c0785c407831567b9be6680d273af3fb9cb.nq.gz
    ├── 4ea1c0d340d7aecf8fe0540a6c58df7b3bb93a4e.nq.gz
    ├── 4eb2f4d68902257214ea0bf6f862a056b11aee51.nq.gz
    ├── 4f11be477be38fa0d239bb958bb4b450c857d402.nq.gz
    ├── 4f3e0169bd8d6d53ae9c8afbdecfa45bffb48ff1.nq.gz
    ├── 4f434a84cc9ca737fd1118ca40e52ea1255e98f7.nq.gz
    ├── 500bea58df59bd7573e00f2fe601c1e2ae5e2bf6.nq.gz
    ├── 506af16f1363fea79295effc9e9cd06303d2cfa8.nq.gz
    ├── 5108707e080e5e209df8b258fb56d902ce28f241.nq.gz
    ├── 513254413601598693495c3f513d12930c53a4c7.nq.gz
    ├── 515e62278422808211e5b9b8bcce2b231cf4183f.nq.gz
    ├── 5174c77bba720204857e16ba09e89b9226e1a19b.nq.gz
    ├── 521301ccadd48617fa56b0085df92403b99e858a.nq.gz
    ├── 5401956a8be922379ce8d58e52b6d22e19bfcd48.nq.gz
    ├── 5467d735a4895a2891104e91a301747b124af5a0.nq.gz
    ├── 546b8633657f5c63421e52796ce9f85d09a9b659.nq.gz
    ├── 586b58d6583eddb2c8d59559c46ed0a3435e688b.nq.gz
    ├── 589b1b94a865db379b1f79085164acfb556ca070.nq.gz
    ├── 596c389e83b59caea5b3d730b37abc4df2540d35.nq.gz
    ├── 59d177e7bc0178d05f8bd4c3ea482e51396a3ced.nq.gz
    ├── 59ed1acfdb9560c0802614924ff42ac874874f66.nq.gz
    ├── 5a8b3ae2ede3f417c6719221de476be49534b06e.nq.gz
    ├── 5a9eac19a37fe94678becbba8cac3eeeae7260d2.nq.gz
    ├── 5bd5b0969a1f9acc4d2a93232e99fab9413899ae.nq.gz
    ├── 5cd1b317870e6389615b6be70887c489e8433ead.nq.gz
    ├── 5d3a5d2c884e3b3700042124c91a0d913f7887cd.nq.gz
    ├── 5e8aa44ff8c80020f2f37151ab1919c7751d8866.nq.gz
    ├── 5f98be8b2c3b2b91336292f29a7e59ca0f33ddaf.nq.gz
    ├── 5fc98eabd8c1b07f3066acb28dcbbe2757a33fcc.nq.gz
    ├── 604f9d78aa6851d636ae5baee3db4ac13fd5e460.nq.gz
    ├── 61373b0074caf68f1f08e16f9cca20145a732e96.nq.gz
    ├── 6255258b16b785657f6b8f59c7a2f72eba271c84.nq.gz
    ├── 62bb929e681f884861b51d081f372c676cb05db2.nq.gz
    ├── 62eb3608590abcf836ee0d1c9a99cc51e98635b0.nq.gz
    ├── 64589941de7124f5209ec8e4d49735e830e7576c.nq.gz
    ├── 64a35a8a9b5734830279f5af58023b8566ba8cdb.nq.gz
    ├── 64ae0be8caac979edfb2228a2f04dbc29cca9d03.nq.gz
    ├── 65c1e2672fbc80e7b7878eac670dad552f4a7da1.nq.gz
    ├── 65e46ac9af16a59f220693e5415fd7bae8e4adab.nq.gz
    ├── 663315df9ad094446ef2dbbe3f3f141e838cdd60.nq.gz
    ├── 68ea6fbed12ae36d38b32df11d3fad0bc990d8c7.nq.gz
    ├── 6bb3c4bb88232d035c6d5816f46c41b75cd3c0bb.nq.gz
    ├── 6d3ba8ff04e145f452e8c405b6d0c4000d06e61b.nq.gz
    ├── 6dca8a4ffa01bf72ac45a88ba51cc9dd4a8ff7d4.nq.gz
    ├── 6ece9e482535637c2f5e43e649dcc5cd0ebcffe6.nq.gz
    ├── 6f60d244f83fc5541b666eb7c31765e3b0851c72.nq.gz
    ├── 70261d9c59b6d7ceb7404394a8126d381a954305.nq.gz
    ├── 70aca577352eb978dea52b249ba68b3b4b0478de.nq.gz
    ├── 70b533970092bb4ba5002627874f5c2602eda898.nq.gz
    ├── 71415a60d079eaedc27e13019a4b4ba87a6a0bef.nq.gz
    ├── 714f03669e52ddbf42d80d98537502bcdf04a662.nq.gz
    ├── 72bf596ca3414624bc7e676510769607d4b75625.nq.gz
    ├── 736b2263d299ffbfb8b101eeb55ae0b20a9693e0.nq.gz
    ├── 73c17b7a218238398f95ee93b62ff1c75c381e4d.nq.gz
    ├── 73ce2388cc364fc5d9c923afc32beba220f5abeb.nq.gz
    ├── 73eb130eafd8932578d7e83aeee9fe9ddebf2263.nq.gz
    ├── 7404181df2222101a3971d74c105ae4ac0e923a7.nq.gz
    ├── 75878a6ccd7f63a829fe7379e6047ac123f9271b.nq.gz
    ├── 789e4dafc54834d8950c1aae8a8d35443574d7f7.nq.gz
    ├── 78e91ba9e3a4f7f506596db54b96853a8b504575.nq.gz
    ├── 7a72e3716dbaa1dc9c4e4b45090c8973361f5585.nq.gz
    ├── 7acae753bd50264d593bcc69ab9c18d4c452b7b3.nq.gz
    ├── 7ada6bd54c6450eff12eca3871a82cc4a5c53329.nq.gz
    ├── 7c57b45ec1c0ef7d18eca5a74025df8469f9072b.nq.gz
    ├── 7c5c2c3f1fe703649bfb48f9c623679fdf133b8f.nq.gz
    ├── 7c7684de22282513d154d0f8fb2a7c09e8bafa69.nq.gz
    ├── 7d1c76e7b2c8f8108210b4209d7ba06ae5b76fd7.nq.gz
    ├── 7f4d4c1498d7939263f711e8b3b03096d4a99e36.nq.gz
    ├── 7fa39cb6b2f4f5b2bc525cc3b14788fd2fce6f4b.nq.gz
    ├── 7faf3bb188d64c284a1747020e00aae85eaba2fb.nq.gz
    ├── 8085fe614d6607d37439a56a4309b802c408b418.nq.gz
    ├── 808bfe2f0b4f032ac51b606bb353d0abb9e9ff6f.nq.gz
    ├── 822bee5ea296e38019d718565993aaa5c3dc1c69.nq.gz
    ├── 843dfac7b7f01bcb1a76d584a622ebccaa40af28.nq.gz
    ├── 84b798f9ba9ceba733bb752b7434becfa1ada4c8.nq.gz
    ├── 855e1cf80342159727a97940f5fbcb04223b67ab.nq.gz
    ├── 85a2f300246e4200a1d51feffbd9d2897a142e5f.nq.gz
    ├── 8603ad40ec1bb38aee4e2e5aec4ebcc02859bd9f.nq.gz
    ├── 87ffc6236d6cf2f81ef76cd9bf20c6ef71c78cd0.nq.gz
    ├── 896059bde27893599f96e0e5814490bcf74b40ad.nq.gz
    ├── 89dcf4e5ccd613eb56d1965e7327b8c2fa69501d.nq.gz
    ├── 8a2f29e7accf064a9bd1a73866c83af30f6bd5f2.nq.gz
    ├── 8b11445bd84ef0badc3ca6012e401ed0f9e40a10.nq.gz
    ├── 8bbc33c6f38a73247cc292dbea9571daf1a3585e.nq.gz
    ├── 8c58bfee527a6c7f68a76ecb26f83671cfb4c59b.nq.gz
    ├── 8d14adce682b6809e54a2c5e902802bb6d79aa65.nq.gz
    ├── 9213f8b1ce6b2d9ba57627f98ea3316a3458548c.nq.gz
    ├── 9351cf570eac2474d304ceee6109bbb5c102338b.nq.gz
    ├── 952d9f8d49137829768283942cb3a7d9c154488b.nq.gz
    ├── 9548047d69edf1942269298af1fe46ff8457153c.nq.gz
    ├── 9650880fb1e7bc91d849e878bc5fa53275ff7f45.nq.gz
    ├── 976ba0294638950e865be3934cbeee3b6305ffd6.nq.gz
    ├── 976be499087cfc984279049a67d60a509ffd32a5.nq.gz
    ├── 996c213a962b84be612b058208aa56a6c1832cf0.nq.gz
    ├── 9a3c6de094fdb9f78c70c3241b6bdfa38180f13e.nq.gz
    ├── 9bbe2df0373b35d0eab4e6f4cfb634d6accae151.nq.gz
    ├── 9c06d00ba764a4e9715dadde1cc288b25f92ad39.nq.gz
    ├── 9cdda4ba73fb43820e7afebe77ed3dbbc04be288.nq.gz
    ├── 9cfa9ce4973608b4f660084a9c8f43988eb7234a.nq.gz
    ├── 9db1a67b5466fa6e88d738a0e9067ebf658a128d.nq.gz
    ├── 9f4a428518f41c82792e39fc3172ac8a020a1417.nq.gz
    ├── 9f6f7d3dae5a286c23f93dc74f91e192d08f50a7.nq.gz
    ├── 9f701c8969610f11abf1f2a2f08cf9925c689547.nq.gz
    ├── 9fb85089d6ed81fee60833b5637849f4345291ce.nq.gz
    ├── 9fd087eae8db4b4ca832aa267d0b5d544fb2bdc1.nq.gz
    ├── a03219ded7239df80f425efd52543c1f11d835fc.nq.gz
    ├── a1d9db2d58d75608cff3c8c1c0d768dcb94431f8.nq.gz
    ├── a583111dc1403f729a63cd2fb104ab2b990608af.nq.gz
    ├── a6113693c4062ca6b1cd1051828726596e01ac7c.nq.gz
    ├── a71b22159c71ed2ea9da05a6bdea63cc5ffda092.nq.gz
    └── a740c3c87051c6017a317165d0e7aa017cfd24ca.nq.gz

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

[Nixtla/statsforecast](https://github.com/Nixtla/statsforecast)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
