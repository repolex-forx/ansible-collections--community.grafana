# Repolex Knowledge Graph of ansible-collections/community.grafana

RDF knowledge graph data for [ansible-collections/community.grafana](https://github.com/ansible-collections/community.grafana), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.grafana
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d7ae4090f2da6b13d5462628b780376eb81ddffd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d7ae4090f2da6b13d5462628b780376eb81ddffd
│           └── chunk-001.nq.gz
└── blob
    ├── 03be73153e4b8675814e4c3ac08179a64a3abde7.nq.gz
    ├── 043a3d9294dcc384284e038c5b8de305d0992478.nq.gz
    ├── 07da942ca102949a41944c19ba6d1c4a61d8f95a.nq.gz
    ├── 085ae0cb8cb3f3f50bdf28eceecbb42e365ebbde.nq.gz
    ├── 087af0e7c805193c23d94c80bb0eed4a514de2bd.nq.gz
    ├── 08e12f95346685722779473f3d7c7a09830c7ff1.nq.gz
    ├── 0c8e265df3605e18d235492c06b6be909059ac8e.nq.gz
    ├── 11171f38fe7395214fca87409a61b090ec24b343.nq.gz
    ├── 11c2114176a842139846b0ea325a32bb7645b5b2.nq.gz
    ├── 135c73e39e666f8a6b98dba30108a51f366883e6.nq.gz
    ├── 140237ada5a5967032bd7c39560e43328a93329c.nq.gz
    ├── 14915de63e8f782bdc1b6ca5a3079bd9273481cf.nq.gz
    ├── 168db5b18da4479239628a5cbc726ccc7b1ee02a.nq.gz
    ├── 16ffab436d1de1195c529c45aa583a93d68362b7.nq.gz
    ├── 1705bb3eb7740246eaab02b9e6f39c348e94d14d.nq.gz
    ├── 182822d9b8aa6aa1bfc6e7e7a18619abeb59a084.nq.gz
    ├── 18d34a0aa1a2164d7d83a67b4ee5ca5cd3e8f460.nq.gz
    ├── 1be7d21fd0622534ab2107a8ff5a0a6dcec4bf2b.nq.gz
    ├── 1d08ff03825f9600d47e69024df146a438cf4c6c.nq.gz
    ├── 1d6266b4998747c205a08eedda54db28f7e495ce.nq.gz
    ├── 1e9bfe7011ab480bae39081a17542deb44397719.nq.gz
    ├── 1ee8c1fa3c0d53057db8e7f3799fede2a20c48c4.nq.gz
    ├── 1ff7191b5960fefa61deafb017b33a9bfcbfc948.nq.gz
    ├── 219790e5d7171cb97b58312c7af27fe264e75d0b.nq.gz
    ├── 21b7cc76014b1b04cd4053c9847cadc7dfe5ec4b.nq.gz
    ├── 2296df462e768e3145e2bad4dc72966076694391.nq.gz
    ├── 2369901d83a9567ac31f3b29860e9c54017bc324.nq.gz
    ├── 286e94406d0c7ee0383cf08a5d1599439aa3bf7b.nq.gz
    ├── 29dbc24642d95d72619d66b623630d383919e07b.nq.gz
    ├── 2a37ca8510733271f822031298da376c9787da02.nq.gz
    ├── 2b3e81c51bbc62020ba6cd6b6339f9fb41ad6b31.nq.gz
    ├── 2cc4036289252ff81f263be5261fb11942d86aac.nq.gz
    ├── 2df5e9f4395671790660d2290be0e8bb56c0c2f7.nq.gz
    ├── 2e7a83ea0602848dab7afaff4455f2606c471dbf.nq.gz
    ├── 2fa7247ef4c42a3014b9da29cab6f2990a4e4a17.nq.gz
    ├── 30d6b1a3eb1c455573f19767fbda66f3c79fdb48.nq.gz
    ├── 3173b342fbd9ad027bf6fcc528ceb15b4c85d2dd.nq.gz
    ├── 33758d30ce69b31d5ce9884507c21d92750a3c2c.nq.gz
    ├── 33c749e8765c706fc912abb40323bf4a27d745bc.nq.gz
    ├── 370cb54014f5714251b578ddbb2fb575fceca7fa.nq.gz
    ├── 376cc7a1e3f9fee6bd7123014245ad5c89390ca9.nq.gz
    ├── 37aa4ee874ea6219c36f7796783642eaca97870f.nq.gz
    ├── 3914b6a8d840ef13d092ff18fda412119ae24464.nq.gz
    ├── 394edad9be16975f09ed353b68f00f7f527bd564.nq.gz
    ├── 39e068f110406716337c51fa192619f416e6db8b.nq.gz
    ├── 3d39e9a0a98f34bbaddfbafa6f1ff8efe2078074.nq.gz
    ├── 3d4f794519ae958c1bc0a60efb85b4bc40d721fb.nq.gz
    ├── 3d84e7cedc8505c418be57e79e3066ddb05570e2.nq.gz
    ├── 3dec298698d40df5fd804134869308df5be3d904.nq.gz
    ├── 3e1ebe73c550945fa9b093240c56e6328fed9631.nq.gz
    ├── 3ea9ca4f0999f79896c6d24ad64f65833c17f613.nq.gz
    ├── 3edac85981fa5d172801a0c5934a4a96970ba5b6.nq.gz
    ├── 3f54afa5ebedefc22d93183686a684428f014781.nq.gz
    ├── 3fc4d4f7d6f2e08d1f5ca3c994948c8d7d1c0bc2.nq.gz
    ├── 4046e3369226dbf2220524c1e1dd1ce2f2e0d0fb.nq.gz
    ├── 40a0047bcc7392f24e373e258662dffb8e61f994.nq.gz
    ├── 41e5cd401f57dfc3e42c77c6de13607b347141c2.nq.gz
    ├── 4352900f2abf9a0d1320fa31d1ae6fea5a5f5aa2.nq.gz
    ├── 45081f93897e224a4561cb597500c5ed50f57779.nq.gz
    ├── 456689858d76e4235f98883611e3bb241aaec874.nq.gz
    ├── 4569d4456070d68978c80fcbcef7c20b87fc9553.nq.gz
    ├── 46c74655e6567cf0575a7603a1e91bffb36abb1b.nq.gz
    ├── 4826f4d72a294405580bcf3dc8a2be5ae3fb1327.nq.gz
    ├── 4ba22771a5c66968b943d515f443588389bc873a.nq.gz
    ├── 4c66cdeb6b25a0b5543efa6b8568e40237bc04c0.nq.gz
    ├── 4e811ab79f8d55fb9a5c401452ec3a61acc0c044.nq.gz
    ├── 5159431d6b5a8e81c06cce05c71a6e1f3b5d8c70.nq.gz
    ├── 52092366d1e4526fb5e29712d2aa9e9e98e992fe.nq.gz
    ├── 524f4d3843cbf771686e6473d4c3c00faa994111.nq.gz
    ├── 525b25ee467457e95197eff5173a43952e2e6efd.nq.gz
    ├── 53cfe4be421183459a0234586d61fa06c6af95d9.nq.gz
    ├── 53ff513fc6a3d707714dea2cec70b565988b8d07.nq.gz
    ├── 576c8c143a2a76a1156312e7addd31fa9ae037dc.nq.gz
    ├── 588a6013e36247378f583eaa1fc7783dce159f14.nq.gz
    ├── 5982d29d6b1d673ee9bd70f3651fd3521cd927ee.nq.gz
    ├── 5a264838b03e1745e8a0b409efbae43d43415b7f.nq.gz
    ├── 5a274f048fe9425eb5f0b7735239f7a617458284.nq.gz
    ├── 5a8aec541a8d4965115db770346fdf70ff8de083.nq.gz
    ├── 5c7f69e5be15b6f15e07dabf2bd49e61c3756a50.nq.gz
    ├── 5d3193637c292918b1e1f8d890c712660cd730ac.nq.gz
    ├── 5e8eea45402a3f3c5c9b0231b52442b77f2e1553.nq.gz
    ├── 6030b0c8b86535a493c798a03e2d8e6cf076f9b9.nq.gz
    ├── 62212231c5599a9830c00e60559a75fd0e31d9f2.nq.gz
    ├── 63dfaff955ae2edd34f63e781db78092059f9d82.nq.gz
    ├── 65b919b7187fdb21e0723e3e6bea522810e7e01d.nq.gz
    ├── 67eb1303c4ad1c9be931fa5e1ca908d7dddd09be.nq.gz
    ├── 693650d62f5237421cc0161ac26d8627fb8e83fc.nq.gz
    ├── 6ae0307d2031a93972191c06d07303e385ac0c8f.nq.gz
    ├── 6bafdd60713b59e950cde16de271cdbc0d4304c9.nq.gz
    ├── 6c060ddc71fbf450fc19c074084b3bf6a56cded8.nq.gz
    ├── 6c42bc5c18389a4e11333b69862a6d93e384b949.nq.gz
    ├── 6e60e0348e99654ddb2a6548c78aeb9fec2a66d2.nq.gz
    ├── 6e99718ac3485ef99c8de2f5d584e61554026eff.nq.gz
    ├── 6f1b35acf3cd22c6e2bbc479cb0f0f6ca2571dbc.nq.gz
    ├── 70ea8461768889755f60bd6eff07e92b1f167182.nq.gz
    ├── 7149cfe0f872099c1e35a8e364e916afa61bc943.nq.gz
    ├── 7489327edb3151d9d3155ba2e3ee99c64d0dea6b.nq.gz
    ├── 74db5e2c74d9e3cb300808e79f758975b31f78e3.nq.gz
    ├── 75a5dfd34d4ae8315060f1fea80a9ed4916bddc4.nq.gz
    ├── 77bfd80ab6a5ca4e0e7acb3425b39f32a5760ebe.nq.gz
    ├── 79c7ab2204e075a53dda4c9128fee33a80bd43d2.nq.gz
    ├── 7ad03b9b75dcc813cd548585ead5fc1c6bb4cbcb.nq.gz
    ├── 7b53e397d2eb4bb13dae1c33a284ed9126232016.nq.gz
    ├── 7bddcb3f493412351c247a06a8d86bc29f86ae38.nq.gz
    ├── 7cc04a99a4de9ff61be4711844214061be51676b.nq.gz
    ├── 7dac847794e0976a6a8fd04eed7a40159762e2bd.nq.gz
    ├── 7ee2288d0ced2528008d73dc50d455db28b3b751.nq.gz
    ├── 8011bba232a34221d23d33453b92fc39b7b6c317.nq.gz
    ├── 81424ef7990f5ecfd96c9152a56096620526d242.nq.gz
    ├── 81785b52d9319fbf7be79620cf090bb9658eef9a.nq.gz
    ├── 8279423cc9718e4c90bb62ee898bd2fbaa49c249.nq.gz
    ├── 83a6dc67952539b7874781b650beb7d5746610df.nq.gz
    ├── 84e78c92617ae68529690744cced1e69a635a7ad.nq.gz
    ├── 85ceeef354658b493ab8d17d08987419bcc32f66.nq.gz
    ├── 86563dd48916da899cc79ba1752c0e00ecc07c83.nq.gz
    ├── 867afb0d3c197d3bc3639b558438dfec973b8f8a.nq.gz
    ├── 86afd70bf6c5dc631de584d579c9d83d1841ffb0.nq.gz
    ├── 86c24a6f5bd0a5365cac3d7a264b71719c011b98.nq.gz
    ├── 86e756e95173b5fc6b46a091fc6cc6c4fed735d5.nq.gz
    ├── 883f50111aa75fbdcb5013db1e64c15101ff79a5.nq.gz
    ├── 895225e69eaa6c2e7e8de37bd8f1e2a7ddb4b98f.nq.gz
    ├── 89c9bfd02402d8fc69941c431db0a5898aad15df.nq.gz
    ├── 8b7efb370d8565216cc5319a02e77637565189bc.nq.gz
    ├── 8e6da991f94f523fa23d39d12d640f8d56cfa88d.nq.gz
    ├── 9255da95e0f43c53d6ecbf07bef7a3ff2d65f799.nq.gz
    ├── 94486f1392b86b12aabbbf4ba8bf110ed22dbc93.nq.gz
    ├── 94fdb57a2d0d2e0286f944cfeca34fc9a440378a.nq.gz
    ├── 95bfa34be2b3fbd5b3f7c65c9192ecc1a2d4fb50.nq.gz
    ├── 9705b1da603ad11cad22645edd394db5970f2f84.nq.gz
    ├── 970797f76436ed13497b39c1ed097af5fb67dbdc.nq.gz
    ├── 9798e4402391d7c6b2ea6b6bd1d9f6c65ac38a60.nq.gz
    ├── 9b839a48db32034f22a263bd04a29d007e0a3542.nq.gz
    ├── 9daa487db111b1d0eb22de6b33920c7018ed1806.nq.gz
    ├── 9fd23797e6dce7d47dec5d9adaa4b67b7e8ddd7d.nq.gz
    ├── 9fde967c7e82f61a9fd3747507090fee6206ed50.nq.gz
    ├── a0abac51a9b0933ba405b0b52b96da3ccb902a39.nq.gz
    ├── a30f05a15679918ede5a5360d0b601c3c33f8132.nq.gz
    ├── a462ffd3c2c634a622d70ec9cbb7ff8e663ca641.nq.gz
    ├── a64fb99e4cb826a6591e603c26fd4abd885973d9.nq.gz
    ├── a6dafcf8cd8b039530128f336ff3a42ce1fd5fec.nq.gz
    ├── a72161f048dd4531efb2b716ace3136ac873fefa.nq.gz
    ├── a7381318f85b04043b5e8de24af25bdb73fb47fb.nq.gz
    ├── a85d32fe7c2d471d082ab85668a5dd8fc5968aed.nq.gz
    ├── a968d4403b1d2b3428977d1162b9412de850fd17.nq.gz
    ├── a9a4ae3632c8fbfe2cf18cba615270037756538a.nq.gz
    ├── a9ff03703bad1c1c3c846d527a02b4ac37823a26.nq.gz
    ├── aa33fc9215130054afa603810f6a1556b60dea95.nq.gz
    ├── ac406a4e504e2b5a3432f1263882594c5a343960.nq.gz
    ├── ad76cc57569bf83cc2d1ce724158ea8c40a0e123.nq.gz
    ├── b045668d912bacf90539567140b49e16b84efcca.nq.gz
    ├── b2e52bc4f35d7e28a04c9c103dca32d6aeec069b.nq.gz
    ├── b2fee63c928b64f0c94d652d7556714d56f8f7b9.nq.gz
    ├── b3684a5031fb56c31a94079664fbc45841465cfc.nq.gz
    ├── b3baa1bc56c48976a3964e04d01064a077c1b5a0.nq.gz
    ├── b3ea6347a7ef2d5171db37a42093afa4fa0beabd.nq.gz
    ├── b7633f3dafb3a2325d8609b46b6f595f3bc1bbf9.nq.gz
    ├── b803c041b4cd440ed69074595efff0cfba198eec.nq.gz
    ├── b86087c5ad10b71ca8508ab7e860e83c0cf30555.nq.gz
    ├── b8c59133d13f7c8bb1b26e1a8214f1047928f688.nq.gz
    ├── b9d14e2c3651e693f0cd6ff4b1bb4b24d5ce1a08.nq.gz
    ├── bac977cfcca8a92b5f8741dda006d617885bf311.nq.gz
    ├── bb6f2506291edb1a764ed7da6057b1fc924629e8.nq.gz
    ├── bd6f2345868b09bab25c06ffa301f65110007575.nq.gz
    ├── bea44bef81caab5f37890464bb524980dda5e5c9.nq.gz
    ├── c192d086fc37b412d8d3e36be564de21ab0d492c.nq.gz
    ├── c37990eb48cc05990b3ce1335d4cd03498dedc0e.nq.gz
    ├── c74c97695f8396a59c390019f54d1b768764bbbd.nq.gz
    ├── c786274f4b5a1c7a441c8245fa16e9fbc691eea6.nq.gz
    ├── c7a1505d377d886a265e2d8bb9e7f8857c7ed59a.nq.gz
    ├── c80a73deddcf6194d166bff6484071e8179425eb.nq.gz
    ├── c8d0751cb87e9d2c6e2445ee0779ef0ef554e762.nq.gz
    ├── cbef21ffd359df13c288d898212989a8edabdce6.nq.gz
    ├── cc8236de6194f33f62ef5618c2be7b9a55419953.nq.gz
    ├── cc90df94e0b77106a3acf2e9cf02415ee217bbbd.nq.gz
    ├── cd0463e8ebcc26d04c44379a1b0296b644e993be.nq.gz
    ├── cf44f836a42a0606573a0a7c8d57210df38a5d82.nq.gz
    ├── cfeff8a52f5b73e3dbc405c54d8f7a2ed9bfd592.nq.gz
    ├── cfff4defe131801b21512e7893378c9aab55011b.nq.gz
    ├── d121711b83faff2ed13b4bfae74ff0ae417576a3.nq.gz
    ├── d36e0c7f014d01ab5ec525f9a9728f6d1ab3c117.nq.gz
    ├── d376ab57190c3394dfd822dc1491c898efa5710a.nq.gz
    ├── d4ff484d80fc981421d290544afdb462cd761368.nq.gz
    ├── d62f076bfae259c123d0802f73acf0b62c0838d7.nq.gz
    ├── d7049abdb392532a28af352d923dde1afbd76ea8.nq.gz
    ├── d79b21198d396b724fd755a1decbd4d4e3f60b2d.nq.gz
    ├── d91a1308207693474dd75722ff1aa58b9f8938c3.nq.gz
    ├── db1e8553a9b9bb2e50069c9b4b78d1fc7dcb2569.nq.gz
    ├── db7b9609d773bafe874f98cba25e7165c531f10f.nq.gz
    ├── e07fa9eeb7903b015df1f34952535a64b7f20fd5.nq.gz
    ├── e1f78a3461ab2067d94e1ca09bb311c1dcfe2735.nq.gz
    ├── e52364852e5da09fbbb4fc40eebcd4aa39fdb06c.nq.gz
    ├── e5cfd5b49aa497695d8d6c322178d6cad8a78dc7.nq.gz
    ├── e61c53850b46a189557a7b1c2d3d6760160b1795.nq.gz
    ├── e677ba6a7b0c586ab2dd15f1c7b08338eb3d967f.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e6d4f66cbcc2a49d6942c0fb69e205c51ba607b1.nq.gz
    ├── e907140bfe4dd56b5a69c44ebbdd931f9bfc831b.nq.gz
    └── ea1472ec1f38b2d1410951194a02f8fb9f1c820a.nq.gz

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

[ansible-collections/community.grafana](https://github.com/ansible-collections/community.grafana)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
