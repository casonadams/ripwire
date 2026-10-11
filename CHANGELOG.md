# Changelog

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
