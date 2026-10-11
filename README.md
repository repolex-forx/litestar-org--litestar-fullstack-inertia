# Repolex Knowledge Graph of litestar-org/litestar-fullstack-inertia

RDF knowledge graph data for [litestar-org/litestar-fullstack-inertia](https://github.com/litestar-org/litestar-fullstack-inertia), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar-fullstack-inertia
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 07938d2d5a82568a1dcfcc2e4280d1694b77029e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 07938d2d5a82568a1dcfcc2e4280d1694b77029e
│           └── chunk-001.nq.gz
└── blob
    ├── 02a2cf088ca70086943a6e8c14b3526a7798aba8.nq.gz
    ├── 02ac5c5f2c0eb823b5fb603e3f4ddfe15f63c6e2.nq.gz
    ├── 02c47f8f97d58e33e21952ca36956a91dfac1a1a.nq.gz
    ├── 04ae63eccb1aa31aad6735ef4ee1faa56dad89a2.nq.gz
    ├── 054b78417cfd4ad05a73aa428dd5a5486ae47e70.nq.gz
    ├── 056ba69236d1d61e20036948d50c9926c34a1a2d.nq.gz
    ├── 05a77e047e86de41d4ea3e9510e169fe1f43e034.nq.gz
    ├── 05dca767999da26012b180281d8e1168521157db.nq.gz
    ├── 06e0733374bf22a06490282f74b81792cd6739ae.nq.gz
    ├── 078e8a1692e130bad0323602c89fbfad37380097.nq.gz
    ├── 07a3844649c78a7e3bd323d791e8ff348de963a5.nq.gz
    ├── 07ff24863f37b5782ce44cd4961256896936ae31.nq.gz
    ├── 0934654aba90e1b2ebf6792069bc1f5592c4a765.nq.gz
    ├── 0a53a4071e6404735785ffe155025ab897b38587.nq.gz
    ├── 0a7c256a643a36b0616ecb6f5e42167455c5ff1d.nq.gz
    ├── 0ad35d127c00b90d8fde8b4635e71d5f7eb5768b.nq.gz
    ├── 0b5389d089968508014ceba6dc4a15ed17b1a894.nq.gz
    ├── 0b9d18b3a2214950356d546d5dc44ab4106b29fb.nq.gz
    ├── 0ba96a88c3912ea07b91f9ed4a4f93ff24c9b25d.nq.gz
    ├── 0c8fa424f2cc74615e8afe05f47c7400f897f0d1.nq.gz
    ├── 0cd9c72ed378951f12aab638fb1c23782e485a53.nq.gz
    ├── 0ceeede6022ac71613a16facd71326498955ba50.nq.gz
    ├── 0d52d51f6b425ef43358ecf4e0262ca7af49f4e0.nq.gz
    ├── 0db9d10421964905ac25a4b21788f55e26488f15.nq.gz
    ├── 0de1ac33023581e14ccaf5c7d59036737dc38556.nq.gz
    ├── 0ea0282506ee4cced6571f0054c6a50eaed4664c.nq.gz
    ├── 0f87bca7586ab404be787cf643c67ce96b6a250b.nq.gz
    ├── 108294bc7818add6fdc273dec1b9e403125dfa74.nq.gz
    ├── 10d0a9c0c1bf3b30f55f2b0744892a0c9a858f26.nq.gz
    ├── 112d97647fc63bb41f0d61114a721956b717a6a9.nq.gz
    ├── 113be1d5c311b799b6b44ceb597c95e18a947336.nq.gz
    ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 12874b7ed4c27666254d22d5ed509c03d9698f71.nq.gz
    ├── 12e116306d427bd9752a171a7a22171e3796ce16.nq.gz
    ├── 132a6212f45672919cb5325519c34da7dd3d6edf.nq.gz
    ├── 141dd63f071d8aa72f9c30c40715dc903e450f47.nq.gz
    ├── 14996a3543e2787465bfe9ebe5bfa3c5cb41aa92.nq.gz
    ├── 14d6fbbaaa70ad204ff9a8b590fcfdc0afb1e6d2.nq.gz
    ├── 155cc7ba04711fa722eae5c53bc28f3a21d4f13a.nq.gz
    ├── 16d02b09430be2a6ff09a0df34dbb32eed3446fb.nq.gz
    ├── 16dbdbad632a7516de54e01b1951c98c3a772de6.nq.gz
    ├── 170cfaebe9a2063cef5490e03e946fbb4a7cd474.nq.gz
    ├── 1738f84a6ca3f439b79d91b7c5e6092e75fe3184.nq.gz
    ├── 181d2c96452b894c14467dfe2da45941be33e9c3.nq.gz
    ├── 187dae4be0a133223a4330d45802dd2e25224155.nq.gz
    ├── 18b5ba2c2a32588553e9f1aea952af3486ec9ae8.nq.gz
    ├── 198860c99df4a45f948b92ef83f72012ff4a7e52.nq.gz
    ├── 1a95827d769ebca2f4c1b73fb34622c8d5303272.nq.gz
    ├── 1ab604b83a208c4961d128ecdc2f73311c42c126.nq.gz
    ├── 1b6047cc21608f1e84193e6bb2d8b3ed91190636.nq.gz
    ├── 1b97a43b8711ba1d9f0a54db7b232656473cc06a.nq.gz
    ├── 1b9b7dcab2901347d3102cf920f0c04c547e8cf2.nq.gz
    ├── 1bb37b6d8d3841a3a93e78fe8258923e7bf7a4bb.nq.gz
    ├── 1bed3bf43cda2ddc4b86415f3d6ccd201b7f5cfd.nq.gz
    ├── 1e9df4fc1d84e2ab11fdc78a13a5159e918e8932.nq.gz
    ├── 1f69322e1f1aa36312ed3c4b5460ce522243637d.nq.gz
    ├── 20889d4161bc48b6db08d18944456aebe9c729aa.nq.gz
    ├── 20928931b1a08415c9c78e1685269f449f06a11c.nq.gz
    ├── 20fa92c514e2cd719630787b5baea7e0310630f0.nq.gz
    ├── 23ae9c604c627f4b772c0831e79c397949d91e7e.nq.gz
    ├── 2437ab055e4a23818206704282e87ab24e4b0c2f.nq.gz
    ├── 245cc82a8094cb5032a2a8620ad976eaf9f76aac.nq.gz
    ├── 24e66ff4b467ec11e286c8348583184188acadab.nq.gz
    ├── 2555af2dc5780e670537b2a92ee79b907d1936c2.nq.gz
    ├── 25b6990eb335a6315beeff7971435a7919c181a7.nq.gz
    ├── 26fb7aeb1e8532a5a50fa31da4e834593852c81e.nq.gz
    ├── 2794bbba99906c1403d623a44bc8c900ce9232e9.nq.gz
    ├── 27f4b49f0a97b7ccf16a74aa6e2df63b8f205593.nq.gz
    ├── 291008656d76a3f8f3511ab6c0ab8c55fce7dbb0.nq.gz
    ├── 29426a52e286117e0a8b8f3e17bc08737868b0d6.nq.gz
    ├── 29b26460a3ca94d2f5bd3b46ec65530e398d9621.nq.gz
    ├── 29f2f71fc77f0b792a66eeaeeec96f83e7703c17.nq.gz
    ├── 2ab13545f93e7be8ad3277c9ae9c0573c71d55a9.nq.gz
    ├── 2b25ad89387f54cf81f8c473db42d168c1a04f0a.nq.gz
    ├── 2b28089f74d407ad55959709e6135181b568fc2f.nq.gz
    ├── 2b645f467e73958bda42c8d71617bbd8f76d0382.nq.gz
    ├── 2bf738922c326374b0cecb9631a338ca694df692.nq.gz
    ├── 2c9bc50f5b4c0ccdad507fd7846b0b4d75de9d2e.nq.gz
    ├── 2d3013cf6a6a597f3b9c7ee7a7489f825c63ea80.nq.gz
    ├── 2e37e037f209f99948a73f1900d129716ee9720e.nq.gz
    ├── 2f06816485f956338a161db9646a55d729c69a25.nq.gz
    ├── 2f7bde4161a6eee37cdaf4b33fe04e5ea5ba9931.nq.gz
    ├── 308c1b3396a97a15a63fdb53c1dda4299498a220.nq.gz
    ├── 30b139c32aeb9472634310423260df05157cc4b6.nq.gz
    ├── 316ed557a9be9a4d8e4cd3fd20cb5672f55cce7b.nq.gz
    ├── 31dfb195e6c616547311e465195986ac770a2f9d.nq.gz
    ├── 32868a40a33184ce9cc45cde096a5ad29dee3e67.nq.gz
    ├── 32b7c707172287fe427bcee0be82842e5d5f92db.nq.gz
    ├── 32f0b4e6ca285385464ef866c3ad88c6114d5e0e.nq.gz
    ├── 331ae19871bb7bf03d40800cdd907b074ceb5df0.nq.gz
    ├── 332e5094ea9d668cda952a109832b0d922cacef0.nq.gz
    ├── 343d25af805226ad39042db4809693db02c2f31a.nq.gz
    ├── 343fac468e2e793a1e1e4fc5fcacb41ddd9d0cdf.nq.gz
    ├── 34ba3c42902dc12bfe36c8bb31c79572fafff645.nq.gz
    ├── 34da8582c1946aef04614826520cc8648c7820e4.nq.gz
    ├── 36226527d49fd3118f1dbcdbd64d380923767a0c.nq.gz
    ├── 3683b1b9c63ec03697a5c6f7f507e40cbef7186d.nq.gz
    ├── 36db51d00f2d5197d469fb13b888ab7aee571f0b.nq.gz
    ├── 36f009e8b40f0d4a5c7f3f6f16954d8456a2b114.nq.gz
    ├── 382197003712ce41d9fc547b0c5e7717151d7eb0.nq.gz
    ├── 3ab6ec8f6d77ae426b4411b2b2024ce242aee363.nq.gz
    ├── 3b0a4238217bbd58d2996bcfcf739675b8b34e8c.nq.gz
    ├── 3b54388cf392a2c46d040574915f8953b3bb76ac.nq.gz
    ├── 3b8d46347416fe4ad3a7ac42e8dc102bb8decdcb.nq.gz
    ├── 3b8d666b2ab74aa2cd84fe662c6aaf0ac5e263d3.nq.gz
    ├── 3d26bab3d1a075a178585304917c7fe41f88d537.nq.gz
    ├── 3d790a955aea7932d34172cd0028c69310e01cd9.nq.gz
    ├── 3dcb764863b129081e5db10c3d86c8d83d244f12.nq.gz
    ├── 3e98da93c20562420fa45656aa8461368bdf4e9a.nq.gz
    ├── 3f3b6876cee4309d99339903e23c0df4865d1c47.nq.gz
    ├── 3f533d24d7785a82b4c0efcd34bd35cc99408493.nq.gz
    ├── 3fe34b512f1314ee62fda3c62d33a07eaf721f39.nq.gz
    ├── 40356ce47a11ba5dfa8688af18e89513c811450a.nq.gz
    ├── 4357563b6b85cc159aa971b31f625c8fa9d8262f.nq.gz
    ├── 45d16ad3f5850f541bd6ecdfaebddb5319f02b19.nq.gz
    ├── 46bd3e79ecf4df96b4520b75fea27ab41876b2e5.nq.gz
    ├── 47254682deb5e2afc87e67e83c229f58821a64fb.nq.gz
    ├── 472c4336b859415d864bbb2b330f525bd0a547c3.nq.gz
    ├── 48144c9d25212144c9a26eb51a3eb28639030a8d.nq.gz
    ├── 4ab109ffe396cc6df0ae2a068904c98ab2c1d4b9.nq.gz
    ├── 4bc2aeb3a42aa1b080332f88a23c8b2cddbdf85a.nq.gz
    ├── 4c0187592943e115861b16e83e12abcebe953f47.nq.gz
    ├── 4c48a9ee115263f475ce2f2700ea4bc7a8d7618f.nq.gz
    ├── 4cd8b8f2efb1a147736fb75352fa9c9d5a560764.nq.gz
    ├── 4cf1c85db710ea012f90aaa0f38a8be39014ea42.nq.gz
    ├── 4e58f77a5603d469b738db232743e40442dbc96d.nq.gz
    ├── 4ed41155c5ba4446c339d8c3bac2311959249828.nq.gz
    ├── 4eec027e62355da6a454d7b8432c49bcdb1fa631.nq.gz
    ├── 506d793c3bb1a6c689235d12ace1e0d28884db6c.nq.gz
    ├── 510e751785c2fb13d772e5fdf5befb70fc6e8ba5.nq.gz
    ├── 5129266f3dc80098feea4da1fc885d357d8d530a.nq.gz
    ├── 517b993384e41b7484159a1cb3f8fda60638c6dd.nq.gz
    ├── 51adb79083b060a57bb1673b9fa1dbcdb6cc1313.nq.gz
    ├── 51d1849d6750594c177d904d194372ebf34b88b4.nq.gz
    ├── 52ead45f64d102992c575f77eaf92688af4d2211.nq.gz
    ├── 532d17268def6e96282e06b29bf413d92bb9bd6a.nq.gz
    ├── 533d62b687ca3ff297ba1a261e2b06f0a4737704.nq.gz
    ├── 552b50f7c8d20dc091b10059771fc1799f6af6b0.nq.gz
    ├── 55bf822df991111924389294c8fd4c6583bd7449.nq.gz
    ├── 55f47c21dd767c56faadf263f276dfea65e70eef.nq.gz
    ├── 57ad06e5b22616eade5d1c64720df3209bc8ba28.nq.gz
    ├── 58f8692297aee85c6a68858b73a976c058b38362.nq.gz
    ├── 5982489146b1f76192dc7c50a06a53e331a07fc4.nq.gz
    ├── 59c4c293e74d95d17f1439907b49c96e2289e51a.nq.gz
    ├── 5a125ae1886f98ad93132625a19edcd943defb27.nq.gz
    ├── 5a5433bf3e2771f1f4944d666c814f428876f9bd.nq.gz
    ├── 5af5444cbefe4b0cf226def0e27b6dcc799119c4.nq.gz
    ├── 5bb33db146a22d0045aff3cf02998fcca49f0411.nq.gz
    ├── 5c10faa7f8f11bea7c846f6cdf06b8d6870dce53.nq.gz
    ├── 5c13b9df2e141b8ce663cb5f76c15d08df444768.nq.gz
    ├── 5c1def0a709fdc802b75c26a35903184d8222cdc.nq.gz
    ├── 5cd3ed99a57970414b710fadb876a8d8b84ec4ad.nq.gz
    ├── 5e405a5ce5eb63def48bfa6e4735352f661c9065.nq.gz
    ├── 5e74cf5a7cea6aff9549de9cb6711fb17c9d0536.nq.gz
    ├── 5f57281fba23a5de1d860d3f9be5b89fc75a943a.nq.gz
    ├── 602715c46cc9b944d59737afee4c42f5a1744aaf.nq.gz
    ├── 60ecea30fefd24a6db916d45941de538c6389fdc.nq.gz
    ├── 61604fda1ee21d4481d7da510af800d0ebbb0169.nq.gz
    ├── 61b5dbbd95eb29b44a1c59a4984add63dfe099cc.nq.gz
    ├── 6357fdaba39981e5d23365bc08eff7567572ad84.nq.gz
    ├── 63a2196e4148c04baf40a784d2af58ea10612563.nq.gz
    ├── 63f060f7e3ffc92d8433891466ea5ffa88e49cc5.nq.gz
    ├── 6426a11a7d88651f7eb61b971ce2b42117287b99.nq.gz
    ├── 643956a51c2e9e3227bdce3c436654acf18fac24.nq.gz
    ├── 643c070c9d290e8b5ab97274e3e84a41698c9855.nq.gz
    ├── 65aac163c7104b2e349427bb03332b284cc9250d.nq.gz
    ├── 665883815f12f27cf6ec54d8cfa4e151ba206219.nq.gz
    ├── 6658cc280217f9233a0dc2f60cc4f526896c7ffb.nq.gz
    ├── 66765d00e1637e62f5bdf8f0c17d6edf88f50880.nq.gz
    ├── 6724e4df588882a9a80231a3c4aca1a50708954a.nq.gz
    ├── 679c8885f18ef8c3e4bf29fd2c225e02046e8e05.nq.gz
    ├── 67bff5cc039b56f179fffc96c58e539ac61b013b.nq.gz
    ├── 67c45976365a70f673c538bf703c4cc84801e4d1.nq.gz
    ├── 684aad83381b817f8f68cea6ab8001b30582e0df.nq.gz
    ├── 689e5216332b8a6d60925c15b1df0081522ee4ea.nq.gz
    ├── 68eb4def3e847857979bfc5079584efd623a1930.nq.gz
    ├── 69060f2310e1fee373a810b8d174008e195cef4e.nq.gz
    ├── 697cd2fc85c53edbfe93f44e676c3fef1bddb212.nq.gz
    ├── 698fc139320f064723e5778e7c2fbab073399884.nq.gz
    ├── 699e09d3186c536c1bf3400c9a049c1524431612.nq.gz
    ├── 69f5d1d222163a39d6df5ac0a704c3235c60d666.nq.gz
    ├── 69f702aeae10fd91af71f7ca19c5c41515387fbe.nq.gz
    ├── 6ac1c18507eceb958fc253f92445829d820c4503.nq.gz
    ├── 6c30d5dd247e036554e65ad42909c4a9ae25a363.nq.gz
    ├── 6c9710da423ecabd4a384694284bfa4c4b0b8ff0.nq.gz
    ├── 6d85a4b656ba894e7b97b10fb50a4fdef3d68df2.nq.gz
    ├── 6dabbb39bbe775f95a4b13f2eeba8011eeb921b0.nq.gz
    ├── 6ddb6ab2b0b16d85c3e2660d77dc08707930a238.nq.gz
    ├── 6f441e86e8d0599f7755b5a07e2729ba72bc7fbb.nq.gz
    ├── 6f9b25751b65e69af8e358456134a8a348062f2d.nq.gz
    ├── 6fb4df380ceb1a8158052eeeeaf59b563b9298fe.nq.gz
    ├── 70b0e6a1e2d2d3a4aa5841890140126831236514.nq.gz
    ├── 7299753a98bc0f629aee0a76b0d26fccac2c6db7.nq.gz
    ├── 7381df15393824a949f2966af94cf12800674d50.nq.gz
    ├── 7400327dbef2c8643da6ef51d4c7e58b4a540577.nq.gz
    ├── 74c152f23c0bc7d2eba1208db2897917078df59d.nq.gz
    └── 754d55bdd1f569b265834a83a7696761db9fd637.nq.gz

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

[litestar-org/litestar-fullstack-inertia](https://github.com/litestar-org/litestar-fullstack-inertia)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
