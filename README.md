# Repolex Knowledge Graph of PennyLaneAI/pennylane-qiskit

RDF knowledge graph data for [PennyLaneAI/pennylane-qiskit](https://github.com/PennyLaneAI/pennylane-qiskit), parsed by [repolex](https://repolex.ai).

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
rlex download PennyLaneAI/pennylane-qiskit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b03b52f855f551b6a82ee934a89dbc3d3e081cf1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b03b52f855f551b6a82ee934a89dbc3d3e081cf1
│           └── chunk-001.nq.gz
├── blob
│   ├── 0398530590e9263f297d8acefeea33f145059c35.nq.gz
│   ├── 066b2d920a28db73b4ba3a0b35e6905eeeef5772.nq.gz
│   ├── 0682850500cc8142d46d711b7f47f6ef41628f0d.nq.gz
│   ├── 068c12500c11e2108be6edbd75b45a4e403ee30a.nq.gz
│   ├── 090c647ae49c7a42d98d332e0d08284d78f77a44.nq.gz
│   ├── 0df1ab4dde75d1a92dccfc92cc982031c11af01f.nq.gz
│   ├── 10bd335a4522daf891e05f12f05910ad58a69d91.nq.gz
│   ├── 13161fe7b1532c2093afbe7b91aa7426eafd3a6f.nq.gz
│   ├── 188d336b881bc41760b3176bbccef8a547f1efd3.nq.gz
│   ├── 1c8f6ae90e6066b584d0846057f52ac92eac7091.nq.gz
│   ├── 21c7dad5bc02f502c6c17ea77d14c2caa9424d60.nq.gz
│   ├── 21cca0833ec7c336f204875073d269c0c60d0f03.nq.gz
│   ├── 22a6473ac0b871caca85a30b305d0c857f33af9f.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2ad508a2b3acb619d064608d6fee05eb9ff1ce18.nq.gz
│   ├── 30e56e2f05bd3fd4cc36c4b5acf59aff6ca60e9d.nq.gz
│   ├── 3441f00b5609d7b2468c4538c8db0a99916b3878.nq.gz
│   ├── 38a783e05ecac172bc394216744391980d6a8d22.nq.gz
│   ├── 431dd9838f7c0931e4d69d58e4f3f46383c4f156.nq.gz
│   ├── 4851f1fa177b6fefc238e26eb058cef60837c5c7.nq.gz
│   ├── 4b4700f41b904cd0abb887e8722d6119d3bcaa66.nq.gz
│   ├── 500d61246d6dca1c01b272bdb5bb4bdf3d2e8536.nq.gz
│   ├── 57eac7b1bd98dbb588be1d7f092560a7372a4d3d.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 6f9e005b8c172b734d433f5eb753ec45a8206de5.nq.gz
│   ├── 70835ddbafddf1f3ef1c4254ffa87bcc80548cf2.nq.gz
│   ├── 734dc40efffbdeae9dd2e9f1856ec4d32812535f.nq.gz
│   ├── 78bd93f69d6c95d5f872d53d80af0cd9d3d48656.nq.gz
│   ├── 7f95f0bd50bf69cd55d2cb53fe7279e2f7d098ae.nq.gz
│   ├── 81c3f14a09f9bbf6c48cf78158a17dc92be08454.nq.gz
│   ├── 8775b6610daecbb6edd3245da68ac8116ec4abae.nq.gz
│   ├── 8f5a65d821101f7086431cf88e16fb34bd6b14b9.nq.gz
│   ├── 96eb17043b37df70cef6587a86b379182eed52bb.nq.gz
│   ├── 9c4f09c2172eeb0550d4dc76278707f3f2560811.nq.gz
│   ├── 9d07929fb471f2fae899e85118ec46ad7742ed85.nq.gz
│   ├── 9d43e5bde49f5d1d983bc584605968d0352cb96f.nq.gz
│   ├── 9eb590ec6865bae76036d34f67dc66bbe531aa09.nq.gz
│   ├── a4420bc389893e287b199a0b63ce23508c40eb44.nq.gz
│   ├── a6d0d8676b2174103435b4e31a7981352b5afcf8.nq.gz
│   ├── abf3e3c04541e11b923b4469cf9195a94f337ed9.nq.gz
│   ├── ac6b81de026c1d9111fa260b6da92ea4b560f7f4.nq.gz
│   ├── aee5c958752c91878dec9b3dcd6e62e5dcef8045.nq.gz
│   ├── b69348d97da3e161718a410312935f4746b6cb54.nq.gz
│   ├── b735373365bc7172f141853a93d0a5eea3733440.nq.gz
│   ├── ba9723fc40672d2363fac5e59f44d118b4bc30cf.nq.gz
│   ├── c0f01c3961cd54826d35eb27c4c1c550aef65df6.nq.gz
│   ├── c51b21f94ad40933b6a7ae315ac80dd9853b347d.nq.gz
│   ├── c661c0feca14ea2ad41d3501b889215fcddcacbf.nq.gz
│   ├── ce8048d888df2704fb0243211e11af3bde4e3ae1.nq.gz
│   ├── cf510d1b3ccda19d64692a87b998b1b0b134747a.nq.gz
│   ├── cf684dab7e3409aa2517e6c5b91a2e71c6050cc2.nq.gz
│   ├── d045c0d591a76e5cca51c4e6b459b844a95ddd3f.nq.gz
│   ├── d9a259015802350bb2e9b9ea963b8b95cc1d61f8.nq.gz
│   ├── d9d9fb92e65be93d98da6e7538c6c16f44d0c7ca.nq.gz
│   ├── df2e70540dba70ef748e792adc5000b6850aaaee.nq.gz
│   ├── e57105ed1193535dcbe6adb25196bc6d3702fc8b.nq.gz
│   ├── e76f803764c7095a9244c574ce9a3509cfae42bc.nq.gz
│   ├── e9fb360fbaac571575ea702cf03d077ab84167e3.nq.gz
│   ├── f37966f3f37e5e081641582fc6da59f91b7cdf15.nq.gz
│   ├── f73a1c04f5adf7b43cd8a36ea66105723e939c5a.nq.gz
│   └── ff2786b5eaef6083b3cedd0a2c7bc673469afe83.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b03b52f855f551b6a82ee934a89dbc3d3e081cf1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[PennyLaneAI/pennylane-qiskit](https://github.com/PennyLaneAI/pennylane-qiskit)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
