# Repolex Knowledge Graph of huggingface/tokenizers

RDF knowledge graph data for [huggingface/tokenizers](https://github.com/huggingface/tokenizers), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/tokenizers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 524818fd09524cb4330322a7b9d22db8a9352362
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 524818fd09524cb4330322a7b9d22db8a9352362.nq.gz
│   └── repolex
│       └── 524818fd09524cb4330322a7b9d22db8a9352362
│           └── chunk-001.nq.gz
└── blob
    ├── 012387859c28fac80c09a32e8460d6dcdd654396.nq.gz
    ├── 0218f8e56ddd6d2024c0ee3db15dbd5415ab1881.nq.gz
    ├── 0278bd6996f7928528b5ef86df3459d023db8a3a.nq.gz
    ├── 0286c84240979fb730f4acdcf1d6aa2d49779962.nq.gz
    ├── 029691d6b269a582f92ee3dbc7c0682459751b4f.nq.gz
    ├── 02e617063fd62ff525f5be2b41ab609031b37448.nq.gz
    ├── 0308dfb781b80bc2c02c1a9617ffa8f2ed8f0c80.nq.gz
    ├── 031e5f0c940fb64280ef01fa688f990f527304db.nq.gz
    ├── 04d40b4d7e9dcf196e0c637cf5dd3947fac47657.nq.gz
    ├── 0693ad1e1dd3277f3fe2ea021d30609f00872638.nq.gz
    ├── 06d124037b6d932615fa0d31b02f8ac82ac0b5fc.nq.gz
    ├── 07dec09048732bb1d5b9d4c944433516a8560cc7.nq.gz
    ├── 08cbb6bf4f7d3bb82853d56cacb2b7c766951d05.nq.gz
    ├── 09b2fc6e187d8e697022a9a29d9c483c45695dad.nq.gz
    ├── 09c2d8397a63ca5def14eb00ece7b1bcf2795eee.nq.gz
    ├── 09e5b9475a3313ac70161ace2f11542b6c58c3fa.nq.gz
    ├── 0a7aca8a0b1ad063dd55701243947db7e22ee58b.nq.gz
    ├── 0a9fbaec018089f13c1277f8b1fd424c47226775.nq.gz
    ├── 0b0cf8c46992e014074b487c110c63d7a51c0b17.nq.gz
    ├── 0b65eba736b128e802b40c92664566398da59b42.nq.gz
    ├── 0ba7d6025b2302ad7cc6f125defea8efc770f065.nq.gz
    ├── 0c2b4c3ff5990c7efc6415062443bf00a81ba3c7.nq.gz
    ├── 0c7bafe427665f861db36e288c1958493ba73988.nq.gz
    ├── 0d18a9a058bfcb09ba8c3c7078d957e7a33f8512.nq.gz
    ├── 0d497e6a55c089e5ee8c8b04f4f65b5cd03c3763.nq.gz
    ├── 0d9dfbb1f1167fe577a31f61e2a81ec60e2073ca.nq.gz
    ├── 0e0fff136447896fd6bf566f70252a64c19a925d.nq.gz
    ├── 0e2a9023b67b72ec9ca2a2b55652b4dfb566b088.nq.gz
    ├── 0e63021af7f6a10734d3ee7196a583d2174c93c9.nq.gz
    ├── 0e75fe557ab4162b9d24a84325219f5794448800.nq.gz
    ├── 0e947494425521bacbf12fc1dde832c68e3fdf64.nq.gz
    ├── 0ec7f9f5930ee3efe438c03e5b0674a6b3decb9b.nq.gz
    ├── 0f51565d63a2510bfb2b41b1456f59a4abbc86ec.nq.gz
    ├── 11069edd79019f7dafbe3138841cf289209270dd.nq.gz
    ├── 11a0685650e0eef5f0a41cfef6d9238ef1d15960.nq.gz
    ├── 1215e6fedd007c0309f5fafd86d93d7c0b19a7df.nq.gz
    ├── 121af3d99f1cb09aff30ff15eb5c01b0226dbc94.nq.gz
    ├── 1269488f7fb1f4b56a8c0e5eb48cecbfadfa9219.nq.gz
    ├── 130a537ba65676c7847a2f724ff287212f90e0ce.nq.gz
    ├── 1316c745bf345e04075c7a3f07cbc4ac319aaeb4.nq.gz
    ├── 131b6d5e05afefb9712aba688adc71026d602532.nq.gz
    ├── 1353e6eb9fd0e41637c98ea5536c5f1a0466dc89.nq.gz
    ├── 14af9fbe459e849d24dafc61c6419213ef0d503b.nq.gz
    ├── 14f452cd80a9b764011ef9883273850de3c7e35d.nq.gz
    ├── 1547c7fe675310cca29cb6c51e763a06f9da79f8.nq.gz
    ├── 15a16f1e268daac5f70292bebe9cfac5243612d9.nq.gz
    ├── 16788dec08e5c2d9af41dc5568a0460c2e98f3cd.nq.gz
    ├── 17550e907487bee6efc148609e98b77cfe48c6d4.nq.gz
    ├── 181e1d58eb02362e28c3571b8c70baef1258fcdc.nq.gz
    ├── 1861e727f6c036d5c6821cc456c440c2a9261e34.nq.gz
    ├── 18dc0dcb711736a8270bb70ce244b8073be3230e.nq.gz
    ├── 19404f99ce29acdac05be874538ecde3e2d2ec4f.nq.gz
    ├── 19f5ff314dd8a1de12e624b098a072164787f955.nq.gz
    ├── 1a6d019b9ed3575d12da25e5314d8c9624402b96.nq.gz
    ├── 1adcc2be4c5c191c951f4abf0ad4363f239b6df6.nq.gz
    ├── 1ba054f5d1c324d8bf10f67fcb0e427af89b3d67.nq.gz
    ├── 1ee3aa06513708c9ed24b4927ec09ab9b0c63d9e.nq.gz
    ├── 1f34e3ca8a4f8b3ed454e09d828918881232ef90.nq.gz
    ├── 1f5e16a4a73d4d1c81dffe8c5fd13771544966e3.nq.gz
    ├── 2057d763e22e1cbfb2e8a877af00fa266c91cd24.nq.gz
    ├── 2095a71950548eca285d9154fc6f3a57a6619d1e.nq.gz
    ├── 20da245e6865b6c072baf3eacf5ec71384783ee6.nq.gz
    ├── 22f94c50b7cf63f0b38231ab1ecec88141a678fd.nq.gz
    ├── 242d339f85ac48c9c7d84830cc4e808d5810fa21.nq.gz
    ├── 24727b9ae771c54b13fc3d791003889480716bfc.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 262fa596c759cf21e480e2212d79d6ec8d6d97f5.nq.gz
    ├── 2798638d4a743445ffbb8273f94dbaf35a0b8a53.nq.gz
    ├── 27a10f007d83540aa334ab201e3f2dfa9a223643.nq.gz
    ├── 2840d2e0763c74fa2f671fed7cb392b16b5bc424.nq.gz
    ├── 29ca5977d389d6ff4788fe263d65957e9c4e55fa.nq.gz
    ├── 2b6b54eb61f15ad6432734fedbff2f2e7f7dce46.nq.gz
    ├── 2bb8f014186718b773a7ffd7c3494b711d8e94ce.nq.gz
    ├── 2bf5ad0447d3370461c6f32a0a5bc8a3177376aa.nq.gz
    ├── 2c0b370954a5fedc9bbae6a6d5c764e500c66cc5.nq.gz
    ├── 2e6631909a671e74db99044a7a1dad512df82207.nq.gz
    ├── 2f42973da23a334d89fccb85bbbad6603488b03c.nq.gz
    ├── 2f4588aa80507599435ae5a91f8b66748fa608fb.nq.gz
    ├── 3036f35d395796057b64d33b34b2380f84db329c.nq.gz
    ├── 307fed28e4ee4fac111f0369e662039ed1d8a72b.nq.gz
    ├── 30b82245d4596ab95180b0c0563fbf701d772312.nq.gz
    ├── 3178a8fd583fea0b4d532d86170d10b835aaa36e.nq.gz
    ├── 3482ffee097ff28bc5885aec13b996fd16708a6c.nq.gz
    ├── 34a6f47f8179c86d016e8dc58c29e7fde7d0f38a.nq.gz
    ├── 357c096acbc86246b2044079d938e861c19cc8e0.nq.gz
    ├── 3600deec5c7d2e8fe0cb94701245eae24fee2cc6.nq.gz
    ├── 37005eca66b087c47b036b58af73ab8238014943.nq.gz
    ├── 37127d5acfd0d6b1d9a66d3e00a959ad40380a36.nq.gz
    ├── 37d414d07450950fffe218e2f1cafa9afcf1885d.nq.gz
    ├── 3801b704cc8b83ee419b44b160b4d2105f4e52f8.nq.gz
    ├── 39440f04ac21d27271118945c724b5d821bdf4db.nq.gz
    ├── 39538c60e0c4e08efb95868de7ea49acb8561b5e.nq.gz
    ├── 39585a304ab5c4e762ba81f5b44e05ad1ad727f7.nq.gz
    ├── 399a57f3aebd586ae35c3ab581e8c57fcf3b2212.nq.gz
    ├── 39c2c85dd686aa53bebf07c4370ce5df6b809ca8.nq.gz
    ├── 3a48a7ff5fbeb773036a295063948c5de71268eb.nq.gz
    ├── 3ad62ef3f034672d3688a85090c004cf50cb90b9.nq.gz
    ├── 3af9a8d60da71ba17ffdf2681b2c46fa56187b66.nq.gz
    ├── 3e8599aa239e04f0a9f8dfa5e1adbe98882dfba3.nq.gz
    ├── 3f739e2fe337bb66d94cb79ece95b07a1c0df02f.nq.gz
    ├── 3fe924956d1046698728de65b7e219b0a4f8fb9f.nq.gz
    ├── 406a6a4d3e05de456a888e189996b7b62b2ed922.nq.gz
    ├── 4141268d82e399bca2845590431ca3653aa7ea15.nq.gz
    ├── 4159365f8fc70e1daf1f4286a5e4980a959f1728.nq.gz
    ├── 42c3fcede1280b7c8034bcbc11aa06d64b634c83.nq.gz
    ├── 42dd6e0fd202503117ea2af4bb46a482c54d3642.nq.gz
    ├── 435498930b2720730036900eb8d9661432101abc.nq.gz
    ├── 44ee426d3f04a624a95f44f0dc7010891f76ebdc.nq.gz
    ├── 44f93821ee80e78a1a8d9aa92b319d29ea01240c.nq.gz
    ├── 4510370d88e2be64172e59319b2f916520baf58f.nq.gz
    ├── 46038770f9d0ec4368b4ef83c1482181921ee896.nq.gz
    ├── 4709834166d2a8b45c4ddb1522003a6b26e6b924.nq.gz
    ├── 4738d5fa60d1a15838580686b0034c4ab6ca68a7.nq.gz
    ├── 4795848f794fc2acc6b55f38dfb580fc5f56636b.nq.gz
    ├── 48277f0d272cd24b12c541ae88f6c821440facaf.nq.gz
    ├── 484df6c95eded9771effcc078230c2233fd53951.nq.gz
    ├── 486f5a568025f1aa42cbbdecad889c21ccb66970.nq.gz
    ├── 495ae53a76a8301ed16b2454b93faab6ccef78d4.nq.gz
    ├── 4afdcb0adc94b4a6a29e9d28ce25357f4490932b.nq.gz
    ├── 4b3bfb57e74b25dbb421dcab6c7e7836ed7479ac.nq.gz
    ├── 4c74060faecd2d983373db5fa4c9f4bcec18402c.nq.gz
    ├── 4e301317e55e8c768204d3f494112f9f7a237bb1.nq.gz
    ├── 4e318c259910c5c8817d06d4c6367e12e3c3d503.nq.gz
    ├── 502b4239b49d6ec5deadde1785dbd7799f1b59cd.nq.gz
    ├── 51e7b6ca0bf863e5b9a8bb83b7f8c8c31c628342.nq.gz
    ├── 52d523dffb35ea8867010118f4b3acade52e2a2d.nq.gz
    ├── 54b82357f2a279b65d5f3fd076a2778870150a8b.nq.gz
    ├── 54e24f76a789fb392a77ca3a0df864589c5f7a0c.nq.gz
    ├── 54fa9053d5acaaa3ba1d3f7ab687ec4899916fbe.nq.gz
    ├── 561f1adfa2163d999e9e364de7a210d6ccc08851.nq.gz
    ├── 56c8af8414b7c27b09e6041928deacf83d67160a.nq.gz
    ├── 579575d3fff9cd5a88bf18a9f8b4d220ecc80321.nq.gz
    ├── 57e0783c8371114675dd3b2c22829f9e47cb1031.nq.gz
    ├── 5973216a96e434ee7169cf01f1ae52641f321f72.nq.gz
    ├── 5b4c451601d9f1018bf757e9fdbed6cbd749406d.nq.gz
    ├── 5cf4801b08b5d07431cdc5433ca566c9626024d5.nq.gz
    ├── 5e39e253974df54fd284cf44bb1e52afbefecded.nq.gz
    ├── 5e4a1c119748ef0a3473fdabe52a0c977f87cbc9.nq.gz
    ├── 5e6e7eb3a5ef19d91021f40cc4fc9026e9867dd2.nq.gz
    ├── 5f8f1bbeb65dddfad9b4b778b7f2d336832fe5ef.nq.gz
    ├── 60d3908820dd8ec53c2dd2fa00a4f6141ee360d1.nq.gz
    ├── 6175cc2eebeeaec68777b3aa812d280ac3605cf5.nq.gz
    ├── 617d656078201f7e1dc46ba131ee692a4143a817.nq.gz
    ├── 623e5b70558559a6adf96412eefbacae319cc7c2.nq.gz
    ├── 62473138fba99247e5315d0a4d81ba043b271d35.nq.gz
    ├── 627f9d1806931a2e20fd35ef4a2a7f3be989bba9.nq.gz
    ├── 63ca4a29d2bd128b37d91e977be6f1fa04d64d31.nq.gz
    ├── 64ef63ccc29a606e8de857f742a18da3d604828a.nq.gz
    ├── 66c670ad81a44614ecb5c8aea224f8f26eda34a0.nq.gz
    ├── 67503e17fefae4375455fe27d88f4b17542b79f2.nq.gz
    ├── 6767f5d8749a18d698c5fc3ee7b98c9bd1e34e1d.nq.gz
    ├── 679ae609d4e3d43ebbe9863637be52a41ba25244.nq.gz
    ├── 6850acb9ef29665202e8cf9e3442639f0440b8d7.nq.gz
    ├── 687a6619460e768d374855902515d54e52d23a56.nq.gz
    ├── 68ac211aa8032249db6b929ca64f9130c358d40b.nq.gz
    ├── 699d0bbdc2f957dcdd700d931639c40499f7827a.nq.gz
    ├── 6ae9752fed194ebb59fceae32079b4d505cc8730.nq.gz
    ├── 6c1467799403d70f2845287117e12e6de575a7ae.nq.gz
    ├── 6c812f8c7be1023169b026ce7666faa623b77482.nq.gz
    ├── 6f70044ed3c56f1dd52db24756f3efd493831b2f.nq.gz
    ├── 7079daeaeb5aee8e9d6bb461648b22b977fd2b2f.nq.gz
    ├── 720ba4c790550e32e98883e61d9930a2dac09489.nq.gz
    ├── 72801c856eb5155ccf321d63be37bd146aff260d.nq.gz
    ├── 728550d93ffd45581e7a18e53e01f76981b61041.nq.gz
    ├── 74c4f2c76d6fc5b963357d118c49a619c96c2e63.nq.gz
    ├── 74f9c60bf09c85ec371eaa3cb5d5b38ab87dd4a3.nq.gz
    ├── 75e0404587f6192579d5c207e070d07025303c81.nq.gz
    ├── 764d1bb02fda1913d58d5c70cb17b4a22515b3ea.nq.gz
    ├── 76f2cf33cfd2117a7ecf3e5cc3bcc357629a662a.nq.gz
    ├── 783692f34642253e92def56d0fbfeb9635a41a91.nq.gz
    ├── 7934d627e8232aaa8911369d96ee91fe6a550837.nq.gz
    ├── 7965471cbb7dc538fb26a27b3a4e1616f5d01c06.nq.gz
    ├── 7ba1bb09babac30d29434ae28d48cc8281b89c1b.nq.gz
    ├── 7bac5f90af07e8c036ee36bb79556ae8a252ce51.nq.gz
    ├── 7bad97c9b7fb17f8efb884c4257b98e42013b26d.nq.gz
    ├── 7c16cdea318b58007d70edc63558cd9ac398af12.nq.gz
    ├── 7c3168342e9819300e61b378c5075bf52727c689.nq.gz
    ├── 7d341fedbb99158fb0fac56877cbd33c48e613fe.nq.gz
    ├── 7e775892d04a91d645653ea9015954b7985d3147.nq.gz
    ├── 7f4cb9334be67baf9820664b2032c5e574b976bd.nq.gz
    ├── 809caefa424f10fe94cd7debe741cb4d4dc2eaa7.nq.gz
    ├── 80ad8142d2c66524978a40684df58031d4e3560b.nq.gz
    ├── 80b8cc2bba6e1e11dbbb9969bcebae6e2407eb10.nq.gz
    ├── 813dc708318e34f201102aeedd49cc508464b703.nq.gz
    ├── 82458f893b279d877452aa64a4e4ce20aa748071.nq.gz
    ├── 82893ca740fdf826e885460aea5382ba7c73f6c7.nq.gz
    ├── 82a7c76cffd35f8077177b72cab7c0079026f7b7.nq.gz
    ├── 82da6a534222ae8dfa3b3a50200f769a493c7a44.nq.gz
    ├── 83a0e827d19c2e36bce2a30fc00656e4499643ec.nq.gz
    ├── 841f10f902fb8847007594a9e155d821e80077f6.nq.gz
    ├── 866a6f99da51bfc123f491c3165c549265261f2c.nq.gz
    ├── 86e926028313c6463e285bc129de5d4213ed42f4.nq.gz
    ├── 88eae8ca53d828c1f3a6f276545f7de75411de1b.nq.gz
    ├── 89ff8dc067d4751919ee628d59bf76dbd21db693.nq.gz
    ├── 8ac4c58ec6c89a113e95579884553d96e290a059.nq.gz
    ├── 8bbb0539594c40b077bb5f138f96834d78bb6616.nq.gz
    └── 8bdf7ec2a3100f87c2f982fb9410d7db12efd832.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[huggingface/tokenizers](https://github.com/huggingface/tokenizers)

---
*Parsed on 2026-11-24 by [repolex](https://repolex.ai)*
