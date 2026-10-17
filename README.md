# Repolex Knowledge Graph of spacetelescope/stcal

RDF knowledge graph data for [spacetelescope/stcal](https://github.com/spacetelescope/stcal), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/stcal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e0e2df9e58d17e8ff28db2cadbbc77fe840b19dc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e0e2df9e58d17e8ff28db2cadbbc77fe840b19dc
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d8a22acda747308f7eb4c798fe58d9fd47a678.nq.gz
│   ├── 0463bcac7bd544c274aa2f3af5c41a365852c703.nq.gz
│   ├── 0588294e1d2c376cea0954906c2fd81c840858e6.nq.gz
│   ├── 07ab69e0d5dcfda24effd9980b7c9b36c7e054c7.nq.gz
│   ├── 103da878e0e9a31aaaca4c6efca7d467e77cee35.nq.gz
│   ├── 10f5b4c1cbe3706cfa3f54679a2c97e6019b5da9.nq.gz
│   ├── 124424c3d9609a1c616c7207c573e828c998d2c5.nq.gz
│   ├── 12881d937fd8ac2fc5374938fa80b6085ef66f21.nq.gz
│   ├── 13b6c622151b172b48ad99b0b99b934c36064fdd.nq.gz
│   ├── 1872d924d433635338c4312b92ffa36505e52f6f.nq.gz
│   ├── 1db9c7e9ea0894fdd2ecc3cf84fead19a1aaf975.nq.gz
│   ├── 1e0741e20afb20a2b477474fe87260d249396cc6.nq.gz
│   ├── 1e266685e5aebbfe95222a099de32eb8f66b87dc.nq.gz
│   ├── 1e6f920b7a70aee1b3105d61ad1269c5c314b568.nq.gz
│   ├── 20cc68abd084f16a995b4d80388ba8afc21725ad.nq.gz
│   ├── 2455475eeab6d9928c06b5eb4590009c33259317.nq.gz
│   ├── 263572aed279873737532a59edef8e9f8a0a3bf2.nq.gz
│   ├── 26cfe7c2e9f6546af7ecaebbe8ca08e9e0da1b3a.nq.gz
│   ├── 2998430ace7552560e6d169154c13a3d6c608926.nq.gz
│   ├── 2c7d2dd5b7a91c5ae2c2b35f835d29b48e62d981.nq.gz
│   ├── 2faa37515534d8e7c1532fd4034fc8a7172e837b.nq.gz
│   ├── 312678f7717013e9d3b6807938cd47ee0f09a86b.nq.gz
│   ├── 3187fdd06ce4db6860c32b8d69e35f8c626e3b7f.nq.gz
│   ├── 37f6a3f07a4ed472a7d61c80e5e9ce76feac10a7.nq.gz
│   ├── 3a57d7b57de88e6284888b40b2c3b998e7ab119d.nq.gz
│   ├── 3a5d7d0ecb459f0a1f03ac3982d986064d47e92d.nq.gz
│   ├── 3d30b0adb01548a6421b5529cd1e8ea66699dc88.nq.gz
│   ├── 3e353b44ff8bf4195e072096e7049f1d96f5e21b.nq.gz
│   ├── 4106c8c2bae908c398d7da8cee457e31d0b9d91d.nq.gz
│   ├── 423d766d5d98463896ddaf9769b9e3d0deef7450.nq.gz
│   ├── 42823895c1d90a5e66347a1498be094cf69afc6e.nq.gz
│   ├── 42e05529f35ddaafd27add2b68a1bb989b3b9104.nq.gz
│   ├── 4315f6fb6d52f6dc225cab294da97bcf523b061c.nq.gz
│   ├── 481a9e39c9edef183212288b3545e27732e79533.nq.gz
│   ├── 4b36dbb12ec7262933c10fa22103b22760db4a47.nq.gz
│   ├── 4cac50d112aa69ec714eb84c26bb25cb960920c1.nq.gz
│   ├── 4d49fa267bf8143155ce8a5b76b6b124a7f1425d.nq.gz
│   ├── 4dc8aed3d37de80dd4b447dbefca3b75be13906d.nq.gz
│   ├── 4e850c31e87843b3ce1c28bf5c61c56c56bdb86a.nq.gz
│   ├── 4e9c79a0f37260db4581f06631f24a0c88580a43.nq.gz
│   ├── 50fe285db8a980a9d7d1a603438cc56facfe4fe2.nq.gz
│   ├── 5299257be684fbf25ba6707183baaa4c46a6ffc9.nq.gz
│   ├── 52c80a4cc3159e667203ed8ae19b6ac4954e1da6.nq.gz
│   ├── 533cebd12b8ea75ba32bb946d5ce7e8f3afb5139.nq.gz
│   ├── 544125be2416ba3b24d93cd7b8ee2f05d7852a29.nq.gz
│   ├── 576c829cd7e7ff4317ee3f902ca4a6ec7802878b.nq.gz
│   ├── 5994fdadae87cf0ba3b2afb338570356e49bc0ac.nq.gz
│   ├── 5ba8ab338402ca0e79d5d34267e7f3b657308f24.nq.gz
│   ├── 60c59e617a376b7298c75b5249fee81ba7a9ea42.nq.gz
│   ├── 6269f4df950bfd53b738621f0eb476e3115a7201.nq.gz
│   ├── 635fd8671e8ea58ce380e849db4952ff1bc12817.nq.gz
│   ├── 6a6fd46c73ccfe4dcd106d4a10e41e07c00a3172.nq.gz
│   ├── 6dd7a2af2d150ae36d7a2950bd4405282d58e2cc.nq.gz
│   ├── 6ff35c6e928a58d8d7de098c397b77bee2f8673c.nq.gz
│   ├── 712a3e386af96ef77f5e6739a51459e642d2fb0a.nq.gz
│   ├── 7756fb4b98c59430e731beba79342c00e4ad0387.nq.gz
│   ├── 7b084d7a8fbed2844e617b633912aaf9c7455568.nq.gz
│   ├── 7cac94506fe0930e34d83324dbb20abad133d723.nq.gz
│   ├── 7cdf9117090d3ae5aaae95fad54debaa36a3decb.nq.gz
│   ├── 7ec71764c242cd3e2ad79c34be8291548eea05f2.nq.gz
│   ├── 7f2406d408292ffbb1ed93947ca702093746e162.nq.gz
│   ├── 866982c6eaeaf4e2e412484eb9c280aa08b928a8.nq.gz
│   ├── 8693e79197b2579b7e8b108aa58da5947500c991.nq.gz
│   ├── 86f8a1394944dbb41a2b1a121d0787ef328fe5f5.nq.gz
│   ├── 88780c5fe76492972ef66c1a017361bda9ccbc56.nq.gz
│   ├── 889438db559c20f5eded14e3bcb18d06f25f1dc5.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b18a7581acc876f2e416e29593309566f5b5514.nq.gz
│   ├── 8d726b0f68187b16e4da4473e5faeda1b8034773.nq.gz
│   ├── 8f5e06b4bee7f7512c14a406527dd14deb5c7deb.nq.gz
│   ├── 8fc1f5af25952b123b2bf8d2124bc88289556a70.nq.gz
│   ├── 920fe5e4344fdf1dd68ad39bb7ff052554f222f2.nq.gz
│   ├── 93c7a5e54a614f5875b8b1f521450294d99307a6.nq.gz
│   ├── 947b0f899f8a67e3cfc896cd15a87f2539fb8db3.nq.gz
│   ├── 95779898fe174765fb82c5be8f826516c071705b.nq.gz
│   ├── 96a05a654ec9c10e1f4595b008f8e00f2b5cbfad.nq.gz
│   ├── 97881b1d9ffd526275aa972c7a9f8e80551318ba.nq.gz
│   ├── 9a5c8c3d532e3d5239794c58f3bb1446c99b12c3.nq.gz
│   ├── 9c717832c282256ccbeb34268d8a245d818295c1.nq.gz
│   ├── a332b567098d49c95c4168c9a4c03e3345caf11a.nq.gz
│   ├── a5003be0c816f1f7db9a670b7f0d09551d9736bc.nq.gz
│   ├── a72b7a446c0780c48add95a51e7c2bccdb93d2d9.nq.gz
│   ├── a75428849c5902e2aab5c565c0387ab44f232672.nq.gz
│   ├── abbfaab382a94a2f0adf29de0ab44ae5dbd42e49.nq.gz
│   ├── af1f0a9ab51884ff96944ca92d286d084f4cee3c.nq.gz
│   ├── af9ba19d7d55475a37a1d752edcac81763276673.nq.gz
│   ├── b42bdfa48116e3389b231ad23d1bb0d24fa2b5ea.nq.gz
│   ├── be0961497368d8f2bd30b8e3c128e12d167532be.nq.gz
│   ├── bf9512fe0af033536c7afd67f7d36f821b99b46a.nq.gz
│   ├── bfaaa8f71b1e85347b70240f99b2768ea5bb06ad.nq.gz
│   ├── c181c2d928e24b7fb92242dab334ffce1da7e1bc.nq.gz
│   ├── c1ceba37b62ecd1c819fb552357a43fca9dae6aa.nq.gz
│   ├── c26479be6ecbe151ba7e2cdc665772734194888c.nq.gz
│   ├── c3b5c11f2687df9226358474b0d466c6e863eabc.nq.gz
│   ├── c4d20d833a90df61037b39ac706059a95829d6cd.nq.gz
│   ├── ca50ad8024b003b1f901c0d7b503661b6a0dd7e0.nq.gz
│   ├── cb3c40a47cca5df671be9db6b6210deffe152c52.nq.gz
│   ├── cd701da5475f77af779361eb5ea0d86818d1a194.nq.gz
│   ├── cd7523c2d6e452bf037c37eec6c6565b79d72570.nq.gz
│   ├── ce401fe13b76598971220be7b29eb47639a3b09a.nq.gz
│   ├── d101b9e3741560bbc01401b84f3393f0d8bcee78.nq.gz
│   ├── d17ab6c3ad9f4b2489d746debe99dd03a428bda5.nq.gz
│   ├── d25b79f0cb0bb2b0f528846863674340b0afc50b.nq.gz
│   ├── d3cec1134642bddef57cac15e4a4a973c13a872a.nq.gz
│   ├── d729335adf36f73cfa64874057b66427f693da76.nq.gz
│   ├── d792ef0f0492f7f2a679ea1b2bf71880b5971e5e.nq.gz
│   ├── d7e16b3d40d0506e8fc27a1ec6d05285c4fa19aa.nq.gz
│   ├── d8539a3c8312f981bfcd9d9425db839c1f6135c1.nq.gz
│   ├── d8d91f2de80bb90204e144673b5a9829786b0b1c.nq.gz
│   ├── d8f7ab9dbc2de90cc6b8ad30db65554a812d46c0.nq.gz
│   ├── da2593d6fe3e407a41a6568255ce0259f8c0bad8.nq.gz
│   ├── dcb49f6d3796f75a345f39209776dd0c49507e06.nq.gz
│   ├── de31cd6cefffbd80cc2990164ca674105740869c.nq.gz
│   ├── e335604293b73324f3178db421b6061131ac3ec8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7acee35e51bd511e7cb02902feb5d893283b79a.nq.gz
│   ├── e8d650681521ad7355924ee95e7cdaae84167b7e.nq.gz
│   ├── e9be09e3070ecfc89362a707fa8e51e20749e1d7.nq.gz
│   ├── ea6001bafd329bf20a06614cdf3294165f3bceb6.nq.gz
│   ├── ec9db57e35d41b865f04893581c1ba305a0ccb62.nq.gz
│   ├── eddf48e9ea07a02cd09d024f214a6971e918f5b6.nq.gz
│   ├── efcfd9e231d6ad6d88d4c989e83acc33601ad4f9.nq.gz
│   ├── eff4d9ba093333745efdd834aba123d3b1a46d38.nq.gz
│   ├── effe1d0869acbae987bc4b05fdb6026322e0513d.nq.gz
│   ├── f1c4218f3de8df6c237d03f785600c98032d3761.nq.gz
│   ├── f2f5c4a8e656da9962bf7e88590de81edb6562ee.nq.gz
│   ├── f692c28793d8799d8776b8ad0916062df0766e3f.nq.gz
│   ├── f780057babee85780c26a5a82eb0898dc8933839.nq.gz
│   ├── f7f6affdd9312146c42df4b6e204ca6ef5a16277.nq.gz
│   ├── fc3b4903724ec157b8dcc0b225214cb5f73050f8.nq.gz
│   ├── fda34e3f82e3171c97aebe2f43fa0cea4398fe4e.nq.gz
│   └── fe835f71199b21e42552e3f5c4748cfe099ce266.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e0e2df9e58d17e8ff28db2cadbbc77fe840b19dc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 140 files
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

[spacetelescope/stcal](https://github.com/spacetelescope/stcal)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
