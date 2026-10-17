# Repolex Knowledge Graph of networkx/networkx

RDF knowledge graph data for [networkx/networkx](https://github.com/networkx/networkx), parsed by [repolex](https://repolex.ai).

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
rlex download networkx/networkx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── abf2feda2252ee4e0d5a66964addf179225dfe76
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── abf2feda2252ee4e0d5a66964addf179225dfe76
│           └── chunk-001.nq.gz
└── blob
    ├── 003ea78cd652354b3f15b92a1fb02c48d0196e64.nq.gz
    ├── 0121367fc4ef766e2587610c3ea32ba33b12b259.nq.gz
    ├── 0156908f5276eda74d91e286fc987acc10578b4b.nq.gz
    ├── 015eaf8276a3b178b0bdb2c67b54ccfdc63256ae.nq.gz
    ├── 01bd8b57ed524b6f2bab24added0e7986cf53023.nq.gz
    ├── 02547fc890c22287c5cacfc4ec6bfc384e6ce785.nq.gz
    ├── 02847daab637bfbdb2cc7bb66aa6397357af40aa.nq.gz
    ├── 038c1871c56171e285a68913dd846adcc3876567.nq.gz
    ├── 0404d9d8454b36b546152c1428790441c6952fa2.nq.gz
    ├── 040f4d49de1cb544410660ec0e4ca758fbd5975b.nq.gz
    ├── 04526fbf46c3a7c028f0bbe1ca81d67572740422.nq.gz
    ├── 0508084e16915ca94c8fc07b1629c7852c392ed3.nq.gz
    ├── 0552e4a942c9c99fbf132300d7288595307052ff.nq.gz
    ├── 0568b7f0fb323b6e5356d2eaea28cd51fe96d931.nq.gz
    ├── 05d26799a798947e766d650335658108a5ecdf1b.nq.gz
    ├── 07983148163d07d4e1728977e92fdabdf1c5f3fd.nq.gz
    ├── 08dd7cd52ff414c1397e3effea504853f3c9caf7.nq.gz
    ├── 08e17d500a403bbe61bc2b338b94f5240290e982.nq.gz
    ├── 0927f00bc5c31ad1134dae0c8f59367baed67bb6.nq.gz
    ├── 09a0f8278731c91cb3ff681654ca42c23869b97d.nq.gz
    ├── 09b722dd1bd49dddae16086115d170ec989f8b06.nq.gz
    ├── 09d34965e6a090e68656a981b53600d583d7da0a.nq.gz
    ├── 09f1d9dc1080b0b4dd5690b02838d269a84025ef.nq.gz
    ├── 0b4e29de7a44d6a75e8db351039223080f8c49ad.nq.gz
    ├── 0b70a2e985b64477ea3d26b89ccb21c8cb4dc6c5.nq.gz
    ├── 0b77b6bc8cc5450b8348fe3981a383b4967566e7.nq.gz
    ├── 0cb8f52965c975013d41be7c3de874cd86ee693a.nq.gz
    ├── 0cf5fe66e582e528ac53dfcbb164b0fbb8f04880.nq.gz
    ├── 0d9890c424d8a3bf636132558d35643f1cac7b45.nq.gz
    ├── 0dcea368a93873fd72195fc8d388891c129942e0.nq.gz
    ├── 0e66fcc19a6d92f4d007d2b54485048cb63ec288.nq.gz
    ├── 0ebc6ab9998db144234c2601c24861b2c48fa339.nq.gz
    ├── 0f53309d4da23a445bcce8cb7570a6de364452b5.nq.gz
    ├── 0fc8176d242edf8163a1436adcd4afcef5d97802.nq.gz
    ├── 0fe5ceec97c5c3c85e5e64e05b4c02eb83978c3a.nq.gz
    ├── 10ac9fc7f0b7ed74c69859ad323b9fbe33a0a460.nq.gz
    ├── 10aebd881fa3f0dc1dbf792f838eaa573ce50046.nq.gz
    ├── 10f1df63359c1e4f3234fb833d967d24477668cb.nq.gz
    ├── 1119c47867d5ce69fe8853bbd0044ae1b3abdadb.nq.gz
    ├── 113c1f87b0a983f220f61df4759a2696d8ee17ed.nq.gz
    ├── 119db185a1ae440fd2cdb6c7f531331642313c34.nq.gz
    ├── 11dc86e93cad5233bcdeeabaf33dd651b4b73d5b.nq.gz
    ├── 134cdff49f3a2b6079b13602309a66015af00f2c.nq.gz
    ├── 13d7167cfc1e4494cbbb2ee8c774e9ffbc3ee495.nq.gz
    ├── 13db0c404fd5d161c1b0bf7c3bec34af641d5f4f.nq.gz
    ├── 13e548d40984bb545753a282f34b2bd008d052f6.nq.gz
    ├── 15d121d90b86a3963944ad6289c9b9e0dcb6ae1e.nq.gz
    ├── 1631af40c217d5a7a3bc43850ddf1ab7e26342fd.nq.gz
    ├── 1649ec82c719226e9caa68268d8953f7cae6ef74.nq.gz
    ├── 165a608c8fefb836b095a2b7165ac6b438aadac2.nq.gz
    ├── 16e80ebdac0c2869abd49e9ff94bfd712bcb6041.nq.gz
    ├── 18c784e84b50c55185ad7e2ce1b8c3034721d4c5.nq.gz
    ├── 19037a0a472a5ed94857c80937469ecd51e36d90.nq.gz
    ├── 194893f75b6cd66c24c622ea81bab424a156422d.nq.gz
    ├── 19c166bff1ab9942a54efe92015a0b434f408d15.nq.gz
    ├── 19d2d8831ced26a516d101e735b6701f39865c1b.nq.gz
    ├── 19fb5d117be94c688616a394ea3322e93bfa3e00.nq.gz
    ├── 1a341763cb476b46f6b97567be5cd3ea1e701532.nq.gz
    ├── 1a7668282d71e7a4b0a926e135311997b10f7d7c.nq.gz
    ├── 1adb1168c43913e95c976d6d918b0fdadd0e7045.nq.gz
    ├── 1af838ce61b91d0c040cd6d283f7881f1abf9afd.nq.gz
    ├── 1bee84d3401e60d6247b69e010d1fbde9db2fad8.nq.gz
    ├── 1e256f4bc69389464cfa164f209bc2db713b79ee.nq.gz
    ├── 1e5144c1049cb250d11e2820afac1e14b5be9c08.nq.gz
    ├── 1e5a913c7c07bc0060274e611cef18b054d71238.nq.gz
    ├── 1fe70a42869e4fd1501ae90b849bfb4de50eda2e.nq.gz
    ├── 2010831c514ec710893350dd734003613e4f27a2.nq.gz
    ├── 207041debff67127379e858f04dfdd9449f14b05.nq.gz
    ├── 207214c1262ed58ac1152a5917a270514748dc0a.nq.gz
    ├── 20c87b2d1183aec6fdd125649a0727e9efe1d997.nq.gz
    ├── 21b91669ac4da238a4b7ec5dcefbf3cde66e9daf.nq.gz
    ├── 23fbe7bbb3f037eca4f7ede25b7edf6305356587.nq.gz
    ├── 25aada68d0a6c2c80545c8db54ceb3e775def44c.nq.gz
    ├── 262623c4bb0fbe68ecd42bed4228a2245d053abc.nq.gz
    ├── 276c87d0745dade0f11bb9374c3479e1f9f8bcfe.nq.gz
    ├── 28074cac8704ed47d063f4ca6b57f1411e9e270e.nq.gz
    ├── 28ca78bf4deb45ffa422d2792b966adfa112692f.nq.gz
    ├── 292de05a083861d6cca44bbaa72ea422358d376e.nq.gz
    ├── 29604b148303703c73ad37baffec043abd4333e9.nq.gz
    ├── 2a72b3753b2841e3122ffd24c7daf172fc510436.nq.gz
    ├── 2b8c12571043f8ef7fe31c195694eead5db7de6d.nq.gz
    ├── 2b9e2bab41eb29067166b6faa331e022d4074ce3.nq.gz
    ├── 2ba7302e63afc2f93e8c7c528dfdc3f58f5d7aa6.nq.gz
    ├── 2bd67445e5d363969fd29e6712f1041babae9865.nq.gz
    ├── 2c308e380c774a6450d4ce275118ccffd65defaa.nq.gz
    ├── 2cbdd8cffe7ba03a4a2ea775ddc287d59b38d523.nq.gz
    ├── 2d67dfd3ff381d51e2ece51aae7ea27ee3091acb.nq.gz
    ├── 2d70708d4fb3d32db1e6ce6932b8bf042ec2c261.nq.gz
    ├── 2d88932eab709b262873364b599720ac9d986e51.nq.gz
    ├── 2dd0ef2fa175fea5ea74f0c71e4c3b22f944f525.nq.gz
    ├── 2eb96e5eb8d97ee557d94a14f1e0cb769e6b02a7.nq.gz
    ├── 2f2289ea3cd296a2d7da745253d87a269d3a247d.nq.gz
    ├── 2f468e10b3ebbf43888ac6761a473bbc2e1b106b.nq.gz
    ├── 2fdfe575b5da0b5aa5a0fdb073926d04149f4161.nq.gz
    ├── 2fed080494880ab6b41207b33f83f2067a6d19ce.nq.gz
    ├── 30a3d6a77452532b60aef95f1d97e827f0f221a2.nq.gz
    ├── 31f4962eb651bc274bd11ced28300785475e2685.nq.gz
    ├── 31fbb6dd03a796aa8abc0dc5afd7c991baf5a993.nq.gz
    ├── 325d670ec1667a2566f5f343f5750e06a8db3089.nq.gz
    ├── 3269ae62a023ff0cf9fdc55122cb6e7c8d2ba319.nq.gz
    ├── 33b61a4b64975bfd0044215825ae5510bec68073.nq.gz
    ├── 33bb6f7e8dbb17ab83efc387249046696a5cac32.nq.gz
    ├── 34d9b22a65a3b46b91eb1f0b6bbb9780373bbdc9.nq.gz
    ├── 34e4030726c104b99c63f52d04ca22fca8d16437.nq.gz
    ├── 35583cd63e55d14c0c389040cbdeab39b27d1bf9.nq.gz
    ├── 356b9ee975a34d7c9a1437c0dbba7d2b26cf0380.nq.gz
    ├── 35ac74e83274270fbbe08225fa81b01e40f227ae.nq.gz
    ├── 35d50e701216bc6c003517ca3ed92cddc261c286.nq.gz
    ├── 36448154c791a7ae533ba7e86f9fa063c8dbe07f.nq.gz
    ├── 367901240444407df6f2797c9fb21ce7c39f3bad.nq.gz
    ├── 36b7c80d30f68cc8651184834d3116774a1c6390.nq.gz
    ├── 37506382c55a110b26fdba32a268545d23f4474b.nq.gz
    ├── 39b7554f3d875359bdfc287fd9aa2081d4c25d45.nq.gz
    ├── 3b05747565e73388b0871fbb7daf0f85ad2ce98b.nq.gz
    ├── 3be3f3638890aac5c069916b8b55973d2aaa91a0.nq.gz
    ├── 3c394db66e651adfc4382e1e8e97aba6f31ac495.nq.gz
    ├── 3cfec716b6fb3f9ed5662110d62c643f3e1b7b40.nq.gz
    ├── 3d2ffed7e444a42e950b81729e213d36d6175c19.nq.gz
    ├── 3d34e428d5c9a9c077459a970f5f3b3cdbcd7fe6.nq.gz
    ├── 3d68c17d185bf5ffae54b613d9a22f6aea9b9215.nq.gz
    ├── 3e5e2269818eaca6e7f66e942660b9f536bb8ee7.nq.gz
    ├── 3e6e0651e4db82d0078a42559ac64586d05fc352.nq.gz
    ├── 3eb431740cf5973f5d18b2381593478e3cba6824.nq.gz
    ├── 3f93b76db748280ce1e1f6020abaf1e19cd85b1e.nq.gz
    ├── 3fc8b78bc401f1a4ef8f3ff0252bf175e25cb534.nq.gz
    ├── 415b5e69193f219ab200fb2df68015acb900e8d0.nq.gz
    ├── 4162bee42c9e4700f059afb0782a3d6d379c9f2d.nq.gz
    ├── 43281701d2b630710acba8f3cef6693356aa461a.nq.gz
    ├── 43907ab59bebf7365776995ed391677491a08e59.nq.gz
    ├── 439a196eb023088c3794612651278035298249ca.nq.gz
    ├── 43ba7cc4b9002b28b5241abbbac34cfec0b7798c.nq.gz
    ├── 449bf0b687285b708faf1f8b3f9a3fea2952169a.nq.gz
    ├── 44bed9438945a39bb5eb85477301f58cfcd70cf0.nq.gz
    ├── 45d79dc554f8a7a22a43c784e20c9207f009230e.nq.gz
    ├── 463844be23a07f71375873bbc71e09c402d51118.nq.gz
    ├── 465b0adcfb80268df44aa0b0dc7ed8e24568fd2e.nq.gz
    ├── 466fe6f77b192e5aee08e292832f7e8bcb933656.nq.gz
    ├── 46d6300649d3b4658a7263cad04354988b4da312.nq.gz
    ├── 46ef64d665869bdfe1e37255dcb92e39dfc56617.nq.gz
    ├── 470b55129a032d38e9a6e7faca29c12a85dd9eca.nq.gz
    ├── 4769ffa71ab823c154e6f7b990f0cb07299090a6.nq.gz
    ├── 47804f9e25372f4bf5fd725c4e873287165094bf.nq.gz
    ├── 480b3a5c841af11b807ba533ae9f809eb1e52672.nq.gz
    ├── 4832b9347756d43acac9a7b33ad7e25b852d2e9b.nq.gz
    ├── 48e47cb1d3a28ba86d921967fb7e5e161495178c.nq.gz
    ├── 49dcae963e3fd0f8309980efb4ff463848132566.nq.gz
    ├── 4a6a98a13b0eae03a82ef594e15368eb744c8497.nq.gz
    ├── 4adbd84de7fca27e58ba2c09edf54b92a0fbdf40.nq.gz
    ├── 4b3dc4ac356701eb562a3179a69023ad83a8d74e.nq.gz
    ├── 4bd4d5983faad8bca5d59594ec2d45ffcdba0c81.nq.gz
    ├── 4be72dbf27281c58d973e1d0d84d101fa369d43d.nq.gz
    ├── 4caf1cd9a2d845752e91051a79ad05a23d4be571.nq.gz
    ├── 4cea418de81cc86edc53170848bacfc12bd50934.nq.gz
    ├── 4d9888609cbc43d4ba2121fcd0feda0985d1aebd.nq.gz
    ├── 4e3db98ed47e6f01d91d695cc8c0f0adb824c177.nq.gz
    ├── 4e8add0b23ae9178640c1cb60ad3198064b219d2.nq.gz
    ├── 4f491bb3aebb7ef575476452d2f7cafc819363be.nq.gz
    ├── 4f7123c1c6375e1ff45fa62eb50d900ebe24f98a.nq.gz
    ├── 5062dcdea91cfa3d7b5b67ec5c69a4815d14b650.nq.gz
    ├── 51588d30deb220b053cfbc64ff6cf93d5ef21922.nq.gz
    ├── 51a5e91e3683b981e68e976aac0f7ce54d637499.nq.gz
    ├── 51c12589fb713176d1a06b272c63e095d04ad2af.nq.gz
    ├── 5207b6299656a7ef6f6c4eb5a390721a4b056515.nq.gz
    ├── 52084930de71269b8f0032db3b6c96101c03a5b6.nq.gz
    ├── 5326ab6459fb24a63fadf8bb8f3096558ba5e9c1.nq.gz
    ├── 532c71d79b7b8936481be8db0defaedf9a96b3e3.nq.gz
    ├── 54463c2a1eab035f29a9e6b4a512b4ddc3814470.nq.gz
    ├── 5510ba0475601c1efedbba85414a83a784992693.nq.gz
    ├── 5651465248c01d3020b6e7defa409a652ef87160.nq.gz
    ├── 56b3e340e0682953bbd25885f9432ec198c9f97a.nq.gz
    ├── 5704b3b3e3cd3b32c3b8f8d7d0680a131c998011.nq.gz
    ├── 571580b8234553b9a2866b9c2380c5ffce4e95e2.nq.gz
    ├── 5776a68bc78c5ae60a3bb9efbab61617ade2793d.nq.gz
    ├── 58c22688660073a6abb59f7639871f711d1bd6ac.nq.gz
    ├── 594b9dc074b751948ade229ad11adfc80325a020.nq.gz
    ├── 59892ce416c9c747e7e1e22b78d3ef62f50401b8.nq.gz
    ├── 5a059596454e806abb459cfc818f47c04e37afb3.nq.gz
    ├── 5b9e49b0f4b051c6638e5f0ba2710f528eb8acd1.nq.gz
    ├── 5baa9766c39c3ac2e02e396879461668cc62bfc7.nq.gz
    ├── 5bac5ecfd1cbefcba5707cac2885ef32987ee98b.nq.gz
    ├── 5bb946eef91a918ec36ef226fa440fbed8371bca.nq.gz
    ├── 5c570131a054a6b605d40d5a6eee37576f978976.nq.gz
    ├── 5cc5a38df9a4139684005491e0183cd563487154.nq.gz
    ├── 5d0cc90a53589a46d0444be6df7c31a1f5beec06.nq.gz
    ├── 5da4bdc083e1948a353342004a0925c6bd02ae45.nq.gz
    ├── 5ea3871638688ed466b72bf3c99c977913a503dc.nq.gz
    ├── 5ea7ed2ce26ab973e07bcc6ec0d92aa4799d9a6a.nq.gz
    ├── 5eab5c1ee79408c9f90a1993415a6c3d7d957141.nq.gz
    ├── 5eba0e21c50b7afc446220519f1ed9818c5f422a.nq.gz
    ├── 60075c16530f65ddd23591dc12f4c1e76f76a124.nq.gz
    ├── 6009f000814753ab436278e2d2cc38e961e80f3f.nq.gz
    ├── 608c110603d12f79edf67a5e9c103a988b0a859e.nq.gz
    ├── 61d8d067d9792659ed7097340c5ece28d9dc2e8c.nq.gz
    ├── 61ea400db91cee0c643114c670cae5563cd652fb.nq.gz
    ├── 62724acfa99ce1b25d5e95c6462fe85a61fe139d.nq.gz
    ├── 62b7f95fb8aebea1f93b55924697e2a1958d3b13.nq.gz
    ├── 62cacc77887efa99026c117687bb9ad82cebd4dd.nq.gz
    └── 6331503f97eaabee965a7f7f302b30e88601687e.nq.gz

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

[networkx/networkx](https://github.com/networkx/networkx)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
