# Repolex Knowledge Graph of tanujnotes/Olauncher

RDF knowledge graph data for [tanujnotes/Olauncher](https://github.com/tanujnotes/Olauncher), parsed by [repolex](https://repolex.ai).

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
rlex download tanujnotes/Olauncher
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 260697336e07cd39afdae1ef257fb8e75621952f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 260697336e07cd39afdae1ef257fb8e75621952f
│           └── chunk-001.nq.gz
├── blob
│   ├── 019cb1772409510972fd47a1cb6ca909b8b4b8b7.nq.gz
│   ├── 022cd025fe23e2a69ada61be95e286fc5f32ab04.nq.gz
│   ├── 023f97840fa0b3eec330a2a1d1610c3d3dcbbdc4.nq.gz
│   ├── 036d09bc5fd523323794379703c4a111d1e28a04.nq.gz
│   ├── 068ddf4769f0e71ccdb66c0f68c0ca0a26282dea.nq.gz
│   ├── 07ac3eea9d0839a699667ab55ae09f80162d99ea.nq.gz
│   ├── 07f00afcb11ccd620a2bc4e2b403ed99afa48798.nq.gz
│   ├── 097fa278e530fbf6cb45bd238f3c574dc3568bf1.nq.gz
│   ├── 0d06fc8b36730ba36427ecdf017466b5dcbba361.nq.gz
│   ├── 112a02b3ea8e145c13a26c5b71e5e063ff0ac3a7.nq.gz
│   ├── 14073f7a3b24a332ab9d3dcff1761cdf644d37cf.nq.gz
│   ├── 14a280f18de2a96e7899002a1c4068046e45c04e.nq.gz
│   ├── 15ca5bd1cca06def481f0c8d89f14ad54d5607e2.nq.gz
│   ├── 1745fdd90369b9ea520a69857c90883226b57854.nq.gz
│   ├── 18595e60095ee3dd7d3c0e984f3f05a9e7b97923.nq.gz
│   ├── 19e854436f34c1311f15bb63ea5346a726a6454d.nq.gz
│   ├── 1ac5d8eb3e69716f4e2540ceaf7837c71fee1e0a.nq.gz
│   ├── 1b80e2e6d325ab1c93bf16b2086ad5b4553664fb.nq.gz
│   ├── 1d48cbbb173360f5e63a626155d9a95718266286.nq.gz
│   ├── 1d4cdf574e12c7205ba961ef3dc45a650b845515.nq.gz
│   ├── 1fcc4d427b4998b1e9cb343816804f3e3a216ae0.nq.gz
│   ├── 1fe70a8cfe78cb0ed5042154ac85f4bec85f3167.nq.gz
│   ├── 2095e6803f65b64059804a865d8e1bec743deb19.nq.gz
│   ├── 20e0e2dfcf0e1f5a2bc99d80661bc31adb72035f.nq.gz
│   ├── 210ab8abfa211a1242954915a1221b354ba031f6.nq.gz
│   ├── 21fa593358f5bb96a30fcff31f92c97006e679c4.nq.gz
│   ├── 220efb0e3d636dd3e69a25bdcae7495892ed2830.nq.gz
│   ├── 226049411a2015acb0cffe32c8829dec01b26b46.nq.gz
│   ├── 271e96e547728dda8d888418e4c5b3321a71fd30.nq.gz
│   ├── 27ed3723a70870a08f5bda76fa4dfd34f869f5d7.nq.gz
│   ├── 2bf46f995932116050cf14850606202b2c9e78ec.nq.gz
│   ├── 2d538875fab74fedb7f910b6781dc8943c0d3890.nq.gz
│   ├── 2e8ab9292d9713cf4b4fcca8dab18970802c35df.nq.gz
│   ├── 2f67004246bc5e8e9a005700ccb70f05469fd479.nq.gz
│   ├── 301158713b4bdb4c6469a931544a3b6fd21c396a.nq.gz
│   ├── 3014decfb3a7cf0468ab8bc2ee7d097168700e67.nq.gz
│   ├── 317781ba4db64523203b3a3ff2a6b9b393641e2b.nq.gz
│   ├── 3189d4281b64457d7490d818433106cbc479d18a.nq.gz
│   ├── 3197b3c8cc5cbbb6147e8e56596b068be30080f5.nq.gz
│   ├── 33993a65121564aee6031cdaef270c89d28f7a30.nq.gz
│   ├── 35ab54639d277f89efbc2370e2911a578ba93796.nq.gz
│   ├── 35c710e4a435e217fd2f912fb27a3f5aedb53fbb.nq.gz
│   ├── 36890a285ff3186b352341a0d40c06d61f159a80.nq.gz
│   ├── 39f910c135117b4bcdc08b5dc2aaaae33eedda6f.nq.gz
│   ├── 3dcaa52c515250c7defa70e211b6b40aa1956688.nq.gz
│   ├── 3e1bdc1e61c9e3fb36896f1ab409522f90bc98e6.nq.gz
│   ├── 3e4946f96efe36540e2443664870f116c0eaee79.nq.gz
│   ├── 425f116c892fe97751fdcefee1a07b8926baabfa.nq.gz
│   ├── 42afabfd2abebf31384ca7797186a27a4b7dbee8.nq.gz
│   ├── 43ad1d08ed035f005faa1acf1a00d82464e1525b.nq.gz
│   ├── 43d40021d2956c3e283e1777d0d703c55d1e284d.nq.gz
│   ├── 43d5826394eab8205618fed42daf38ec908072ae.nq.gz
│   ├── 45de85c4e9488fb615b1abc963143d07cf7e5179.nq.gz
│   ├── 47a7f9fa4aecff6ee0b23706139bd10cf305f64e.nq.gz
│   ├── 481bb434814107eb79d7a30b676d344b0df2f8ce.nq.gz
│   ├── 491a572e257802b48b39c35d1f2baa3ff700596e.nq.gz
│   ├── 4e3e66108c64cd10058dbf3a040eb15a7574ab04.nq.gz
│   ├── 4ed79ec05a68fdef2e3bde8329e01fe9885e5bf7.nq.gz
│   ├── 53bb39ee2c106870295fb4531dd0cf48069fbe29.nq.gz
│   ├── 565020c393184cb97b696e6504cac4d3d8f659a7.nq.gz
│   ├── 5848be3fa45e5068bd03165b0cd94f1fca6388e0.nq.gz
│   ├── 5a140e1b95cdf3c027ec5bb2b254a9e02b3f7e92.nq.gz
│   ├── 5bbb5855335c061df5448a19582209b830ccb21a.nq.gz
│   ├── 5e29f0fb2475d3d338391ef198f1301302dc38a1.nq.gz
│   ├── 5f121e7f2c6e2708ac0a398e850708872d53cd24.nq.gz
│   ├── 638f9501f61ed6988e48d497979bfb6e5cfc0472.nq.gz
│   ├── 64e608ad2661a28dfe6202069c72c130aa23813f.nq.gz
│   ├── 675cd34870c67a62d9d17607989d5d5e0308994c.nq.gz
│   ├── 6a032a4d184fea05ca3b92843c2e7f42e1361e80.nq.gz
│   ├── 7072559f6b103dffc18f9ab37300678909401288.nq.gz
│   ├── 716d0253d6bc63e70a60c2c69caa3e43ddd05055.nq.gz
│   ├── 71f6a800a455fcf52464b946be92c228e45338c3.nq.gz
│   ├── 73ad286fd2dccf81ac91779d2200cf3a9fab8fc6.nq.gz
│   ├── 74e7abd81add2fab65891a278aa506f165c52123.nq.gz
│   ├── 75819a389ea41c89a5d9501435431915d002d4b2.nq.gz
│   ├── 759901803f0ae690760dffec134b5553a84797fb.nq.gz
│   ├── 759afcc356b7bc6a81e0d575e3a4f3f3be2c5b1d.nq.gz
│   ├── 7935654ed06e0bea77f8c4bf2adb103918f275e4.nq.gz
│   ├── 7bad3dfdf5778d19f8195495a6c119649da5de18.nq.gz
│   ├── 7c8b42d81eb5dbe73316c735cff2a2a431d308d9.nq.gz
│   ├── 7ceb2f3c550efdbc82acc26c788a67d0a5c1da32.nq.gz
│   ├── 7cfdedf3fdad094b153d35d66e919ec3cd36e4bc.nq.gz
│   ├── 7d0ab587c851359bc4834a4bf45a031766aeef69.nq.gz
│   ├── 7dffa0d0dbd2800888075ca46e17d820e5739d5e.nq.gz
│   ├── 7e3c456910633512546fb9c3cd288688dabd7807.nq.gz
│   ├── 7ee7bf2dea6ea2ffd15bd2c31550c0cf1d4ad693.nq.gz
│   ├── 7f7bbbe573f23ee12a921f8756cfc0dd06b839e7.nq.gz
│   ├── 7ffe92b58c388b0949aa9988839a93b58dd68ca3.nq.gz
│   ├── 8404384c1e0a578660f692177aa83e4832593aa9.nq.gz
│   ├── 85b803a14409433f03bc997026c5a4b68eb4f54a.nq.gz
│   ├── 86550fd94bca01156bc9a99928567c073d90c808.nq.gz
│   ├── 87b48750f0ebca9eedd9ae529ca5c23e486470b2.nq.gz
│   ├── 87bfa39d58be9d6ba5e36b186af18ff740dd62f8.nq.gz
│   ├── 89e6517b2b1d21b184c69dd53c7589320d6e8d4b.nq.gz
│   ├── 8acd587daaa9550867493ca9b0a5437d82e2cfe2.nq.gz
│   ├── 8c0c1e84cb4f763f540b8cff8c44afc008a96101.nq.gz
│   ├── 8c66dd2d6c8e8c72c3acb82affa717bff21b2f52.nq.gz
│   ├── 9168741fbf1b73db4c61bb995544b791f99c3353.nq.gz
│   ├── 91aa7afec313526d15865c597acfb04e58a93819.nq.gz
│   ├── 92c9edb775a470bc68d5802b2cddbd458682f567.nq.gz
│   ├── 92e522f38197ca8d41c763effbc81c8fe63344e2.nq.gz
│   ├── 93bac4f6c9857c785ee7fcf3ea79ec72034064d5.nq.gz
│   ├── 951feb40b2f2a8bf70da1f9ddc21b2639cfbd3f6.nq.gz
│   ├── 9697b0f260682583188111ab2deb9f0cc726f6c4.nq.gz
│   ├── 96a19250a37738957e11f2748613c5c20c9bd244.nq.gz
│   ├── 992ca2cac8a521402eaa62eb60837a5e13c868d8.nq.gz
│   ├── 9b69269066518a7157d4179695e6f36702373c28.nq.gz
│   ├── 9ca71c1a7959e2ea1a6d712321d15405be18cbb3.nq.gz
│   ├── 9d7009ee28b4dc67f8df7500ed55151e635ad893.nq.gz
│   ├── 9d7364aadb8242fddac586044f8ec2a30e2c4d2e.nq.gz
│   ├── 9dbc37cdb70ef6c8dd47ad21b78b52505505fe16.nq.gz
│   ├── 9ee9997b0b4726e57c27b2f7b21462b604ff8a88.nq.gz
│   ├── a119e01770942ccb324925e88ebe5d2f35a1fe9d.nq.gz
│   ├── a15b354594e1f6f1b11a16148e9a127a96563ac5.nq.gz
│   ├── a43bfb8ede9cfabb1b614a20a6506099a0d6ddd2.nq.gz
│   ├── a4ea0a149829d08167b049dffea5decf2a3026c4.nq.gz
│   ├── a768f62d29fb839b7af6fd8549488efdd681b816.nq.gz
│   ├── aa005c944de6cf133debfeeb031f94c97b3b3f96.nq.gz
│   ├── ac0764e98f07f814088d2a944cca2f3e5785d73a.nq.gz
│   ├── af4c59054b27ed61adce9793905016b56db27013.nq.gz
│   ├── b02c5e50de06375da924ffcdccfc5452bb57abd1.nq.gz
│   ├── b262cf4f177ca0c04f79c19b2c095dc8f7ea117e.nq.gz
│   ├── b3d70404db6a679f537bf43156427c8dd7c68256.nq.gz
│   ├── b900f3cad4faa9c12922422e5cb397907dffb179.nq.gz
│   ├── b9a610c698b641605980302edbd97f5216c48f5b.nq.gz
│   ├── bedd4a264cbb21851b5d055d03bac7e029c8cda2.nq.gz
│   ├── bee04f5ea9e371e51ab1220a0f4a112d455002de.nq.gz
│   ├── c1cb9eed7c3291b093d12d6928566545c9813e90.nq.gz
│   ├── c297e638bcb18e9bb8015d859093f2b3558524c0.nq.gz
│   ├── c75bb648647e7c0c2ea4b3dc2c1e9274ba87b653.nq.gz
│   ├── c842653a8c465fe1aaf464d33e0c11c1dd560756.nq.gz
│   ├── ca7d033ac8f3b33ab95e3b36cf3c222723dde9e9.nq.gz
│   ├── cb2ae942cb898caf8efa6c78c0cb8f550258be30.nq.gz
│   ├── cccdd3d517fc5249beaefa600691cf150f2fa3e6.nq.gz
│   ├── ced683a7b7ee71270b27a655f5552c230a36eea6.nq.gz
│   ├── d4b64105e6bdacc23207f4b7746ffceabfd1f728.nq.gz
│   ├── d5e14d80f84870d883c2d2ab27ad9d794feeb094.nq.gz
│   ├── d5f37d46db9aec74b0b6b9449dadbe90c9c5da3a.nq.gz
│   ├── d63bb57765b1455ebdf0117c7d00d8964a166e2a.nq.gz
│   ├── d731dc27fc8f6718cbfb5045124855509f36ecdd.nq.gz
│   ├── d8bbc8c78ee2ea3c7c61889f9212123ea017a892.nq.gz
│   ├── dc72a28c6f3e6d178adfd7c0383b29bd2b57d2e4.nq.gz
│   ├── dda0a4bc5fb99e9ef2b7f97dd799357f96bf9811.nq.gz
│   ├── de74c1f30eeb28d8a9830b38c200ff278ef72b3a.nq.gz
│   ├── deebe05ef7358c56b8e0b98ffc459428badde905.nq.gz
│   ├── e0c21d4e5be4a4d5a790d35800939d30f32ee85e.nq.gz
│   ├── e37a3fcf71d27740bb11707afbfd49b60da77bd6.nq.gz
│   ├── e546e411a023a7fb57591007ecd595b0f16a39f5.nq.gz
│   ├── e5656a0c52d405df343e168eb40c38c8addf170d.nq.gz
│   ├── e6241a10e66e5609c72c13854cae6cf218884d05.nq.gz
│   ├── e95643d6a2ca62258464e83c72f5156dc941c609.nq.gz
│   ├── ea1bc509a546d87b13519114f4a22b456f37fd24.nq.gz
│   ├── ece9e960711d20f393c2be8cdfbbb18434775baa.nq.gz
│   ├── ed0e1c5a266ea418db5b4629bcd1bbd699f99d35.nq.gz
│   ├── edb9c968bdb74aacca020aab0f2d23339bfb0c0e.nq.gz
│   ├── edc9f1ccea7ae1669793376b765d5ad1d585a762.nq.gz
│   ├── efd53b9185889a91c85a8aecce24b28187ccef38.nq.gz
│   ├── f0b124240305728d818d51713a3dcb2bd88c25be.nq.gz
│   ├── f20fa00db3e44831a7c059753628e123d66968f0.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f59903206dd733d9138464ace4f21b4d41f8e5ec.nq.gz
│   ├── f69704b8914a5bb9ba7a39fb3a542b21d72ee16b.nq.gz
│   ├── f6b961fd5a86aa5fbfe90f707c3138408be7c718.nq.gz
│   ├── f75feb2206aa92777a6f84f9cef6ecbe17addf89.nq.gz
│   ├── f88722ea2b8840d09dae02ecf163aae7fb9706a9.nq.gz
│   ├── f94cef44e439dd538d732804fe057ee2e63a4c73.nq.gz
│   ├── fa0f996d2c2a6bdd11f5371de4268c8389d6c720.nq.gz
│   └── fab5a7c24f20ebb0fd93d9d8153d4295fee94775.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 260697336e07cd39afdae1ef257fb8e75621952f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 176 files
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

[tanujnotes/Olauncher](https://github.com/tanujnotes/Olauncher)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
