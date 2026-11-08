# Repolex Knowledge Graph of qdrant/landing_page

RDF knowledge graph data for [qdrant/landing_page](https://github.com/qdrant/landing_page), parsed by [repolex](https://repolex.ai).

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
rlex download qdrant/landing_page
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 84bc96c85c54074a27b98cba3be28b49faab4f16
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 84bc96c85c54074a27b98cba3be28b49faab4f16
│           └── chunk-001.nq.gz
└── blob
    ├── 001526a1ab0c5ad093a9c285465241ebfa8c3609.nq.gz
    ├── 0053a2fe7e58771db48db26cfdb125d591ad054b.nq.gz
    ├── 0119feb9a2f9a9d8f5a0ed47618e11a5c21f4b0b.nq.gz
    ├── 0160cac1964a1ce10392685d8505b8a7cb0b43d2.nq.gz
    ├── 0174eb6a98572a7fefa36031c2bcd468a090a42d.nq.gz
    ├── 01954409a35194699fc47ab6e2dd2ad195d30f60.nq.gz
    ├── 01b7eafe3b4aff873f33fe80ed7ca996fc6dc643.nq.gz
    ├── 04d001289a0d8bcbb6d89023a1402900fee6c9e1.nq.gz
    ├── 053487fd729c3805e8204c75ee10f18214ef71e1.nq.gz
    ├── 05e8576817d44135f21248abfa6f0d957e871fbf.nq.gz
    ├── 05ed82a3dc0b06958651f1485d34138612a7dbcd.nq.gz
    ├── 05fa8308114e04045f69ddbf8df84e7489037956.nq.gz
    ├── 065c8af0943900ff54ce806081ee91353a78f4ca.nq.gz
    ├── 069f6319e0c49475aeb704ffcad138d8efeba14f.nq.gz
    ├── 06de754a692ca75888de796971ded2dea1e17a61.nq.gz
    ├── 0726380de3ebe69eb7a273bf350aaec5d472cf84.nq.gz
    ├── 07afc38d381d78f7027d0c58c80e510765a4cecb.nq.gz
    ├── 07c3b49f29537a6e7991ac05cda520bacc58115d.nq.gz
    ├── 07d2f8d3377c1c64642796235188ae860b71288b.nq.gz
    ├── 08bc76500946f52d93ff4fd1831f856a6d70b3fb.nq.gz
    ├── 08e0d44a6266543fae21e5b0df8394b4fc2453cd.nq.gz
    ├── 08f31f3aab4a90ef2484d29bece40ae1b3a6ab22.nq.gz
    ├── 0913d013b08b351d12d003f65a2fb1171039beae.nq.gz
    ├── 09d9e1115b28d8df3eb2fe24fd69889ede2e5595.nq.gz
    ├── 0b87ab225eeb415391fd5fdcccd67f050be73c41.nq.gz
    ├── 0d67020a4c661cf1407a0938e4ce501c6914fc84.nq.gz
    ├── 0d7a941e3f46e8259c37ea7c6f3ae503c104323b.nq.gz
    ├── 0d8b30a0e0717e953e18d2b218253a92eace0ea9.nq.gz
    ├── 0e01bf8574ce6d7203ca0826be1e83a77a8f1715.nq.gz
    ├── 0e4454405561b6110e8b41abe536cc498b84a52f.nq.gz
    ├── 0e8fe2de684095b0ac9ed2dc855c1d666a9d1c2f.nq.gz
    ├── 0eec5b408f6add25a16e8d7fa52dc3df834b3ec1.nq.gz
    ├── 1044fbb296c52f6a55ebf3f7547754f91bc97560.nq.gz
    ├── 108d2403914d5b59259ea3a75fda4e373b03b8a0.nq.gz
    ├── 10e9d34095fccf13e075bf4930ea8012456ddeb1.nq.gz
    ├── 112551337b67fee99af07424940ee0568b2712c0.nq.gz
    ├── 1199c982cae3d2a520d2eaf4f397fbd3f2aab304.nq.gz
    ├── 11e4cc994992423b36145b50616322116559f52c.nq.gz
    ├── 11f626123305c7b374074f8dc902ff4e5539bd31.nq.gz
    ├── 12509a8c65f71f45b02b02c05d20b76d13114e97.nq.gz
    ├── 12739cf59815ae9f2b97ae7661ce1eb2b0c628f6.nq.gz
    ├── 12cc53a594a76dd4d6b06a13642c5466a68ccbfe.nq.gz
    ├── 12f85b4c6af9cf362c1ba04ee0f950cdf7608699.nq.gz
    ├── 136a33157bbebb0a626a1814ade59ed4c04d61eb.nq.gz
    ├── 15f78091c0923558c0fc97cf947eeee7f3985879.nq.gz
    ├── 1612d85021f9fb15a249157ea631b460cef440ea.nq.gz
    ├── 16324e4f14a82d69f5bde3c5f27ad7d536e17112.nq.gz
    ├── 16cc41375c8e5bcde4b1f31126d6f89023312ed1.nq.gz
    ├── 16fedca85d8d5c86b5c4849c2fb7fe569422f701.nq.gz
    ├── 18baf889a96c558062a0c2a0a682f703466808e7.nq.gz
    ├── 18da088c0bfa31f002f1ac96b1721c7d08a49219.nq.gz
    ├── 18e8b7915c4bb4f186794bf430f0c11fcdcf9bc0.nq.gz
    ├── 19acfbea278132339db735176424614bd9072ebf.nq.gz
    ├── 1a0b7bb9cb815c60fd635481fed324880720da3c.nq.gz
    ├── 1a4bb0b326a962850f4f7e78d28379b8593c992f.nq.gz
    ├── 1a797fa624ca23b48363c4b0ab3713d0988393db.nq.gz
    ├── 1a8c9a2735ec9fd55c001b29127f522990b13e7f.nq.gz
    ├── 1aa3f37ef9269c4a3ea3c443e9a279da30a8bf7c.nq.gz
    ├── 1bdcf906abc0e211a210414fb2fd24b25ae70fb9.nq.gz
    ├── 1c9c26104876a0e3601305d823931eb6b99cee90.nq.gz
    ├── 1d8be6a9aaab2bdab4b7bd92d6c29386dae8bf5e.nq.gz
    ├── 1de970b7def0dd262a8c23bbe79824cfede05bb5.nq.gz
    ├── 1ed944e669016227a6bbe485f6e2690729445b22.nq.gz
    ├── 1f0aba411b96d3e39aa0a1e990b8a401e6c443ed.nq.gz
    ├── 1f12ab848576ff180363dc35a6829c962e1416bf.nq.gz
    ├── 1f28c5a37967fc1566b9f54ff267bf92a467a295.nq.gz
    ├── 1f2b97f387c5ba45fd4e32dbf49dd1c386762fc0.nq.gz
    ├── 1f90cfde7fdb9586323fb457095268f284ce2946.nq.gz
    ├── 1fe63282f4ea33e2f68fb6268499a0a3e5f43e6f.nq.gz
    ├── 1fea2a80537fdb824d022ab0744a51374d97c9ee.nq.gz
    ├── 1ffdb23763e7dc5d8b08f3a6d3b253b4ecb233ce.nq.gz
    ├── 205c3c78733d6d2b139ebf4f9a004a2191c287d1.nq.gz
    ├── 20b94e3ee2fb7cab94ba3c8ab8b0dd4eef909984.nq.gz
    ├── 2168249003ecbb73e09c8a10f7b573d80f316e20.nq.gz
    ├── 219585cafb53dc75226c315b9250784568bd80d9.nq.gz
    ├── 22bc028498da222d2a7a56c14c8f251923a6eb5e.nq.gz
    ├── 22ecd282c00ea195914667112442e7739dc98d49.nq.gz
    ├── 23ed535841177205c1cbe8786e30852bd91ee2cf.nq.gz
    ├── 24572dfd24147fb1022b86cbf4034742bb65a546.nq.gz
    ├── 246637600b2d2899de3d9e41b65bc1728c19f7dc.nq.gz
    ├── 24cdc0d4ec5e0927c30b4c57d0e2015083e00dd2.nq.gz
    ├── 24ddb4a4d526977fb506018784d17628ed9c8b6b.nq.gz
    ├── 25a985b2a1a7a21fd90c8188b7277ede4bf4470f.nq.gz
    ├── 25b3e933bd8c5a9e245c807795af115a8c259063.nq.gz
    ├── 25f83b798b6700564198486ccf1523d4fa4a6e0c.nq.gz
    ├── 274d507a5d955865cf9ea475a48e885a2e3ecbf1.nq.gz
    ├── 27698208ae545b90ed9a0dc8174ed89c6ade556c.nq.gz
    ├── 27af73240659c371e2fee80479a0aa97a4205b4f.nq.gz
    ├── 285183088fddffd3e104ce6499b2db5127012f42.nq.gz
    ├── 28b2837d06e448bd2b1ae5d1b47f9efc8dbb058c.nq.gz
    ├── 296b7412780a04742458abb1cc73122323e1d2d9.nq.gz
    ├── 29fe49b2753662383a517826e7543509a8080a2b.nq.gz
    ├── 2a234bf7998ff26e6325896541f72f7254d3fd3d.nq.gz
    ├── 2a333fc7e0b4d7ac9e678215ae1f0ee8fa42ac76.nq.gz
    ├── 2ade6dc194f49ea667380e3b1b53eca0dadaab4b.nq.gz
    ├── 2b50a41d8c217ff385c5271162b64886ab204211.nq.gz
    ├── 2b71c3fcab096b3482aed0d9ee9557c987e18110.nq.gz
    ├── 2b826f77dd16fe1faca32215c0f58a11a03574c3.nq.gz
    ├── 2bc81acc90d267f9319dff62f0503122bb766e82.nq.gz
    ├── 2d59b2c1600ec3dc65aff14f7e82edb5d1fe50bf.nq.gz
    ├── 2d7fdc902e011c7de905294dd44fc7a4eacfa2d5.nq.gz
    ├── 2d9410a363f48334f5ab396c96353a3db6ac932e.nq.gz
    ├── 2d993d887e94abd2524fcda05628f1000f37740c.nq.gz
    ├── 2dc6230995540cdfa5ec6000e47cdb577f6261c1.nq.gz
    ├── 2e0ec57f157a0de04b00dee18b36a3dee86112a6.nq.gz
    ├── 2fb7627063852bbe752ce2a4e03dd8cc153e2c4e.nq.gz
    ├── 3120bee4c109b0586594c30ce55fca55de468b50.nq.gz
    ├── 313e03ef16b79984734aef5e1ffa6a3af60e7f4d.nq.gz
    ├── 321843978573b881c8c8b6183e15b6b41d38abe8.nq.gz
    ├── 3239943741dd6a4156b36684028cc7fdf52ec5d0.nq.gz
    ├── 324e4e80f687495a85902e61c5f1c2ca6dd22351.nq.gz
    ├── 32eebf5493b54208d3b193c93a6b096d9b7e7687.nq.gz
    ├── 334cb403c7af8a332f946bed7faf6ef04cc8dc0d.nq.gz
    ├── 33df5f46bed3dc56939c708dc37974bab28930ab.nq.gz
    ├── 3433c605580886be8735d6e7dc951e239d30adbb.nq.gz
    ├── 345594a40a8e8ae959cc2e28282fc821e0725d2d.nq.gz
    ├── 3484ed95948b856ab20253011dca8cb7ccf397d4.nq.gz
    ├── 34b02aee9437993c262387bd68c08d80c3a1ee8f.nq.gz
    ├── 34c9d6b6e3b2dcd06c84a7c3d3b06f977c224cb9.nq.gz
    ├── 358ade32359d337a2876d2c54cf078fb713608ed.nq.gz
    ├── 35a7d8fa5a60100a8612c2416b424889ceb7b05f.nq.gz
    ├── 35b92852542080f224fd1eb5b649c14dcb909c33.nq.gz
    ├── 35caf0b831ef74555e95be35896404077628e8a4.nq.gz
    ├── 371f3752ca7bc65fa119d4c277e24f832bdf4358.nq.gz
    ├── 372dbad5be8ab11e68be2be9243d27c6387cdbba.nq.gz
    ├── 373f816f5b44a247babb09ea0f48faf965fddf8e.nq.gz
    ├── 37a0e4371c99dc31fcd1ce9d618da32baea75093.nq.gz
    ├── 37fc849acb37dc3b3918ef77dda5991705ec702d.nq.gz
    ├── 3823a881f14a192120ee8aa3f0c19f453ebe1b77.nq.gz
    ├── 384ef381250c0a85aef45b2fbb5a06bc10fb03b0.nq.gz
    ├── 38a07584370d0b896680d804d568d8f4b7dd6d85.nq.gz
    ├── 38e7c3e20c4748de7914e53b66f22c408c1ba7c7.nq.gz
    ├── 399a5cb328fa6f155e39bb5def724ea952c24461.nq.gz
    ├── 3b97d289b4766922c49b49c347942cf17f378280.nq.gz
    ├── 3c45091f8deb7bbb5434972fc9a97f59dd8147dd.nq.gz
    ├── 3c98507d9cd8eaf95419db0ac2dcb3fab8cfa564.nq.gz
    ├── 3dedcd3b707a4aa3609ad36511bf78078fe6c986.nq.gz
    ├── 3dee6ce444156c3ecdd3c45166364335b1caa01d.nq.gz
    ├── 3e050144820f0902b8f4aa17c0c747ec2c16e0dc.nq.gz
    ├── 3e9f4636b8e31a00f00b3f21420b65362eeac817.nq.gz
    ├── 3eb83ee0dfe8aed696850bcc9ab0a1502e7f8e7e.nq.gz
    ├── 3ee5d588de587d314679b897044365ef03e4403d.nq.gz
    ├── 3ef87b3dc2a11a9e59c0f7be0638c0fd03e9237c.nq.gz
    ├── 3f8550b7a7dd1d261ffb0f7ea9f3e0d57f2562db.nq.gz
    ├── 3fa39cade581ffd66cf8af2dcb8d9a1547ad7580.nq.gz
    ├── 3fafb9e1cf81a34aba8dc54db6b105161f3f48b1.nq.gz
    ├── 4098fbc1eb471ba7a32187cbf2557c0e9e2d7920.nq.gz
    ├── 40aebc7ddd286aa0a606935b867e933a884f100a.nq.gz
    ├── 412305e9ddce6afbb4b8daf9935aef6586c96ee1.nq.gz
    ├── 41270da6bcd06b1acb9acad9549e214c16a2542a.nq.gz
    ├── 41684f3935f61b1e63318856b28fe9592591f516.nq.gz
    ├── 42c5127a37f05307cdd47f8546eb74bd42b0d81f.nq.gz
    ├── 4328ebd63089d2627a13fa77e93e57e57520baa3.nq.gz
    ├── 46371f7f2745d22d878c1187fbdd5516aa7649e8.nq.gz
    ├── 4650dd247f1e1c6954e65a0d92b549424a3ba596.nq.gz
    ├── 48147a1f598704a0cc31e1c040ac1c325962d03c.nq.gz
    ├── 49f5769e01851f0fcaf1fcb4ca3c66d193444c84.nq.gz
    ├── 4a52096072f7ca679195311dde141302cb1d6499.nq.gz
    ├── 4a6fce0f8218a299a6b277bfdbb582bba2a5fa8f.nq.gz
    ├── 4aa397a264fcbb5fc61d517844e4d0e0e0d2c71c.nq.gz
    ├── 4aa8c8d4ce0597ff87a2b21937e222522980eba3.nq.gz
    ├── 4aecadebd752f8558fddd71858a94d40fa6074e5.nq.gz
    ├── 4af720a46e91b254ff1ce00170bf172534c41164.nq.gz
    ├── 4b0d59d2c979795a2963a3124bdc3f7ec1c2ccec.nq.gz
    ├── 4bdb4ea251295dbac2bbec17cef2cc53a4059378.nq.gz
    ├── 4c29c231c1195a54407590869117c7236f96d752.nq.gz
    ├── 4c4c4f7b62525e735cee14704e62ed43b7e306aa.nq.gz
    ├── 4c5748db8ceb1801584fd01fa3fafbcad6091f32.nq.gz
    ├── 4c708cb9198860d1179c4fa7e1fde1eab5c7bb8f.nq.gz
    ├── 4d3b967d8548e37aeb509b3a08039a96283647f5.nq.gz
    ├── 4e196991c357d6f688b2afcdefe6b5adf46fb3f5.nq.gz
    ├── 4e9c66ecc0b814fe4af9779b99f47b200e42d3ea.nq.gz
    ├── 4faaa5192cdd1fd38ed8e58dc021fc534a541e0b.nq.gz
    ├── 526534db0bde6ed36a581defd436d1c3092c92f3.nq.gz
    ├── 52bf76f783e1fba2b27b0230903b0c97271d3f50.nq.gz
    ├── 54ce6cefd700dfd7a51c709b0128cc6fa0f84735.nq.gz
    ├── 5507ab627a114cc4beeb4b0e47420f86eef291a3.nq.gz
    ├── 5592f40122fbca385bac882319e72c92896aca78.nq.gz
    ├── 566e16d1d58d6f1aac77be4aeffc4af4eb2a8522.nq.gz
    ├── 567e6b5aa0289afd7088b6fccecb5c6a8d8f5e53.nq.gz
    ├── 568575d20c4148c6d14dbee775ca1edcd7919bcc.nq.gz
    ├── 572f26a85c524326bdf9123551555d460d1095a1.nq.gz
    ├── 5779e536164ca470e714a754d86c8d889dfe09e7.nq.gz
    ├── 578fa537ae76dc54eb4b983b11d56b676988df9a.nq.gz
    ├── 5a6132e3a64053d0514ac45a00a4cbd2fa6704c2.nq.gz
    ├── 5a67172c1c29c7ac5090cb2f3ca98b013e7f9828.nq.gz
    ├── 5a6b54fc85990fde6fbe7107f52896054c4ee564.nq.gz
    ├── 5b036a3a77f4fbbb6a0437d2d9c2aa4fcbc874dc.nq.gz
    ├── 5b11a483fc48021837bbe2994bbd260d37d3e91a.nq.gz
    ├── 5b5861b01521838349eb8fa9bd029766736ad24e.nq.gz
    ├── 5b6bff9a6cf9ea7b0c637431ca36e7333e3ae77d.nq.gz
    ├── 5b7b9c6c7209bb471ee60543c6f179535ca5433b.nq.gz
    ├── 5c379af80b4937004c1bd85944934056d8c9a687.nq.gz
    ├── 5d9e2ab42caa2300de3857a02550ba1a8e97b3a1.nq.gz
    ├── 5da8d126cc3c42903e3f62506b4ada607ab97ee4.nq.gz
    ├── 5db1b3816d279bd7019380c7293019346ef51cfa.nq.gz
    ├── 5df5628785fd938ddac072fcf1d4c5901045362f.nq.gz
    └── 6017cddcf156e96a6e34ad92a30aa0c778a5b739.nq.gz

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

[qdrant/landing_page](https://github.com/qdrant/landing_page)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
