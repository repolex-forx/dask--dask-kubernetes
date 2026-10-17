# Repolex Knowledge Graph of dask/dask-kubernetes

RDF knowledge graph data for [dask/dask-kubernetes](https://github.com/dask/dask-kubernetes), parsed by [repolex](https://repolex.ai).

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
rlex download dask/dask-kubernetes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b02f631764c07c5f023e3b100ad2f13d93c556d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0b02f631764c07c5f023e3b100ad2f13d93c556d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0237db3e2fb6c1985f0c51f2e07c3aad080d55f2.nq.gz
│   ├── 038fb33d54cb4c6a1d28f3ffde13f379f24ae10b.nq.gz
│   ├── 0666e2cb211a13cf03c7b9be3e0ce278a9450be3.nq.gz
│   ├── 0bd5077175b033af12c94b79d0d37d06a4c96495.nq.gz
│   ├── 0c5ae023baae59c96798ab35507256f080d89d92.nq.gz
│   ├── 0e0c2a8900e2cab65f2d949df58004b11d9dcc3c.nq.gz
│   ├── 0e8a0eb36f4ca2c939201c0d54b5d82a1ea34778.nq.gz
│   ├── 0fcc73dbe9e388738724c292d74a5f2c69f0d291.nq.gz
│   ├── 0ff35a52235268703fb25bdda0926b506373d57c.nq.gz
│   ├── 1002bd4fd4b8d23b5f3c9c5b4304f68ef16619ef.nq.gz
│   ├── 11126df86961eb5204fd6c154a6ed798bb7f3200.nq.gz
│   ├── 14db57a58f8d2535aae9393d9668432f4db2346c.nq.gz
│   ├── 18369c26a320ccb9f77a395ffbb54497b045ee2d.nq.gz
│   ├── 1bb9459695faebae38c0428a375b91139a2bab9d.nq.gz
│   ├── 1ce4a976750b836ac478fc513ffd1bc4c9f41df5.nq.gz
│   ├── 2158381b814f186c7f3371005e1fcc3e9af1ed87.nq.gz
│   ├── 225e6b2be34f2a207fca9fd94c010b04782dbc47.nq.gz
│   ├── 23220dbe376f58edb779b4b0b4c25580d6e4f0ec.nq.gz
│   ├── 2406ff216548defffa207973c61ed99223f4eb39.nq.gz
│   ├── 28504220a22fc517bc0acfb2fe3b9421dbdbf20c.nq.gz
│   ├── 28d0de07339dd7874fe9824a9db33d63a8377372.nq.gz
│   ├── 2ab72c8f22cecec39d28396ba8a783880550656e.nq.gz
│   ├── 2b5ba4c8e44227355de686b02a1702a03bc86bc2.nq.gz
│   ├── 2fc5ed6c22c30f0dda4e1257f046dfb6288b5c87.nq.gz
│   ├── 3178dee6578005036a265645eb775a73c3313376.nq.gz
│   ├── 3630ed1cd17dbf0e719414643eb66f9beb3097cc.nq.gz
│   ├── 3c2b254f99e6d87ea6384062ef87edda4b8da477.nq.gz
│   ├── 3d8d852a9c52ff22424606a0e2fb6004177e9378.nq.gz
│   ├── 3fd55e0bcae081c322d4dc34e5e0a6a0bf08291c.nq.gz
│   ├── 401da57f84bb8e3c0059b1067d3048e554389df4.nq.gz
│   ├── 42b8ac1e9004a353d8ba1f9fec6269e22b6874cd.nq.gz
│   ├── 442949bf9f6c83ba0a4ffc7afb492cb32c7ae9e9.nq.gz
│   ├── 4579760adafdcb9db3a218cc19845c281a3acd17.nq.gz
│   ├── 4ace81ba0f8cc6f971e8f2c8c80c5000d4572020.nq.gz
│   ├── 4d73040ed4c9a2429d8e7479617f9a885bc2554c.nq.gz
│   ├── 4d9b61c55e3860e1f2cdbcda203a454c68007c9f.nq.gz
│   ├── 5133e2de76d2625478b973509a90a93a62b92a74.nq.gz
│   ├── 51def30300a3f284e73a54a4dd201731ba985cd8.nq.gz
│   ├── 552a17fb864532c6547c0f93904f1057677907a6.nq.gz
│   ├── 56a4ca6b43c085afb6348e5b77b54b5aaaf7a9bf.nq.gz
│   ├── 5733499264ba3d4b0b1757d830f8bf7ae898ef85.nq.gz
│   ├── 574e69cf88cdb9bf8e6ecdc3aa174dfd7c564df8.nq.gz
│   ├── 57d610ccdaaed1e3292f30ed6a09a6250f200618.nq.gz
│   ├── 57f1301be3538bc35ff9036dc02d6dbc37b8086b.nq.gz
│   ├── 5a74316bd7398073a215623b40e2a8848d71c2a1.nq.gz
│   ├── 5aba8e738f80ed3d1a62c705f5d8cbd440f5bfda.nq.gz
│   ├── 5b61f4a80687557648d82d38fb536f27062d8e82.nq.gz
│   ├── 5d6720cc7ae7c5dfa9ba0cd1353f7ad4d9e190d9.nq.gz
│   ├── 5e30243cf6a88e0cf6b52f62e1bc1ad10cb2e6b3.nq.gz
│   ├── 5ff6254b851ca63d292856083f701e58731c2944.nq.gz
│   ├── 60f9ed9229db5c766199a3b7c44a82cdd2d423e1.nq.gz
│   ├── 612484250045c801e5266d2ea2c999dc04603194.nq.gz
│   ├── 638a5fe074439d53296e613ab905beb77a2feead.nq.gz
│   ├── 6434a94fd715baf67d8aa51549190040da3dfa59.nq.gz
│   ├── 64a919ff4ecbf2265a04a849c19f0dd76eb61d5f.nq.gz
│   ├── 6896228e795ed8ae039d7645bcd174bc79d8e558.nq.gz
│   ├── 6abe402c7684119ba0bcac4fa98a00a16f3f9c8b.nq.gz
│   ├── 7069a232a1a1ed33f06b72d3c66fb5153034c194.nq.gz
│   ├── 70e723e281b2de242ac00a592a8f554095cd859e.nq.gz
│   ├── 73cf60a7dbc945b1e7aea9335d1ec94c1dd6b019.nq.gz
│   ├── 78f31e71b6337c436c2381b411dd63ed71638475.nq.gz
│   ├── 797d1b961c64d58b85f08b45224d5253fd537219.nq.gz
│   ├── 7cecae8adf582b363008cb9e1f04cb65d1ace2bd.nq.gz
│   ├── 7ced4ccee5a82d01e63e991feb909d742e8abd05.nq.gz
│   ├── 7dd46c93e0b285c9bdbf8137caf4d4be35a010ce.nq.gz
│   ├── 7e53a40b30b239fff0d25baf0546a26016f1e828.nq.gz
│   ├── 7f8c8bf94d703d6766fe59afddcdd78aa8647b56.nq.gz
│   ├── 8468733ba49d9a113be8bdc8d20b9b8da94f3fad.nq.gz
│   ├── 847c9ef473585d22091cde4744146c8fd145756e.nq.gz
│   ├── 85cd9a8b8ae0ecc8794cb704d2c365422ee921ef.nq.gz
│   ├── 8688e0aee51e3ff19d6b765ec83b05634f7f72dd.nq.gz
│   ├── 8a04d773aa93b744371b7fccfeabe4842bd34fc7.nq.gz
│   ├── 8c81150fe32e3740914d3b9e6e2047cc7b8a9b33.nq.gz
│   ├── 8cdce6d9124d070871961f12f4e361cd76a2db7a.nq.gz
│   ├── 8ce0229b3095b465601322f41edaf2e66359218c.nq.gz
│   ├── 91b73727b420edeb1d71c5b9936a1491025c0cbe.nq.gz
│   ├── 963c95c9508b4934e8dc3ca5e4b4e1de73a48c1d.nq.gz
│   ├── 984ae17781bad8f94990f9d42ba2f86d8281ce06.nq.gz
│   ├── 98d418a17ef1b008515668a79b87d0127eb902b8.nq.gz
│   ├── 9c7ddfc9dfd770b65a3ef11af7bc23be200d4dfd.nq.gz
│   ├── 9c99dc8dbd4a8917af0da3d83c14184432392253.nq.gz
│   ├── 9ebe794c73b8648e4b84ba5cbd7928d720346a83.nq.gz
│   ├── a174f1680d6a9f002060461c2d3398c057e357cf.nq.gz
│   ├── a23ac9e1763e8cb6041804dd89902b1dc49499c2.nq.gz
│   ├── a3818c17c36e4f2b62d938eeedc1b53d90f90f16.nq.gz
│   ├── a41c175c390dae5228d562fccbbe426d68cc3b01.nq.gz
│   ├── a780d4922ea5e5dd20382d72c53eee8df55dab2f.nq.gz
│   ├── a7ace36fb75d008b08e94809b2c98162408d9c41.nq.gz
│   ├── a834e06717e2d1efac8d3e9cb2b0cbe6800f6107.nq.gz
│   ├── af15dbb1f2c345976f1d81e0da9ccd43b41d6116.nq.gz
│   ├── b0c55688e27cf630d09dafaf67effd6664c6e4a8.nq.gz
│   ├── b1fadd862238d32ae1f4c6ad4582823e2fcffed5.nq.gz
│   ├── b2ffec609d48e1840f27af82df9b6e37d32792a4.nq.gz
│   ├── b381d683cfa761781fd1e6f197aa3090f9965739.nq.gz
│   ├── b41f3635e1036312ca36b790c7bb01e9532c1e8a.nq.gz
│   ├── b5572d8e02faa475344f6a14a2fccd1fad388485.nq.gz
│   ├── b5be99089e0967b30a34e9222534f1624d080e89.nq.gz
│   ├── b8d1cff22d178738270969edab98aa08fbaa755e.nq.gz
│   ├── ba23a5ea32fcf51426ba0908472430fe0105e2b7.nq.gz
│   ├── ba5e0eeda3e0b017dd4e7364206085ea043cc6df.nq.gz
│   ├── bb4c8ab232b521ba9e73b3a6d024030f339a5a60.nq.gz
│   ├── bd32dffd10d2bd86c7c9064cd31247205d335ee1.nq.gz
│   ├── bd72ff6d5d3d03019a1e78aeb142d21a90785691.nq.gz
│   ├── bfeb36c5d8a72ff98711e466bf9ceb174abdce83.nq.gz
│   ├── c0fbb2b0a074ab15dee384329e9b8422dec174d7.nq.gz
│   ├── c1acd8eacf8ad6feb754bd33334cc54f0eb04580.nq.gz
│   ├── c1c6dc3dadf155a9a5e7444cb1eddc9119f26ef6.nq.gz
│   ├── c2c5650dc43d557016492b7c506a888f722fcba9.nq.gz
│   ├── c32ae624d380377ae21f6883327ab26470b5f04c.nq.gz
│   ├── c33fe1292a7738cc2a7fdcbeffb2164966d7f594.nq.gz
│   ├── c66b44cfeccb9cfb84a75d21b410b1313ea1cae3.nq.gz
│   ├── c6fcbe081a8e68fa6c11cf47328eb597859463b3.nq.gz
│   ├── c7122229e5bd492a1f0f0f251a7cee99b471975a.nq.gz
│   ├── c94c213ba84751ca9d613c2780e96a42984ee66f.nq.gz
│   ├── c9917fa41dbb5559526a6b7c3323a455913a236e.nq.gz
│   ├── cbaaf68b1c327ac0216d907e404fd6c706b0c787.nq.gz
│   ├── cdf2aa3a7114bd3a19911ecdc1ffc4ceb0686218.nq.gz
│   ├── cf1eda567f7c89ac22bf6fdd4a29c7c9f82415ea.nq.gz
│   ├── d01ac4911da8d42e50194020f1bcc1ab5c806aa1.nq.gz
│   ├── d19831355c61625e8b4086a6b640873fee33da80.nq.gz
│   ├── d93a1c64f2bab9ee780a5d552964da0d54eab2b4.nq.gz
│   ├── db0d0b262e2ea59b8f5571375006d66cf56e9b95.nq.gz
│   ├── dc107c8c3b29a304d37ae5e39f358c9d3e1eb785.nq.gz
│   ├── dccb67519b71658df53499f89d0e39a035e7f36d.nq.gz
│   ├── dd2fca6c42d74eb431f9d6298a221182e2481e5c.nq.gz
│   ├── e021147d742e36679e83c60fe2cd7e2bc2ed31c4.nq.gz
│   ├── e2e801f5a8d0d5ce8267407262edea136c2e2f56.nq.gz
│   ├── e88ac7c69be3e24a8d1f2d47ae2bd867d8d322a3.nq.gz
│   ├── e99ebe60847e274f8d7d8bdbcb978f1d48ce6a6f.nq.gz
│   ├── ee33206b1ee484d82f3580b4283851af69b1f743.nq.gz
│   ├── eec873f9ab210b2c3bf1b618d0d5dd70f011a90a.nq.gz
│   ├── ef910412991107968c72c4254ccf61c43c06f179.nq.gz
│   ├── efa5ac06e6d6646c985c9849802b4946937ff46f.nq.gz
│   ├── f43d0ab7874e1d59dd2ffac869798e2ec7998394.nq.gz
│   ├── f48211111a0ad6d34424cd3626dbf8a418f17945.nq.gz
│   ├── f6e925646fe7f0208de3f7b160c0b59b543e9e3c.nq.gz
│   ├── f965ac17e1838080848674ae68ec2aa4c01a84ae.nq.gz
│   ├── fb6f9cc5dc22bfa41f6024b58789a45fe01d622c.nq.gz
│   ├── fcffe51bce582c608860623f5d04b057414ee301.nq.gz
│   └── fe51488c7066f6687ef680d6bfaa4f7768ef205c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0b02f631764c07c5f023e3b100ad2f13d93c556d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 148 files
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

[dask/dask-kubernetes](https://github.com/dask/dask-kubernetes)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
