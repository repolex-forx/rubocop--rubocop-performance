# Repolex Knowledge Graph of rubocop/rubocop-performance

RDF knowledge graph data for [rubocop/rubocop-performance](https://github.com/rubocop/rubocop-performance), parsed by [repolex](https://repolex.ai).

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
rlex download rubocop/rubocop-performance
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 22a6f2175b4d564fdb3a3d0840e7cdb604e18092
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 22a6f2175b4d564fdb3a3d0840e7cdb604e18092
│           └── chunk-001.nq.gz
└── blob
    ├── 0050d23f548e06ec112e7355de2c14a977d5cb89.nq.gz
    ├── 053e2f3c7cc6a1ae3605528881a0e34d52c426ee.nq.gz
    ├── 05578e30e842b89462cd1d126a3a9f89bea43e3c.nq.gz
    ├── 0642a0c3072e71d0678b7e1cd9f3669a3c3050fa.nq.gz
    ├── 070ebceb28be22cb173f8fec64ff3378967c3e5c.nq.gz
    ├── 0937a252af49c20e99513d31987413238bd86ea3.nq.gz
    ├── 09c15f12d0a1bc00fa26b02a488531b6d6feb1d2.nq.gz
    ├── 09cc47f7b026d80d57086e1fa85429d0bacc0d95.nq.gz
    ├── 0a48d87305e586b5956d96260fa1b2fe8967f7ad.nq.gz
    ├── 0b92360663ee0ded1b154641e1bbd95e77eda336.nq.gz
    ├── 0bb544e73907fd9183f7779566b33ea703288c33.nq.gz
    ├── 0bfebd81699f889aa643c83d5043e1e75ad5079a.nq.gz
    ├── 0c97ec5671462227bc216a402a9b74f558247245.nq.gz
    ├── 0d2bc9dc945bc367351a3823ad5c72f106b2163e.nq.gz
    ├── 0e26cb278e8d80f6e1e82d788a18293eb9414ef9.nq.gz
    ├── 0e5b857e8c8e6360ad887f55ec124840d790aead.nq.gz
    ├── 0f1b4c78ab9afd3c1e347d487d1c5a88f7c0c1b6.nq.gz
    ├── 0f3ab345a1cb15703c0e8f9fdc3ffa71b9d13035.nq.gz
    ├── 1068e168479796a03d357d8f8192d2639aa78f02.nq.gz
    ├── 123fee93759ab9df19a56614a14ead6a823db1bd.nq.gz
    ├── 134067bb89e1b033e407572686fecff098556ca5.nq.gz
    ├── 138e822dc27f469108d9335fc3ec791738750fd0.nq.gz
    ├── 14d8f93fbc993f27ff533d1a0d89d4a8d34c3da9.nq.gz
    ├── 18552e433255d4a7b0ce18af641d698a623779d8.nq.gz
    ├── 1987d3e0378f63cd3bd5f003147070eb3db60071.nq.gz
    ├── 1a431a46f9766c08a525e30bc4359eb112f58c98.nq.gz
    ├── 1cdbcdd991d65df7f717a62f3da98dc892320600.nq.gz
    ├── 1f07df42309be89f74988e657e013e942d704b95.nq.gz
    ├── 20b725c10cf9dd2f5c99f66fab9e2336054137c1.nq.gz
    ├── 220127e2d733adf7301084b151e5120b6faf5747.nq.gz
    ├── 2398a194399f17eeaef0852a4df8096a0979d35d.nq.gz
    ├── 2410adf7207633df164de6f509b12ee4338bfdf5.nq.gz
    ├── 24386e15a34b1e0a1dbdb94d9b06493d149c48b7.nq.gz
    ├── 249bb616bfa53776994a44745e14fbf1f662ecd1.nq.gz
    ├── 25ad54bbc2534bd05b83231d594e46ecd414d380.nq.gz
    ├── 268934e78bf415e1aa60c152500e443838712900.nq.gz
    ├── 26ccd77b5e954b37e099847417f0d58164447ad6.nq.gz
    ├── 27aaf379195cf1cd5c23f37b98ca3fde71868c62.nq.gz
    ├── 27e53dc6f274d69a9cc84c561403b9b609661b63.nq.gz
    ├── 28f6e515cbac0f6f05aaa107bcb24aa48f7ee6c2.nq.gz
    ├── 29f3b4116d12759bd45feb0d5a8ad9a87862953d.nq.gz
    ├── 29ffaae3d8ce169b3d5385e6898e417c33cfc4b1.nq.gz
    ├── 2aade6c4135d1013e88dadb349ea0f387d0f9cc2.nq.gz
    ├── 2c082d3376716f879eeeab7a4f5d3c741593ea80.nq.gz
    ├── 2c9a4586c320148d7ecc672d3412499117379626.nq.gz
    ├── 32f8e9042c2473f39a6d415fee5ce4de33dc5af1.nq.gz
    ├── 33058bcd5fc3939ba3121832e25fb298a18d2d0c.nq.gz
    ├── 33ab80531f40937e436efbe9100ead22e3f23b5f.nq.gz
    ├── 347973270640fadde20982f677ce03b1147d6760.nq.gz
    ├── 3711cae81316780989e1bc8e50b6e4c9ccce0c58.nq.gz
    ├── 399d299a7304da09ae56863ee9f856272b07ac4e.nq.gz
    ├── 3ac28f8f39e2a0ceb0d75018939e2977072f31b6.nq.gz
    ├── 3b24133338298abefb573ca99d306496607ea91c.nq.gz
    ├── 3bc4681d8324b2bddb3bf65cfcb92f32380f9c88.nq.gz
    ├── 3e707774eb43b6d8bc86e4e459f343e4f3e57adb.nq.gz
    ├── 40c9a565dd245b39a5778e6b527395e3beb080ed.nq.gz
    ├── 4150f69a476e79d1d40791631124eb584c3fedf9.nq.gz
    ├── 41cbb572d5dabdaf5b46df57208c329f8150c351.nq.gz
    ├── 43ecb2d10c9b01f3fc34a2858f0d0ee3265ae20b.nq.gz
    ├── 4419be7d6b1fea67b560fdf39f2c96c4816214c9.nq.gz
    ├── 475dd2431c05ed18420e26a258cfe0278f1705d3.nq.gz
    ├── 48f1b75bd28801dae960be3cb9d90aa18b6c43fc.nq.gz
    ├── 4bbc0bc3961507d470328046ddb28a2795047a0d.nq.gz
    ├── 4beec7079c8e93a9005c8f9916c36c32d49bb23f.nq.gz
    ├── 4d9bd1e958d606a6bca206e885ced8132bdb17a1.nq.gz
    ├── 4e4d7606a8f74dd20b7c4f51ffc149bd814f69e3.nq.gz
    ├── 50d8f14a3afb30de804d18ce1076d4d9631817da.nq.gz
    ├── 52723dde432dc024d29b788888598685ca15611b.nq.gz
    ├── 55d53330582476367bc651855ef5e6e2e39b9639.nq.gz
    ├── 55f3f2ecdd5e8aba597447ae0cc9acf8cdd048bf.nq.gz
    ├── 56deecc789c00f12cbea3d6757907686fa6da886.nq.gz
    ├── 5792a1173ebbe34463fd31b4da16fa6c14d1e53f.nq.gz
    ├── 589bb619de7aff99b9a8ffedab5b522866e7abf1.nq.gz
    ├── 5a7608ab755bd9c1580b9a486032fe45af2fda40.nq.gz
    ├── 5b540a9b4ff5f79fe6666d8dbcc5845ff309de08.nq.gz
    ├── 5c8f24e61f63e9e7d81924157019c9c30594d145.nq.gz
    ├── 5cd024cd4b441ab8036c6b99cdea6e01318dfa0c.nq.gz
    ├── 5cf764aeb8c93da140cdbc73d3162debef31bf93.nq.gz
    ├── 5d50f8cfe2341075067d75536cc62ac39f959363.nq.gz
    ├── 5ee9ba06aaab809c02a759477eb9c4c76c5acf17.nq.gz
    ├── 604e059d779170a6d6667b7f34d648e6937e90a6.nq.gz
    ├── 61d5807475c8beecbbbfc0b6fe3597a360d3b547.nq.gz
    ├── 647c615b617ed7a52c49ef50d650cbb8cd484da3.nq.gz
    ├── 659371d1248756d11885c8e1b941e2bf73c8b839.nq.gz
    ├── 6601c0f5f88d87e1b7947805d7639136117a515e.nq.gz
    ├── 67af349acb0d57ce3d9acf455985a4d26fc5f5c6.nq.gz
    ├── 6a3604a59717637bfa42f898170f68efb446dc55.nq.gz
    ├── 6c4d54aa65b480e0c9a23426dad37186cb9a1d2c.nq.gz
    ├── 6d94b639124c3fe26a70a0b0246a4e687bef0ce0.nq.gz
    ├── 6e9a7e48f525defd3808e0347705747fcb5c00b1.nq.gz
    ├── 6f187a0522879db6aaeda54a439ddbdb1e10224d.nq.gz
    ├── 7012a54b83dec822b5b4f4a839d625555753d4be.nq.gz
    ├── 70aa77b6c5cd047da29dd01fd061dc2d906b09ce.nq.gz
    ├── 724b0772c513415eb76e37183c83930e27089fa1.nq.gz
    ├── 7415f0ec3e74bca30a62e1983db898c737731bd2.nq.gz
    ├── 74b261c1250cdaf78631326babda35cc61fdb312.nq.gz
    ├── 7591e9396d7e6dde45b7a9a63a84a3166019efc5.nq.gz
    ├── 7a50a45c4b47b590a3f83bc745d09cbd33e1fc44.nq.gz
    ├── 7bb9543416355512bca0110b6ab28fc86e57e99b.nq.gz
    ├── 7c92397bd1f2e02f96acaa627f852c501f1a4265.nq.gz
    ├── 7d55f40edce7eca1f5b4298279d39685e197083d.nq.gz
    ├── 7dd70447634c37de9362a1a0c033e1cac1b5dccd.nq.gz
    ├── 7e6060ef1b09f734de7e883d0288d8a50fc9903a.nq.gz
    ├── 7ea0da3c941aa66566254eb02990912b4b374628.nq.gz
    ├── 7ed4227d4e839159ce1f042ca2e100122e328b88.nq.gz
    ├── 7f4ef6bd67bd4b319bef8d36830dd076dde2ce50.nq.gz
    ├── 7f59388be85ee1ebdf6eead42115f4186a649f19.nq.gz
    ├── 81328a9ea69f8f876a28e0b337c2ade0189e43b7.nq.gz
    ├── 816f2d954474b15fd8da805ea07251e13e6186af.nq.gz
    ├── 82587559a9aa3a2a62e9dac652e2fae35ab2bd51.nq.gz
    ├── 826c9ea2455a5deb07dac5479c7586f91d09a65c.nq.gz
    ├── 82f85bafb6d09a5a8dd69a0c118c84572c0d09f0.nq.gz
    ├── 83e16f80447460c937aeaa44a64d743b27863077.nq.gz
    ├── 84b0847b8365d3d97da0dd5ca93c7b260ec74b69.nq.gz
    ├── 89ecc299c4ae3c113f0f3fa5318bfd2efbf9efd0.nq.gz
    ├── 8ace1d96fe420b433b0537d715c8ebdfe62b651e.nq.gz
    ├── 8cd0f312b387bfa40ced1ed09d1fee6253a11f45.nq.gz
    ├── 8e342165a72aa9eb9c1f37d34bc735be2778e595.nq.gz
    ├── 90062bf6b790e12749da2e0a65b31f74b2bc07a4.nq.gz
    ├── 9126c43a600b3d509d8da226b8d95be60583d588.nq.gz
    ├── 92530dc39bb4fcfa23b00eaced6d720c4af92f20.nq.gz
    ├── 94a04b17c7a2648c654dad7e9c5d2da244a386d2.nq.gz
    ├── 959ef4cc6411f011462d674f11f0df3dca57c822.nq.gz
    ├── 96f1f91226e4ae9a3962b17364b386ae5cdbe82f.nq.gz
    ├── 9756070b91286d82045bb1258d6f7982fbb8f299.nq.gz
    ├── 97e21714d4709210180f04adf12e35298d63ec77.nq.gz
    ├── 987d69f3bd0db280773f3dd32b4dcd4be3a28b8e.nq.gz
    ├── 99961b053f559ff407537e8c7f3b6e1416c07119.nq.gz
    ├── 9a1f2f2bb934a9ad0fc9d04f50787db428b23f87.nq.gz
    ├── 9a4d4d909b7a1c7318b75106465d490bc9717b52.nq.gz
    ├── 9c21003b3baeaafe7788eb6c9fb0fbc4db782539.nq.gz
    ├── 9d3603c3b2b82e94a6b6bbc4edbf6d464a440450.nq.gz
    ├── a19ade077d36b05ff659abf5bcbd8a9723b96495.nq.gz
    ├── a1bb69d4ed668e13656d84368a30eee6c042020b.nq.gz
    ├── a21d13df8a20a2f5675f275209044e0c9ae54f15.nq.gz
    ├── a50d0e68fe1670c58c516724a12d0f49019f2df1.nq.gz
    ├── a5bb6f587c96321732f7a2489736365a621e4f7d.nq.gz
    ├── a65db86b0cd7b8bb13b5a5fbe5a3ad2d136d322b.nq.gz
    ├── a7c8e0ce3696a0027a2c8ea159731805b92b4f9b.nq.gz
    ├── a846b7a4fb53f8776d8f9f57b0e0a2e45aaca9ea.nq.gz
    ├── aace763f0a7997401858f7735eb6677251ae052f.nq.gz
    ├── ab2e516be70b3da5ea0292627fd5d560a8e210e4.nq.gz
    ├── adc26bf6e8c5fc4c0f343e00b230473a78058ec3.nq.gz
    ├── aded9c2eb1be9244a9d4434674e7e3b878ecf67d.nq.gz
    ├── ae352130b5afef22a7798388cdd9f6fc49ab4ad0.nq.gz
    ├── af1fb2b8d84079cf5637e00d5dca8d085df5d111.nq.gz
    ├── b18fd2935736768f4b1eb12f15709ba4c2f05171.nq.gz
    ├── b1bdf70f56cba24253f5f6abe46c4f36e5e92579.nq.gz
    ├── b1f796605e602648e3d6751979fea1efa19e6291.nq.gz
    ├── b28df8c8c438f5bde125b2f2272a78b3562e4c05.nq.gz
    ├── b36d6a2e6615158a65c352cc28738820156dfeec.nq.gz
    ├── b4394c09253291c9fee5215573fb9496c497f11a.nq.gz
    ├── b783fcd81740b6450887f5ebef0a032b34ce14f4.nq.gz
    ├── b796739dc1da2c02cc74a274d76a17b8e77de767.nq.gz
    ├── b91129f8115adfc56ed9e768480d0c09fbc6cbec.nq.gz
    ├── b94697a122ef4de2ef020252bbd25d0f8de46bf2.nq.gz
    ├── b96c96739e16411708e4311eb0b9497624b60f10.nq.gz
    ├── b9dc26c851460541fbf0305cd2aa50c2f28db672.nq.gz
    ├── ba35c06c03e71debc868e9d2474ead968a1b3c77.nq.gz
    ├── ba5328329b2dec9411d49ee0db10aced96c0b6f5.nq.gz
    ├── bba8758a6b509e8a83520e3aa5f6adca4d1642b1.nq.gz
    ├── bbbc6a12f764a7720c77e1b9cadc1f9ad9538de8.nq.gz
    ├── bbfe929adaaece4cf5821d6002fbf1e2647b8054.nq.gz
    ├── bc66fd7c98b65032f7ba7268f9ad79e9fdb608d6.nq.gz
    ├── bf68aae26c037e4a65f0660a938969520d8b80f6.nq.gz
    ├── c3f256d54154df44c91ae9ae5ca2338cb8b59481.nq.gz
    ├── c56f7d3a7b2d8197b537e93113f92d7d400559e0.nq.gz
    ├── c6d4b592bf979eca9414bbf676de21266db12382.nq.gz
    ├── c9957ece78f95e8b9862d382b53d3116d9cd3db3.nq.gz
    ├── c9b57eeff0b0d3a125c28521ca0bcd7e47b955ba.nq.gz
    ├── ca1298747435126876bc1aa2e86d9e973219b4c4.nq.gz
    ├── cb31fe75e179c0a2d0e2c8bfaa1bc32ee5dc4ea2.nq.gz
    ├── ce5a8d6d6858d233096525e004e335add1d85bac.nq.gz
    ├── cffb9e4acd47a5252879cb954b62b168e602f2b8.nq.gz
    ├── d04e2bda99b75d2c1029078317d57583838f5c81.nq.gz
    ├── d0d26c59712c1dc0eb0487e77cfa37eea929ed8f.nq.gz
    ├── d1022c7b14aa9995f2b762400ffe1fba084bb0b3.nq.gz
    ├── d120a6de3b78ff0f3f04c3d2ee96f1d3f480ef7e.nq.gz
    ├── d1fdc9ca84db9fdc8396650df3122135d86fe51d.nq.gz
    ├── d2740cebd01d490a94e0de55f7400453e90920a0.nq.gz
    ├── d319e7fd961c6ae9084894a1ae62b95aaa2ca450.nq.gz
    ├── d454c1308a89f804bc51b0909c24163c7f8d2798.nq.gz
    ├── d7da5fe6c33fac402ce96078fd44c205857e97cb.nq.gz
    ├── d871cf44ec3173b8b5a5b5203d4ef88bbbf3fb4b.nq.gz
    ├── dae920c4eeb30e6043fc19ea1f2dacd2d572c77d.nq.gz
    ├── dc0f4708afeddea906532f9d3cb1928e102462d6.nq.gz
    ├── dc603ec9f0610c72f5b37ec2bc4a111e4c35dea4.nq.gz
    ├── dc6a67a920dd7844211cc0e8b01d2ea543e39108.nq.gz
    ├── dd0eef6632851fe227eebb726d969f5d1ad8dc16.nq.gz
    ├── dd793cc2505c32826e2796780d47f6092a765183.nq.gz
    ├── de078e95937b3c12f7dca8f33607aed654b8d4ab.nq.gz
    ├── df6f5de636bdbd777ebd0a392302ab0465e0ac8a.nq.gz
    ├── e1f543b8c59efc676ef22b4d98fad0f0bf26b437.nq.gz
    ├── e29208e06045a094e50a77f9bd67d80f95f08ca4.nq.gz
    ├── e2afa904fef2a735b05d39362567a7c359b03076.nq.gz
    ├── e6422c0b39d738c2d9e515378f2dd613181e62b2.nq.gz
    ├── e682975b148fc158a6ffdc2830c4b0301a558e35.nq.gz
    └── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz

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

[rubocop/rubocop-performance](https://github.com/rubocop/rubocop-performance)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
