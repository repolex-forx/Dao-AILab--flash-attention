# Repolex Knowledge Graph of Dao-AILab/flash-attention

RDF knowledge graph data for [Dao-AILab/flash-attention](https://github.com/Dao-AILab/flash-attention), parsed by [repolex](https://repolex.ai).

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
rlex download Dao-AILab/flash-attention
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 965c9212e6be33c821ee9f2b461564c5c91a2503
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 965c9212e6be33c821ee9f2b461564c5c91a2503
│           └── chunk-001.nq.gz
└── blob
    ├── 01589adedb3ab348af47785f9dc451d12481dac1.nq.gz
    ├── 02252ec1cec06b2b06ef99fdeb9e324c1035738d.nq.gz
    ├── 022cdd395768e2d029927bbd954020ab698247a2.nq.gz
    ├── 02b50b98b8d1a31492b772683c5a4b566e65921f.nq.gz
    ├── 02ca85ad672277db5e85b827effb8a4737d08201.nq.gz
    ├── 030328544962f40db3f965a18dc24e8c9f000f57.nq.gz
    ├── 03364aa1af55795a2b92efec04e46037b72c5761.nq.gz
    ├── 039c9180226c1f504b43ce559ad6bd9cbdcc8cf9.nq.gz
    ├── 0401866388d114b31a8dcad045f0bda9e334c14e.nq.gz
    ├── 04630753e5643f01281d0310b0766f0b28c8e47c.nq.gz
    ├── 055276878107052a2bd2810e5a0b07182ef1cd58.nq.gz
    ├── 05562f8e8bcdb58e947c6f402a49eacd2d031871.nq.gz
    ├── 055e75b667079d690f0ac22c6df9e9bb3e0b3a83.nq.gz
    ├── 058d9fa099b39000759c8ba938835da22c445860.nq.gz
    ├── 05a0baf18b6a0dd2fbe6bfc08e104d1bb5811f7c.nq.gz
    ├── 05d11e2e2583660775720695fe88e21650d38d4d.nq.gz
    ├── 05ee14f43fe13c88f672bd0e79a24802777b876b.nq.gz
    ├── 068348d61290e3839dd082b540d898578ba1e8e2.nq.gz
    ├── 06c0e608a3e48ec7fad2081bc6ff82425ea1c56a.nq.gz
    ├── 06ce6453d103c92c2c141dcd780f2c1aca756f7c.nq.gz
    ├── 07290deebd6dd368fefefbcfaca4a31b3a6b041f.nq.gz
    ├── 073b6135def83045e18cc1ce5169c98dfcb9c74b.nq.gz
    ├── 0841307209230557940e4a27d36afaed02865df3.nq.gz
    ├── 084dd5f4b8ee7c0c688f60409c644022e6c00a81.nq.gz
    ├── 0904631968411eb227d729a328a36fa4ec97cf02.nq.gz
    ├── 09b2aebd54031b6e080638cbed3605d0ef3fe83e.nq.gz
    ├── 09f724631c0f4a38e4fa42517a2ba0a7f650cc9c.nq.gz
    ├── 0a1ea1a938f6ebfad588cf2ea91bbb0c9b138e9c.nq.gz
    ├── 0a397f4acf2ab3a1c69aaf643b00d5ec9f65c1dd.nq.gz
    ├── 0b1077a4d637b41d854badee5970cb2a52b2abdf.nq.gz
    ├── 0b6430abc2ff56903f969d6f53ef88e0ff0604c9.nq.gz
    ├── 0c25c088494d52f3b68251235d29c23a46ffc430.nq.gz
    ├── 0df3cb0fdc49e14c5205e8f977b2a13f258a8f8f.nq.gz
    ├── 10697f012d82724bfce5db1c36d420b30bf28cea.nq.gz
    ├── 10d86e5e99c4cd379f94fba6127355a1b5204c04.nq.gz
    ├── 10f72182fa97128ff83db68d029ae4a2cbdce2d5.nq.gz
    ├── 117121414197181eb850e2b73abd3c26ffd5c4f7.nq.gz
    ├── 11a15718234641bfcc8549009fa5f3a4ff8087f2.nq.gz
    ├── 12851474031205db74385d6fbaaf097b6cbf548b.nq.gz
    ├── 129c05ff53f5c7b7dcc79b949d7d97da0c0f5d16.nq.gz
    ├── 1335fad7f2b66c58822bc8be52134aabdc0099e1.nq.gz
    ├── 146a7bc3430bccee015f6e3dbc120e7e6064fac5.nq.gz
    ├── 14941715b4baec8f55a7b762198155e0a6cf817c.nq.gz
    ├── 160bf4306840bb55e72bfcc5ae6d10c99356e595.nq.gz
    ├── 1650671e059ec358f8109c1d592694458e77d489.nq.gz
    ├── 1660b9214f2f9f5b6b679f66dd79a4b96695e4b3.nq.gz
    ├── 16927295b8203e797f17bdbd5998677072b64e0f.nq.gz
    ├── 16debf27799fb8f35873208b60a77e0e39a6b596.nq.gz
    ├── 170cdb5cb8c6e6795aa75db821c8d22a01079c67.nq.gz
    ├── 178453d3045bfefd95018320d357ea8662018782.nq.gz
    ├── 187e21dad03ab588f8a7709f16768bac3582b70c.nq.gz
    ├── 18a5603cf1f51f5c97469ba94cf3adb872c90e7c.nq.gz
    ├── 1b5a415b73f236f3e05fb14b9141959559e18526.nq.gz
    ├── 1d2964bd5e25ab14a124afcdff3776f17ee137d8.nq.gz
    ├── 1d810c015edf03aab54db03c1c162c92c2ce679d.nq.gz
    ├── 1db3f1e6d803ed909f727a05ca81fc7e74c3b5af.nq.gz
    ├── 1e230ab084bf830cbabc4076526355e63452f7fb.nq.gz
    ├── 1e570e21b86ff1dfcc71540867b032c5d2b755a9.nq.gz
    ├── 1e8f6af71bdabf35553d2e7c972f84e73c09e7b5.nq.gz
    ├── 1ff58cbc2889a2c06c51df560d2b35ca4e079201.nq.gz
    ├── 20636fa5d2e7ee4fb057d0b7c2637e45ee3b353d.nq.gz
    ├── 2104b5385e83118d468e6ccbe5673c356efbc0bf.nq.gz
    ├── 22410d31209dcd5118fdf4a3408240000d904b97.nq.gz
    ├── 22c2f7b1ff49186e23d2ed2de73bfc31e6e7b2cc.nq.gz
    ├── 230059eab3468082b8023468bad52f1bdfa76267.nq.gz
    ├── 234944d4d6907fb3e1b0c2c3c315a2bee29d7775.nq.gz
    ├── 2349cc59fa2a2057c58674d92fc7bb219c23007d.nq.gz
    ├── 23584d3098a245bcb2b09653bdf0f426eb63bde2.nq.gz
    ├── 23baae61731cdddf816e8089f3ad454cb49ca80c.nq.gz
    ├── 2400132764dde5e7752a542984e4fea976e84350.nq.gz
    ├── 24a0b50486d3a579a15dd1b14e7aa45f3747aa88.nq.gz
    ├── 25bb8691dc9f6a95297301efbd91567a5c22d1c2.nq.gz
    ├── 25c96174c79bf203dea2bb301dd4ebbdbd5a6457.nq.gz
    ├── 267db86e2da2fbfc1070a480ac7de9cd9d034a55.nq.gz
    ├── 26d25fc1909b3be0251f7b7f4d4a8fa1e867aa9c.nq.gz
    ├── 284eeba18235c2acf4b6eccce2f670ea19e27495.nq.gz
    ├── 28819a690a3b4341557d994ecd4021d9be0bd81e.nq.gz
    ├── 295e12062320be819dd835de4a866607650431b2.nq.gz
    ├── 2aac1970b1b0322f086e01df74f7d5875c202479.nq.gz
    ├── 2b22d8e2cc560e8446063e406fd6540fc688292c.nq.gz
    ├── 2b3ba3145b0e8bdb40acb30db4e6d86354afc0fb.nq.gz
    ├── 2b472118f0a0025917edc4c706492ca5dc8fa205.nq.gz
    ├── 2d504315825da06c5b06cdf2c79d0f8dfb32d758.nq.gz
    ├── 2e06c89a8c7c9ce1fca71611da21abb7e9b23113.nq.gz
    ├── 2f4ceaaed53398201d5666028a9e0015e14426bf.nq.gz
    ├── 30390838d3901f1d95db65d5adfb263f4c9a6c30.nq.gz
    ├── 31f06f24cfc874669287906f823162c37351bd1e.nq.gz
    ├── 327decbd86fff635e83ce45bfc7f2f088ab3c257.nq.gz
    ├── 329d71b317a6cf93ac7d0cc24320c8e7e8e2e8ec.nq.gz
    ├── 33587d09413dbab5edccfa3806fca829a6f9f9da.nq.gz
    ├── 357b64e83b67bf763b32e969505ef9686dc85291.nq.gz
    ├── 365017c256d027bc48a01077db434a17c0bed18c.nq.gz
    ├── 381837e60874e44aa5e0efccb8749b2ff41ac3fa.nq.gz
    ├── 385c99c460a8bc2f099895a2b66e362a69c2d8ba.nq.gz
    ├── 38f3fbd406db8989f4a9806e64075bf52444c529.nq.gz
    ├── 39c774e6f7797bd9158a813af1c09e8829076bad.nq.gz
    ├── 3a2920a90accd3207ed114ba5af117bf5ca21191.nq.gz
    ├── 3a408ceacbd6ffa11d6a4502d83f6f397407c1d1.nq.gz
    ├── 3a45776537f1ba7ad56b7bf873d413bbdf0caa10.nq.gz
    ├── 3ab2b3f0aec84e7ca2a94f6e3ccf34f1fb76fac9.nq.gz
    ├── 3be45956bb4febcea1ec0d835da3c774664608fa.nq.gz
    ├── 3c9544407298d1e839b0c7851cc2cce4a0f01cc3.nq.gz
    ├── 3c99cb6b5a007154f2f18071b5c67e0a63b2c149.nq.gz
    ├── 3cc915c8caad8eb82651db56d2d67e12239d3f30.nq.gz
    ├── 3dba049adc7820fe47b84d7eaeb660e5d0254cdb.nq.gz
    ├── 3dc7569cbdb614083dcfddce077116b7d410e32b.nq.gz
    ├── 3e608e9f71e099c58ec93666333e620430514fb3.nq.gz
    ├── 3e85a0a212cb831a62363dac16f5016f27271934.nq.gz
    ├── 3ed9694908c466b3bd153418a672347359deb640.nq.gz
    ├── 3f25fad5f0e331d583ab47f5d266038ca8a9d3c4.nq.gz
    ├── 3f4d858ff572ef21225c2a41bf41b3891806a37b.nq.gz
    ├── 3f67b8199c641a95a36ed2b4ce5c28be634b192b.nq.gz
    ├── 3fab436bd853ef7f22b2a50a87963ccd1add00ad.nq.gz
    ├── 401e817bdd38274fcb20c722ce208e64ca41ad36.nq.gz
    ├── 403d13944d1b884890d8d37c45f946f8d89848e6.nq.gz
    ├── 409b745fd4e2fced832866d10399adf0c9fd7157.nq.gz
    ├── 414bca23c93bd1a392237ec5a9c33daa8a540044.nq.gz
    ├── 41b4b01086a1aa809e485d5efe094cabd7d884fa.nq.gz
    ├── 42740f0228b3e6295901bc3f99495817e1dd613b.nq.gz
    ├── 429f8720945b77514e1e6e2da389bf5880fe38b0.nq.gz
    ├── 42a8481b787abf1dc767e85118fe8a8951955da6.nq.gz
    ├── 42cd60716a4654f469aa7d6384098bc1068f381c.nq.gz
    ├── 43567a52ecfb05152c46583b38c9155ebb496fc3.nq.gz
    ├── 435cf0501a3c4b24efd35d72fbcabcaf19748589.nq.gz
    ├── 436c264dc2acd534a333e0bc4b28f93139d8ec7c.nq.gz
    ├── 43b88c1a1b6a36e5093133ffb4016a7c48b49931.nq.gz
    ├── 44b7693ed764e384bc4e701e28da81174806c559.nq.gz
    ├── 45302fd4d3cb01b804ec5d5b99c86d24379b5366.nq.gz
    ├── 4602fd7414d251e40f9d42250c23cc974d596661.nq.gz
    ├── 469ed4b6c7691c581bbd1db5b8587de860afcb16.nq.gz
    ├── 47463a7151cbfdcbe3a59f4c009fc249886a38aa.nq.gz
    ├── 479725e3528c220596c69683061082abc9dd7bcc.nq.gz
    ├── 47b3817cd281d772e7366347682e97e4cb4cd861.nq.gz
    ├── 47da39e250092678fd1d00b53636040038d4765e.nq.gz
    ├── 48f6eaf0fe713439881f05f6303c5054fb79f73b.nq.gz
    ├── 496d8322523ea37b35c8ade0a5ff855968daca64.nq.gz
    ├── 4a927c6322bbd6c06fd035c0225937263b723535.nq.gz
    ├── 4ba478b01fbdbc2ff5aab0a15fb698eba369f61a.nq.gz
    ├── 4ca103566d673d97f7a1324eecb6795105ced521.nq.gz
    ├── 4cc99335b7f5c8bf8d4114becfe19df9450e3c29.nq.gz
    ├── 4d3c553e296a5cc9fbaec634a7916af400fa9130.nq.gz
    ├── 4e00f3f00406c44b4feb44fd4564abc3692df36b.nq.gz
    ├── 4f7a387a746616921f8ce1dbf67e8f82f26c78fc.nq.gz
    ├── 4fb8f71d01e8faf7648ac1988dd4f908870f25b5.nq.gz
    ├── 4fc4831cf58d6f188cb21a9b3ca9824d276d49a5.nq.gz
    ├── 50cc9b51d3e2da1ab843a5e0db4f2b086969306a.nq.gz
    ├── 50d2d7a89086ffc029e70af6ab4b9c5729394857.nq.gz
    ├── 51faa8c166c3edd38f78b431e541e2503d1de9ef.nq.gz
    ├── 5205f4542ec426bcc1c8a19e423c1f81a875e8b6.nq.gz
    ├── 52aef6f388836375167f8e2087ecc5124e4ed049.nq.gz
    ├── 544065d1de063814ab362ff61c743da414ccbcc2.nq.gz
    ├── 549eab11aa3c770bea97bda727495f3e141ec24b.nq.gz
    ├── 54d3ed393ab66f6884efd70ab10936322b44edfe.nq.gz
    ├── 54d720efeb32b028401a6d619213ce6f31aec598.nq.gz
    ├── 5547238b34892248ac2e2b2c464556136e304468.nq.gz
    ├── 56ab6760d68cea3655273af8dc5ba42a571ddf25.nq.gz
    ├── 57a06bd6e66002cf7f91736cfab6c7f0505c08dc.nq.gz
    ├── 57ffd57dd9dc3971536e8c98750352a195dc472e.nq.gz
    ├── 5860e4b33f3d9d85fc636137c559331d51783a5b.nq.gz
    ├── 58e212134d7042abfd2e8abad223f68eb2e47fed.nq.gz
    ├── 5914c9964973d4ccb0ebcf3785ee2e52825caf2b.nq.gz
    ├── 593bba5280a61c75520dd84f2ae616c2126fb43f.nq.gz
    ├── 5ad47c94fdff599dde62574d1c535c4bbacae551.nq.gz
    ├── 5b8a9b9e486b0866359c0a9064f7b4a5f50f7ebd.nq.gz
    ├── 5c04d08085fea0baeb5d653ce9afdded5a3c5c66.nq.gz
    ├── 5c28123f158fa026110c6592439f216772f82353.nq.gz
    ├── 5c8877a756dd56a03ffaa3ce9dec728a8a65f752.nq.gz
    ├── 5d20be6d2a7428fc95b7be228cd50b46b9f2eb9b.nq.gz
    ├── 5db64d3d7b184f6ffb01ae0e1a26e0acec3bbe3d.nq.gz
    ├── 5e63a15515fad74539074fe8781f4a63f0bc1742.nq.gz
    ├── 5f1c298c4c409464d70fb1a30eedf54102b9b460.nq.gz
    ├── 5f4b207c53e4cec0edf0d50166fe2fd8c1a5d120.nq.gz
    ├── 60be8139c7eabb53e94c3ee64cff8c7339774a61.nq.gz
    ├── 6118dfa2283adb16504b0cbd9f0a69adb5bf7fda.nq.gz
    ├── 61cb0af2aab26a733af5a057394a811f9e333418.nq.gz
    ├── 62b05332c2e0b417b5ad331cc9eec52dde4dd6ee.nq.gz
    ├── 62c3fef3e3dbe5399bc3a310f55b283c61f251f3.nq.gz
    ├── 6316f81e7b9cec8b08f58981cc5f5d279b958eea.nq.gz
    ├── 63189cd5d65adba3eb303d8db8757243ced1d0a3.nq.gz
    ├── 636cd559976767adaa2a445f8983fabf2e3c1acf.nq.gz
    ├── 64f99c05a3224317360ece6215e24a6297709602.nq.gz
    ├── 657820f28547f075a26085c447b6f79aa7a43ace.nq.gz
    ├── 6594d56012392b19ae445d2f6e72501f81a5b837.nq.gz
    ├── 66080985f943e6900d3c55c09a919c433f1784be.nq.gz
    ├── 6652824d0752d4247e407256e7c5ea4fded56c4a.nq.gz
    ├── 67527809e2b9cf39df172b3e1e43d7944173e486.nq.gz
    ├── 67935a6e20ad25cf68679f6f046b9872d95fc7d7.nq.gz
    ├── 67cb5b41707ee928bb54b71962c04f3255fb094d.nq.gz
    ├── 67fa677ac5f47c1b8db0334a49844c6235fa8de4.nq.gz
    ├── 6848e8c9dbde4b5469db19d87290260c187f07be.nq.gz
    ├── 684c9737828ce5ce4465d1191b577dca7760f897.nq.gz
    ├── 686a765f0a60a7ae1569d73baac3e1ab029a7688.nq.gz
    ├── 68dbe702271a106394a4c059d568d7c59fff3e2c.nq.gz
    ├── 6a7fc29dddaae4145b4d6e8f760032871e0e1c60.nq.gz
    ├── 6a90f01b86a5e22f9bbef3f5ec7b5d692e1450df.nq.gz
    ├── 6b4033d134e4093fe278f7b3f8c7d3128ce9f36d.nq.gz
    ├── 6b73ff90dcebf8b8f4743391f0b26de9356bdaae.nq.gz
    └── 6bba953fc69863996ae757310c10b1c5b39354b7.nq.gz

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

[Dao-AILab/flash-attention](https://github.com/Dao-AILab/flash-attention)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
