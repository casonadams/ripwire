# Changelog

## [0.3.0](https://github.com/casonadams/ripwire/compare/ripwire-v0.2.0...ripwire-v0.3.0) (2026-10-12)


### Features

* **arch:** implement --arch layering rules, --mermaid diagrams, and --zoom ([eebcb78](https://github.com/casonadams/ripwire/commit/eebcb783df86083847117b53756e46a284e11fb4))
* **cli:** add top-k, schema legend, test layering, and git-HEAD delta parity ([9d6368a](https://github.com/casonadams/ripwire/commit/9d6368abd8f7c6b01048e4c9d5ac2714adb7ebb7))
* **cli:** complete 1-to-1 feature and flag parity with ripwire engine ([3b44f34](https://github.com/casonadams/ripwire/commit/3b44f348e71d529c343bc13d102c59319e41fbe4))
* **cli:** complete 1:1 parity with CLI mutations, session tools, and advanced queries ([9f3907c](https://github.com/casonadams/ripwire/commit/9f3907c02ac268201bad19fcbfa74b32792d697f))
* **gate:** implement --map-diff, --seams, --pr-context, and --merge-scout ([396d729](https://github.com/casonadams/ripwire/commit/396d729967fdf9187be81b6a7845d27fc2ca342d))
* **gate:** implement short-horizon-churn, nesting, params, quality acks, and exit code 2 contract ([2c9db2f](https://github.com/casonadams/ripwire/commit/2c9db2f4f1ce31499c7fd182c9b9bb08a26339a6))
* **grammars:** add HTML and CSS tree-sitter grammars ([b7f1392](https://github.com/casonadams/ripwire/commit/b7f1392dc20d19c2874c92dc58f79f09f8289601))
* **grammars:** add Scala and Erlang tree-sitter grammars ([2fe8403](https://github.com/casonadams/ripwire/commit/2fe84035e677eb6fd5a8f4215fcab4c1c3e041a9))
* **grammars:** add SQL, Protobuf, GraphQL, and Dockerfile support, expanding to 35 languages ([c951c9a](https://github.com/casonadams/ripwire/commit/c951c9a6681da097940b5d0a3e4bff76cb3dc617))
* **grammars:** add Zig, Solidity, and HCL tree-sitter grammars ([5020560](https://github.com/casonadams/ripwire/commit/50205606f7f8f885aa5f942f5afc9b2504376010))
* **grammars:** expand language support to 31 languages across systems, cloud, functional, and web ([224fe31](https://github.com/casonadams/ripwire/commit/224fe3106447c9a0ad5d212eb763affc8659c2ad))
* **make:** add make validate and make parity targets with cross-repo validator ([07bd1cc](https://github.com/casonadams/ripwire/commit/07bd1cc911af447eac9c62af03138a855c6911ab))
* **man:** add manual pages for rw and ripwire with automatic cargo install ([beb21ab](https://github.com/casonadams/ripwire/commit/beb21abb27c6f6ed466890477819c7bebcae379c))
* **metrics:** implement --biggest-first, --nonlocal-state, --lint, and --lint-catalog ([8e0a923](https://github.com/casonadams/ripwire/commit/8e0a923b27e1cb48979d7bd7affb32131f468bea))
* **navigate:** implement --at, --verify, --pack-task, and --graph-query ([44a139a](https://github.com/casonadams/ripwire/commit/44a139afe44af00b964a97277ac9e456639650b0))
* **parity:** achieve 100% 1:1 behavioral parity with upstream ripwire across 36 commands ([83c7742](https://github.com/casonadams/ripwire/commit/83c77422750795658207ba1486215b331d0e03f5))
* **skills:** package and install 18 ripwire agent skills with --add-skills ([7affe30](https://github.com/casonadams/ripwire/commit/7affe30d01be7e479e4a1d7a2d5abb7f6bcc093f))


### Bug Fixes

* **cli:** default top_k to 200 in dispatch_default_run matching upstream ripwire ([3dc265d](https://github.com/casonadams/ripwire/commit/3dc265dc6f53be1e51e4a9e66267dad034bdc005))
* **clones,cli:** resolve target repository paths in clone detector and fix endpoint splitting in path query ([7083915](https://github.com/casonadams/ripwire/commit/7083915ecac75b43747d4e014bccfdcfb7dcdea5))
* **gate:** validate git refs in merge-scout and fetch full history in CI parity validation ([7137f4d](https://github.com/casonadams/ripwire/commit/7137f4dd1850b9f09192bcaaf28b4fbbac84f01d))
* **parity:** resolve CRAP complexity scores and enforce unambiguous path matching for --at ([8ab1d36](https://github.com/casonadams/ripwire/commit/8ab1d36cb149302703ab0fb2fc4298e9b41b4261))
* **skills:** ensure all skills trigger on ripwire and invoke rw binary ([462ad06](https://github.com/casonadams/ripwire/commit/462ad063788f7dd051ec3ef849a555e7a1449c23))


### Documentation

* **sync:** update README, gates, workflows, man pages, and skills catalog ([02f7337](https://github.com/casonadams/ripwire/commit/02f73373479121a01bc06fe3fabec3e8c290b043))


### Code Refactoring

* **gate:** format pr_context and reduce cyclomatic complexity ([05f9b1f](https://github.com/casonadams/ripwire/commit/05f9b1f81cb1c0000491bd3862ffdea4aef9e886))

## [0.2.0](https://github.com/casonadams/ripwire/compare/ripwire-v0.1.2...ripwire-v0.2.0) (2026-10-11)


### Features

* **cli:** expose all top-level Ripwire workflow flags and XML query serializers ([dce2f10](https://github.com/casonadams/ripwire/commit/dce2f105e8c2ec36ab7c1c196d231ebf9c83fec5))
* **navigate:** format navigation commands as canonical Ripwire XML ([e6ca76c](https://github.com/casonadams/ripwire/commit/e6ca76c8d0d8632a42671cc95423f6d3ec0e5a1c))
* **serialize:** align XML schemas and child tags with Ripwire canonical dialect ([5ed0c00](https://github.com/casonadams/ripwire/commit/5ed0c00dd6ad088dc001d87c0f1af9e56423c109))


### Bug Fixes

* **build:** add MSVC C11 flags and update repository metadata ([fcecdb0](https://github.com/casonadams/ripwire/commit/fcecdb0dd991e92bc139b79e05a02522dc56ef22))
* **cli:** match Ripwire exit 1 and error reporting on missing navigation symbols ([3e98f34](https://github.com/casonadams/ripwire/commit/3e98f343b815cd5f4d70027c19c1e132c7eb77d3))
* **cli:** resolve CRAP threshold failures on navigation and query serialization ([1404301](https://github.com/casonadams/ripwire/commit/14043014d61addeddeac96be0e863847d824e5cf))


### Performance Improvements

* **clones:** cache file bytes in candidate extraction and fast-path co-change capability ([4c23c25](https://github.com/casonadams/ripwire/commit/4c23c257b42de54c811762dc5fb5289079591d33))
* **clones:** parallelize type-3 clone pair evaluation and direct-scan readability bytes ([c9dd57f](https://github.com/casonadams/ripwire/commit/c9dd57f6ad4f031106177ce53a1c9cba2cb73076))
* **hits:** direct CSR slice indexing in HITS power iteration ([457aa92](https://github.com/casonadams/ripwire/commit/457aa92255fa45a3fded2fec4489d2745749ae6b))
* **ingest:** optimize directory crawl, parser reuse, and reference span lookup ([b90f7c4](https://github.com/casonadams/ripwire/commit/b90f7c43478a78e8cad733d43cb67364acc77f6a))
* **kgrams:** sort-dedup flat k-gram vectors and thread-local markdown parser ([0a6c9fe](https://github.com/casonadams/ripwire/commit/0a6c9fed57ce4b7f7529e7eb0c3977eaa7262265))
* **rank:** precompute reciprocal out-degrees and direct index CSR gather ([a4c14ae](https://github.com/casonadams/ripwire/commit/a4c14aeb3872994b8fcb04abf8face0dce8f61c2))
* **resolve:** stack candidate buffers, parallel reference resolution, and spur matching ([80647f5](https://github.com/casonadams/ripwire/commit/80647f5a7174d4241ae299c8f120933bfc002bba))


### Documentation

* **www:** format CLI commands as structured cards with operational mechanics ([884e0e8](https://github.com/casonadams/ripwire/commit/884e0e872256fff7b86104cb81294861d7a7418f))

## [0.1.2](https://github.com/casonadams/ripwire/compare/ripwire-v0.1.1...ripwire-v0.1.2) (2026-10-11)


### Features

* **cli:** implement categorized clap CLI and core MCP stdio server ([f40da01](https://github.com/casonadams/ripwire/commit/f40da015e1ac1ef7e7b08a39ea6f88d5b8cc6e2f))
* **clones:** implement AST clone detector with Type-1/2/3 matching and idiom demotion ([cf47f85](https://github.com/casonadams/ripwire/commit/cf47f85e908dc1889f2f02d0445118169e902404))
* **distribution:** rename crate to ripwire and binary to rw ([a840f28](https://github.com/casonadams/ripwire/commit/a840f2818da638e1007324c1ae00ce2ffead08c6))
* **domain:** implement SoA model and thread-safe string interner ([42ee6cf](https://github.com/casonadams/ripwire/commit/42ee6cfd59cc8aca67da2e135dafe9a7ab5f73b1))
* **gate:** implement pre-commit contract checker and affected test reachability mapper ([f28d1d1](https://github.com/casonadams/ripwire/commit/f28d1d1e7264dffcd6ed02eb749dc1102af71cda))
* **gate:** implement quality delta pre-commit gate and baseline snapshotting ([2744531](https://github.com/casonadams/ripwire/commit/274453162aa0823e68865b69adc6ff0c28ebc562))
* **git:** implement git commit history mining and shotgun surgery co-change detector ([815f95c](https://github.com/casonadams/ripwire/commit/815f95cf96c300e9ff3b89fc8bb4c3ae5e58a7b8))
* **graph:** implement reference resolution ladder and in-edge CSR construction ([aa9317f](https://github.com/casonadams/ripwire/commit/aa9317f883d2dbdad5ce7142eef57893f8ef8972))
* **ingest:** add polyglot crawler and tree-sitter extractors for Tier-1 languages ([a2ce0c5](https://github.com/casonadams/ripwire/commit/a2ce0c56bb2e631a4292aab37e95e3078443299d))
* **ingest:** add remaining 11 grammars and specialized language handlers for 24-language parity ([a1f2b30](https://github.com/casonadams/ripwire/commit/a1f2b303609a7b240e31ac1b0edb3da7d02d3d79))
* **ingest:** add systems and enterprise tree-sitter grammars ([3bc2790](https://github.com/casonadams/ripwire/commit/3bc279037d6635a85acc621ebea1c8fa4835e845))
* **mcp:** complete full 33 MCP tools suite and atomic edit operations ([182176f](https://github.com/casonadams/ripwire/commit/182176f4eb33bf89e466a2707ffde50503ed7f04))
* **metrics:** compute code complexity, readability, and maintenance hotspots ([4f8c866](https://github.com/casonadams/ripwire/commit/4f8c866433dff912826ba2b51ed2721229c19062))
* **packaging:** configure package include for crates.io publishing ([0a224eb](https://github.com/casonadams/ripwire/commit/0a224eb82f3e6f0db9635499e134f721a61766b7))
* **rank:** implement deterministic personalized PageRank with block reductions ([df73fea](https://github.com/casonadams/ripwire/commit/df73fea8d73e770648cbc79803762e055e04738a))
* **rank:** implement Kleinberg HITS algorithm and streaming token budgeting ([9e5c9d5](https://github.com/casonadams/ripwire/commit/9e5c9d5745f0e7eaad19c1867fcea250b9124d86))
* **resolve:** add scope extraction, call qualifiers, and callee deduplication ([919bdde](https://github.com/casonadams/ripwire/commit/919bdde2fed7c849260239b1d094f324d89eaa67))
* **serialize:** implement 64KB streaming minified XML serializer ([a18ae78](https://github.com/casonadams/ripwire/commit/a18ae78d12f134fefc317e23bd42e176f8e7930b))
* **serialize:** implement interactive HTML/SVG call graph export and Louvain community clustering ([0bf1e62](https://github.com/casonadams/ripwire/commit/0bf1e6242f67eb77d26ecb5e08bdfee33b8df94b))
* **slice:** implement ARISE intra-procedural def-use variable slicing and dataflow traversal ([a19506a](https://github.com/casonadams/ripwire/commit/a19506ad6b2979f881675c8599f733a5b95908ef))


### Bug Fixes

* **ci:** update tree-sitter-kotlin upstream branch to main ([644a486](https://github.com/casonadams/ripwire/commit/644a486eaad1c72ae31e215f2fe67e735ef1a61c))

## [0.1.1](https://github.com/casonadams/ripwire/compare/ripwire-v0.1.0...ripwire-v0.1.1) (2026-10-11)


### Features

* **cli:** implement categorized clap CLI and core MCP stdio server ([f40da01](https://github.com/casonadams/ripwire/commit/f40da015e1ac1ef7e7b08a39ea6f88d5b8cc6e2f))
* **clones:** implement AST clone detector with Type-1/2/3 matching and idiom demotion ([cf47f85](https://github.com/casonadams/ripwire/commit/cf47f85e908dc1889f2f02d0445118169e902404))
* **distribution:** rename crate to ripwire and binary to rw ([a840f28](https://github.com/casonadams/ripwire/commit/a840f2818da638e1007324c1ae00ce2ffead08c6))
* **domain:** implement SoA model and thread-safe string interner ([42ee6cf](https://github.com/casonadams/ripwire/commit/42ee6cfd59cc8aca67da2e135dafe9a7ab5f73b1))
* **gate:** implement pre-commit contract checker and affected test reachability mapper ([f28d1d1](https://github.com/casonadams/ripwire/commit/f28d1d1e7264dffcd6ed02eb749dc1102af71cda))
* **gate:** implement quality delta pre-commit gate and baseline snapshotting ([2744531](https://github.com/casonadams/ripwire/commit/274453162aa0823e68865b69adc6ff0c28ebc562))
* **git:** implement git commit history mining and shotgun surgery co-change detector ([815f95c](https://github.com/casonadams/ripwire/commit/815f95cf96c300e9ff3b89fc8bb4c3ae5e58a7b8))
* **graph:** implement reference resolution ladder and in-edge CSR construction ([aa9317f](https://github.com/casonadams/ripwire/commit/aa9317f883d2dbdad5ce7142eef57893f8ef8972))
* **ingest:** add polyglot crawler and tree-sitter extractors for Tier-1 languages ([a2ce0c5](https://github.com/casonadams/ripwire/commit/a2ce0c56bb2e631a4292aab37e95e3078443299d))
* **ingest:** add remaining 11 grammars and specialized language handlers for 24-language parity ([a1f2b30](https://github.com/casonadams/ripwire/commit/a1f2b303609a7b240e31ac1b0edb3da7d02d3d79))
* **ingest:** add systems and enterprise tree-sitter grammars ([3bc2790](https://github.com/casonadams/ripwire/commit/3bc279037d6635a85acc621ebea1c8fa4835e845))
* **mcp:** complete full 33 MCP tools suite and atomic edit operations ([182176f](https://github.com/casonadams/ripwire/commit/182176f4eb33bf89e466a2707ffde50503ed7f04))
* **metrics:** compute code complexity, readability, and maintenance hotspots ([4f8c866](https://github.com/casonadams/ripwire/commit/4f8c866433dff912826ba2b51ed2721229c19062))
* **packaging:** configure package include for crates.io publishing ([0a224eb](https://github.com/casonadams/ripwire/commit/0a224eb82f3e6f0db9635499e134f721a61766b7))
* **rank:** implement deterministic personalized PageRank with block reductions ([df73fea](https://github.com/casonadams/ripwire/commit/df73fea8d73e770648cbc79803762e055e04738a))
* **rank:** implement Kleinberg HITS algorithm and streaming token budgeting ([9e5c9d5](https://github.com/casonadams/ripwire/commit/9e5c9d5745f0e7eaad19c1867fcea250b9124d86))
* **resolve:** add scope extraction, call qualifiers, and callee deduplication ([919bdde](https://github.com/casonadams/ripwire/commit/919bdde2fed7c849260239b1d094f324d89eaa67))
* **serialize:** implement 64KB streaming minified XML serializer ([a18ae78](https://github.com/casonadams/ripwire/commit/a18ae78d12f134fefc317e23bd42e176f8e7930b))
* **serialize:** implement interactive HTML/SVG call graph export and Louvain community clustering ([0bf1e62](https://github.com/casonadams/ripwire/commit/0bf1e6242f67eb77d26ecb5e08bdfee33b8df94b))
* **slice:** implement ARISE intra-procedural def-use variable slicing and dataflow traversal ([a19506a](https://github.com/casonadams/ripwire/commit/a19506ad6b2979f881675c8599f733a5b95908ef))


### Bug Fixes

* **ci:** update tree-sitter-kotlin upstream branch to main ([644a486](https://github.com/casonadams/ripwire/commit/644a486eaad1c72ae31e215f2fe67e735ef1a61c))
