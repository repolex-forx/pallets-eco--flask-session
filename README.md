# Repolex Knowledge Graph of pallets-eco/flask-session

RDF knowledge graph data for [pallets-eco/flask-session](https://github.com/pallets-eco/flask-session), parsed by [repolex](https://repolex.ai).

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
rlex download pallets-eco/flask-session
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bc2fe67958bff5e46023c4807b5e75ca350554eb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bc2fe67958bff5e46023c4807b5e75ca350554eb
│           └── chunk-001.nq.gz
├── blob
│   ├── 0168a53c536556aad7996ce7ef367a1efbf68e5a.nq.gz
│   ├── 05a9e555d28046b95729a7fc54d07dd55daff673.nq.gz
│   ├── 0d51b3a827b4e419eb81ce3360b50369d1f608d8.nq.gz
│   ├── 0d61012b4c7558afa8b2485220558aa86a19763f.nq.gz
│   ├── 0e3638be083b6b9e1e482e141c7d0fe589012119.nq.gz
│   ├── 132eea281123139b16f479f234cdacab5debe0aa.nq.gz
│   ├── 16a48a49768ddd2d39cc53587a1cd986284c6187.nq.gz
│   ├── 1a904266b0a0f614faf3da032a842c868c393a87.nq.gz
│   ├── 1f1d39934046488c4c88c9b41d3d76ddc5407971.nq.gz
│   ├── 2285f25ec6f57a9af6516df5d80b23c30f7c3fdc.nq.gz
│   ├── 2351b7d45b33c00284d2b4542229b9a7ed002c78.nq.gz
│   ├── 2399b1a3524c36c9430262fe282aa61df48bdd91.nq.gz
│   ├── 23fb01019c348a739b9c9b764f45a805d8ed0eb2.nq.gz
│   ├── 244be6336584c5341aa0b5d5b58cf68bcfec94d1.nq.gz
│   ├── 26057c03aaf4dedaf62e0735da02b575d8a1c66b.nq.gz
│   ├── 2f6c644c0af1680e2f48b067e9f8bb30d24badf2.nq.gz
│   ├── 3132b48129e425b113d83ba8417c5dc95042771d.nq.gz
│   ├── 3463412d5cac79cae6a8628030d32fccafd50ffe.nq.gz
│   ├── 41e033a69eca5e45820c83956979a72d92e4401e.nq.gz
│   ├── 41ff5cdac54a9f61d7bb3637b310399dc1ec541c.nq.gz
│   ├── 43c659d9f4a215e014eb2f5378164d93a6efeee4.nq.gz
│   ├── 4693014662b645bb08f8e756de9c6bd132eddb17.nq.gz
│   ├── 46f0cb5897f5e1c228e7e55497a3dfe69447fa54.nq.gz
│   ├── 4a65c924b02b91ba6a985473f527f0a3173a952b.nq.gz
│   ├── 4a8d74b165d3105dcaac6952149fbb87fa8dc177.nq.gz
│   ├── 4afc2c1a3c77a71bfd52edaaec9f6ec2fded522e.nq.gz
│   ├── 4b6a31ebd834cd140b761ff811e83bc4aa8c29f7.nq.gz
│   ├── 52abd2053effaf8ef3c29e01709707532e61b8c2.nq.gz
│   ├── 539957e443dfab07cb043b63a7df27186d3fff8f.nq.gz
│   ├── 540ccb1a1b5e233cdb16ff20ed027d0005f87f60.nq.gz
│   ├── 541877932396f468c9a69adad899708397eb5228.nq.gz
│   ├── 58915a2ca60cb29aeedf37f722c8bc460e2e3d61.nq.gz
│   ├── 5d4caee9ffe35ec495c1112897343608915dce1d.nq.gz
│   ├── 607352229643f48e41a1c5b0c951e2b08021ce52.nq.gz
│   ├── 63aecac1d2664dc51728dc465e0f46d1382015d2.nq.gz
│   ├── 63b24ce13e642d22ce048c5b09e13e1d5b6948ee.nq.gz
│   ├── 65b6323aaac2fa414afb25fd99b6a549bef66fea.nq.gz
│   ├── 65cbf5562f9822ee455b2797992b2ac926f6772c.nq.gz
│   ├── 66a4269137542fcc16fc39e20f1a5a8772cd5349.nq.gz
│   ├── 675d9e9e475934bf2ecd8ad11b2b306b69a59730.nq.gz
│   ├── 68c2df207f2afd122226051268c433dc598cf17e.nq.gz
│   ├── 6a650795fdff167e5cd3e0eb6ba51ae1acd0fe9f.nq.gz
│   ├── 75559ee61898c01082f1dc8338f9ab2f6c1afdf1.nq.gz
│   ├── 7c59964b673f6ad21332b953e6a8a9d9bf4a2911.nq.gz
│   ├── 7eeaac17188ab262251100142e517cd47a4d9019.nq.gz
│   ├── 84298fd92f0b8857e9d84fbfaa670508bd7bc146.nq.gz
│   ├── 85c34d56fe843b98b4a36f82d3e67d8082aae9d9.nq.gz
│   ├── 868d1b0633784b6f9e8032ebd2393a5ae7912787.nq.gz
│   ├── 86d6893fb46788fdb5538fcf94107f46f4c742a7.nq.gz
│   ├── 8ab8425c311264373099778613ce0d6d23c47cb3.nq.gz
│   ├── 8be17b236dc4e32f30347adae488872524a7c2da.nq.gz
│   ├── 9094e001ca70f833678dce888378c1246f6b9e2d.nq.gz
│   ├── 94eeb2401d19673b2af65cd1c70656cd557e7394.nq.gz
│   ├── 9703f52e9cde80516e923abad36020d14093a346.nq.gz
│   ├── 9907be9f52d6ba722b050d50a729b12d5732efba.nq.gz
│   ├── 993130357ed948007c5b758deaf98985ac0817b4.nq.gz
│   ├── 9960da0773a7c6524ef0273b5bc10e33388ac7ca.nq.gz
│   ├── 9fef8fd5f5fcaa9622fd82e924b7c63e3c1bcd7f.nq.gz
│   ├── a26503064a9768a46a7ce2a56539f45437a351de.nq.gz
│   ├── a53a98cf3d4b093c6696becd3df4e1c6c0660fc9.nq.gz
│   ├── a63048f3622120bd5013f704b5919c4df073b38f.nq.gz
│   ├── a7d4e3a046d68788acbd1f4536a3a91b5ac4c66a.nq.gz
│   ├── abed80df2ba72230af770fcd93198ed81023864c.nq.gz
│   ├── ac535f11d25b1eec515ef665406d63a51b161253.nq.gz
│   ├── ae051c7dcdf7788bc6774ff61a222c8df0646134.nq.gz
│   ├── ae8bb63a06b304b62d23dd9591ad0faa1fb6f838.nq.gz
│   ├── b8088dd384c8e1be1c3d901dcb75e527354e89ba.nq.gz
│   ├── bca0e99163cd76831a0cf2df0bf1a846cacd93bf.nq.gz
│   ├── bd0e3603e912565485e58ffa568873f8ff3ef2ac.nq.gz
│   ├── c88e2d84b663d355ea3bcb46f414d83a0d98d2b1.nq.gz
│   ├── cd7f6855b3c78936027784ed78eb70464da1ca7e.nq.gz
│   ├── cf0faa24e42d04e04b4caca7953076b743af2b0f.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d68d09b5458d0da5b67f8bcbd5df638f444e2263.nq.gz
│   ├── d6e7aadd245704b7493964b01ff4e95c1beed113.nq.gz
│   ├── da44440507627d5d4056ec6378b4f73aa4aa8d09.nq.gz
│   ├── dd4191d95d12238d1dbf97d6c55db50000e37681.nq.gz
│   ├── dd98b3791588fc988284f608aec230f8adb3cb0e.nq.gz
│   ├── e192eba3c5a39b733290cf49690db6a65b02f992.nq.gz
│   ├── e8c34b9ea9be886fb180e143d7d816b1c1095f33.nq.gz
│   ├── ea58079addbda361a6d43ea155dbd414963bb77a.nq.gz
│   ├── ebd5075b27a348102a245de70a3ce6620f9b153d.nq.gz
│   ├── eda9bbb1b59867d2949951b45fee45bfaed3b5a8.nq.gz
│   ├── f1bc15012e1fdcd9d6cd220a90eee00141788877.nq.gz
│   ├── f319dcbea1203ed7f50028940fce8e27f8e816ea.nq.gz
│   ├── f393b5548be24134654dec2a1b3864411858b852.nq.gz
│   ├── f398377921209a0afdfab497c6f4220aa47c9417.nq.gz
│   ├── f80d9a4785fa74220240ad382d4c968702f7521b.nq.gz
│   ├── f9aa01d4cc6ca6e290c8ee0d3d449f6b20212879.nq.gz
│   ├── faae610d713bc60676d84ab00e2497e7446b8696.nq.gz
│   ├── fc8a1cea2d036510e3c6dc7e05e937f4d25795ad.nq.gz
│   └── fc8ab27d9735af3f341f930b322ffc076db036dc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bc2fe67958bff5e46023c4807b5e75ca350554eb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 100 files
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

[pallets-eco/flask-session](https://github.com/pallets-eco/flask-session)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
