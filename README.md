# Repolex Knowledge Graph of apple/ml-cvnets

RDF knowledge graph data for [apple/ml-cvnets](https://github.com/apple/ml-cvnets), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download apple/ml-cvnets
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0c0f79822f0ae6670319b5befccb7be24adca16e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0c0f79822f0ae6670319b5befccb7be24adca16e.nq.gz
│   └── repolex
│       └── 0c0f79822f0ae6670319b5befccb7be24adca16e
│           └── chunk-001.nq.gz
└── blob
    ├── 0134ae017592f9a71c9e1751c6ee1d78c1e1b0ee.nq.gz
    ├── 01e535f766ea66840121b635ec4840068063e548.nq.gz
    ├── 0209c7b097fb4e91a55e86334655dba58e0a42fb.nq.gz
    ├── 0289c4f1e8023e8cd1a83178d97d5bd32f9599cd.nq.gz
    ├── 02d54a653a5d0929f0eaf5f921f2d88613366d1b.nq.gz
    ├── 02effb5d17e3865454532cc36182b8477e643a35.nq.gz
    ├── 032810008d45f9d48ff3dc75de9d12508320db89.nq.gz
    ├── 0345f87674638e1d9a8132790193d12b7c6293fe.nq.gz
    ├── 034b5cf3f04bac9b38137d2602a362373b4ef4ad.nq.gz
    ├── 03ac0ca3aad46ddce92bda5be9c9f6f058187ddd.nq.gz
    ├── 050a0fc02e73dac1f1ab101114c46be6413bc7c6.nq.gz
    ├── 0527dd321c9d8778e30959a0d2e99a56605cca5d.nq.gz
    ├── 056446fa8cef3249fd0ead8da6fbdd3b95ad9453.nq.gz
    ├── 05bd57478c5813983ec17985892227a5fad74327.nq.gz
    ├── 05c1c40e8a48f86614b30d6b7220aed2b97a6781.nq.gz
    ├── 05c75c635fccc28b55d362eccf1d1cc6c48ea79e.nq.gz
    ├── 067fb216030552f8cf642864951508063a432d41.nq.gz
    ├── 07c4efd273a3f04d0728013e20eff9db05094a8b.nq.gz
    ├── 07eb03aae9c5b20f8321984fbe118e3000470989.nq.gz
    ├── 080863a3cb5c669c20a8784bf393900852b0c370.nq.gz
    ├── 080ce8ebffae3185ab3f4c2735bf51e3964f0ac4.nq.gz
    ├── 0823c18b795ebf9212ace7fff368871572a703b1.nq.gz
    ├── 0830d2134c34da7e164227bc3509fea070690419.nq.gz
    ├── 088097c9f57df2b0e2d17e1a3ab4abf20eba290d.nq.gz
    ├── 0917584667dbfdc3714dd47ba11ad8a955cdf328.nq.gz
    ├── 0927bdddf4a2ea81a4e83e7dbc62500223d2e475.nq.gz
    ├── 09a6fe75eb54c9cbc6277f020c91e78fba4aff1f.nq.gz
    ├── 09f3c7da5e636a388f8140ac6500ff6dff953be4.nq.gz
    ├── 0b6f46559ca4f3bb6e9aa2f6bc50adf49df7091b.nq.gz
    ├── 0bb908e1b32bc783b1042ccce0df472399640b70.nq.gz
    ├── 0c98d8257a4f19658d07551a935fc760eeb55eb8.nq.gz
    ├── 0de320ce9f36002f5328e3af1bf74b4465247261.nq.gz
    ├── 0e8375461e41ead6d7fae2b2d4ee25f34f966f25.nq.gz
    ├── 0e87b77a9dfbdc66a9e36bbed9b81612ef283811.nq.gz
    ├── 0eea517847fca7b355dfb1c43454c713149b8b42.nq.gz
    ├── 0f9bcbcee7e4f447549b96f566a9a53c8561063a.nq.gz
    ├── 0f9ca1e7700338406e7899dceb5db75b68898d3d.nq.gz
    ├── 102b7d5149ae385c52ce1b0f3d700302addde110.nq.gz
    ├── 103e814f695294ec38a4e6990fba7e0859fac991.nq.gz
    ├── 10460b56cf1f04ddd36b98f8471b14440f4608cc.nq.gz
    ├── 110cd5100fbbcfed0a16c64e149050996fe2aa64.nq.gz
    ├── 111681ed6f29ff3cb72780708cef991c1ac03888.nq.gz
    ├── 115aedd1c80cfab5d078cfa040f382ba47d3182a.nq.gz
    ├── 11665c90608986f1772a9026f3d599f48db58531.nq.gz
    ├── 1270df599154063033ecbb8badc3b62a1fa56788.nq.gz
    ├── 1350e11ed9e7f7869ddd6c8e3ab77669716ff79e.nq.gz
    ├── 1402caed07527613257fcab03af1d8d8c1d1cde6.nq.gz
    ├── 14592e2b50a6cefbc9579f522b1dc9b0913c2b81.nq.gz
    ├── 14d4d82528e620e3985810bf73ad559363b4d9cf.nq.gz
    ├── 16db6307e3850048e36d664987c1d052c5a9df0a.nq.gz
    ├── 16e4f0ee001714c6243aae2b9ee7126df3c358db.nq.gz
    ├── 17bd365305262aa4ad05ee84c478d509cc8f07fa.nq.gz
    ├── 17e0d32257912e9983cb0fb2c6a406a4c9be0bfc.nq.gz
    ├── 17f3d37f20d39162d908a321a8e86624a73bca7a.nq.gz
    ├── 198c0d1e9cb673b8df01ab5a645dbb4699cb65bf.nq.gz
    ├── 19cef65f5e159f8fdda7e8d437668995ac61516a.nq.gz
    ├── 1aa5c4cba03e4d71e0225e499372d9a6c3879e11.nq.gz
    ├── 1b6323bc256cfb91fda46ec56342f60410c3ca83.nq.gz
    ├── 1b9fc19368df70632f6b3a571f2e563720dbe7d1.nq.gz
    ├── 1bc24161f81c5ba04ab99ecf7f921840b4e43887.nq.gz
    ├── 1c236fd3f7f9125025fc83e1492bfb5d976ecf0d.nq.gz
    ├── 1c6810302c30e7b368b2451713d5793192c79940.nq.gz
    ├── 1cd8c1845ea4b03aa1c099ab633666f074c40020.nq.gz
    ├── 1d61257182b175183459af468cbc29e2d782dfb2.nq.gz
    ├── 1d877ee53f08508be6aea64a3b2b56a98d884a93.nq.gz
    ├── 1f1ccd0dbc7e6da9bebb46876de58609d71e5037.nq.gz
    ├── 1fe0fc728c1c426ad107866ba0227fcd68e1e281.nq.gz
    ├── 20178ca0770409ea72dd892403f6e9054618ebf7.nq.gz
    ├── 2023653d7f627e6b251b1c6c557f776d953dfafd.nq.gz
    ├── 206bc70e4b926d03887725b4c5ddce661f711617.nq.gz
    ├── 2086264e28a79a2c0a1bbb20440efe9961ebfc77.nq.gz
    ├── 20baa8fe9336b990ed47387c11c8bb100dcb08f4.nq.gz
    ├── 20e62e804840e1b29d03feb0ea34229d4ace323a.nq.gz
    ├── 22fe31b6593434613f28c56bc492f87d9ffe33be.nq.gz
    ├── 23ef399fd19ae3ab8ffe7c75686768a3ff70bf96.nq.gz
    ├── 2460cc5d575c96f3a248b6cd3ac82d573af05f26.nq.gz
    ├── 24c66e1c04108e2498eef620d1bc8ed5ee616db8.nq.gz
    ├── 24d45f6e26a466bb9a7420e62edf1f4b0efc95c3.nq.gz
    ├── 279c98095ba99816b8d0e7605b698d87abd93de4.nq.gz
    ├── 27a264afb9d902860cf684a1f9822a04a37b3c88.nq.gz
    ├── 280f94b834237934ebe29f220fd7691a62ab634b.nq.gz
    ├── 2870d821f484dbf3b622f3c74c0804d37bb180e2.nq.gz
    ├── 289a55ad3cf2eee4dda897a73ec00eb13fbd60a9.nq.gz
    ├── 28deacbd90534d43ee7a8294efe71fb08bf2b6f5.nq.gz
    ├── 293fb5173e08875e984aaec9e89c3d810dbb3e14.nq.gz
    ├── 2985cb4477de450474b9dcd08306992cae9b5cb6.nq.gz
    ├── 299868eb0cd5aab2fc21f6ff8326dff656db2ed2.nq.gz
    ├── 2a68b4fc61e54743d29fa194d9232372a81f60cc.nq.gz
    ├── 2adc4598ef642c6a3a0fb8e3f6c864176062e5cd.nq.gz
    ├── 2cb8f84501178d61e400380f0b34d3f59291c031.nq.gz
    ├── 2cfde74e8590955652fbb5d6c4797e297019c6e3.nq.gz
    ├── 2d070ab1faba9f74227516c9e55bce68fc108afc.nq.gz
    ├── 2d74583a504f231d7ec2e20fd650d8561f043d9f.nq.gz
    ├── 2db8a91ef2561113a292b506413cb0bcda22e8f6.nq.gz
    ├── 2e19b1c01265a8572085f72d40b8e6535448ffa4.nq.gz
    ├── 2ec56f3128119fd948d646a8a125e3cc292adc52.nq.gz
    ├── 2f36c142d693120db546c84aab880963bef9f4e1.nq.gz
    ├── 2f551478397ae4f83bb934c2d7d1c9c85d7d3a21.nq.gz
    ├── 2f7d732029268d7855bc635e157442573915b63c.nq.gz
    ├── 305e6d5f6e6ff4e29824749eec7cfc827a226fb1.nq.gz
    ├── 3062e99960fe77ccfa9874227430e310b8ee1b08.nq.gz
    ├── 30a3415145ec593c24278906d55e8f81b8d3b6e7.nq.gz
    ├── 30b557279b45905605bfb9215f36d0441ad55bc2.nq.gz
    ├── 322ea127b5b3ab76834796fd113fba6219a1f99a.nq.gz
    ├── 323cbd045c9cc87069661c8dd665b9fd0adff9fd.nq.gz
    ├── 327232dc6fc2abaa073cb2e223ec86bf024afa37.nq.gz
    ├── 327f9790e63b7e0ceb7c016d75f7c39e0f88791c.nq.gz
    ├── 32e1625321580c66c64bfcb3783bea5f213e76a6.nq.gz
    ├── 33fdfdd5e6dbbd7fa0f2b2db48425e0d79bb187b.nq.gz
    ├── 3445d8e32405568303be33e080aea33b2bf7b2f7.nq.gz
    ├── 34c110a10a1c2637318c1fa85df9c2604d83507b.nq.gz
    ├── 3581bc6b83b2dd7bf983ca754aec8c8733913851.nq.gz
    ├── 360141cbb08109cfcebffcb952123e2ae8bf0632.nq.gz
    ├── 36546453882426597eb22a52f1d81bb71c7b937b.nq.gz
    ├── 379851c77c8111ef72d2853c5383238cfca9d6c3.nq.gz
    ├── 381e2a6320d5e9d471a100ef233b4c0481944d6b.nq.gz
    ├── 388ccd027cdb57b00e32d3bd2de0570fb4bbe7f9.nq.gz
    ├── 38be8c6deb1417476683e824d3b82751e548e0b2.nq.gz
    ├── 3a1d7eff370dc95be175d01ba4644b87ebdbcc88.nq.gz
    ├── 3aaa0d0011be1902326f5faeaa37e929248a5ffd.nq.gz
    ├── 3c8b9751def78e90016dbcc2d2537e7695ed5459.nq.gz
    ├── 3cae8744c051596675bdff08fcc2621037852741.nq.gz
    ├── 3cca5937d675f26cad57ed16282089c1ffb911aa.nq.gz
    ├── 3ce1ef050c89fe917a8a0abc8b611b24284e1c0e.nq.gz
    ├── 3d169fa9efc88ebd98f474cccc378db129e05700.nq.gz
    ├── 3d8a2f500f98fc555b8e0219aaf4403d2bf5650b.nq.gz
    ├── 3dbdb408a73df0e38197ed3a8749e13ea43eb0ce.nq.gz
    ├── 3de18da84b35fc7aa72a75874ad3b4ecebc50710.nq.gz
    ├── 3e11f5f3f5c7d93d8977f3f0054b966c0695273c.nq.gz
    ├── 3e636d77c66c1b7d0e5f6331658115005ac59a3c.nq.gz
    ├── 3e9b8cb7cb58d43f79b6c76bc0db7709dd395bd6.nq.gz
    ├── 3f42a6f831c2d14a78fe04eb45afea40e73d61a8.nq.gz
    ├── 3fabdbc91a7e4d6b588495f4772729a64b346574.nq.gz
    ├── 3ffc8bb2bc145e3cac26dc71a2fe480b0a19fa7d.nq.gz
    ├── 400fb06a006378608dcf1ae478cf0916d078f255.nq.gz
    ├── 41279cbb0f7ae134ce435bb0325dbe1ff5988460.nq.gz
    ├── 4159c2183fcb9eec2d0ff1bf40fe41fe2c3ea2ce.nq.gz
    ├── 4186fda7fc78231b4abd7a54b7a19d68b8f23bbe.nq.gz
    ├── 41c697692bc2505ba6a2cf846025805e728d8a07.nq.gz
    ├── 4336818a323f3fb14a2966056b5bf927705f77d0.nq.gz
    ├── 4512de8efa974cb75f272e5fb7c558f335d43821.nq.gz
    ├── 46688bee5777bddcd0e2d297c6d72368499a262e.nq.gz
    ├── 46737725452eb62370630b5c2db29455e5b251a7.nq.gz
    ├── 473b485360bb83462792ba31a7cbc2985770867e.nq.gz
    ├── 47613d3000c192b24d66339173319bea1b6f14ba.nq.gz
    ├── 47b6f7b600eff77998e01eb7bf6bf9f49069f8d6.nq.gz
    ├── 47c46eca4d1afc399739280a137108295a7bb068.nq.gz
    ├── 4859eff0a974391a89dda29486f10e3d1f3fe067.nq.gz
    ├── 48f9d1a590db424f6ddfc17f03b5e8d304ec85b9.nq.gz
    ├── 4931d0d30906f884cf62e0e0730a6db7527ad7c7.nq.gz
    ├── 4aa91913942fc27e1cd26d85dbd96a38b191b907.nq.gz
    ├── 4aa9fcc1645b5389338b65b77059a903bb4ed572.nq.gz
    ├── 4bae29a338671241a7cf6296aa31b5662a892491.nq.gz
    ├── 4c494cab1db4636f650df28af48eef487040522f.nq.gz
    ├── 4c77db37b2cc9b8c3457cd815fe3c5278bd8f505.nq.gz
    ├── 4d16fb6bedd807e61643dd7fda42484796937439.nq.gz
    ├── 4d7eecb7e2a3402b1bacedb3100712517af37a0f.nq.gz
    ├── 4dc54b4db3dd76714c22694772d2a15ac1cfc2df.nq.gz
    ├── 4ddc05dd8af761135f5abb7f1477abfd14f5ad52.nq.gz
    ├── 4e17edfa091b08a54ea46b6d7026be61700e9b38.nq.gz
    ├── 4e316c6ee58a677673dbce99712e462c6a40431c.nq.gz
    ├── 4ebbc004cd0b57f7f81811ad31f6d8fb37cf7b49.nq.gz
    ├── 4ec6467b8eeb45399817ae790b5ab0808705f44a.nq.gz
    ├── 4ff0f97d9d49508caecc0068b493ef3524607697.nq.gz
    ├── 5019c80ae568a6457c1821dc19348db9cf083c3d.nq.gz
    ├── 50403e2e796dcc0abc4bbd7a3635a41ac141a01b.nq.gz
    ├── 510b2202f7406d83426a7031ea90b1b02473fcff.nq.gz
    ├── 517dce5b24ed62889e4832d09a0b9e4c4decd9ad.nq.gz
    ├── 5183b97c4030415c64aee1e540a021a727ff2796.nq.gz
    ├── 51eb82bf36c00de4ccb2459236b57044f08ec711.nq.gz
    ├── 53e4fc313c9f81a4432d0bbe9bcc1040e655122d.nq.gz
    ├── 542c9da92dc77428c355a6a0a106ede0a5af999a.nq.gz
    ├── 54617b2fe2006b9cc23b970f8793b59fa8a65d69.nq.gz
    ├── 547ba4835b8f83c6871f5ef3aa09d744ddbc3727.nq.gz
    ├── 548134f064dbb9abc99338fc23c34551c9494067.nq.gz
    ├── 548cc582fcaeb5d2c70694059598f752c16015a8.nq.gz
    ├── 54f3aff67725ddd32f3e403874f330b51f3b7c61.nq.gz
    ├── 5638e1d4600d59915f1c4763c73fe439a588e254.nq.gz
    ├── 5685ed8300b45c5b952051754db9509d8880bb2d.nq.gz
    ├── 56bc5ecdbd3c49adb1f5b146ed92943e71ae51c5.nq.gz
    ├── 5721293a5902993780d9ee4e179da7b86b146c3a.nq.gz
    ├── 5730d1d4aea8cd3e2e49b8cdd82867b2846c4293.nq.gz
    ├── 584cd6d05f98078071d99dc6d4176714dc8cdc91.nq.gz
    ├── 58c51d1358685bd28e7f3c0d28c6a42057a30a48.nq.gz
    ├── 58c877b38031922b2d39f2247b37515cd44ca3db.nq.gz
    ├── 593403b6822bccfe1c1f168fe47a0e358ba90a7e.nq.gz
    ├── 5939af426c951b7940fef098261aad797b575b9f.nq.gz
    ├── 5a3275f3aa9706daa81cd1a15347221b6c67821a.nq.gz
    ├── 5a8898e3703303c5af6b7bd1a80ab3511322eeab.nq.gz
    ├── 5ad5c141d03d4605ea978e089cecfdbbb070b8eb.nq.gz
    ├── 5b96948dbad5056551b0d63a7e8d3b5e410d8aa3.nq.gz
    ├── 5bd58954d35a291915e024dd10be758e410d9c15.nq.gz
    ├── 5c53d70079b4b053ed1f5a8b1b0d6883120df625.nq.gz
    ├── 5c5e28d3432fe80a77af6c1b8f791b4797e038b2.nq.gz
    ├── 5c6b19361414c6cb4e8323cbbfc6e86b4cc2a3ef.nq.gz
    ├── 5cb06b979584aa4a3d8ee135d4a41164b6bf40ca.nq.gz
    └── 5cc292418636dbe9c403670c0c417c61d1bec5d0.nq.gz

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

## Source repository

[apple/ml-cvnets](https://github.com/apple/ml-cvnets)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
