# Repolex Knowledge Graph of pradyunsg/furo

RDF knowledge graph data for [pradyunsg/furo](https://github.com/pradyunsg/furo), parsed by [repolex](https://repolex.ai).

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
rlex download pradyunsg/furo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7b0cb83657e744b667bf6888671e3455d6481f7e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7b0cb83657e744b667bf6888671e3455d6481f7e
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a4f1f4ad83aa63c6630c9834c0ab8622751ee9.nq.gz
│   ├── 02429d54fa4e5aefb361d672b4cd7cb125ed1d61.nq.gz
│   ├── 032660b823f848f5cffb7873da6a7768586cdf47.nq.gz
│   ├── 05d3f4c91d9f04e531c9f40acde051cf47d41084.nq.gz
│   ├── 06e3556ab662a3deef718ee7864f2ca8bfd32abb.nq.gz
│   ├── 0a4240f29f34534c5561c9c4621cf62bfd585db6.nq.gz
│   ├── 0aa671716703722bea9a8fc89ba60d96861bed16.nq.gz
│   ├── 0f9c0b71b699fccbde356b8edc3e5e4675a10296.nq.gz
│   ├── 10fd7c77a144d7ba6dbf8826ad0fdc18441b754b.nq.gz
│   ├── 12c089e713cfe02181084ec221ba22b3b626d396.nq.gz
│   ├── 1413cc486d0e4835c22bbf4e8ab11d693cd545db.nq.gz
│   ├── 14c17bcecd79b9ce7aff0afee5086f5dc6982815.nq.gz
│   ├── 18a83396ac65d09e89bf95145affb450d8183120.nq.gz
│   ├── 1bfbd138e80a30a64d796b836261949f2e597bea.nq.gz
│   ├── 1ddce9fe2e95097d1ccc42f6a98c6db53c946797.nq.gz
│   ├── 1fa81bc3ce14b2f20dd7ded46e2e5c43d288b1c3.nq.gz
│   ├── 201b5e69990517724211ce004ac0188b74f8ba1e.nq.gz
│   ├── 205021e49dd1f7342400b8e1254cc4e310fcc4a1.nq.gz
│   ├── 21efc7a58fb47b8569c49948575d2739d759fa2d.nq.gz
│   ├── 29591e3ea44279fe5261e5dd8638f34a5a162452.nq.gz
│   ├── 2a5c71a2b798715132176ded65d5549b00d4b097.nq.gz
│   ├── 2ba588f423164fa8c88ff9d1003fe5de0f4d01e6.nq.gz
│   ├── 2c6c13c46036519aea4d91fe60d46da60b7d92f8.nq.gz
│   ├── 2dc83247b7b9b34c8e21f2628a456e41592f4380.nq.gz
│   ├── 2e36a6e3a0720d4c9943e26c11cb9f63b8c2447a.nq.gz
│   ├── 2e4fc1690c759cbcb03043716cc476be7a544e57.nq.gz
│   ├── 3142982bf2a36753240c3b2bb7b134c7dc2859f0.nq.gz
│   ├── 334f67fcc5f9a4e4425cd4764d0fed18a624d32b.nq.gz
│   ├── 35d228130b9516fbc04c29078e3dce0c9b4f46f6.nq.gz
│   ├── 38dc34b58b8a29c76861241b5fa7484ffc4b6f83.nq.gz
│   ├── 3ad522d624b31104d4ece1a151e3dca83c823169.nq.gz
│   ├── 3d5ef2081be0dae00b01c75445652ecf6ac07dd8.nq.gz
│   ├── 3d9b3eba64b1424a157f13ea3d05c6c7ac86a858.nq.gz
│   ├── 3e1f022f838091fdd0c4b9c2fb14f69b179495e1.nq.gz
│   ├── 3e86aa7e5fe3e7231a09034855fc9659cbd4d91b.nq.gz
│   ├── 41909d0d889a6d0e504826d300abdede4ad4f184.nq.gz
│   ├── 45131a3e46d13c08748257cb6bf54de4ccb312b7.nq.gz
│   ├── 4552331fc79c84e9743abe9a7407e216534eb5b6.nq.gz
│   ├── 45bb8d6010d78c1bf8939886ece2f772aaee4b3e.nq.gz
│   ├── 4a09601124f14d9d4ede324fedd835d696ec87ca.nq.gz
│   ├── 4c05e11a20549dee0f5e0896a8f330ff7d28c5bb.nq.gz
│   ├── 4e981ec8d685ffa945efe12a989d5e7f3df3721a.nq.gz
│   ├── 530346ede3a7bd8b6904a152c998f5b07467781c.nq.gz
│   ├── 535b319faadbe724f14d59ea5abfd589f758f25c.nq.gz
│   ├── 5ac55b91fc5609d22b18e437242848a2c4dca893.nq.gz
│   ├── 5bdd7473128388830055bb07d1878b8cc49ea7cd.nq.gz
│   ├── 5f4dcfa6c8242c7947fa35f810bed4364cc212de.nq.gz
│   ├── 5f61e0ec508c3e30805ba55d90e0b70a8fb6d0a9.nq.gz
│   ├── 612f5fd4ba90572b36269f0d99fbdc7bda1c78c3.nq.gz
│   ├── 6136eebbf9c8b715952922f85f11a6ba2f15bb54.nq.gz
│   ├── 6578663537b328149c942b7d9197377cb0d36313.nq.gz
│   ├── 66c157405a073963be99e8e63cfa833d3531d6b6.nq.gz
│   ├── 672331d5c0d8827181cfefb12aafcca75499b7d5.nq.gz
│   ├── 6b382162f353f10a3dcabc4a9816c6da85a96e78.nq.gz
│   ├── 6b605b004e61f21f35ae93893c2583e4608f33e4.nq.gz
│   ├── 6c9f4c23056194c66411d58d274b5e4c1f328443.nq.gz
│   ├── 7152c58881872ad187c7c1b977fb1bd09485b301.nq.gz
│   ├── 753f30f03c709b99efeb718d01f29c800e78b97e.nq.gz
│   ├── 75853f42c894c599f6be2b2920c30a362e5fecf1.nq.gz
│   ├── 762a52c58ffb28ea3b032443b334a0c243bb32cc.nq.gz
│   ├── 7856fd630656a738d32a0f3cb471cc5752040103.nq.gz
│   ├── 7873e56b2e1497c1e96ba4e707992c53ada1d05f.nq.gz
│   ├── 7c6df216b43c6836bb422ab1cfead400c080a023.nq.gz
│   ├── 7e8b9196a1c683d87f5f2c89957fafb7a5a6f40a.nq.gz
│   ├── 7f5427bc44f17285eb9cebfb97cbb7ed450cfbe1.nq.gz
│   ├── 804e3cf535f5d9587bf51bfcf678f39ad07f99ed.nq.gz
│   ├── 80e41f9af45c843e0c522defd4d1813445c3be04.nq.gz
│   ├── 80fd0962a257dddb17b96eaa48596bebefd869b9.nq.gz
│   ├── 8466937f6726d68dae745a5c1af00e28908a2a80.nq.gz
│   ├── 87a1e4eb7cd1574f3a8aeb0bf2fd0424af0f55b9.nq.gz
│   ├── 8a696a1baa8d507a762d716dd9b2d91013777b42.nq.gz
│   ├── 8adc990a5739ead6d27e0521cecc789df008722e.nq.gz
│   ├── 8cce097b82e51e0f1c9dbc3ec5dbf667f3b74c41.nq.gz
│   ├── 8dd087c86c8ac98e60f2441deaf168a5d77e0eb9.nq.gz
│   ├── 9437e7435dbf927b0f396b837f8af35062e9fec6.nq.gz
│   ├── 9534e59957e03be4cedab21de612c5de173b9cdb.nq.gz
│   ├── 96db38f14ac0745f6a09f3a5f4910b053f4a5c19.nq.gz
│   ├── 97e741050a3270c1441b8c3c7826af7600086ef3.nq.gz
│   ├── a487ec517c0e4c7bd3f04438ca5389242c03e2df.nq.gz
│   ├── a551f1c6cafe29d8609a7907ce5f63861948313d.nq.gz
│   ├── a6ff7458f210aa2f83aa0bcd902d6803600ac880.nq.gz
│   ├── acb6959fcb94981e58684b68c5ce4abdb085bb35.nq.gz
│   ├── ae9492c2d11e4ea0945fe08e9601dd669e164492.nq.gz
│   ├── b044a29821ffe3b70e45d6f0522b54ed7f1be931.nq.gz
│   ├── b183f5417d9dbda547dddda178aef67fbb65be9c.nq.gz
│   ├── b290d8598538cfbef2a659b844a9e3ecf15eeb28.nq.gz
│   ├── b2e3bdb34789b353c293ef3ddc3f1137bf115cbf.nq.gz
│   ├── b4ec23a8da7f558543aa5cf2f8d30cf988289bcd.nq.gz
│   ├── b672fdf37f7c0fe623e5b3b685e3d2d845758b20.nq.gz
│   ├── b8d8575482e50838926e2cd8a90bdad4298610b9.nq.gz
│   ├── ba7de20f947627ba37aabd409b3f1c4f48b5c895.nq.gz
│   ├── baa0cd4eff09bd5e1bc22c7a467f2de97b44b838.nq.gz
│   ├── bb282ecfb4b7c63e9491763ff9a58295d9281b0a.nq.gz
│   ├── bd815a69c2cd6522d197b7c24d344a2fe9afa644.nq.gz
│   ├── c0adba0e436a8b56e2e77a4c03df260b296210f5.nq.gz
│   ├── ca72e84fbb1af5a8f4c68183ee3e8055af085fc6.nq.gz
│   ├── cb4600b213b2330e81bd69c11be4eec6f52c3cdd.nq.gz
│   ├── d1c747457b69762d0f348e5298100f340da6cbe4.nq.gz
│   ├── d66de371f1ff5c42c2ab3ab6ff650d66d34f1bee.nq.gz
│   ├── d8a8775e99ddd8e0242de8d9eb4c3d50ed940757.nq.gz
│   ├── da2f514847bfa25226c03c1048718715c854719f.nq.gz
│   ├── db8d24ee9c28eb87a197fa94318d62440490cac2.nq.gz
│   ├── db9e8344fad7cca818d4ee1bc570b0f879f0acd4.nq.gz
│   ├── dcfd163d47d1ad807b78d7ed0be04686cd6bda75.nq.gz
│   ├── dd270e1a94bf83b823a85697c369aab10a6406bd.nq.gz
│   ├── df53ddd9cd44e2afe53e53dc1e77b6e82b8328da.nq.gz
│   ├── e04cd92dd95cc64d9b66296f3dd518fccd4a1fcf.nq.gz
│   ├── e11637c326df403bd98da8ea29bbb37d256feb43.nq.gz
│   ├── e233b85c69249452a08c0b493b39896eb1d331fe.nq.gz
│   ├── e4a684ee4aa248c6f44bd871c43245c71e1a7fa0.nq.gz
│   ├── e4d2eb3fd37c70ab1ec9b0ef97a547b91b039d97.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea0739dddcf56ce0582338d81c9fc64d0853423c.nq.gz
│   ├── ea904059cf21a3e04e51d8476c449a4c76853fbc.nq.gz
│   ├── f18e99dd110638d0b15e81e24b614fd5e73c9702.nq.gz
│   ├── f2de090e02f872deb7a3f18fb4922836cf104d28.nq.gz
│   ├── f617da7c6234998be506000b86da02082bd8e942.nq.gz
│   ├── f64afba66a9fe6e81e11578a69248c845aa10d38.nq.gz
│   ├── f68b86eedf0985c6e5a9182dada4b5ae91ba433e.nq.gz
│   ├── f6ec656cf2a80de1572973caef8b486a3abda693.nq.gz
│   ├── f8d385a62ec95bd54f5f1d18bf432af54970806c.nq.gz
│   ├── fb5ab95ad875b1eccb0810750e5f0728c9ed33b1.nq.gz
│   ├── fc52dc5848d2aabf5e0549fc88694acf93884087.nq.gz
│   ├── feb771c554509f7bc62c71a146173550bfdd141b.nq.gz
│   └── fed5c43bc3641d2a83e665ef561107c675303e65.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7b0cb83657e744b667bf6888671e3455d6481f7e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 133 files
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

[pradyunsg/furo](https://github.com/pradyunsg/furo)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
