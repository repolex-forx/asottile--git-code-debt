# Repolex Knowledge Graph of asottile/git-code-debt

RDF knowledge graph data for [asottile/git-code-debt](https://github.com/asottile/git-code-debt), parsed by [repolex](https://repolex.ai).

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
rlex download asottile/git-code-debt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e8f2f643895c482f8ff9f110210434e7662a04b8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e8f2f643895c482f8ff9f110210434e7662a04b8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0010524db337e416e4947b0943a712070df225d3.nq.gz
│   ├── 05cc6fa968bf299f14cfc1dd06fe13a06c2f679e.nq.gz
│   ├── 07eba6da38d7d42946ccf5f36403b2949f9006e6.nq.gz
│   ├── 092cf41d73fd5f07999cdeaa7cd307c7f030c55d.nq.gz
│   ├── 0a108bc24e943a9ae5774ff5a39cbaaeee3989f5.nq.gz
│   ├── 0b2ba2528d6555daeadc122cac0ffb2a3e40b9f2.nq.gz
│   ├── 0ca7ada960568fff04400cda966fbdcb106abfa2.nq.gz
│   ├── 10ffe39c6c63f12581cabfb7ed362066edfce999.nq.gz
│   ├── 15f3ead2e7b4fa219dd8cf7a4c31882d864386e0.nq.gz
│   ├── 1605c3fb523148306df03f106c4b62faa500361d.nq.gz
│   ├── 170654f27d6d90f168e26437046e3a71b2efc408.nq.gz
│   ├── 1eca868af8d0a814ba264f1b23e788c78704e02c.nq.gz
│   ├── 1fe1d9aab90791971e4d4d362ab4789e7159ab2c.nq.gz
│   ├── 204a7408d0da19e608aad49117665293b6699d41.nq.gz
│   ├── 20f05b42997292bd8b4bf6db07840c7c9c8cc154.nq.gz
│   ├── 222f97138661b6573562eaccbb0b1e50eef65241.nq.gz
│   ├── 22badd1fd469f23b093c805827c99d51f1b7a7db.nq.gz
│   ├── 24a1a0be41a6966929c7c017a5802115d0141896.nq.gz
│   ├── 24f95637b343b4bd44cdaf50b4e99b2fe703d9a7.nq.gz
│   ├── 250e97271e70e3fe35573d1ca35fb16208283729.nq.gz
│   ├── 2a7453c22b5e31324a32d1a187edc2d4e4ad1740.nq.gz
│   ├── 2b662e63d4265e5cf9918059201d985b6dd75bd7.nq.gz
│   ├── 2b67da9cd89aba985fb0d991bb9db3313bb383bf.nq.gz
│   ├── 2caa9dcaad94f4d7725ba1f768d9bb6b39ab7845.nq.gz
│   ├── 2cda13e5f0d91b2110d84c9dd0c488719332afdf.nq.gz
│   ├── 2d1b1de118a6d8958f1b620b8867ce4f1a62866a.nq.gz
│   ├── 2f4126d305f8c3f0b5515ee10512d966ce9fd4ac.nq.gz
│   ├── 2f7d3139b2d457582223166f5a5449725ca4f506.nq.gz
│   ├── 335bd7885bcdd52ae1d846575be5577a00b9ae65.nq.gz
│   ├── 357a1fd53befdbb995f45f89493b63ec4e472106.nq.gz
│   ├── 35fb8c6b19f99b9eaf5162d972768639f980ed47.nq.gz
│   ├── 37328354fc482120c87dd6fa966ed54e38448491.nq.gz
│   ├── 3c2bcf48c3fef27c0135c73b09d4df670bfc7713.nq.gz
│   ├── 3c705fb9ae2149f3d716811a229f33b710b7dcdc.nq.gz
│   ├── 3d93aefb2da505dba9c0114404cfaaeee5ad0d3f.nq.gz
│   ├── 3ec65365e5b4cc6d4b7f5199f13c04116efb7568.nq.gz
│   ├── 410bddf6495e4a2935d0e132b9f6ae0fc74f181d.nq.gz
│   ├── 419fe153698282bac5f157c33f8d48ea5a7b9bab.nq.gz
│   ├── 443cd2a31b367da99eb2ce05b7b0d601b05173a0.nq.gz
│   ├── 471ef1245726ab8d34d26633a0e2ac26479bd8f2.nq.gz
│   ├── 48b447d47980defeb1bb8412e1fb1f47f515d7b9.nq.gz
│   ├── 4f8617b81bc1137400d55823c3d0d4f56fde8b6e.nq.gz
│   ├── 5131d4823a17f51d4aa589582e2d352a98767c37.nq.gz
│   ├── 5e1b499d4c5754c664542a282bb48f157ebc98ad.nq.gz
│   ├── 5e5492d847d9dd0cefddc2a0fada17f87b667319.nq.gz
│   ├── 63daa5268ef660926f2a2e6e8e7fc03ab7dae205.nq.gz
│   ├── 65d52aeb0c9e9abe564604cd83211d92fa4ca0d9.nq.gz
│   ├── 69ef077cd155d13811a720a037a265dc652e2b7c.nq.gz
│   ├── 6b789049c0571f2ba88b295f7a7a671eee5b646d.nq.gz
│   ├── 6f0371b32739a8fdfe8bec377590c2c59845cbc8.nq.gz
│   ├── 7043722530b1682830d930645352fef76bf6e2f7.nq.gz
│   ├── 706c2ff1c6f7af968e1d0ceb0aeedbc7ab0cd3c4.nq.gz
│   ├── 7c0389791336872a5d042e62e1da1c7c79fe94f0.nq.gz
│   ├── 7e3dbe3d5a7deb3cbb5daabf2806ca57243bb631.nq.gz
│   ├── 800f31d1c4bd8c83eaa68818fa00824716e239f6.nq.gz
│   ├── 82b31fc8df49726073b97b5eb0e15e1195a789b7.nq.gz
│   ├── 82c0582af20632bc0e8247866a7a45be9f8f6843.nq.gz
│   ├── 851fce2b547f612233dc02a6d8966b5a1002e15c.nq.gz
│   ├── 8553df9c105c69722dbb521b582627930788e2f6.nq.gz
│   ├── 869014578d654a802d49223cf884cb9a651ae382.nq.gz
│   ├── 87183b359c35fce0fc4c824f3119a89468f3c37f.nq.gz
│   ├── 8845e8ca429f8e2fde7acc471c3fd7fd5acb53ae.nq.gz
│   ├── 897ba47c0a92c2ce72efada4cca8dee7da0fc2e6.nq.gz
│   ├── 8a4bcec8571040fbf7ad56e236d93b7bfbea25e9.nq.gz
│   ├── 9121e87b201534d432eacb8ce75fbd120d86ad44.nq.gz
│   ├── 92a22213d647a0bef6d8378fba37d974d88247fe.nq.gz
│   ├── 93c4741f5600f00b78203ce4e4d4dd07f02d10c4.nq.gz
│   ├── 96be086b0ee55cb315ff666c4ba62d3b68e77878.nq.gz
│   ├── 9785669d6b6bbd202ecda6a963228263931ee1bb.nq.gz
│   ├── 9d07341a540c170f47ae927cd10ed9243f7faddc.nq.gz
│   ├── 9e1373cd8bf678cfe7c0fad971303de217533660.nq.gz
│   ├── a0373e1ee2fe5e361de26f30b040ee9c6a22f8dc.nq.gz
│   ├── a241c359433b238dc10e3f013e07b3453ce4e1e1.nq.gz
│   ├── a2b188b62d0db4fbbf0e6eb86761ea6b4155125c.nq.gz
│   ├── a53eea3ab064fba818b68d455e7fed64537f1abe.nq.gz
│   ├── a81999da5595b1025dcc1b8b1f4245e4a34b5ecb.nq.gz
│   ├── ab05eb65c0000be44226f4b5fbfb3661d2cc57f5.nq.gz
│   ├── aee2a076517ceb88dcfa8c4c32b7035c6b4502b5.nq.gz
│   ├── af2b4554c5602ec35d48b8a13d68b02779695ae9.nq.gz
│   ├── b407a3d77fcfe8f2e0747de1b128f19ba5323481.nq.gz
│   ├── b6713f5d68f79efa2ab4093bf8c41f38718a2df5.nq.gz
│   ├── b7a79b8a3a1c86b615a1f01ccc9fe88773ca8906.nq.gz
│   ├── ba54fd1bb36c2d8eb451959523b67d5999461ed1.nq.gz
│   ├── ba86cb1473582839233b012a15b99c3c2762cc19.nq.gz
│   ├── bb5e8a9f5ac860521d768b84e79cdfe091aeb91a.nq.gz
│   ├── bd4093adcd2ceae35e4781fc895a5a1c20f6a963.nq.gz
│   ├── c4063229bbe5e4fea2370a9b00c8d66ef11732d3.nq.gz
│   ├── c588d1e1527b26aa27f7216f701008bddd654b46.nq.gz
│   ├── c7bd7121f2d29ab3bdf4d6a4c199d2b0b234e62b.nq.gz
│   ├── c9881bb04f5a29f5d3f4c590b4fa794aee796f7f.nq.gz
│   ├── ccb52fd7ed6071eca17d159d7d8eba30cbfd18e4.nq.gz
│   ├── cdc97b163b4e145298df40d32b54e4c76867aed8.nq.gz
│   ├── d1c991138dff7ac88d89121d634ca55b9851ea99.nq.gz
│   ├── d4911c17b6cd9cab2a1e212a70ded1626104056b.nq.gz
│   ├── d5ff27670a4cfb0080e09e6a2d4db2da0db7013c.nq.gz
│   ├── d86d9ea06347dbd79c04079484155ea94fa2c3ed.nq.gz
│   ├── d8e82a2566b84df00cb4e4d57ea35fa4a5c91639.nq.gz
│   ├── db6bb9fbcb680ea9d398d9f4a0570865ca712752.nq.gz
│   ├── de5ff1309c4fbcc25334f0d037082013b55329db.nq.gz
│   ├── e0e13de6151fb15ba224a6d01783f103d3705574.nq.gz
│   ├── e2f19ebc3cbf929b94fc5729bdbb895d074b14a0.nq.gz
│   ├── e301e98d9547b746fa687b20133fc73685e7136e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a5429e8ea2920b85a66ce1a3e3ab87658c4242.nq.gz
│   ├── ef4b872b38f9f9594c8a7a8ef9fb678d7228d06b.nq.gz
│   ├── f0687512d905d3a2bc1be88fc00a568a40097ac1.nq.gz
│   ├── f4060ee182e89da5cd9efc2857d537f1e5da25ba.nq.gz
│   ├── fc55ac4a98af68fd0ecf7c9ad3d073e386e9b51f.nq.gz
│   ├── fec9ba57f6f566fab022fa91078e44a362335c0c.nq.gz
│   └── ff6318e82151e830f21fd4885882e2332eaaedf1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e8f2f643895c482f8ff9f110210434e7662a04b8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 118 files
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

[asottile/git-code-debt](https://github.com/asottile/git-code-debt)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
