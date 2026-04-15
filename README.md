# Repolex Knowledge Graph of tornadoweb/tornado

RDF knowledge graph data for [tornadoweb/tornado](https://github.com/tornadoweb/tornado), parsed by [repolex](https://repolex.ai).

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
lexq download tornadoweb/tornado
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7d6465056ceb7a054b3f64cf1c18271753b10482
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7d6465056ceb7a054b3f64cf1c18271753b10482.nq.gz
│   └── repolex
│       └── 7d6465056ceb7a054b3f64cf1c18271753b10482
│           └── chunk-001.nq.gz
└── blob
    ├── 00066ccdfd44aea7831ca27d15ca20e4547222a1.nq.gz
    ├── 0064c6fbd1fff31b630b8579712c26d73feb4fe8.nq.gz
    ├── 008078ed9794e2e7ba91fafb717a1de9f3ad0e66.nq.gz
    ├── 00922ace4504a8f8137f2aecb65c3ea02cb5d5d8.nq.gz
    ├── 00cea136b24265dc098eb1d3cb45e0fe719f47b5.nq.gz
    ├── 00def8f38cfcd962daa8e9ddc1fe7bf5ce6d68a1.nq.gz
    ├── 01e7f8a06fac209ea5f273d2246eb2cad8331969.nq.gz
    ├── 036aec224736dcdd887c030a2cc3fa0e904aef88.nq.gz
    ├── 03aed18162eabf622ac3c53d3ca1a873bd1118a3.nq.gz
    ├── 03d94839cb0d2b3a79709d0e7d252afba05ef1c9.nq.gz
    ├── 05781c757ed846b86eafe2266eada3dcd070a174.nq.gz
    ├── 05b5e6dcc54d7f76ad813115e87b2dec32d9d156.nq.gz
    ├── 06f99ab755b8a53e375d4b22c307f29561a944af.nq.gz
    ├── 0af465abb25cace57eb16f4718c89367533f05e7.nq.gz
    ├── 0c62a70f86e5af0ec78769bde4bd749307bc9d97.nq.gz
    ├── 0c9ad832431859b7adbb1f4caa7e72741a09b1b1.nq.gz
    ├── 0cf04f857fffbbdba56f6d2e4608cce19e4d2adb.nq.gz
    ├── 0dc567d17164c0ef2d3d4f2d1b48e8ef68d120e7.nq.gz
    ├── 0f1f3fcf4a82e0b2fdc7bb54fd22cd565f1307a2.nq.gz
    ├── 100ad6bb5f163a3710e9ead5bdb41385a1335922.nq.gz
    ├── 117a9d7f99e34adc958f3b8df96a5952b8bcd5ce.nq.gz
    ├── 11886d00799952c7699798f7ba442c424a52321a.nq.gz
    ├── 123824de8de729a47ec59e059e929b2415f8bef5.nq.gz
    ├── 144406ac37c79eda9e52877a3bf3f42b5e923456.nq.gz
    ├── 145868bd861bbccbae2082c7b623b46f6d0ac73b.nq.gz
    ├── 1628073a32118b0e420948cf168d24dce65908de.nq.gz
    ├── 17a7549dae4a0c8a40ba90de2aa9f167f71a4d7c.nq.gz
    ├── 1820f177202e4dff9162a0951ff59281199c6fe7.nq.gz
    ├── 1c5cff326a8271cfd481447c9ca79500302f292d.nq.gz
    ├── 1c689f5c154269519be8bda66962dc276b2b5f39.nq.gz
    ├── 1dab6125922f048b5888fffb30f4d41dc80ebe0e.nq.gz
    ├── 1f53798bb4fe33c86020be7f10c44f29486fd190.nq.gz
    ├── 1f90bf68c7363e9801894088c02af66e7bb3d684.nq.gz
    ├── 218fc6530efffa82356d1ff6b138eec8f500e6d2.nq.gz
    ├── 24dd4ccf45b0b9c48907fe767c3ef0c7a6bfad7b.nq.gz
    ├── 250a6e4eb441ae91834a0f41b7a697c65e5e2563.nq.gz
    ├── 261d3d346980c5fa54cd0cafc82baa90499adfa7.nq.gz
    ├── 2684c3890e08b47db3e47f207e4e97d3013dd2e2.nq.gz
    ├── 27346484a6d90530d3ec1ac1ac48fb7f2717cef8.nq.gz
    ├── 28d541c2924bbd427317a0ada89f0e42b11b5455.nq.gz
    ├── 29fe9befcad0304c0ff094f76a23b3019d1dd747.nq.gz
    ├── 2a03eddb383d6c060124d2a273b6f1b091d841b4.nq.gz
    ├── 2ac091f37ae9acee5f1651d2b20ce6026990b2ec.nq.gz
    ├── 2ac784ddece6122a6631734ef9f2f5e24b512117.nq.gz
    ├── 2b71adda253ca5c31242f34b9d1bf0971a501ab3.nq.gz
    ├── 2db6c2f51414823a7651de1e771bfeece96777c4.nq.gz
    ├── 2e4b28482dc6f369669888448c4bc786f51fbd81.nq.gz
    ├── 2e5eee792bd4dc7d95997a620df9f6b293a87e36.nq.gz
    ├── 2ea722be39f1a7079f3272479d07db01df88c0de.nq.gz
    ├── 3327634f98055b60ef2cd6ff1e42da812b8c6892.nq.gz
    ├── 339ef659b1cfbdc72b222109bfc34488ca24ed64.nq.gz
    ├── 33b4f668e2b2113d287ecbd4941f02ebaf64f099.nq.gz
    ├── 34de6d38305ab87afb36c9e91cf624f846ccd989.nq.gz
    ├── 35ea0e29daf901f053bb3d6e6bb8cd565989dd48.nq.gz
    ├── 37ac6deba2976937447c76739780182edc74b97d.nq.gz
    ├── 3837d4c4f910706557a3541df103e10469298cd7.nq.gz
    ├── 3a45ffd0415b087e267385067678f87bb117728f.nq.gz
    ├── 3a7ac1ad5d63e6b37cd399c697bafa5683af683b.nq.gz
    ├── 3a7da2c65223f6287364cac1c99f4a63f30f9f25.nq.gz
    ├── 3c691cffd2bce02ebc89e58c37b91203db68593d.nq.gz
    ├── 3d394a3edc88210405f885f6c84ed3ba821f5065.nq.gz
    ├── 3e6b6342e2057b2d6e9401f4407ced3ea258b59e.nq.gz
    ├── 3ec76af77c4180c7a53bc597e9471651503b000a.nq.gz
    ├── 3fc3242eeb6bba042f17eeaf53f4a4392592c7a0.nq.gz
    ├── 401795a0056a1bf3a49bd6f1d79ed5f53581df24.nq.gz
    ├── 40cdd7a4fdee6974ef0169de3c1ba0de836a18e8.nq.gz
    ├── 417afeb5d64acbf353e365965a4a87b80693355d.nq.gz
    ├── 4206253c10b01f75971b5367ee926d784f0b64ed.nq.gz
    ├── 42235252d6d916acc292640e56536d25d5014031.nq.gz
    ├── 4432bb17584488ba240fddfbcdf91132124aab4b.nq.gz
    ├── 4493ad1f76888f29760e3dc665ab3307307245d6.nq.gz
    ├── 44dc6633324307e6834e0346eefe7874f1061b3c.nq.gz
    ├── 464469fac1ce07b47817b641da827d0c435b8cd5.nq.gz
    ├── 477b762dc98b76b528611ac4383a70cec74df096.nq.gz
    ├── 48a63c4137805410637e42686d6a6d6232c954ed.nq.gz
    ├── 494c4bf67ab5b01b2975a33ebea0b82e5d71db66.nq.gz
    ├── 4bf9f79367e80b4793d6f845fbf66addc1e677d0.nq.gz
    ├── 4c6edf586ac86df70a9dbea33ad4d1478114ace8.nq.gz
    ├── 4cb5a4f4344a83e5e1735f38b816ade50716012a.nq.gz
    ├── 4d289f5004e5118c094cb01b9407b3701435df2b.nq.gz
    ├── 4e1c9871f1f61025fa49cb9b70cec8209006dcc9.nq.gz
    ├── 4e3c7250bee75f47ef37323cd802c7c567f37545.nq.gz
    ├── 4e7ec0490cf6fcb87d79dd6ebfcdff05a6a5bef8.nq.gz
    ├── 4ead46a49a44ba4b51c60649343c1e8fd6e429c0.nq.gz
    ├── 4f19663c3259749f516082e4ce18503fbc6d419e.nq.gz
    ├── 4fee72678fad128770d4bdf767233ef9c53379e1.nq.gz
    ├── 5033948155bcb88b184c5df6ba43562d4d8c8e0d.nq.gz
    ├── 52d97327979636b0184193c489bb51a2a63b26ec.nq.gz
    ├── 5390715e5fe7dec1782a0226a40f3e8de4641b76.nq.gz
    ├── 54ce8738098285c682ca520417935ae4c05864be.nq.gz
    ├── 54d20661e84c198f037cc313d1e2fcbbcb906548.nq.gz
    ├── 5500ab4c5cee71fe0d1322dec8f76c35b32310d7.nq.gz
    ├── 5638559cecca5effd6190830f2ad224c61c93903.nq.gz
    ├── 57caa7d19a43c1237330c9ca5fe0f71e25d3df37.nq.gz
    ├── 57fdca54b0d5249bdbff281bde576e57342059e5.nq.gz
    ├── 5ac3018b9f8074a54c1bf1bfbb1899e7eeb4a0d1.nq.gz
    ├── 5b0dd1b8d06e2709e1971612d1d81f1d304ee13c.nq.gz
    ├── 5b4f9918a1ab8d96480d90f81164be65c9ede436.nq.gz
    ├── 5b748d36954cc4c6be886173e3f4b2ac89914228.nq.gz
    ├── 5bbff30bcb42cbb5b4d5b80e331933a3836cec4c.nq.gz
    ├── 5be231d032416f18c2638d658f4e89320849fac5.nq.gz
    ├── 5cd35cdfce20fa4460eec20d4e0799d1d4381244.nq.gz
    ├── 5cfc307c04a9fa1c4d538bf165a1dda82a64f6a6.nq.gz
    ├── 5e545df75823f5b89bc337efac7ad1748f03254f.nq.gz
    ├── 5eb93c6ed6070455c8dc1a209bbe455b88bd2928.nq.gz
    ├── 5ee2d3ddcbeb1c413a895c2d9b6f23db93e9ea83.nq.gz
    ├── 5f3b171d1fa055988dd01af0436a549ed663bb94.nq.gz
    ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
    ├── 60c2a7e754e8c4e8bf9971d9367a4aef873d0f3e.nq.gz
    ├── 60d0b70ca7ab6c42f39ff3abd515ba8686c00db4.nq.gz
    ├── 60fb30c61f9af067779faab19e0096dd8c168ba3.nq.gz
    ├── 61e01c5790d938bbbfdab643e4990981733f6327.nq.gz
    ├── 64428c59ea75108a13dad16e3fc517dda02b4c45.nq.gz
    ├── 647b8a7dfc85e7059bfa45d0435cdb8e26514c10.nq.gz
    ├── 65b794d9beafd5662679fff18ca510abaf4d5cdc.nq.gz
    ├── 66349a3f64d8d6af6cd499a8cb20ca4e425142e9.nq.gz
    ├── 6741867c3e4b11e852d1680e98acc917d31505d1.nq.gz
    ├── 67d89c250eaae5d1e083f784e203e8224c04ca3f.nq.gz
    ├── 67fce7ed047f0fef7b766a82aa9358c72ad2135b.nq.gz
    ├── 68142f48291c1bf3b4d8deb827bd8e58734bb759.nq.gz
    ├── 68c6301b1df5f8e778e41032cca46876506b95b2.nq.gz
    ├── 691fa305b6a5fb53b967014f7a17521342ae23da.nq.gz
    ├── 6922fd8060dc8c55ad0db82f50dc671a753dcb3c.nq.gz
    ├── 69dbbce7396c9bd64e4b6d9d0b5f64ae04c95947.nq.gz
    ├── 6b470d3bc11a874ad19149aafe8ade8af45740fd.nq.gz
    ├── 6c5a3d3589a35b3d21db08808c737dc479e81382.nq.gz
    ├── 6e02697ea619bcc577a3e2c3b7a67559c24c1977.nq.gz
    ├── 7001b801f634e3fff7ff589fcfcb6410eb693af5.nq.gz
    ├── 70e7d52b3e1b5eeadfaaf54592430d61855bada9.nq.gz
    ├── 719282c0b72f4f29f17161fe66a0232ebcc4d727.nq.gz
    ├── 71fdceb1c9726d302aed5f55b38f895ef7c07223.nq.gz
    ├── 729f9b84dfb925679a4625ec904cfdd9862b79dd.nq.gz
    ├── 73e2ed0ceff583ac86fba13b023f345332c2d682.nq.gz
    ├── 74cd30a49fe71c9fdf3896550de2df25eac09d7a.nq.gz
    ├── 74d411ddd0c533b660ef3f23eeac868a7bfa4924.nq.gz
    ├── 75d544aad0f83dbb0115e32cc468bf458ae84cd8.nq.gz
    ├── 77c0d6eb9bfb204c1580509b57238a655cab08da.nq.gz
    ├── 78fa4b19a23b8476d2bd0247a78ca0471685b79b.nq.gz
    ├── 7a5d285218abe8e782f2febc6676585c2293c297.nq.gz
    ├── 7c4b72ebc667eeabc25dbc3789bbf89493a172a5.nq.gz
    ├── 7de6350ab5da835879d97c83aaf01a311a5099df.nq.gz
    ├── 7e7b4bba3a8624b523791fb3954382341d75a3cf.nq.gz
    ├── 7f3819f034158159761c8c83e133be188894e692.nq.gz
    ├── 7fc4fb881aa013942949fa8e0fba7cb2ca8c7095.nq.gz
    ├── 7fe0110fda72745e6fc8a22875aa1b83816e02e3.nq.gz
    ├── 82eabc94e0de65de7d39d22651fef6c6a8f04f8b.nq.gz
    ├── 831fe5ce0e2a7f293daeb7e406a5f12e7ef93d40.nq.gz
    ├── 834f04ea309bdda995c22e7aefb557fee9861c22.nq.gz
    ├── 845c3ff2e8a77902f739b52c0f58361414c8711e.nq.gz
    ├── 84e87ff161553a0002526c446a5cecce9fe92564.nq.gz
    ├── 8515bf58fb6e23f53dc1b4d2b01910883874c76e.nq.gz
    ├── 855b5ec441018f80e8043aee770cc1462be806bd.nq.gz
    ├── 859ed6793008a4a95bda3126650b5c11c38b4c8e.nq.gz
    ├── 860e3d1b2aa19d79deb70d7ebd67be2acc9e48bd.nq.gz
    ├── 87cc9ff3282000b6b835645d32c8089dab141e12.nq.gz
    ├── 87fd205384535876482f550dfdebe080a5c7ad30.nq.gz
    ├── 888ca35cff01d92b6342de560b417597cf763c28.nq.gz
    ├── 88d72c8623a4275c85cb32e2ec35205b5b907176.nq.gz
    ├── 8902ec1f22e5150c3814a0f7f2520d8acfdaf93a.nq.gz
    ├── 8c7fda818b5c27021c811d25e5e9f8be39743efd.nq.gz
    ├── 8d72b2b2f8d59a0732f1a78cb33074d8cb95a84c.nq.gz
    ├── 8eea05db5f4219cb1f7dc4dc8b638dc5dd5f8875.nq.gz
    ├── 9006f116d1c203b74f4afad7a1dc01e545d0f3f4.nq.gz
    ├── 90fbcb12975b53571e7feea687126d7d9dbf39b5.nq.gz
    ├── 922c6d2ff5d28ce19fc1721c7e8c599c181531d2.nq.gz
    ├── 92683ae9b935bd71e5649c96399175ed3db58a8b.nq.gz
    ├── 9304032d7db83424b877273ea0e6e693aed06d41.nq.gz
    ├── 9552633330101cfd45a89efa85ef9db95063c863.nq.gz
    ├── 95f8e84f4b0f7fd4383df2153508c1de7b9090a8.nq.gz
    ├── 968938d70529329bb4f51bc8ca649ce8205fd599.nq.gz
    ├── 9878b3b91f9bf59050f36e48b4f8afa63b406361.nq.gz
    ├── 98a29a8d0435048ca1f4effa988fbaa1e8781235.nq.gz
    ├── 992c29c15b7042ce99f9ec2a6c2e440682f93388.nq.gz
    ├── 9a910e4c98ca02b844a69fe7a0a3433473b4e197.nq.gz
    ├── 9b1218625a154b2f424dfd18978a768fbe77ce7e.nq.gz
    ├── 9bd1d49c06ae93e7c5b5fa2755fafb4d37569659.nq.gz
    ├── 9bfb5c72302a5676ecca572c481ef49786f653ff.nq.gz
    ├── 9dfd92205e7630fd83db7034c6d2b256e7c50c9f.nq.gz
    ├── 9e8def483d84ad65ae2ba7e6d450e36dfa08e93b.nq.gz
    ├── 9ee1f2f0f3b167622e48ac03c075c9c1806fb8d7.nq.gz
    ├── 9fbc744e11f012e7622e07fcff53ddb25e577c00.nq.gz
    ├── a29cffee710c810672dee4c19d66694d090ef08a.nq.gz
    ├── a2e0872b8f8a7a41e19b1eac1c785c5a3131cb2e.nq.gz
    ├── a2ed1449504e4e3d037ec1af5c0d4b44a6ffb44b.nq.gz
    ├── a397e3fa1cadee67d43a411c46cc40eb1deb2ce8.nq.gz
    ├── a400c326057f3c29536dce3050bc7678aa1886d3.nq.gz
    ├── a40435e812d280d7cbcc1c97909af6c8b38d868c.nq.gz
    ├── a42b80b11e30df367a047fba656d073d40cf432e.nq.gz
    ├── a4629626419a83fc0f6920fa70f5a106d1f70779.nq.gz
    ├── a4a799974f3a1936b305736efe5c3b7b119d7d1e.nq.gz
    ├── a4e35ad652085b4764985331275f07fca35cf4b8.nq.gz
    ├── a5252529c2d8a0c649d3e786e8fe4391d7deffb9.nq.gz
    ├── a71e19fa6f9c1e5a8231c9a47fdefa77f59b777a.nq.gz
    ├── a76532cd8a15a12af09c4a51f3da3a58a392eea0.nq.gz
    ├── a7a2e700c1538e915943c8469e696cd13036da90.nq.gz
    ├── a920aa566fdb7d35c7beb117f8defbb9f8d1c8c5.nq.gz
    └── a97bf9c57460ecfc27761accf90d712ea5cebb44.nq.gz

8 directories, 200 files
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

[tornadoweb/tornado](https://github.com/tornadoweb/tornado)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
