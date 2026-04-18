# Repolex Knowledge Graph of pypa/build

RDF knowledge graph data for [pypa/build](https://github.com/pypa/build), parsed by [repolex](https://repolex.ai).

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
lexq download pypa/build
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7b7ae078aa1dabff33ea72d07ed15dd298acf80a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7b7ae078aa1dabff33ea72d07ed15dd298acf80a.nq.gz
│   └── repolex
│       └── 7b7ae078aa1dabff33ea72d07ed15dd298acf80a
│           └── chunk-001.nq.gz
├── blob
│   ├── 003400fbbf51eb5c0464742096b39e0ca99f4135.nq.gz
│   ├── 01df961ea023dee14fe918f67aab18ea7603a318.nq.gz
│   ├── 024e9e6fcb35d80a22b91033eceef2deeef3bc7e.nq.gz
│   ├── 058472c31a9bd56a8ee01c5508df025885e167b9.nq.gz
│   ├── 1201d193fb7bd4190755bfbf386bea39ad201e86.nq.gz
│   ├── 16e296b638dd3d784329c759b447190d2dfabc3a.nq.gz
│   ├── 174aad73675cf9a712a4118e17b0b328ba12c47e.nq.gz
│   ├── 1a4be2f68f75034548cab524d6f06c34dc91f3de.nq.gz
│   ├── 1d0a57c992c9e6459774bd9ea89ec89c83d5c6e9.nq.gz
│   ├── 205750f3f29984ba1bed89222caee17d3f933d85.nq.gz
│   ├── 223ef76a1b930ade702379b22d603c6759dec288.nq.gz
│   ├── 2796891b1c4685db2181af194f8f39d3911452fd.nq.gz
│   ├── 2f20f14b82163da48f23a9c1eb3ed9874735044e.nq.gz
│   ├── 32075ce8b2a2d98fe542e6f361e5ee3512d7556e.nq.gz
│   ├── 38f862df759904164d7ed8b2352a54761a9793b5.nq.gz
│   ├── 3900263231ac5dfd5d415f7b0d49aa6e886a0ad9.nq.gz
│   ├── 395503444d8a586f4f47bacbe55f40e277c24c56.nq.gz
│   ├── 3c6a0fc5ff7f5ebd39c8a47960f3b0c59702a3c1.nq.gz
│   ├── 3cf39657cc13542a3965f2d71bb22294fdcd83ab.nq.gz
│   ├── 3ee938219dcdf45804da0fd98a446a7d29912ac4.nq.gz
│   ├── 436dbbb00580a46a80b6794cdc33409e3fd99455.nq.gz
│   ├── 43bdd44eff2ea6d5ac19b59f36da33637b393790.nq.gz
│   ├── 47cabbd01ac5d1013e6d7c9eed209515f9324409.nq.gz
│   ├── 4b072551c4c9adb024bfc1625fe26f4c12ec599a.nq.gz
│   ├── 4f25948edab3db9d1c323338bb60d40d72712008.nq.gz
│   ├── 51191efe94554800d139c78916dae0c13cb6b2f7.nq.gz
│   ├── 55c1e601be18f5a4a71d110689f65a1e7199b3a6.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5c609a53ece6499415cc4ffc7b5f1c0f79a82719.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 60bd7020cda4f9b87ca0baf7af6bd3aa6460e390.nq.gz
│   ├── 6a62ad1b511e16218d2ab35786948191a7653563.nq.gz
│   ├── 758e2239eec6d0c263e272227d1e202fb7a0d700.nq.gz
│   ├── 77de5dfc08314a86820e6115dc048775a2b1e49f.nq.gz
│   ├── 79a813c29893fc93dc6880b4d61aae3c3df62d52.nq.gz
│   ├── 7c39e0e74fda84bc2b15daf264951526ed9d6e46.nq.gz
│   ├── 7fee6fa23d09788e398da7643ded4e24d7f125af.nq.gz
│   ├── 853fc55261c9568ecf3eab21e81ab5fd20c4a89e.nq.gz
│   ├── 8563a94d52031bb0d2eb2c10d1b10e4289e8d0f8.nq.gz
│   ├── 85a4a41886137ba474c355bf059474abf613a534.nq.gz
│   ├── 8667fa3cedca02280291c410f0d1c85b931583ea.nq.gz
│   ├── 8b2a7cc3f33d859dbee04df3e605587a702880b9.nq.gz
│   ├── 8f3d973a76cab4e0e7b12dd4d6a87e53b3671686.nq.gz
│   ├── 90d5f693f67aa2da7fff41f11c802bd95e027613.nq.gz
│   ├── 93416d3066ee995e9fd8971ca800a8b01f1b5ba1.nq.gz
│   ├── 950712681620ebd2b1b2d67c11274a96b6dac41e.nq.gz
│   ├── 9d70930d9f312ee285d576fc3cd27a7809b29545.nq.gz
│   ├── 9e2be6a05cdda7866b342d274386fab053f478e2.nq.gz
│   ├── 9feee167a2d0280aa73c425e0a8ea3d5597c15e5.nq.gz
│   ├── a57c41eb88aa61a7b7d02cb602b7d44b9e22e643.nq.gz
│   ├── a8e0dcb5d9b117807008c9344a410eadb4cd0118.nq.gz
│   ├── a9114b78c19e7aff196299e11c62b3d4ad669253.nq.gz
│   ├── aa0913d26f513312ee4e1683a76a50aed72bb7fe.nq.gz
│   ├── aa22d23e3ab03ff0b1f2478c3821e3f73905ba5c.nq.gz
│   ├── ac76f5de83a3c462a87e4e1ebf46d1035e435bc9.nq.gz
│   ├── aded4cbda127700f6df7f555801d771a51d1fd2f.nq.gz
│   ├── b19f740edcd83c8a7945be6553be2a070cb38b4b.nq.gz
│   ├── b246e596e58b497aba887e97b32cb2c0bb417413.nq.gz
│   ├── b452897425a2432efd1a608720b3fde639295a1b.nq.gz
│   ├── b48aee6e6497781deb53976717217de54bcfdd41.nq.gz
│   ├── b91bc69b2c81e6b8983382f10a359e941a597a79.nq.gz
│   ├── bfc5f9a4411d0eea93884891e450ddf86ccf5c1c.nq.gz
│   ├── c199a339420e496a077d5e44ea218394fa63a170.nq.gz
│   ├── c3713cdcc9b5df70576fb1d5d010c7a17e02e038.nq.gz
│   ├── c4866cec0e95b4ac74dd376e8d8afd4bb6cfbeb8.nq.gz
│   ├── c6867ac3731403c358ebd38f45ae9c459d33649e.nq.gz
│   ├── c6bfe2af665a40b00462442a4a0ab1841de57afc.nq.gz
│   ├── ca06f98d518f96ada4d2b2aa627138e7c59cdaad.nq.gz
│   ├── cb8449656bb312906ca2440d55b91ffa39626187.nq.gz
│   ├── ccb695935e7d12a45ce956139b0f3cda7a31b0c6.nq.gz
│   ├── d1b361fb8291506a78edba82853424f4bc07056e.nq.gz
│   ├── d450292adf4babe0a1eec965059fd673fd7255ec.nq.gz
│   ├── d75657793a48c55ac32889af7de523fe58b1ea1b.nq.gz
│   ├── d7bcddc26717a59e433d4939ce79d041c5f85ab7.nq.gz
│   ├── db992789274ddf91e6ccaa7d5f8eb6d77bba4000.nq.gz
│   ├── dc9ecbb32ea9ffa7c99f2f5455615958dc80c1de.nq.gz
│   ├── ddcddeb29fc4591dca1aa8f4c8024a4fc42ed210.nq.gz
│   ├── de4edc88d1c831e7aa32c3420aa56cc2957eacca.nq.gz
│   ├── dedd54e3ee30ffc29a7561321bbdf4f88901f7f1.nq.gz
│   ├── e3b0a0ccb65afce894b85df05b880071e197d52e.nq.gz
│   ├── e56e6751eec55c60c6f17f411e42b52e20648c2e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e69e3cfd8974b2038cfbe42d30d28b620cda306e.nq.gz
│   ├── e74afad022cff7bd0f10c066451efeaf74f20018.nq.gz
│   ├── ec2b9200da276dea9a8dbc7104ff577c61ba51f8.nq.gz
│   ├── ee56236566693dba5f2f3de40de0a49d07c5e5fa.nq.gz
│   ├── f0b45ae0a310e5fa876034b50b83158058ab72b7.nq.gz
│   ├── f4ff9da789a92427ac0d99feca0c0b277f703e91.nq.gz
│   ├── f576baa1727fb6224450de2c175ca4057ea7e8fb.nq.gz
│   ├── f95a1bc6f14ca5bce54d709619c15dbe268e06a3.nq.gz
│   ├── f9ba4d532b23d2215d5c55d5a39c63abd2da819b.nq.gz
│   ├── fc0db78e19fa0bc722d97fab52af3938183b66a2.nq.gz
│   ├── fed58e04f506889b86c49fcc3e9ccbba99e51f2d.nq.gz
│   └── ff14b639a7b070283bfe3cddf1ed91c401043b0b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7b7ae078aa1dabff33ea72d07ed15dd298acf80a.nq.gz
├── filetree
│   └── 7b7ae078aa1dabff33ea72d07ed15dd298acf80a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 104 files
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

[pypa/build](https://github.com/pypa/build)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
