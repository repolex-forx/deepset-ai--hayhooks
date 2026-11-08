# Repolex Knowledge Graph of deepset-ai/hayhooks

RDF knowledge graph data for [deepset-ai/hayhooks](https://github.com/deepset-ai/hayhooks), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/hayhooks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3c574973d4354df5355753845d7d45066e44d7c3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3c574973d4354df5355753845d7d45066e44d7c3
│           └── chunk-001.nq.gz
└── blob
    ├── 001b0624ce5e54827bd23a7d1899fab47c4840c8.nq.gz
    ├── 00760c229ecfaf9c1ba9f3c31b317c6517cc21bf.nq.gz
    ├── 014927f49de4f65aeb65904121a173ee73c39e13.nq.gz
    ├── 01c12263847f076528f0c88f19217732cb6f1686.nq.gz
    ├── 03e9785536dd9768ea418f173be8b2c9022f5c73.nq.gz
    ├── 04009fee816986de47a4b4df436c79dd38892ad9.nq.gz
    ├── 0421f37495bd9690b935840da7b855fbfbf19495.nq.gz
    ├── 04d40f33789592ce94a4818972873b75874e4ab9.nq.gz
    ├── 067f484b8a112b6829c6f581e31b7472d0489cc1.nq.gz
    ├── 0e4108ffd3cdd28ba83b0d597eacd0c52287e66f.nq.gz
    ├── 0f7d6664cc8ea59ac663eee0101e2ab77328092f.nq.gz
    ├── 10e6f49f5c66c48ee71fa9b329f652bd1f52db3b.nq.gz
    ├── 1173220596f2e43dee8313c2046ae8104c6e6ed8.nq.gz
    ├── 120f8b94c35c9f1fa38cf640b9600f436a0c59e5.nq.gz
    ├── 12520eb8ee9cfac1ab5f62d4fbc7e5bc64a0fb55.nq.gz
    ├── 128e48682918a0cbdbcce6626fde539b13a71dda.nq.gz
    ├── 142932a2f66f1acbc38f3c0d236a7ef6e901e6ad.nq.gz
    ├── 144ab88e9cb50cc93d0e3389748893ba7599e4b3.nq.gz
    ├── 1455990d51da65a9a77c9b41b106e68eb3b0dc28.nq.gz
    ├── 155f978fda7ca29fabb0b6ca03717cfb419418f6.nq.gz
    ├── 182584e94fe85a3780c78aa2150d612e64f3e6b8.nq.gz
    ├── 192d4b838d4e1fb3d33a643b2730fc67b1e118b2.nq.gz
    ├── 1935c9e35a800c29573406edee5e9716845cffbe.nq.gz
    ├── 1c221d5c1a62abc11dda50caed80595699998034.nq.gz
    ├── 1d937ba524bfd0bf9fb29c7271d1d6be65a8dfba.nq.gz
    ├── 1edf6a7e9af9acf8459a6d6f0779492bc168cb36.nq.gz
    ├── 1ee0905ec43b8a0b5c230c1002eed545673b67cb.nq.gz
    ├── 221a3bbc7821b1f5d480a54bbb96d5d564340c7c.nq.gz
    ├── 22d60058096576eae146a82f9281d7d18a2c1ce0.nq.gz
    ├── 24153decbd63a5d2c56f2d5c8322f649497f172d.nq.gz
    ├── 25157a1a2014a3944291c581667d6f34a82b339e.nq.gz
    ├── 251c84c501680dc827885f2512eb77f9b4738e0b.nq.gz
    ├── 255428cd49bc76477ba201a5aa2c5414c15ecfe6.nq.gz
    ├── 255fbaafc318fda3f1bf5785b0a3cfaf9b1b3a3a.nq.gz
    ├── 2588b3a072115ff88df075bc8f594cb401d40cea.nq.gz
    ├── 26190db0aa16582709b2205911a56686dc00fcee.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 262dc23bce133dd634bbc10047d7af93117eebf5.nq.gz
    ├── 27544ef22d8a03e33ca2f8ef2f5009e18370a455.nq.gz
    ├── 29659474e73a333fb2a34d3d5c90a1ccdc50689d.nq.gz
    ├── 2a187529870eb350d4cb5990a6a542a74836fca4.nq.gz
    ├── 2a363f6ed943c60f938342448e31d86303248eba.nq.gz
    ├── 2a546a1a608f4125bc9a83330a88720c741b6055.nq.gz
    ├── 2bef9f99e25df3eef99196829a001d746ee86a31.nq.gz
    ├── 2d0529654d746e59c25d80009c84fea8ff6ecfb7.nq.gz
    ├── 30d20af9707f6267c2b6044ae22b82c0140a45df.nq.gz
    ├── 31301854de3dabac6807f6bda9621afa32c2e6cb.nq.gz
    ├── 3137d4c4c30afb43caefa2abcc868fa86c2eb116.nq.gz
    ├── 31676291b278dec96002e0440698fd5a71b50573.nq.gz
    ├── 32032277405151e7012034e99c0dc7e41e7d286f.nq.gz
    ├── 326be3cee61430ea62b9c2865b1e456a9b667d3b.nq.gz
    ├── 3369e88ae8e27269934ecc2557b33b63f41cbcaa.nq.gz
    ├── 338d796b13cd7fea12c87145989a250f4da4538c.nq.gz
    ├── 33e0389f7255f18a136e358d3343fe16ffa8ff5f.nq.gz
    ├── 34221649a5c6fa9bc955c131ec3dea9a8944ba85.nq.gz
    ├── 343c5ad01b8f00c64258127afb1ab2cebc191a10.nq.gz
    ├── 34f3a73f913cd61fc65c0afe1baddda1a2cac9d7.nq.gz
    ├── 35d72f559d36d7965dbb63c026ba6bcee903e245.nq.gz
    ├── 369c127f0cdd51e4364bb4c8ffe190e1d098c00c.nq.gz
    ├── 39062c7dd9412378ebd4392251b29b384fa9f301.nq.gz
    ├── 399391ce776c24bf66f921c30dfd3046ec9e6a79.nq.gz
    ├── 3a5647838318d6972c298722279d135c2af300a5.nq.gz
    ├── 3c7363097b8bdc6eb9d0169281602078ae78b16d.nq.gz
    ├── 3d90ce937bed270fec5626c17b4d2802232288fa.nq.gz
    ├── 3e6e3ab8a1f255eacf99a3642940d4fcd4d6af57.nq.gz
    ├── 3e93f0e96a50636e3ec466eebd226bbdff100b86.nq.gz
    ├── 3f69893e98129d2a2c473e1146c0fc6c9b77e562.nq.gz
    ├── 3ffc337f8f47735a61d3f3824a6aef4ae03f1d42.nq.gz
    ├── 40039864414c054c9e87e0a2a9c046b561571f24.nq.gz
    ├── 408b862e1712adb20b96465d018cf56a0950277c.nq.gz
    ├── 41f84ded64b9c04ecbe63a311f3845b4bc89737a.nq.gz
    ├── 4209a6f1e9b3c03a5a2932be96a96ab4885eac7f.nq.gz
    ├── 42395a1633d5975747982a59f75a4275fa12592b.nq.gz
    ├── 42eb1476ff0f57cd29e22a7e17c3171e867eb245.nq.gz
    ├── 43fe7ca799ae7a5b608f3e76d1e93b5a32e8e69e.nq.gz
    ├── 445a4be179da62681ee4220a8024c0039d9cef39.nq.gz
    ├── 446854be07c3bf1627a47d0e9c237c13446767a4.nq.gz
    ├── 4592816c255dde80f93bcbe6e5e4e841c0d5b46f.nq.gz
    ├── 459a591196c1d89a523962c011773c722502ca7b.nq.gz
    ├── 45da3f4a4f1271b5e1820638adfcdf4f20f5ae97.nq.gz
    ├── 46918cf5bdd48d1a8253608096fd0929b6ed6be1.nq.gz
    ├── 46bf0267008adb615bb58194d2aef29ab4b1b7e9.nq.gz
    ├── 47242af26b358b6e3ef4e4cff440c0ffe22c90a5.nq.gz
    ├── 474564d1b6b5ef8a11d1f08699c91949a3168f86.nq.gz
    ├── 47702e24bb659f5d640e2e8dc86b30800ea1b1aa.nq.gz
    ├── 484afcf5f4edff89a544f6785639a2ec7da6f275.nq.gz
    ├── 48f514658838a5f706e10a6ebd528b16fd6bac5a.nq.gz
    ├── 4a3defb02284fe493fd0aa313a7e8d924984253a.nq.gz
    ├── 4a5f7c98878880c8f134de9382941f5cbe81f5bf.nq.gz
    ├── 4a69bc318334a3b611f1cfb8da774fcd92e1c3e4.nq.gz
    ├── 4abda4ed0f8a8c40f92d612387b0668eda0f860f.nq.gz
    ├── 4b19b9e2a0f09b9265ca3de634353aea015fd724.nq.gz
    ├── 4c34b32f85c2f4ee6a0223935293313e3bf84699.nq.gz
    ├── 4c65f78ee4c005975a1c84445639ed8a4c3830d8.nq.gz
    ├── 4ded6888ffe406a6d7bf753c73302fd2cb92f55c.nq.gz
    ├── 4f7e0d1bbbd6297a06988c960f4179df402b0689.nq.gz
    ├── 4fbd46292076866e92b4d3a5c28d206a5400523a.nq.gz
    ├── 5074666eae2925c8c15eb2df0d147a6d01757c72.nq.gz
    ├── 5113e7220b38866e9e7b6826588e589df9a801f3.nq.gz
    ├── 52b3192fee08160cf74fa27a1b44243f917d1c50.nq.gz
    ├── 53a0ae2b1a5e1cdde504849fe404157b21c541a0.nq.gz
    ├── 541ad359f2594b0b2565e16ab2e22511044a67ed.nq.gz
    ├── 543e71fe410edddc433e4b8bf784b3254826c3f5.nq.gz
    ├── 546366758e85a173b20d99b74a6fc93397433c6e.nq.gz
    ├── 549d3cf3d129708ce11bb2ebf171c8301fa849cf.nq.gz
    ├── 54d00ebcfbefebe0e73605fd687ab0feba2c7be4.nq.gz
    ├── 56ba4963e0de74cafab72c5b13742c6826b8977b.nq.gz
    ├── 575055f4cf5791d53d9975ae2a8630f861ac3264.nq.gz
    ├── 58aef51d11e5f3557d7e3e15ec336a565ddd0c96.nq.gz
    ├── 5965b548c9b7248a20cc4e402262d32803c7f2cc.nq.gz
    ├── 5a6dcc4220314686e85054b3fffab8a722818902.nq.gz
    ├── 5b21ce404d2146f9139827191d061033fe51164d.nq.gz
    ├── 5bb73b40aa3d038c4ef4f24dfd688718a966bdd3.nq.gz
    ├── 5e409059ab607d330e960b8642876b83bd299b67.nq.gz
    ├── 612e74327ab9b7569de43aceefa97d4c9e4fe477.nq.gz
    ├── 6393dd33900c830d660d5e1598a4b9dcbbf0fc1e.nq.gz
    ├── 6404158189026a380ca6c84590930fa080a24504.nq.gz
    ├── 6462de8fb0afafafbd5c668ceadd6b508bea75d5.nq.gz
    ├── 6480cb1cacf4d8d53e77e689dc38379d2a5fe5b7.nq.gz
    ├── 6542ed95871a6f3bef2c2af72e0e01a05a75f02d.nq.gz
    ├── 673d1f6b43f26d956e59091f401643b5d273a96a.nq.gz
    ├── 676ed569a885fba47bd79e6c84afc57483c658cf.nq.gz
    ├── 68908c679d515f3b3f27f9ab6a6a29d93cc5441d.nq.gz
    ├── 68a343e63a1fd3ecc0ef761dbd751baf4c5633a3.nq.gz
    ├── 69085ea3bb370994ba1ed9744cb7e4fa23916d42.nq.gz
    ├── 6a3a0e4c2a3ffa4edc10e2642afa7454f7a8ba9f.nq.gz
    ├── 6a6c94252c9eb790493c73b83550858e5214764d.nq.gz
    ├── 6c5cf6c28dee2dda9d259ba1c18ecf4b6659087b.nq.gz
    ├── 6d26bf3de0d1890c9b7cc52c0bf90b8aca295333.nq.gz
    ├── 6d666a6a19a885cff30caf2cbb30f30bc3cae5c0.nq.gz
    ├── 6e72780aa994f1b5dcb6f485a09690c9eee2da0f.nq.gz
    ├── 6f14c1bf3c463489e79535bd973199bd57ce082b.nq.gz
    ├── 6f9f0a50b9af1e7ab3c3c506ed529a03bb8623db.nq.gz
    ├── 6fd5f4861bdf5e686b98b2cb28f8315d7ca6f4ff.nq.gz
    ├── 6fd877e74bdd07be7cd1c7ad3568ecc91bf2864f.nq.gz
    ├── 6fe09611eb3ad8ccae509cd5bc045bf1d16fc122.nq.gz
    ├── 70886239bf9af7a27ac97e57eb9722a34b32d93a.nq.gz
    ├── 7149302c898e4f5d783395f621e110eed895ee93.nq.gz
    ├── 71a8983c535320102c0298511122abb86adc0c84.nq.gz
    ├── 71ce0bc3d9460a06d23ed982eef03e1cf334d24a.nq.gz
    ├── 71cf9430943e5807dc9c91d1b3a7e4ebbff472ea.nq.gz
    ├── 72e8c7828432fb00264b8f8ac190461fbdd51ac2.nq.gz
    ├── 73d020e66f5d046926fe5ec3a81c0c796597c58c.nq.gz
    ├── 7592eb2405f27ec80e31fa62226c3c8888a08418.nq.gz
    ├── 760f37920a1e4c9b28c10d9d8bd943f30f8c67df.nq.gz
    ├── 76fac0211adf17c430fe158f99e0fa72c16690c4.nq.gz
    ├── 77a23d2865656ff0afa8cbdfd78354c4e3204d28.nq.gz
    ├── 7847b01c2cdddf45d96250686688211ccfb67a3b.nq.gz
    ├── 7852af64b0db98c18fb3c6a0e5818edb70036573.nq.gz
    ├── 7ae8a233ee4d62f0bcf85ef6a46cd555b2c935a9.nq.gz
    ├── 7b3caf568762dad91b5a547f08b95ac1a0eeeca0.nq.gz
    ├── 7b442176893c091c3f22679c859f87ec29fb6588.nq.gz
    ├── 7b6c8e32f1565a1f288a17761b8de57bc0ed8cd2.nq.gz
    ├── 7bc44ba06855e66ac39b9379175c0096c2e1a949.nq.gz
    ├── 7c0c2d131cf056c98f751d821561bb25c9ede81c.nq.gz
    ├── 7d18ad273ef0936bcb7a2aeb5289c4fc2de09373.nq.gz
    ├── 7d57aefbe0eeb33d28277694762e43483b13a56f.nq.gz
    ├── 7e94fca8afc71ef041c780b7929cec6a18cc6113.nq.gz
    ├── 7fb9400832fd84d27540b1967f8383b971179e04.nq.gz
    ├── 803a86d2025126e8fb29a4c825acc2c285c30cec.nq.gz
    ├── 820ede390d075d9ea80641dc1b08126adf545721.nq.gz
    ├── 82c38f5f8e8ecfd224d53eabc37e17e65b03277a.nq.gz
    ├── 83b927df8c3d3f1e9d22d09c65fc0469deaca036.nq.gz
    ├── 8425a0e1f6738775a37c63232a15243d7a885b3d.nq.gz
    ├── 847914e17694b3f38f5de39164e258cd3e067e66.nq.gz
    ├── 850fc9cbbb10aea1160f6e613d609109e7182fbc.nq.gz
    ├── 863d7e069b403cec2062f88b0ea93716bf863b5b.nq.gz
    ├── 86c58ba6ec342e14096a74360fc2276effb92297.nq.gz
    ├── 8798ad2287f0a681a4c685d868490e907206fa01.nq.gz
    ├── 87eedae2a7c1d918ba07ecd52e3ed7800d875e55.nq.gz
    ├── 8942f0fb719e54aff2c9b7d133da71d328995ec0.nq.gz
    ├── 8b300047799f8cec3d2aff1abaebaa9bd0b09370.nq.gz
    ├── 8c4b6e6327de1e30e7ae1be829f37a308bb099dd.nq.gz
    ├── 8cbe404303e3575dd3bab34342e5fcb040822cbf.nq.gz
    ├── 8cc5462cb9cd0b4ddd7fe47b599f53e91312b7c5.nq.gz
    ├── 8dae76597a2fdbfb7ee93720bd8246a6e3378bc9.nq.gz
    ├── 8e651f349fbc18ce1200c88c847ca639bf420719.nq.gz
    ├── 91ac34d61950de4d119f1542287a37e8dc75e228.nq.gz
    ├── 924e3863a6aee9dd6333dd172a1162a34539e9f1.nq.gz
    ├── 933847b19ec34f5e63b902b101c98769891ce412.nq.gz
    ├── 935b31cf4f2d8fed6bac9bab70605d20edd6289a.nq.gz
    ├── 937db8f467c885a841eeb254586007349528380e.nq.gz
    ├── 93822dcc50449ec37918b8f1783e4f9575691a45.nq.gz
    ├── 94227013f961c946e9a61490d668823fbb62c50f.nq.gz
    ├── 9432c7b8274fa5b7b0ffea8423b39c5ab205cc66.nq.gz
    ├── 95f3039c0649f5649bb85649256b0a040029d917.nq.gz
    ├── 96d5ed8687e3fe790dc44fee188ef7ea80847ca0.nq.gz
    ├── 977fd6f3e970b43fbce0ec5fae8b5d6458e305db.nq.gz
    ├── 978ce2591d89e409621490f9900288f5b9a6779a.nq.gz
    ├── 9848e970f60a694d91763ace08b9ef1b2f518e7e.nq.gz
    ├── 992c7d56562aaf2b37b459cb34a5423ac32d82c6.nq.gz
    ├── 99b83bfce1a82911c72288aafb32699348f4daf6.nq.gz
    ├── 99c4ac2688b9aec4b0059f13027d427e3574e891.nq.gz
    ├── 9b56e08262b6039dd05b30387490b8b3af2794a7.nq.gz
    ├── 9c6bf085feff03786bd332bcde72a65893098292.nq.gz
    ├── 9d8012499a24063dec3cddd2ba736254cbfbc4fc.nq.gz
    ├── 9db954bdfd5f7ccfd4abec92496e89bddf72288c.nq.gz
    └── 9e217a6d5ac2f4087a1d2de772bb2ec859582232.nq.gz

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

[deepset-ai/hayhooks](https://github.com/deepset-ai/hayhooks)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
