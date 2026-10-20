# Repolex Knowledge Graph of sdispater/pytzdata

RDF knowledge graph data for [sdispater/pytzdata](https://github.com/sdispater/pytzdata), parsed by [repolex](https://repolex.ai).

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
rlex download sdispater/pytzdata
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 11dda19bc50a2d4e246326450bd2e86389cf67c8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 11dda19bc50a2d4e246326450bd2e86389cf67c8
│           └── chunk-001.nq.gz
└── blob
    ├── 0014046d29a38e9b8006f746fea794d7f71eb479.nq.gz
    ├── 0133548ecac014f4b37f0abcd471a5a6b4e7ed5f.nq.gz
    ├── 0160308bf63690a6dee51c3c8849f494a47186c2.nq.gz
    ├── 02b07ca232053d1d908d019621b792986bd9b429.nq.gz
    ├── 030d47ce0785f3bdb75314e0d03fb20c3e0172d5.nq.gz
    ├── 047968dfff4dba196d5c9695e79cf28395d9a0aa.nq.gz
    ├── 0559a7a4a4288d7e3c3b1bcf47c57a7ea82be2ef.nq.gz
    ├── 062b58cedcb40e56f72bc1de503abda9747c7487.nq.gz
    ├── 066fbed008cf662455eeca2c012ab8cb5bf1731a.nq.gz
    ├── 06e777d57e0267a0635b6b284729fddcfe6221dd.nq.gz
    ├── 06f0a13a662aacfa70c489d2fec5276362576089.nq.gz
    ├── 07b393bb7db14cef1e906ebe63cfbbe8cddc79d5.nq.gz
    ├── 07c84b7110ad9589810b916390aedc7ef498f423.nq.gz
    ├── 09511ccdcf97a5baa8e1b0eb75e040eee6b6e0c4.nq.gz
    ├── 0a73b753ba597f89cd57cc3875e7869dc133778c.nq.gz
    ├── 0ae222a2f8bb2fb1b7abe17d08e076674c51541d.nq.gz
    ├── 0b0aa4eb2222bec40c9c8511acfb5854c7a67aa0.nq.gz
    ├── 0b1252abb7e4ab478da26eb0be59c45b9b15abca.nq.gz
    ├── 0b86017d243f1b7bbb41d6b4feefcb2b7edfc7d8.nq.gz
    ├── 0c80137c74865843bda4de544fbd726522ec3521.nq.gz
    ├── 0d09a43cccac66a53ce9db90ca4c94c6bbf2371c.nq.gz
    ├── 0e4d879332d21c93c229fc25587205020eeb3127.nq.gz
    ├── 0e797f2215ab398bc59b8e4d60e5260fcb365c3b.nq.gz
    ├── 0fee1d7805ef72b47febf311e1a518f83aedf6a0.nq.gz
    ├── 10998df3bbe67aa8a02602301d10ec2b2c33006b.nq.gz
    ├── 10e0fc8190a401f67b861ced3b8b16401432a565.nq.gz
    ├── 117aadb8364cd7901388098503f4538c7b445aeb.nq.gz
    ├── 122e934210cabf0b29a2dd7d11eb8220ed1cad43.nq.gz
    ├── 123f2aeecfc88f2e543f99d6a859e02788170852.nq.gz
    ├── 12ce24cbeae404efe6921081d21289be452ff88d.nq.gz
    ├── 13ff083869a9ac8476775587de8476654a100017.nq.gz
    ├── 146b35152aaeffb5940d30910ba37703f4096285.nq.gz
    ├── 15808d30fb1bb250cce195a00a2d7dca321df7d3.nq.gz
    ├── 15a34c3cedb7c9ca519c195f5ec0ce9d8d1885a5.nq.gz
    ├── 16f6420ab7efc7ceac3b0e42fe37836185cfc463.nq.gz
    ├── 177836e4fd98399bd4cdda410648cc286408b95b.nq.gz
    ├── 17ba5057727dd73bd5f6234cc5b239b71a861945.nq.gz
    ├── 17f26169904928e4061e4ee58bdf7a6c62001524.nq.gz
    ├── 1a7975fad7f7e96f7101eb3c64c9b420eeebb621.nq.gz
    ├── 1abf75e7e864625b975feebdd0b232d0de624b27.nq.gz
    ├── 1ac3fc8f529e5431ff61c43232f243c72e1eac2f.nq.gz
    ├── 1cf502984a27deae869b3a39ccbbc056e487d398.nq.gz
    ├── 1d994902db21814a626e42639d7a96b18ee73756.nq.gz
    ├── 1e94be3d552ea0d6e29824469866c2a51a187be9.nq.gz
    ├── 1efd841261a977ae218d408f9cc308c3e312a5e8.nq.gz
    ├── 1f761844fc44f8228bb748235bfd30be6c389cd1.nq.gz
    ├── 1fa0703778034551487b7b55d80d41ad220f2102.nq.gz
    ├── 20c9c84df491e4072ec4c5d2c931a7433d9fd394.nq.gz
    ├── 21ebc00b3fc096035b9810519d778d04a3562a44.nq.gz
    ├── 2218e36bfdb95ea041b166f183895a6ca4871ab1.nq.gz
    ├── 22940dac3ed15e64232fc1a6eeb5fb7545d2a260.nq.gz
    ├── 2364b2178b03853b1771cb3f34b964fdb82e2e91.nq.gz
    ├── 23d0375fba3377a3d513d849c0d29c82ad2add64.nq.gz
    ├── 246345dde7cada7b0de81cc23fabc66b60d51e79.nq.gz
    ├── 24c43444b6751343d2915843d03e55753d4d7359.nq.gz
    ├── 250bfe020ada912671d670e77403a269c74b658e.nq.gz
    ├── 254af7d12f38af0abd6302a4df574e45b50d1805.nq.gz
    ├── 260f86a9180677d86fc3280b06f01d6a6cd91c94.nq.gz
    ├── 261a9832b3ee4bda7c9935b566a7f7f0e6489e97.nq.gz
    ├── 2698495bb3f953685e45edb916798cd24f772664.nq.gz
    ├── 26f4d34d67b46513491f26c2e661c6e653cc130d.nq.gz
    ├── 27973bc857b4e618218ca2790acacb81f7c7bb82.nq.gz
    ├── 27de456f16ab549627b284a39e2265cbdb4ad8e9.nq.gz
    ├── 287f1439266639f9564149d6e162feaba3fbed86.nq.gz
    ├── 2892d268094ea785b045e53cb441a551672aabd0.nq.gz
    ├── 28b32ab2e0b9053f39a91d9f28b6072e41423954.nq.gz
    ├── 2a9b7fd52d37a1ffe9fc589daa04d88c6c71a6e0.nq.gz
    ├── 2adacb2e500e2f9621b2debc1756d308747b67f6.nq.gz
    ├── 2aea25f8c210369e0b805d0dd5f0e899190c2340.nq.gz
    ├── 2b479bd0ecb17b5741ec30ae1bf1ae64c74f2b0b.nq.gz
    ├── 2b6c3eeaba0903d03c3d44fc6eb661b136fffdaa.nq.gz
    ├── 2b8598f26116627acd31a64aee7ed12e73d9f0a0.nq.gz
    ├── 2e20cc3a438bb2076bfc1856045075dd041cad3d.nq.gz
    ├── 2e873a5aa868c5605443c48510646f1408d58c4a.nq.gz
    ├── 2f357bcf50da794541a518510777bd5c470b9b77.nq.gz
    ├── 2f3bbda6d3586a2ef5b94bc28ff37906fbc758f5.nq.gz
    ├── 2f75480e069b60b6c58a9137c7eebd4796f74226.nq.gz
    ├── 3002c82022f7e9a4ff1ad545ea617106a13b24e0.nq.gz
    ├── 3021bdb61473603f78138e235d1d66472b4e3d04.nq.gz
    ├── 30943bbd0a8251404c407cde82243294071baf22.nq.gz
    ├── 30c6f165052efa4fbc176cbcf19b626b1615d88b.nq.gz
    ├── 314613866de53e1457f6cbf2fb617be7e4955edf.nq.gz
    ├── 31f0921ea04cd201675b613082fb4b0b0b91941c.nq.gz
    ├── 31f7061371910ad42e4310b7a646ba1a98b6cba4.nq.gz
    ├── 32a9d7d0c9cbfa841cc4e922fd1b486a34b57370.nq.gz
    ├── 33cc6c626565cd877d8295843284411bbb940eb3.nq.gz
    ├── 355817b52b1b05680bbb57e4dc8de358eff27a39.nq.gz
    ├── 3582bb15cd7322088839b0134987ad10e717b6b5.nq.gz
    ├── 3643628a24723239a13d61b2215c907cdba03985.nq.gz
    ├── 37cb85e4dbfb7ac9c01eecf584a1a721ed251e93.nq.gz
    ├── 39d6daeb9b6dd3b225b0ddacceb6984e8204ac7d.nq.gz
    ├── 3a70587472c633aaa178c7f979b8b3884d604372.nq.gz
    ├── 3b9cc7b20317766a22c02a151c9ec0e79692a3d4.nq.gz
    ├── 3c6529b7567f032882863fcd48b790e0988261bf.nq.gz
    ├── 3dab0abf4ed950f46a23282c59f6f6fa3b6ba758.nq.gz
    ├── 3db6c750333fa6dc1efc84b1abc24528fbc00b0b.nq.gz
    ├── 3dd85f84ff48fb8553b4a964659872ae1fb7d33d.nq.gz
    ├── 3e4e0db6ae0a5a704f8cdd549071cc5b7124e2fd.nq.gz
    ├── 3e80b4e09f792e37422ffafe42355aeb3e6940eb.nq.gz
    ├── 3fd846de97cc07a67bd6db2bbe90220efc994b99.nq.gz
    ├── 407138caf94e467b52d925f96ad80b506e16d9ec.nq.gz
    ├── 40d7124e5346af056c75e2f7012a51d94e8154b7.nq.gz
    ├── 419c660ba76f34949423fc2cbebb9824007587fa.nq.gz
    ├── 427fa563033fdd8533ae56337fa20befe9719b42.nq.gz
    ├── 4303b903e5e007484c0d8e1eea43a35e9b53f38b.nq.gz
    ├── 430d2392cd27757c886a9649b754d3fdc98d02b1.nq.gz
    ├── 43236498f681cc06f64ca2afa613880331fe6fbb.nq.gz
    ├── 432e8315bc9dfa74080467f9e08073d9fdcc833a.nq.gz
    ├── 438e3eab4a6e581c6f5e7661098bf07b1a000593.nq.gz
    ├── 43b2f344dd15f4ef3d4c6bebb456aa2438fed26c.nq.gz
    ├── 440ef06b5d55fba8f1407184757e1785aec1fe8e.nq.gz
    ├── 442b8eb5a438985092d8657ebcabe8859037482a.nq.gz
    ├── 446660861227aa8ceb7084f48c3b2654ea64f4dc.nq.gz
    ├── 4506a6e150dfd73884811c8c0f5a0e21dc76a756.nq.gz
    ├── 451f3490096338f40e601628ac70f04112ace51d.nq.gz
    ├── 453306c07566a94c0c391024fb16ee36245a0a40.nq.gz
    ├── 48412a4cbf9241ea83887876b1b8b22c367ff4fd.nq.gz
    ├── 485459ce0397787a099064952c66989712ae707f.nq.gz
    ├── 49381b4108b1827f24ad7d2c18064a22624092e7.nq.gz
    ├── 4a826bb185531c34eb37959037c68fbf08c23f71.nq.gz
    ├── 4adb5f420354329154d7f035af0ef710d797dbb2.nq.gz
    ├── 4cb800a9187901afa985f1ae67565d654021cabc.nq.gz
    ├── 4dab6f9005bea50a065c685ec8260b0da2bff921.nq.gz
    ├── 4dab7ef0859c244b916d61b7489d7371881e0ca2.nq.gz
    ├── 4dcbbb7ea21e193cd2e2578a17bc955caea227a4.nq.gz
    ├── 4e0b53a082f11f9b9debf5e110b97b1b0473c9a6.nq.gz
    ├── 4fe36fd4c11f998ba3f626c5e23d97bd82d12791.nq.gz
    ├── 508446bb6aee2841ab88e82607a6ad6e748e7db7.nq.gz
    ├── 5213761f891303f95e1962570568ae62ed387950.nq.gz
    ├── 52753c0f87bbfa457ada89d400908a3d6537ac0e.nq.gz
    ├── 53c1aad4e0a541ee3c2c4c6de33a79ca93a7d244.nq.gz
    ├── 53ee77e88e5ee70cb690feac41d1436160f685fe.nq.gz
    ├── 5553c6009acd272cae012a08b618c2fd649dceae.nq.gz
    ├── 556ba866933d37f3cfcf8042045d64e209bae30f.nq.gz
    ├── 56593dbfff9bc50bb32e64ff282d0502e75526c0.nq.gz
    ├── 592b6326066dbcba3ae770763f024de7fe718dd2.nq.gz
    ├── 5962550392fa78514061582e9371c32b9f1d929b.nq.gz
    ├── 59f3759c409a1fb50e632ef5ef613d3fee7af7ef.nq.gz
    ├── 5a0b7f1ca032be1adf8ba91f863e727c5ec6a026.nq.gz
    ├── 5a25ff2a6afda2cb09b9e147ad20610bc1923444.nq.gz
    ├── 5baa3a8f2ed24f68c49bd7e3ccd4772a8e734414.nq.gz
    ├── 5e565da2f6b138b70179cb7e72347163ab44b6ab.nq.gz
    ├── 5ee23fe0e59f044598675db44d53c20590b88934.nq.gz
    ├── 5f3706ce64cadf081a6c56abd7ba423575a4abb2.nq.gz
    ├── 5fbe26b1d93d1acb2561c390c1e097d07f1a262e.nq.gz
    ├── 60150175c0fdd34a3dff6404ad5a4df69b5f0b83.nq.gz
    ├── 604b85663672d83658f331a69cc8f41cf2a2b5a1.nq.gz
    ├── 60aa2a0d695ba577ff87624d479f1eb25c8f1caf.nq.gz
    ├── 60b5924dc12f14c274073b1fe4ccc590b742da5a.nq.gz
    ├── 612b01e71cf873b7f8a80d25d7906d77aa91ca5c.nq.gz
    ├── 616afd9c83d7992f86477f866926d61d2f65c25b.nq.gz
    ├── 625b1acccfa7fa206b39f61aafa69dfd5d65cfc4.nq.gz
    ├── 629ed4231944255aaa0725f807517df48b39e135.nq.gz
    ├── 62c64d85dfbdc41ae8e78bc8304ceb35b16b4255.nq.gz
    ├── 630935c1e1a8c1a87e728fc1dcc4c930e81b30e9.nq.gz
    ├── 63188b269d077e29f48a42a03c2a52aefdb61320.nq.gz
    ├── 633f866158ac742cf754a2c43edcb07e3a094f3c.nq.gz
    ├── 63d58f80f556e1c3135d6dbcb2a2dfc6f61b4fc9.nq.gz
    ├── 653b146a60e5e5641a07bfc82f9590dad1ed69f5.nq.gz
    ├── 6575fdce31183d8238b18f2f30ab5b9227c7071c.nq.gz
    ├── 65a5b0c720dad151ffdcba3dbe91c8bd638845c6.nq.gz
    ├── 66490d25dff9bcc8f710b0141f1a02e64aeb32f3.nq.gz
    ├── 66ae8d69e3f86cfdd8d90a9b1d094d807f75f27a.nq.gz
    ├── 66af5a42be440f1fb8fec3b915afb49b356f63a5.nq.gz
    ├── 670e2ad2ce22f08d496b42363caa2e424121b20c.nq.gz
    ├── 6752c5b05285678b86aea170f0921fc5f5e57738.nq.gz
    ├── 684b010e8b6bad56b084072403110b94e8cfe2dd.nq.gz
    ├── 686ae8831550bb0fe033409c8b4df460fcd61a04.nq.gz
    ├── 68ff77db0d95c7d054ef33c05e05ba71bcbbbdd8.nq.gz
    ├── 6958d7edddb85d298c5f2b890b21d9ca2056e9c5.nq.gz
    ├── 697b9933eb72e93be3a144fe610354076a53e50a.nq.gz
    ├── 697cf5bcf7f151ffc1c1fc4247e4e9c7e3ff01a3.nq.gz
    ├── 6a241b398e68824b01c345cd6d0f802c3886bc44.nq.gz
    ├── 6b94a4f3124658a723d3b189ad21b7c4f5baa3d4.nq.gz
    ├── 6d688502a1ca80f2e57a6de2790ac3193879d248.nq.gz
    ├── 6ed8b7cb07634b9d669c6c36448fb8df0fdb32a3.nq.gz
    ├── 6f802f1c2acf9cc73481ae86c9e099fcfc28cf25.nq.gz
    ├── 701df228d97e9bf3f2b10c5634107daff2f7bd3d.nq.gz
    ├── 714b0c562889a8a774d9aa27810d8400164d00e6.nq.gz
    ├── 728305305df3d82fca7829ff3e9581583758dbeb.nq.gz
    ├── 72bea64ba83546e72ff9d6a4f9a9e64cc2d93b47.nq.gz
    ├── 73891af1ee95a4d5d602967fd5a965c8a7ec1327.nq.gz
    ├── 73a4d013fcb82c2beb6f885f359b9ca20da054e7.nq.gz
    ├── 73b9d963efc99f7af196755a6b2be015d9cb7a67.nq.gz
    ├── 74d6792bf6fcb791bfc0af1f827737f612abef67.nq.gz
    ├── 756099abe6cee44295a5566ad6cd0c352fb82e64.nq.gz
    ├── 759592a255408caf354d0c4a2e406ee5a1638181.nq.gz
    ├── 7636592aa7773fad6810a93b305c7dcd688cff34.nq.gz
    ├── 776be6e4a6d5a054152135a1ad149576052f49a1.nq.gz
    ├── 78b9daa373d2aa2856eafcc92ebc6d899cafde5c.nq.gz
    ├── 791a9fa2b38729ff10032f9e1f021754c76c87f5.nq.gz
    ├── 7abd63fa608e0186b9f154d9fcc32472c28f6759.nq.gz
    ├── 7ad7e0b2cf8fa4fc844fe8cc9c58e4f3018cead1.nq.gz
    ├── 7b61bdc522b5b7f4397fdb9246185f4d972f4b6c.nq.gz
    ├── 7bbb653cd7ce09d88f8a1701853bfe92ac7db0c4.nq.gz
    ├── 7c42a921550c3b54228a03a28222375f90880b83.nq.gz
    ├── 7c839cfa9bd62842cf23f01d5195b239bc5a437c.nq.gz
    └── 7cae0cb7562e5c0f9fa46913b71a5c3628c01bbf.nq.gz

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

[sdispater/pytzdata](https://github.com/sdispater/pytzdata)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
