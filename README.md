# Repolex Knowledge Graph of twisted/txmongo

RDF knowledge graph data for [twisted/txmongo](https://github.com/twisted/txmongo), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/txmongo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 128c88151fa43cfa2503293ebf3e4a700587eb3d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 128c88151fa43cfa2503293ebf3e4a700587eb3d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0cfbf08886fca9a91cb753ec8734c84fcbe52c9f.nq.gz
│   ├── 0fbde50154f047f5bacff3c600d069afa4e5fe6c.nq.gz
│   ├── 119c70c7510f2aae104c4c7bae21ef2e7bf2c9d4.nq.gz
│   ├── 172ace8ea4ef5c38463737dce230e946df7a730a.nq.gz
│   ├── 1b14e0c188f6e4a80b89c9f48f75606b7420d7af.nq.gz
│   ├── 1d95483d56e89e776f387e58687571c3679f5dba.nq.gz
│   ├── 2287268594047703c38c7d32fdbbddce6c8fce01.nq.gz
│   ├── 24bcbe14450ae48f8021ee0ebc3d765c4c98ae30.nq.gz
│   ├── 27b96d0f60e67b9cbf73ebc47eeef859b1b0e0cc.nq.gz
│   ├── 28f3aff1305739252c146d10e1779ed781f7a3f0.nq.gz
│   ├── 29f5c061fbcc283dc325758e36903b81afcd55a4.nq.gz
│   ├── 2abcda5b8ea0357752bfbd15658f9f4c91979ee6.nq.gz
│   ├── 2ba2d378622b7b9b04c37120a62491c5322021a9.nq.gz
│   ├── 2e04a0bfd92436addb35fda2d25dbaa6ea5283a5.nq.gz
│   ├── 2f0165664ef7d9acb0aec7b658ebff7e8ad7c2ce.nq.gz
│   ├── 3278a2897132a2c8326f56ecd25a5ddfee61ab6f.nq.gz
│   ├── 32a6e97bbe8380fcf60196a8cc7a58d4c8dd7b16.nq.gz
│   ├── 32f1d5dce21bf69a7907eb4d884b2f1165ec2398.nq.gz
│   ├── 35382c6256cd36066d653deef1b35f08e91883d6.nq.gz
│   ├── 38ef4167d56725c121effe3d6d7e14d645eb769c.nq.gz
│   ├── 3a5e62dc7bfdd81307edd98bc6977a4a6e1421a5.nq.gz
│   ├── 3c4a062c30256d025139a65d7b291984a6be59e6.nq.gz
│   ├── 3ec9100db3c06765d15b8502288927628f706c4b.nq.gz
│   ├── 44d9e374bed36021234b5f365d8d214d57827da8.nq.gz
│   ├── 465ddff22bea405e9e29fe69c0b80da247552a15.nq.gz
│   ├── 481ec87faa8acd7daa368f2d78be9b1647ac630f.nq.gz
│   ├── 49e60b8b80dd557921a539fb5400ad68661b99b4.nq.gz
│   ├── 4be800e83a4a6c8c01cede4ed55cf3913c69514a.nq.gz
│   ├── 5065ff76a3b4f1827dd1c0f827fe39348d00ae1b.nq.gz
│   ├── 50b7f67905639ebf265c1021e8acef4720a51ddf.nq.gz
│   ├── 5172b446c34d2d2b030d157483bdf448199dad4b.nq.gz
│   ├── 518deb4a3f7e13bfda593c47692a6bc0c10c737b.nq.gz
│   ├── 548b006dc16804b8e5fc36d381c4ec975a6de2df.nq.gz
│   ├── 54cb52e5217b401d12cd8c3e62348eeb80fe6aab.nq.gz
│   ├── 5ba220eead4381436cab78a8f61d69c649e4d2d6.nq.gz
│   ├── 5e181af5cd674a828bf25efb665d5741cc5c356b.nq.gz
│   ├── 5fdf2a3af77db65b6c54bb3c2e60c53dad6a2f47.nq.gz
│   ├── 64cbf454fe5438e0b7cefe90527aa0ae1ee806a2.nq.gz
│   ├── 65056a4f35ac3c962e8ad4866d30be15a2dd7e03.nq.gz
│   ├── 65d412af9ae8ba2f23e8f824ab2c768c7571e6e9.nq.gz
│   ├── 66e094eeabfd40e64ff2ab99783dfc0db5bd9d38.nq.gz
│   ├── 693663327d4ee1cd568982b2c8b917bbd5ca78ac.nq.gz
│   ├── 6b7354ddfefa0a9559dbe761e459f783588c2457.nq.gz
│   ├── 6e1ca18a276547a2209dac28e00814facb3e79ce.nq.gz
│   ├── 742fc4de292873e0821c5def6585d9d8b73b304d.nq.gz
│   ├── 7440d2fab226827e663d8d88c542374baeeeafa8.nq.gz
│   ├── 753070f826b4767751578079f942788f9ca62473.nq.gz
│   ├── 759a866185340180dfb9ad37dce1b02bca997772.nq.gz
│   ├── 7ce15f94cc9e1cec641e5b82dcb2e70f4b0a4d0e.nq.gz
│   ├── 7df344533ca65754f026345d45f2d1449b57a894.nq.gz
│   ├── 82dcdb4f404f4b3efbb29453decd23cd617d19ef.nq.gz
│   ├── 8445e8318882d4f23002aa86dc1010abd2a3ea0a.nq.gz
│   ├── 87824b572bb5bc87888d4b10b73858cd0bdf251f.nq.gz
│   ├── 8f13701023f00d47492ac58998d80e42bbd51241.nq.gz
│   ├── 92e5edb2a35751b6956d32d9868e0aebce8fbd59.nq.gz
│   ├── 935c301c0e44cc5a1d63cc92f41a066511ef0bff.nq.gz
│   ├── 9385e94585a4b8bf3fc7a51103aa425f7a8489e4.nq.gz
│   ├── 94b8bd3f7de605bf21f8586d5110cf563dd92587.nq.gz
│   ├── 9947f771fa25609a2a3acdba570c4c97a0a42642.nq.gz
│   ├── 99f01294c2062002b6373ca87fa25c31e9cccd22.nq.gz
│   ├── 9d02073f75bc9f81a844fb21f2b382b4372bc0e3.nq.gz
│   ├── 9eb4c86cfce8a3c4620387de0f53744afc7aa222.nq.gz
│   ├── 9f67d040dfbe0e1fab73211be6faa58c1b67c895.nq.gz
│   ├── 9f7d9c39790ffe9225bbe1b666d7478e6b975ba8.nq.gz
│   ├── a981bb48d794753863dfbb8401bfcda439cced86.nq.gz
│   ├── a9dfcfd0039c92e595ed101e5c171b0c9985a201.nq.gz
│   ├── ac93c3361aed3c999712a671a17163df84355437.nq.gz
│   ├── b05234936855f7e0170d739e282127bbfee7e8a0.nq.gz
│   ├── ba227b158555ce544b3ea58dc33b9f9d825fbc4f.nq.gz
│   ├── ba77e12f4c1653e619dde07f3610f0a1e1201e69.nq.gz
│   ├── bc4f0d54e446e0fc408e66afa63bb6370bfd26b3.nq.gz
│   ├── bf464d61e2a4e2fdfb0e64569f1ac84f80ea64fb.nq.gz
│   ├── c1140ee046549da9743806c9633f174924a1b2e0.nq.gz
│   ├── c40e8a794c5b577c9e516f71ca040df2bcfe3b25.nq.gz
│   ├── c5839d87ec504e638cfcc01899598cf9e7e51a0c.nq.gz
│   ├── c815e4d49487b5365da09328b198028516856587.nq.gz
│   ├── c9e551cc7b9941d448ad77a80a328ca9453b14a3.nq.gz
│   ├── ca247f92cd0621cfdd1555f838e0b071af65063d.nq.gz
│   ├── ca96d3ef99c816f15b2f907a8d6dcbc85472b604.nq.gz
│   ├── d002fa7a12399313e667411825bf604df3042a37.nq.gz
│   ├── d35a958311d3f83dc1f9fe48fcfb3705c42e9fd2.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── db4b9de89ff833a0cdab74ea746ff34cdd46d97d.nq.gz
│   ├── df36a49ed5d5475a146ebd339322569365b7736e.nq.gz
│   ├── e42a68a5f944665b08cc191d4e0a50c7f2804d85.nq.gz
│   ├── e528aeb0d75a988e6cff30b9ecc76d726fdbe22c.nq.gz
│   ├── e661b090554e0606963259481420c5f15b6d5d0c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9b2619af6ab8a5e06722838b92f5576ae283b1f.nq.gz
│   ├── eae238281c8613e1d74daec29396cae7530cd0a0.nq.gz
│   ├── ebeabf5be59dfc57ea982805cea1d898625a7e36.nq.gz
│   ├── ec635144f60048986bc560c5576355344005e6e7.nq.gz
│   ├── f2681b523888393d50552e98b7b8ebe561471209.nq.gz
│   ├── f60d03acd21e89f12af79a6d46faba97ceb8bbfa.nq.gz
│   ├── fb28a6bb8a17ee1eb4ed9a8978c86dfecffd4a37.nq.gz
│   ├── fb55c26ace861a18f3fd17e3b5a0a6e66365bcea.nq.gz
│   ├── fc9a8d69cd7dd11bc6b8aa2e5fc74456824dc22f.nq.gz
│   └── fe07894592da98d47aa15488459ff978237af522.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 128c88151fa43cfa2503293ebf3e4a700587eb3d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 106 files
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

[twisted/txmongo](https://github.com/twisted/txmongo)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
