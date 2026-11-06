# Repolex Knowledge Graph of ansible-community/ansible.content_builder

RDF knowledge graph data for [ansible-community/ansible.content_builder](https://github.com/ansible-community/ansible.content_builder), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/ansible.content_builder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 80ad207031f14cb2af65b15acb5830670028db2c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 80ad207031f14cb2af65b15acb5830670028db2c
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ea512595d502e767929f90bee361043172cc4e.nq.gz
│   ├── 028eea9f95abe9ff2bf21da361b06f2892f5f74c.nq.gz
│   ├── 033d0feb9a55e00b8b338b323b70164d4c9745c6.nq.gz
│   ├── 0485bd7fc57c42d7cdcb02c54aa45793ae5dccc1.nq.gz
│   ├── 0a39835597f00a4015c2dcb8402942b8ada5adc2.nq.gz
│   ├── 0aed21c01f33da7b5e6c3b1fe4153090f21ea3d3.nq.gz
│   ├── 0ca63a4c9fe7c2e952c322df98005e7c4afe1d37.nq.gz
│   ├── 0ccec6d285eea8459f7d48eb4c4968fcef463171.nq.gz
│   ├── 0d61ab9760bddca2ad90977d2d97ecdb227ed6a3.nq.gz
│   ├── 120d8a016f04bd9c9a32c133fd16e649368ece80.nq.gz
│   ├── 14cea52cfa931a143c8e51be9fd4b5bf3a9d2f46.nq.gz
│   ├── 1557578240927973a98bd988a68a360e3d3e39ca.nq.gz
│   ├── 180f21f1d85cfeb6242e6a75cf0ecc43db162125.nq.gz
│   ├── 1c78bab2238e3ef6da36b35a210feca355adc54b.nq.gz
│   ├── 1dd3bc02c06cb023090aa80af648c9a919d61989.nq.gz
│   ├── 1e4c1cc410238420d680e0a181467b65af7a091a.nq.gz
│   ├── 1ee83619fd0b6630af464258fd908a4269d974ca.nq.gz
│   ├── 1f8138c1aa10b91aea6567f2071a946bc893c5a5.nq.gz
│   ├── 237964407d7c9d08db1006df1d73c55e3ad2d014.nq.gz
│   ├── 254c7e6b90c9cc2db57489acfa99dbe0a56c6c66.nq.gz
│   ├── 25fdfbecf503c52ee56b567f4b1799a417c94073.nq.gz
│   ├── 299d1e04fc9d7ccea4319bb44053669ecec295be.nq.gz
│   ├── 2c73454b304c71c21c2abb65f7a9a808669e6608.nq.gz
│   ├── 2e77cd36999b7b7b5c62081203a912b97ba18d0a.nq.gz
│   ├── 2e816670da3b640dae954c5673e54e63c82d27eb.nq.gz
│   ├── 308478de6a1dcabff8b6bcb34270ae0b1917bdaa.nq.gz
│   ├── 339c2629d86248984c6aa107e9c95850493e8824.nq.gz
│   ├── 36d5010308b0b1bea16fa4abf81057702e070b14.nq.gz
│   ├── 3d82a3224dfea88dd79de2ac59127c4da19f0dd9.nq.gz
│   ├── 3e372f9d0366f0b244844fc4d2860153f2bc6714.nq.gz
│   ├── 4068e36ef2e80bbf257c93433bb4dae3c3fa7715.nq.gz
│   ├── 42165582ccb48a13fca5c354a492bc10029b0b55.nq.gz
│   ├── 4ba2a6db8864f3e95955e663739391cb7034dc33.nq.gz
│   ├── 515f525389ead8a467bc9a44fdd07f587dc905e0.nq.gz
│   ├── 5652e79d1c4f17faf81a48993abd21c32870a543.nq.gz
│   ├── 57067349b6da5c07f2143b8e2678b878997401d5.nq.gz
│   ├── 587bff2487e5d28c7fd534d37e0eeeed091b4fea.nq.gz
│   ├── 5d8f20776af49de3e1d72fe388f4d3f7c20b3a48.nq.gz
│   ├── 5e999759c85ddbf33e4a8ec6e72121609d6fb076.nq.gz
│   ├── 5f191692c1388df7abf8d0e5cd411953491f9fab.nq.gz
│   ├── 64c785ffbfc1f71b13af6b172e8df7d1385a9ab3.nq.gz
│   ├── 65748b3c7282bbd58fe3193f521731608418f204.nq.gz
│   ├── 65b9f89f1b12e9f6ac5263f5035948556e4176cb.nq.gz
│   ├── 68129ac8d1cea25d3d180ad4d7dfce0dc0098a42.nq.gz
│   ├── 6b07ef8f09b2b9a9366bffdd0cdd9698de6dc772.nq.gz
│   ├── 6c6e7e171dd990daf6384b561bd1bac024d4f012.nq.gz
│   ├── 6e9065f3ff234792031572c93a91844fccd3c75b.nq.gz
│   ├── 742ce2620708c017a5f30885dfb2df5422d88a3a.nq.gz
│   ├── 74afdb7bb1975a155a6946f6cbdcd9d6caa141f8.nq.gz
│   ├── 762c50064232cb1e3cb26a56f0210e220c3e1958.nq.gz
│   ├── 78696116fb186a994b76477caf1e0d70a181ff7d.nq.gz
│   ├── 795483409da053dfef7ff5e2d53ed92d449ef7e9.nq.gz
│   ├── 7c05957c2165277c9d776eea3050565b3b1366b5.nq.gz
│   ├── 7d534802bfb88be70361de83c89428f35082e0bd.nq.gz
│   ├── 7ef6aa0f5f9d14b7b033789fe237a1277cec4025.nq.gz
│   ├── 80a7e6c563fb945ab085dedc9fc5cb80468ddd30.nq.gz
│   ├── 843514348bdd3dab19228b4841675f74d1fa588b.nq.gz
│   ├── 894b72760dbb716b55dc326a31119ad3b1846c32.nq.gz
│   ├── 8b9ab12b83ac6062a4d25743394616aa80e53bb5.nq.gz
│   ├── 8cf48169910f59e60a8c64469249c741010ee53d.nq.gz
│   ├── 8d35340b443193109f413ed226e3c9313a510168.nq.gz
│   ├── 909fb0b5a0520af7ff8ef5c099aa286cf629161e.nq.gz
│   ├── 910b5ba2282e95fd0b2c1c8ab019b2133173046e.nq.gz
│   ├── a0c3f6a43277f0776f958cc30e6dfbac33e2410e.nq.gz
│   ├── a10cb8ab93b04e22d3900ae28b5d87057c144289.nq.gz
│   ├── a650a57f2f3712ae66ebd9abb340b83c3af6d1b8.nq.gz
│   ├── a6532f81e71aa2a4a9f619a0223f7eb8d9c6dc39.nq.gz
│   ├── a77aeba5b001507fe6aed3b083015395128db015.nq.gz
│   ├── a9400592040e3b640447e0d74fde0f096fc6e25a.nq.gz
│   ├── ad29f68daf5d74c806100524606167721b970341.nq.gz
│   ├── b107314b16e526bfe7de3a387063586264abb9b3.nq.gz
│   ├── b4611203cd755730f5082856d6dd0c7213ed8234.nq.gz
│   ├── b77fe54a2404762c6fc84bb6f0f4e8af1199561a.nq.gz
│   ├── b791d9e9b8129f546f3883349c84c0775c7cc2df.nq.gz
│   ├── ba9c980fb86bef62c1cd5c86cd09c6cde80b0cd1.nq.gz
│   ├── bc2ae97a3ac5fe09d9003c937c5732686895a4e3.nq.gz
│   ├── c1057fa10f5e2fe6a73440d21314ecb170a815e9.nq.gz
│   ├── c4b45493e3702a789e75857b7a1b0e883add5302.nq.gz
│   ├── c4fd3106ad7f8112c505f06c77d82dc1796832ca.nq.gz
│   ├── c529f139019847cf8a5293b5d120e22e0bb464e8.nq.gz
│   ├── cc56bff27c29b396f1c01d73af385485876c4759.nq.gz
│   ├── ce5ce7e2ec91fcaaa044370dd18fa344d76d8683.nq.gz
│   ├── cf0449edae1ef7cac36735c0013dc427dd2d3ea4.nq.gz
│   ├── cff1b31d4be3a7d02ac3ba3ab7ac2a4cdbbccec3.nq.gz
│   ├── d2a54d3f155dc1768e2d863c42456d919aeaaa1b.nq.gz
│   ├── d2a6595ec73b4b9feca794c798ab0c79862f5722.nq.gz
│   ├── d50d1c03a61a6e878c0c6b500ccecacf691291e3.nq.gz
│   ├── d528e43c1e9b647a714f27910ef017ce7475996e.nq.gz
│   ├── da86bf683eab74f42fe0eec2a183b673ed35a18c.nq.gz
│   ├── db05cca3257498630b6977214dfe984edeefa84d.nq.gz
│   ├── dd64a934b4a86c1919e66ca6839c7bc9915aea77.nq.gz
│   ├── dee58e6b50eb2573f45206c8ce0e77459b21241e.nq.gz
│   ├── e36ffe376d4b2a923011cad639878ed4e559c0de.nq.gz
│   ├── e530c1046f1abfa86a10c90314a85108c7c367b1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e97622cc356f840ae19a15fdf9ae760a60227b9d.nq.gz
│   ├── ebbf9a716ca5a3ddecd95f54f8593b33cc53fff9.nq.gz
│   ├── ed24682ccb5d1c003ab4fdaf8d3680fd5c160f1c.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f54cc36dbbf9297648581bd16cec6cc429fd535f.nq.gz
│   ├── f6762f5bc0dc8657c091494c5835882fb03e6e74.nq.gz
│   └── fd864610d52f2ca74ec5e5d6c29c17b53f2c6e1a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 80ad207031f14cb2af65b15acb5830670028db2c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 110 files
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

[ansible-community/ansible.content_builder](https://github.com/ansible-community/ansible.content_builder)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
