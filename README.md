# Repolex Knowledge Graph of zenml-io/zenml-projects

RDF knowledge graph data for [zenml-io/zenml-projects](https://github.com/zenml-io/zenml-projects), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/zenml-projects
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 544862bd165982fb40d23d44bae7b4108aed6975
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 544862bd165982fb40d23d44bae7b4108aed6975
│           └── chunk-001.nq.gz
└── blob
    ├── 007640b782b816a809d48f16f28220b06528e1f9.nq.gz
    ├── 00cd62634ff9979dceacef5673a2db65c550bfc6.nq.gz
    ├── 028a0865b67b51682c11d95d2a5cb8313d68dd0b.nq.gz
    ├── 02d2efe82f836a524a9ca9198a8af4e87161147a.nq.gz
    ├── 039ebd0d71d5ee89bd04e55a82f7a0cac9386751.nq.gz
    ├── 0462cde29955be4455d271b2dce5767d90f8740c.nq.gz
    ├── 055bb6facacc5324ed2e44701550b669339170bc.nq.gz
    ├── 056c6f8d6a1fc769e6b223be13ecac3083138401.nq.gz
    ├── 06473701cfdae1d4afe4c5e6f166fc5ddf62fb93.nq.gz
    ├── 06c22038cff7969e857b724d1691fb219d7572a1.nq.gz
    ├── 06cf292f376755f6f3440e6682f42461400c3749.nq.gz
    ├── 0751a3a8992091f6b8133715cd230b629c9314da.nq.gz
    ├── 07a9478f0c9339da300a954a6b7a82d0973dab76.nq.gz
    ├── 07d922faed544e4548c0ab7f3179e52127b411df.nq.gz
    ├── 0805615d1c48480e6264679b66a95ac4139865bf.nq.gz
    ├── 0862735c076bc3647dc193c0bdf3cc5dfb446fb6.nq.gz
    ├── 08b398eab2f7033f2f10badb04d3c83d08b08fcc.nq.gz
    ├── 0969e542269ef95d223cddfafa673bcaf9098204.nq.gz
    ├── 09d1d9b0db7c864289e62a78ad006f87ffaa502b.nq.gz
    ├── 0a47c72af932e78314b57aba96ef8fe2668440fb.nq.gz
    ├── 0b8dc54ade5eba72015d230a92eb5284025bfc22.nq.gz
    ├── 0bf08248b31d35a4f40261fc5ba97a988ca3950a.nq.gz
    ├── 0c77775739b3a29158c3c03522beee42595e6d51.nq.gz
    ├── 0c95e73cf9a9ede92f218c7a20e6d27c344482e0.nq.gz
    ├── 0cb4de0e0013d2f4b2561b7affb49389299c91a6.nq.gz
    ├── 0cea03f2654bb9c22c542aed7c44692e648b4cd1.nq.gz
    ├── 0e0b872f7757614dbbb4b3aadae25311377c7352.nq.gz
    ├── 0ee82fc8a6fffc9d406f2f3f722a5aabc5cfaa75.nq.gz
    ├── 0f09cfbcf0252cf3752aa219bcc8719e24cafa34.nq.gz
    ├── 0f0ec9fe5dae2a403f13c91053ee2d22e7252160.nq.gz
    ├── 0fd2df7801bcb279a09a5e19e2e412e1c9e9c77f.nq.gz
    ├── 0ff22b8335edf06f72e6101cbd734ccad05dc2bf.nq.gz
    ├── 11c2a8ad304edaa5335e788b1502fe689fe7f812.nq.gz
    ├── 12d82e0b8804966ecf53aceb1a06d8afff99198e.nq.gz
    ├── 13b19865c9796a6bce841acf0f05f498ec2bad2c.nq.gz
    ├── 13b5c15b5f41bb6dfa1e7e45e482b2338201a004.nq.gz
    ├── 13d17c554fbbf71d633b4aec560ccb88749dac19.nq.gz
    ├── 144858e7707759829628db7ad7692cb2f52b76b1.nq.gz
    ├── 1469eb41d26dff090e1181d57a24eb2eacfdad0a.nq.gz
    ├── 15b84cc5d97d166ceb46e2740df71bfb052862ab.nq.gz
    ├── 15e1257511244514876c60c307a42b499853e162.nq.gz
    ├── 15fb5d7f867b24c9b93c30822626c60af86c5752.nq.gz
    ├── 164d7ea109e028b1f62afd2e97c68f1c11b01762.nq.gz
    ├── 17e59870074718101d584557eab1925179f52932.nq.gz
    ├── 19b8b08c0c8e1dc84f3a768689b518c3314f656f.nq.gz
    ├── 1a04ed46236b4cc56ef8b39fa27a999005cf9a7c.nq.gz
    ├── 1c00a8378cd98b8813b284d300eab6139e224b83.nq.gz
    ├── 1d884084981eaa7ae3a7d676b87086049e37c58f.nq.gz
    ├── 1e0a8ac5dac0af2d2749d72b8d20e905d89b215d.nq.gz
    ├── 1ea3730659be90e837c627404b4be6944e0945c4.nq.gz
    ├── 1ec648f15ff33bc379587785f647ef576f753513.nq.gz
    ├── 1f055c197d70ea3e82180ab7abdbc627870cfe0b.nq.gz
    ├── 211f4c1bc9ffc4883b12ac618039f343645e478d.nq.gz
    ├── 21d25123f2b2fa970a9b268140c21b3ec5e6bd32.nq.gz
    ├── 223b5c7e25a5c0215918fa7234ee48ac5d8ff0bd.nq.gz
    ├── 235217725647f9e44c87ce685c31c81ca27ac83f.nq.gz
    ├── 2386a548dc16fe46135a3807403e3b007bdeb208.nq.gz
    ├── 23e271a8a3d79deff83f5136c68b54f4bbbb56ba.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 265bcd40f399396d0b724a55825398b0073bb62e.nq.gz
    ├── 26a68f7dd12394d33eae170788c4c8a9abc04ad1.nq.gz
    ├── 26ba865609759abd2d7e6dfc9f407d02981b5a94.nq.gz
    ├── 27c41526102de3433f76742f07d5839cdd97b739.nq.gz
    ├── 28422e716695dbc4c49b66ae7672d547920ed079.nq.gz
    ├── 287559b15242c947217183e23ec6bbee31a4efbb.nq.gz
    ├── 297452d0470ce6f7d4c809d119f6a0d045db911c.nq.gz
    ├── 2a00be32e9bbfd06452f6e06f470a6a218d7a63b.nq.gz
    ├── 2aafeafdc345367cf239163ed7bc47d4bce73395.nq.gz
    ├── 2acfa8df5c8af012f3206cf0dc501d736afc420f.nq.gz
    ├── 2c5c3bb76d6fba3233b938d9f9a9aaf51ac5e8ce.nq.gz
    ├── 2cd901621e5b255435a834cdb2b6bf53856deb14.nq.gz
    ├── 2ef83457a1e6cdd6d26bebac071838f076cc5e09.nq.gz
    ├── 2f2a0e6ad37f0b97f82d9f037c4e2ce3a31fa303.nq.gz
    ├── 2f4073e52ec307b92a66bb1acd27b630ddeafead.nq.gz
    ├── 2f489e7af96bcda96480da8ae617e52b3857e788.nq.gz
    ├── 2f81e713c6c0ceb8cd2004d09623fdefe3de1109.nq.gz
    ├── 2fecf64b26726ce19ece1ddb7acfb46d1a05f14d.nq.gz
    ├── 2ff32a3be9772088d1829ebcbe3227f3ff14f7ab.nq.gz
    ├── 300bbccc2301049061dcebce3210cfd6f51d0743.nq.gz
    ├── 30d577500e445202ee8a2db48e4891f372a2ab67.nq.gz
    ├── 31641f22af087d49f98840448bd84f86b6b72b53.nq.gz
    ├── 31e4300b713dc46e78fa59ca676026c8938b5916.nq.gz
    ├── 326f80a090a67febdb9937d31b5090b6415b8661.nq.gz
    ├── 33263262e5ea855770a1e941ddf2e6e32ee96a1a.nq.gz
    ├── 338b547117d948ce8cab1a7c5ce342b469e1f463.nq.gz
    ├── 341d88705865dc49a79f636a9a612e880aecec70.nq.gz
    ├── 34d3ebc282458fe9199cf1f80607a5529ceb3542.nq.gz
    ├── 358183fcf96facf81402289af48dd30282e3dd37.nq.gz
    ├── 358d5537c8c5b66e2f2e3696ce43b83156b417f0.nq.gz
    ├── 359abadb2d4c92fe71757fd61b7ec9af34709d3a.nq.gz
    ├── 35e406eae805b49775febfd762c705c9bb460992.nq.gz
    ├── 35f26d3bd29e2f5bc220e1ff370719fe4ad7192a.nq.gz
    ├── 36148b510b0753869644c605987f4780510c18f9.nq.gz
    ├── 362665d842dc7d3853f6a2a80baff995d2bf3121.nq.gz
    ├── 37be1479814dc5e97ccbee1db9e3cbbf776dc720.nq.gz
    ├── 381591a3ad9e9cc932ff3ceb46b98454b4244ece.nq.gz
    ├── 385231690d974a85c36ce9ad12e390f9e97bf522.nq.gz
    ├── 386b53b8c3091d620b2d24b129aa0958464a4311.nq.gz
    ├── 38a3676d79de7db3ddc09c39bc2b24ce47b08f92.nq.gz
    ├── 38bc99643a785cd56f32cbb001903420475fe21a.nq.gz
    ├── 39a196613719a4c023cf41649a65f3547b82484f.nq.gz
    ├── 39c629ba3571aedd5ed30177f5761895a2561108.nq.gz
    ├── 3ad666de72cad4ca1d484ae2d58c093705e2af86.nq.gz
    ├── 3adb796247cb789fe0f1a3d09ae22bfa1b63f782.nq.gz
    ├── 3ae835cae9b690822464be122d4a335d77a8180c.nq.gz
    ├── 3b48ec62ca1ca11393cb8292288a1c83caa8a685.nq.gz
    ├── 3bc7ba2d503f455b1ca3c9c8021f0d3177c48bdf.nq.gz
    ├── 3c097d1c473c8ea6d7f579a9bba838ff380759a0.nq.gz
    ├── 3c83a127aaf0e4d8334c9bed81a56a92d2bc7f39.nq.gz
    ├── 3cb888f4dd5a2709f78a69aa8b418e1a3cb48b2a.nq.gz
    ├── 3cdaf4044897ecb1f248909a5ea41d582d405b2b.nq.gz
    ├── 3d3ca42ade26626c4b2b8f1645f0eb419fe71098.nq.gz
    ├── 3d544ac03c67f229a3c109fba50ddd58d57e1aae.nq.gz
    ├── 3f565edcf10f558f26f015b3436b3fde45b847a5.nq.gz
    ├── 3fc4b5f9b266d5cea8490cfdf39f8e8f84116d4d.nq.gz
    ├── 3fe0f2f55c5874c8384eff7969a97d000667516e.nq.gz
    ├── 40839d86208cd35ecdff0dc57db2310b9150e1ae.nq.gz
    ├── 4131e911580b06c23ffcfc6c3458914cbd51c1fc.nq.gz
    ├── 415862b558838463814c10d937b14a0ba3c3c557.nq.gz
    ├── 419d38beebf00da656bdffa55cd8fb51170f7a6c.nq.gz
    ├── 42704739078f5bec1ba442a5384a7cc0f26899bf.nq.gz
    ├── 429f44c7704d982c68b2de0306392632dc6b7b64.nq.gz
    ├── 431d03afcb3e6acb0cec9b0dab76ada06526c5ca.nq.gz
    ├── 432aed9753ebf284f4eaa16ccf5e3408b31dd276.nq.gz
    ├── 4398360451bdbeaa9b99f3d275caa3a4640f974e.nq.gz
    ├── 43aa74bdccefffee5bd3154f80e533122c2a6ea6.nq.gz
    ├── 43f9f81035bb2da173576fb7215e13345878a87b.nq.gz
    ├── 44a089963133eed8a746726a0012bde1c3579b4a.nq.gz
    ├── 44a2f70773cfb906079db2497a0a0f0a66b91742.nq.gz
    ├── 455f4d7aed45e1272b330a2054eab17dbff9fd12.nq.gz
    ├── 45c5740052cc894c3834572bc7ff97cd15271752.nq.gz
    ├── 45e38e1f1a682884cd10cbd8f53f7d7c45cbddd5.nq.gz
    ├── 48c8cc338be85b6398dc40d602f462e5aa845b99.nq.gz
    ├── 4905e4712365d8739e5bd7193a362eb29425dae5.nq.gz
    ├── 4985902835e0fd3c999b9c6c9e160d3d116c4e4e.nq.gz
    ├── 4b202bfbce9d77b8dc67a3c8e2c9b72c996bd472.nq.gz
    ├── 4b667b312d31a60263f2fb4b3036df13e4c68668.nq.gz
    ├── 4c840019cfacaebcf46a7389fc3066ae0b936334.nq.gz
    ├── 4daaf1504eeab4f156013a6d6a726069eb04aa51.nq.gz
    ├── 4e1d963991486113784fd3f5aefe3a006b3cb15f.nq.gz
    ├── 4e306419c8501e19d631e63497253ca9057c0a61.nq.gz
    ├── 4e97da2a3f4a96616d7271975c62fd9e55d7b4a2.nq.gz
    ├── 4ed5e4d6518fa1dd541db13f9df7f45650cabbad.nq.gz
    ├── 4f624cec849847ae65938f80689a5253dd3accf9.nq.gz
    ├── 50c5cce9a7302f1bb5dc5d15c0eadb199426e296.nq.gz
    ├── 50d59418157d9822be66fca518a03f5307e4ed84.nq.gz
    ├── 51f4040b0db61f7cabb13971bebd899377740024.nq.gz
    ├── 52227cb2fae3c30f7077dbff5412621fbcc4d0eb.nq.gz
    ├── 52a69530d799f872ffe3d60352618f3662715519.nq.gz
    ├── 530b95eaaae3e4f66a0bac3c20dd4495972ce774.nq.gz
    ├── 53269e2f8c1bced105a596b86abe915d11b3da89.nq.gz
    ├── 5334aa7ca6864819631aad2993cc42f68d72a6e3.nq.gz
    ├── 5366e3021a00198820dcf0fa34a79e7b24285ccd.nq.gz
    ├── 540bb73395adf4e9440e92f653d7d55cb5e7cd73.nq.gz
    ├── 5558b7f3ab636e2ddbeb305a7a669de274c60d69.nq.gz
    ├── 5594a79642e631c0df46d00b96ba7d5d00622f2a.nq.gz
    ├── 55ee0fa1760d20fd6d09998f9d05018909da7750.nq.gz
    ├── 561b5d6a37287a6c633999dfe0efc5fbd07b0bbb.nq.gz
    ├── 56cb9789c134257148e1bff6419ce93e5c50c756.nq.gz
    ├── 56cfc47f88452eba238736e21923015ec32d8054.nq.gz
    ├── 57b5706ec741b74507ae552a8e2d7cd8e56d9e05.nq.gz
    ├── 587974d074435b61cd253b8d33fc3452f9b109c8.nq.gz
    ├── 58b6d46372a238a7577ee16301afabe1697d7294.nq.gz
    ├── 58eb5980348e651e3bb83e34c75de59f110ddaa2.nq.gz
    ├── 58fee0b56c0948e3623a472a888796b73543d124.nq.gz
    ├── 5a926dd0b65b4a81113df9f09fe2df77dcc5d7aa.nq.gz
    ├── 5acc79b084c7637e572300bc07357afa498c2876.nq.gz
    ├── 5ce505f3446df99b541b206ab409a8b4fae3eee6.nq.gz
    ├── 5d0c5c755f88aef3016eacf36adcc3d7236dbf7a.nq.gz
    ├── 5e0585391669924d49dbf5f0917fe77501072318.nq.gz
    ├── 5eb2c64275194b0ba5c78bc715f0145f27f6fe17.nq.gz
    ├── 5ecac286c132690e97faa716c5faba5bb09526ec.nq.gz
    ├── 5f4097aa590212a4dab089503704d468706eeebd.nq.gz
    ├── 5fada61fb9f699933fa73e2bfbfd23f59859520e.nq.gz
    ├── 5ffe01d133cfd9972f90ca337ee07c50bd4d6885.nq.gz
    ├── 604083e0e5b67b0e223235598c9c8e6a5bc10ee6.nq.gz
    ├── 609e97d2f6fccbc14a197e1ca68e3d67c974f398.nq.gz
    ├── 60e8edf6c1bc6138c5c332310405fc4e03fc24af.nq.gz
    ├── 615ec5e0936ccbaecd1b2b19bab65d5cc4725e71.nq.gz
    ├── 6267b8225a1e9102590cf99de0c258df77c1bf0e.nq.gz
    ├── 62d3157c3889c7d2f6d5709f469ecc0e4269de69.nq.gz
    ├── 64fabdb77fe9cab4904e2a373ae656b838b20f8b.nq.gz
    ├── 6510a1f4b3ba3f6644ff83a13292cdf251529880.nq.gz
    ├── 65c0ff02841dc86b7660a4bf01b8724c9c0c3e70.nq.gz
    ├── 65ff28fee6264baf8b4de79f7247b26f8a69f35c.nq.gz
    ├── 66cfbd1add04dbe94f7bed5b9c3176449393106e.nq.gz
    ├── 6760a28bdbb897b800e672f42a8894fa8190ff88.nq.gz
    ├── 6762482150bd01aa8f6ee2d675fe4e72e17a746b.nq.gz
    ├── 67dcdb9262e201c4463776376c41f63a6c1b712e.nq.gz
    ├── 68c3218b270a11d0ad980a5d9a2a09566207ce04.nq.gz
    ├── 6b2208e066ba1993da125c32c198275b7dec537e.nq.gz
    ├── 6d785db6cdbf6744a968af1f796a2560c5cc4789.nq.gz
    ├── 6e78dcd8c455e329dbc75e8c6a40973a7d108911.nq.gz
    ├── 6e8342984ecc11dbc825220e60beed8251a0f0ab.nq.gz
    ├── 6e9fab25377fa50441dbf348ab009b59f5da5d7b.nq.gz
    ├── 6ed805c040bc29c1e45942020b028da311be32a8.nq.gz
    ├── 6ee60a5875a2083d0b97a4820dcde70ef9f9ad1a.nq.gz
    └── 6eec718dff15bbf1a390d4514fbfa7b20c62c448.nq.gz

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

[zenml-io/zenml-projects](https://github.com/zenml-io/zenml-projects)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
