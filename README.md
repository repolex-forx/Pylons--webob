# Repolex Knowledge Graph of Pylons/webob

RDF knowledge graph data for [Pylons/webob](https://github.com/Pylons/webob), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/webob
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c0d70f985ff6f04dcc59822ca5216cfd0ada666c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c0d70f985ff6f04dcc59822ca5216cfd0ada666c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0061486ac102c21054cdf0858b547c8ee9c7739b.nq.gz
│   ├── 039a7726db8c37314c86eb2f71cd050a6338b3ac.nq.gz
│   ├── 06e0f6b81fed56ddb90d682f2f546dfa4b4f1269.nq.gz
│   ├── 11cf343335cc4f23ddc2a84e2b02616e48354372.nq.gz
│   ├── 120ad592e481ad0bda6047661c78bf4bbfd10afd.nq.gz
│   ├── 1271b3d64901af1c11a9f0e0ee1501c56aaed936.nq.gz
│   ├── 1540b5b3537d061730401d0da85d6d656c79d53f.nq.gz
│   ├── 1b32d9e7b11dec2c709dd7699b93a61cbffffdb6.nq.gz
│   ├── 1da8617df6da91fcf1418a8bcb24dcac0ca2c219.nq.gz
│   ├── 2369791c52f5cb99c88fb24dc37ecf453e70804f.nq.gz
│   ├── 24acca0bae81753b19e761f2ddd00814944b445d.nq.gz
│   ├── 298a092a63816e8fb3ec1c7ed9d3ef725457be3b.nq.gz
│   ├── 31053bd675fca364e473debdec34f80067f72395.nq.gz
│   ├── 35ef861ac81260e451c41ffda1871c68469a1952.nq.gz
│   ├── 36631e2d165a6178080665b44bfb17c62f08ab0b.nq.gz
│   ├── 393a144e044ff9e45b9f4e29c99e8c42eb7f2f88.nq.gz
│   ├── 3aa271e8227b9efa2ab025d3489ea6fa24249ddb.nq.gz
│   ├── 3c9e7a2f0440ddcbf2f72c42ecfd190962d2901e.nq.gz
│   ├── 3e9420eca3593d7c62f1682066e722db909f4977.nq.gz
│   ├── 40bac60fd06ec40d18286b52c26a76ec9971f2ed.nq.gz
│   ├── 4299a90bb2579963b54411b77dafb61c255368ae.nq.gz
│   ├── 42fb741c181a2b6e28837e9bac21167b8f04e9a3.nq.gz
│   ├── 444115dddaf4c3207f9f1e083d34be30a4c3baf6.nq.gz
│   ├── 487954522bff75b0747815475058526c93c7baf3.nq.gz
│   ├── 4bf930fa291a09c67bc8fc61d4cb0081201719f2.nq.gz
│   ├── 4d50b696e886d8f93e48d08c3c20e14dfb1104b7.nq.gz
│   ├── 511c42ca63f2b8d34f466953d7cd2fd80062d972.nq.gz
│   ├── 51628588e8adbc263f03f9770042876aca0feb2f.nq.gz
│   ├── 524cbc48a64345fd12d6c3217aa814513f38be7a.nq.gz
│   ├── 55fbef9ea114effb31bc45b197596f1a997d1e8b.nq.gz
│   ├── 5737055179c779b424f85fe92776d847c5e82905.nq.gz
│   ├── 5849824c9eb4343279946f57bb83a4f77ff6873f.nq.gz
│   ├── 5896483a70262d3aedc9d5827dcd4c10f420cf30.nq.gz
│   ├── 59ff3e1b9c8ffd2366f18c479142c5812869ee47.nq.gz
│   ├── 5e503538bd802a1ecc8967ce31a7466148ea1a5c.nq.gz
│   ├── 5f2daf52c1119d3286c18c2cb80375bd6b911637.nq.gz
│   ├── 639ca09167fc1daee6233b262746ac0fc06164ae.nq.gz
│   ├── 63ca1ff7642ff7da1020e71682d2a023011e9fdf.nq.gz
│   ├── 654166bff388162685904eebc070d173c6951dfc.nq.gz
│   ├── 654a8090052194ef6a6295bdb05e1290139ecac7.nq.gz
│   ├── 659df805b39dc1e87e1b2ddde55f39a5fc9dc7df.nq.gz
│   ├── 6a385b1e0d64f59bf146505fa7d6a1bd614d5bdd.nq.gz
│   ├── 6cf2576300e5f109d2ef39c97d30e2354934d773.nq.gz
│   ├── 6e08d0c524c99a6befe37106e6d9b58c7e43be0c.nq.gz
│   ├── 6f8db571ff658e82343b61dc13ff6c5aa5c15772.nq.gz
│   ├── 70153d7301cd9c6dc6601c7ed3fbb8cee82f9ddd.nq.gz
│   ├── 70c237c81c98a030d894f2bebff808e3b7f4ca96.nq.gz
│   ├── 7230fc96a36e317eba9c1c07d2d6ced21c3e8b1b.nq.gz
│   ├── 736a68267931b4feac38ab43657c20f8f0f0d0f8.nq.gz
│   ├── 823bd4994ac8b47f11f2ab7ffff0a2c4c77d1a6a.nq.gz
│   ├── 86fbdfbdf0db834412eb27c72b5ed83b187fcbc5.nq.gz
│   ├── 899acbbc24d601c89d0e987fb330856eb9428c7e.nq.gz
│   ├── 8cfd6f84bae1811f4ccb41dbb0cfacadd520a8dd.nq.gz
│   ├── 8fbe73f79dab39f44e097e530ab9b5f56d2b3997.nq.gz
│   ├── 90193a5c17705c91426a7b7b2273559941c404ae.nq.gz
│   ├── 93b5c6031639911e793ae9df0e51acb0f21e2900.nq.gz
│   ├── 97486b1e86df7fe764508eadd22c3417308cba98.nq.gz
│   ├── 97cee5a4fd8663d5f438be62092f5bc5c46ba395.nq.gz
│   ├── 9984e6801b805183f59f962aa4eac90d6737c054.nq.gz
│   ├── 9c9f87ea6f912e147958c78e2f190d39962fe3c2.nq.gz
│   ├── 9da7285a22c49d7806e085786cf1567a9b07c4db.nq.gz
│   ├── a10a9f60a3f98456fbf828bb887b9371e2ef8941.nq.gz
│   ├── a3d364c02aee6520064e0293279d220fd7dc0aa6.nq.gz
│   ├── a688f1d06bf4d1624167fec92012456b4ca98b5b.nq.gz
│   ├── a7790ca76afd2e3ad05b7243972f47d264c0d7b7.nq.gz
│   ├── a84a19bfc4e8636487f4cb9e959edc2a8721fbb3.nq.gz
│   ├── aebe2818c2c6cc2bee0fa1374b748592be430273.nq.gz
│   ├── b0a0ef2f6cc30c3afe2e926f547a10d429502f77.nq.gz
│   ├── b4584f5ea6519711ee2ed4fba73546cefe55e327.nq.gz
│   ├── b4c2e52e7c2bd54590be09b5cdcd2ccfc09428a0.nq.gz
│   ├── b56382043c78ae4a15ed412bbb2303fed61f763c.nq.gz
│   ├── b77f456a900ccd8562396fc84555f4a9fff7df73.nq.gz
│   ├── b7cefd273f0f837babf2df458eed2a1ae3fd3314.nq.gz
│   ├── b9faf956f15f3c37c3786999d96b9eb8f615ea28.nq.gz
│   ├── c056749d3694ebf29be6aea5680f267ae1b0b216.nq.gz
│   ├── c1ca2d066097a5184df36b950b160e2c9bb6eb39.nq.gz
│   ├── caa1bfbc22720d42a9ad51deb96ad8f63df35ce3.nq.gz
│   ├── ced59e3dc6c9a8fbd37cc96030a8303d0878f017.nq.gz
│   ├── d10f0d4500aa482b170ee0da78d52d46adeb7321.nq.gz
│   ├── d1108d86d7f7a8763ca547e62b4575aa7802e2f5.nq.gz
│   ├── dbb95ba5f7815967973c33a8fb5c21790b8b411c.nq.gz
│   ├── dd0f0cc878fd5759e996ac546c63eb4db0d2f9d8.nq.gz
│   ├── de1116db85554d4db8a9270669b279e71afedf9c.nq.gz
│   ├── e07721a3c83b538c31d5ef1114951ddc3d21fe48.nq.gz
│   ├── e356f331f29ab7154354321428644438417a308d.nq.gz
│   ├── e45eba14b6ea9ff49280954b81253b928a254c8d.nq.gz
│   ├── e68c5c2aa79ac3c1d485f582310b771d0b5baa49.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8c83fcc7270d7b31e1a2d9dc1d884786a426c92.nq.gz
│   ├── ea3aa785925aab93b95a61ee8bb97ba51357a8b4.nq.gz
│   ├── ee82918e644790360eb052b569885a5c9ce2cabf.nq.gz
│   ├── f5e83c9457e798645d60ff2fd5fa1f86c923e9fc.nq.gz
│   ├── f633085fe9e4891f76c4bb8c909cde6a16bb4eed.nq.gz
│   └── f66ca2023e8f5c4b4155d14dd9e8e21be2a1ee67.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c0d70f985ff6f04dcc59822ca5216cfd0ada666c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 102 files
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

[Pylons/webob](https://github.com/Pylons/webob)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
