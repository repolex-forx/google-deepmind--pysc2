# Repolex Knowledge Graph of google-deepmind/pysc2

RDF knowledge graph data for [google-deepmind/pysc2](https://github.com/google-deepmind/pysc2), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/pysc2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0df53d38c153972f1e368572ba65b1442a0fd41f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0df53d38c153972f1e368572ba65b1442a0fd41f
│           └── chunk-001.nq.gz
└── blob
    ├── 02c17abacef8af193f9f3c6c77d351232c1c87d3.nq.gz
    ├── 03b870d847ea6b3aca8fdda4789ada26f98185e0.nq.gz
    ├── 060d9f0261a01f2f2eefbbab66d4633e2d422c43.nq.gz
    ├── 0740c726baf0d66d81a89b64aceb5cfb35978033.nq.gz
    ├── 07725ac3d28a67f77536f0edaaf7091f8fb477d4.nq.gz
    ├── 086f7df5bb43f55536181d08ec13f28a7257176e.nq.gz
    ├── 08fb929c72e940216137ed4e690abeef7c5d89da.nq.gz
    ├── 094b717de71d150a8011f4869562bbdb3e3472ef.nq.gz
    ├── 09d6724b649f6dc7939e444fe283d058852347f9.nq.gz
    ├── 0a684fca26f423e42c782cab85c9353c8a24a9f8.nq.gz
    ├── 0b2cd762fbf62bffdc15e602217294b3c6cf4638.nq.gz
    ├── 0b5b5bebbeff71c5f47b30d68479cc62bfc27398.nq.gz
    ├── 0d7e890b303b1f5907aa25f6e437c6f47fee71d7.nq.gz
    ├── 0e44d9ae157815461e0538524587528e43d48daf.nq.gz
    ├── 0eddf369b120be42cb87aae5bf599374ae3fe6fd.nq.gz
    ├── 114ee1fc7aa5058b061cf7b87b223ead56ef5f06.nq.gz
    ├── 126aed43c95966c3f10d3633a3f5e3f7e1452ad0.nq.gz
    ├── 13fca57ad8847a9f26cd2cbecd6fc697911fe932.nq.gz
    ├── 151428eb4cd3a0d8964c3efd78c3a4f3d96502b7.nq.gz
    ├── 153c2445cea5380bb213bdce974c16f82dc6a390.nq.gz
    ├── 158d7e419f0a1dc3faa34cff6db053c0dd2e007b.nq.gz
    ├── 15d6e799934e4d5ad32540672535c9931f05d500.nq.gz
    ├── 160b8d4a10bd4df8b9c35d9476c74afb4f6d333b.nq.gz
    ├── 164e17e43043098315f5160f03e1b4870c5699f3.nq.gz
    ├── 1695afc0662c4490abd5df0a5492aa3de0f77656.nq.gz
    ├── 170882835c36c38ea19880514ff0b860601b8dd4.nq.gz
    ├── 17d7abe440a3ddce239f2b00fdcb5cc4f0d3b90d.nq.gz
    ├── 18a807d6b1fa0357dbc41af75238006ae80e3c08.nq.gz
    ├── 19250310362f59b99eb4d505b619b2bd8056bd0f.nq.gz
    ├── 1a51b4310ef9a5818399a1d53e194ce9e1407b56.nq.gz
    ├── 1b386a3f7d63cec525c03f481de29a50d1c592ff.nq.gz
    ├── 1ca485b7ffc8662f39cf02e0f8cb367dc82da403.nq.gz
    ├── 1cd414edd650b34ce6ac5e1d1f37484cd1f8c096.nq.gz
    ├── 1ea76a1ecbd58c609318ea8dc4bf6affd57735e2.nq.gz
    ├── 1ebf463cfb72040edb44403dd88df33e504426c5.nq.gz
    ├── 1f01ff9aa5c6293d214be3469fa8bcac8838f334.nq.gz
    ├── 1f7f737689bfafe29ec5486733638980a0840824.nq.gz
    ├── 201242b86a58fac79030869bc15ba9d384d175d2.nq.gz
    ├── 2022e99b5cdfe41ccbe314376c28d4a7a0862ab9.nq.gz
    ├── 206dca3804e017ae54a1f5d8b0c6da241c7ab9b4.nq.gz
    ├── 2136f852b2919eb8db6f42795a7cb359a2f814ed.nq.gz
    ├── 21873699bf4a2bbf97b9928c2425750bd2b07868.nq.gz
    ├── 235eaa7d7bf2f4d91375e65f1726e7a595ae4cf4.nq.gz
    ├── 267696c4a83061c19955af53842271ccf5d659a2.nq.gz
    ├── 273e8be9d5fd5f417ba92ac8a3a699d4d490c1af.nq.gz
    ├── 275e04402b1fdf7dfe536802a2a1947625355dcc.nq.gz
    ├── 27f99d224cb11f786743dc2cf05c0a08f0d5a765.nq.gz
    ├── 28044733ae8221c4807ccab0f41ef0a3e26753d6.nq.gz
    ├── 2881a4c31833bc57965abb4bd1d83a329d1b2635.nq.gz
    ├── 28cad83e07c496747c3ef6f25482235b39ce0d48.nq.gz
    ├── 291c5e3dfd5cc5f82930d399a5dd24cac2973f91.nq.gz
    ├── 2bbc2226e1ba845636d670e594456146aec5e25a.nq.gz
    ├── 2bfcfbba51588f1131e00b3d70e06e3b8f94cedb.nq.gz
    ├── 2e189203898781b7861651726b755cca25d469c4.nq.gz
    ├── 2e544c7758d4ef9a40114b1d3c76366762f5747a.nq.gz
    ├── 2fba748b68bf6d41b84f37a634532c90a66b3eca.nq.gz
    ├── 324035ea9d43f6176acdbceb66b87e03fae082be.nq.gz
    ├── 33586c1ad83f7ee12c172886f39a43095511dea1.nq.gz
    ├── 35c867154e2659e50ee4ef78670e114795326f53.nq.gz
    ├── 377b482424064bdda1765794a9ec86fd40dc75ff.nq.gz
    ├── 38392d690d048f230d406d80a10b3895c5d78d5b.nq.gz
    ├── 3956bda75594d9280a41464bcac8e198b1906837.nq.gz
    ├── 3aa68e37251c4a9d4c8c5c64d306073b01fd80e3.nq.gz
    ├── 3b861e7258a1a04e84c96fae00ac4dfa65938050.nq.gz
    ├── 3bb872847abe9058701ab24defee9689d80170e5.nq.gz
    ├── 3c135a03f5072d07b6c7a92a3bf7d98f84a833a0.nq.gz
    ├── 3e1bee423d1f7ad75fca72fdd04ad1da8603c12a.nq.gz
    ├── 3e90a26e953293be9fec4f9c75a8ad6ded205f68.nq.gz
    ├── 402b3b7d52506598d5c3d419264a6a2b8e699ad4.nq.gz
    ├── 404d33762815b95ff1e813a6a3e0a3dda15ad30f.nq.gz
    ├── 40aceb69e6d000a57c5a97d17e89a8d7530c19ff.nq.gz
    ├── 425ea7d17c89bf3895aa22d717be2e784655eba1.nq.gz
    ├── 436492c23a8db6385d7999efa1c297bb84d84eb8.nq.gz
    ├── 43c24d1c6f2c410325dff35e252d449a6a05f463.nq.gz
    ├── 44ca033d71d25d8756ec67609c64bb3b0f2b3b77.nq.gz
    ├── 4593345033a6678c46be6ba351d0554a341726aa.nq.gz
    ├── 4602b9518f60fe041e6bcc600fef49a465e0593f.nq.gz
    ├── 480e008bde8cb9ff4077cd9992c5c75fe4301650.nq.gz
    ├── 4a924fcf7af01bb8eb2987dcd22cc53b3dbc4573.nq.gz
    ├── 4b082899b0e6322c43c16ef195a7956529c13afa.nq.gz
    ├── 4b52938469edaebe2e4608877af7448b2488a1e0.nq.gz
    ├── 4bfc153ca4b7e29bdad8dba43fd5fd9b20b99aea.nq.gz
    ├── 4d43ab89e69b14bc559de5e70718994e05ab57d8.nq.gz
    ├── 4e2e3c64374473d8e4675e7de98b65c64c601fa6.nq.gz
    ├── 4e31cd8f0fb14c5e76285c568500b735719e5774.nq.gz
    ├── 4e5219c6fcac6e713a0973da46ad57089384e622.nq.gz
    ├── 4ec928134a3928e2551313b202f9fdbe825f2f70.nq.gz
    ├── 4f104d626118af84f2fb58b27a8f03840736af37.nq.gz
    ├── 4f758cd438569d068ba608c982ff4225fa826b49.nq.gz
    ├── 50c6ef34e6de1ed54edede8dd000d256e5d43280.nq.gz
    ├── 51dc082fbdd6e381aea78efc1a5d10baf7a0a9b5.nq.gz
    ├── 5578bad987fce1f1de858ac2b26ec1df4040affd.nq.gz
    ├── 563d1cb1dc2f6714fc8f67bb36f6ad0538e3c589.nq.gz
    ├── 58e008a4ae4d7634a884cd5141b65c8af16787e7.nq.gz
    ├── 5a0023c8c21597152a1b20a5a303dd48040cec46.nq.gz
    ├── 5a9100f21982f8ae51026a9e3422914f2af2ebe3.nq.gz
    ├── 5bc0e5ea6f3a6b5f9525fef59c3a1c02841aa613.nq.gz
    ├── 5d32a709d2cc9bbba01d7ebffdbde794f1702f49.nq.gz
    ├── 5d4962d78486f9b7c03477c24a2ece9637274796.nq.gz
    ├── 5d59181e040a4bb35c477a51a0a118b6f35856c3.nq.gz
    ├── 5f6b087828d0b34bc817314f1243e7b1d3aac529.nq.gz
    ├── 5ffb0868f81d96225114cd1035889ce4de329008.nq.gz
    ├── 60519cf8afce474826b061b7ebfff10b829dd8e5.nq.gz
    ├── 6135c97d38b20a6601053b615dca944161bda816.nq.gz
    ├── 631152a6826e61a7ecfa04cd889787d18829b073.nq.gz
    ├── 63c5f7c3c57274999c97499b905f3929157cc0c2.nq.gz
    ├── 6457919d51165b385b38450d007f793d8d405d92.nq.gz
    ├── 677800375c4ee69a23de351f0a99145080db0994.nq.gz
    ├── 67c3349ac13da39ed6f5c7d1ead0a330b12fcc65.nq.gz
    ├── 6902806dcabfe5b2d494eb059a0ca5e74cb1efa2.nq.gz
    ├── 694530fa08e8b6b8941902eb4fbe043ae068073e.nq.gz
    ├── 696898821a6d8bd85fe4c4caa8e774f4733bb92b.nq.gz
    ├── 6b56529f40927819054217c063a2805c4e49b0f6.nq.gz
    ├── 6bdeaa55dece167f830204ca94e144f3c16add30.nq.gz
    ├── 6d23175a33cee775bb879d02c3ce6ede4eff4921.nq.gz
    ├── 6f3f55b7141777ef21f2170f64529d29a16ce43f.nq.gz
    ├── 7111b106e06bb9df52e2894e81e28c5db1dea911.nq.gz
    ├── 714b45e2f41dfb0946634a0ab179d4e804953212.nq.gz
    ├── 7282b7dabe46ac80dc6c73a8deabd4b8ad0cd31b.nq.gz
    ├── 74e2561904417565c3a4aa0afe5805da068295cd.nq.gz
    ├── 769493cb5a844c920e0f0ffb89a9bd231783c8c8.nq.gz
    ├── 775237a793334f0efbe0dc5f776bdfa68336d993.nq.gz
    ├── 78647b05c96d51595cf84ac5efec5adbb86d6db5.nq.gz
    ├── 791a734de3808f0e032b1160274f8999555120d7.nq.gz
    ├── 79394ebfb5772fd55cf7f7042574c73e5fec1998.nq.gz
    ├── 794038879a10fa3617887d4203c476f7161e0034.nq.gz
    ├── 7a2d2f9fe6267987cae9caf8ea747e64e0d1006d.nq.gz
    ├── 7a2f8299d16b131039c874813342ff505866c692.nq.gz
    ├── 7afdc1238990970ad5f7b7ab619f5e02e3aa87e8.nq.gz
    ├── 7b649b9df60691a6696692511bef3f163907c21b.nq.gz
    ├── 7d86e583243c11f4088067244161506aac25dfde.nq.gz
    ├── 7ebda450aee5f82c6d64f9b32ce65ce2544a0c17.nq.gz
    ├── 81b94e0db088d2f20f39268e262733c6abb2f3fa.nq.gz
    ├── 81da36fc5782010e2f5bd771df73a3da162aa1a2.nq.gz
    ├── 83777603d562e8028e6a06115508c8fd35963555.nq.gz
    ├── 84493b649c82362bfc18033c99302c28220d510f.nq.gz
    ├── 873b6255c3cb7841a95c6800afa27adc0a2f8dc3.nq.gz
    ├── 87e1a4b3f1972f1698c7bc95c376b419104dc757.nq.gz
    ├── 88d99a85af769f495aa5b8f60105650f244afa4b.nq.gz
    ├── 8918c66f8e65a93b6d2e3442bf12cc0110b0ad59.nq.gz
    ├── 8a82cdedf300bf2aad7a2ce1b418559922da1acd.nq.gz
    ├── 8bae06814b2bd812b9008d45b08a37acd7ad9253.nq.gz
    ├── 8c35ecfd7133aeac353696fe330cd73bfa7bc6f8.nq.gz
    ├── 8d6a52923b23094f47c571f2ef2357df05ac2b68.nq.gz
    ├── 92d5616ba9926ade495dd8409f22708a94f4b767.nq.gz
    ├── 93aa4ee2341d123d8e79c83c73b2528a5ebe5639.nq.gz
    ├── 957d480bc1ff50c979e64c7d0f67e25f1c437fd0.nq.gz
    ├── 95fa552efc0c0e719d8cc4a5492ece553467866a.nq.gz
    ├── 98256e58ee78a2c75b93ffe333bbd9b0050bde5c.nq.gz
    ├── 99698d7643aa92254eba3828e3dddce79fc7b2a2.nq.gz
    ├── 9b978423670fcf3bdb492c86724784b920c9dbff.nq.gz
    ├── a05d0423e9321037d3a7aaeff7676cf20e4db953.nq.gz
    ├── a1b39ecefac1959736e0c75bad51790c8736e4ba.nq.gz
    ├── a2ed8dfab65bc338cf99dd5f05bdd75807c8753c.nq.gz
    ├── a565134a2cdd6d5a1d7bc0d5ff79028ad2f519a7.nq.gz
    ├── a769401ab8da879f744e80edefa0dda9b7982d0a.nq.gz
    ├── a8c8838daaa3a5b7bea65a8e202715bc7285d1a1.nq.gz
    ├── a9cb61539286073e579af91bfe65e6817c505d3c.nq.gz
    ├── aa53790a5ba3a7459f1bb54e925bced1d03adf1d.nq.gz
    ├── ab0682cf768cb0402921672eba1f238d01681250.nq.gz
    ├── ab0dd2037bbe038f3a3bc8f4745c7682c9df06da.nq.gz
    ├── ab434e8aa2d4d9686cd6b61311c02adca274907f.nq.gz
    ├── ae404bb75b9c5ad48272744aadb42031c06709d1.nq.gz
    ├── ae7c78ff2430e687eefbe3a67f9390a6dae4038b.nq.gz
    ├── aeee58213ec38fcfde31de4bbbaffd04b375f3d7.nq.gz
    ├── afdfe50e72e0e63f3b2bd373e6147a170277ffdc.nq.gz
    ├── b02fa64736655e7d1328197a397cebb4750c280d.nq.gz
    ├── b1620c71621000d7ddb333d1b80bbfb38bf7cc56.nq.gz
    ├── b179df0b681017a76887b87b3622dce54f59048a.nq.gz
    ├── b1b13244dfeb4a71a38087d7029b0074e269b58d.nq.gz
    ├── b253aa328c679c8236142511b0f0d21e3351784c.nq.gz
    ├── b2944e9c308e9c3161a72773644ae1c733745710.nq.gz
    ├── b3508c2a11c0c4ff76ca3629f071777c84bb0f43.nq.gz
    ├── b448f59d96496180612caf69070ea67546124625.nq.gz
    ├── b519098ef0da954f9e323072de656123beb20377.nq.gz
    ├── b586bc827884ed2fd3ea3acdd5d5073ef1bc2ed8.nq.gz
    ├── b6ada4791fda1c8f1482bcf7f48b8bdc108cb638.nq.gz
    ├── b7e9f56b7c27b8cfee3444b144e0bec967895477.nq.gz
    ├── b839a3f00ff8aa9576d56322acdf56c8a757d130.nq.gz
    ├── b948c641d12b56fec1fdb523e166201c727bca3d.nq.gz
    ├── ba38e397a6c04cd89779f392bc87efe7dc9697e8.nq.gz
    ├── babfaed0341ca400fa180385ac89c6ffc7851683.nq.gz
    ├── bcde25970471060dce645e721e14da16cceb8d5a.nq.gz
    ├── bf0311b21b7949be0b670d38bdcbf7776f84d099.nq.gz
    ├── c0bf06202f04084eccef7a409768c0273d17677e.nq.gz
    ├── c1273127642be0ce5a5d9e5e585d392ee77a6374.nq.gz
    ├── c2312eed085c9d710a4fad058464014a0552b13e.nq.gz
    ├── c28aaf995a69052fdabd30abd51b35ca25069d94.nq.gz
    ├── c504c28f0e2cd6ed8ee6d5af782a6c7c129cf228.nq.gz
    ├── c53b219e874e72130fc165ca91f2081cbada8955.nq.gz
    ├── c599f9d94f53419c8abbc94511303c3397a1ecba.nq.gz
    ├── c8c86ef7b8148a6062724dca2b7010d952696b62.nq.gz
    ├── c9ff3f54d1f55ea08027a33b0da28cdbc1bf7424.nq.gz
    ├── ca42d00cc1d03c7cd1481ab3c829c9fd1bc1db7f.nq.gz
    ├── cc0b8ba2cbb4413644c2a584d1c5bf8445221716.nq.gz
    ├── cd6912701688f518c76c41db5f3542f0cdfe606f.nq.gz
    ├── ceb93f6eb3e288be6dfa8b8fc55dc7cdb6a08c89.nq.gz
    └── d1ccf7df4c1b36ce6926251df683bc2607e1864d.nq.gz

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

[google-deepmind/pysc2](https://github.com/google-deepmind/pysc2)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
