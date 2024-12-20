# TODO-list

 * [ ] Make [unescape functions](https://github.com/rust-lang/rust/blob/master/compiler/rustc_lexer/src/unescape.rs) available through `proc-macro` crate
 * [ ] Make crates.io work without JS
 * [ ] Improve integration of rustc_codegen_gcc into the Rust compiler
   * [Add support for building gcc and libgccjit](https://github.com/rust-lang/rust/pull/125419)
   * Add support for `backend = "gcc"` in `config.toml`
   * Run rustc tests with GCC backend in rustc's CI
 * [ ] https://github.com/rust-lang/rust/issues/126638
 * [ ] https://github.com/rust-lang/rust/issues/67533 (https://github.com/rust-lang/rust/pull/128780)
 * [ ] https://github.com/rust-lang/rust/issues/50784
 * [ ] [Cargo doc --examples doesn't pick up default features or report failure](https://github.com/rust-lang/rust/issues/130560)
 * [ ] [rustdoc: make linking to examples easier and detect dead links](https://github.com/rust-lang/rust/issues/130493)
 * [ ] [handle doc(hidden) differently in rustdoc](https://github.com/rust-lang/rust/issues/129415)
 * [ ] [Add new rustdoc lint to detect if merged doctests failed to compile](https://github.com/rust-lang/rust/issues/127603)
 * [ ] [warn on strings that look like inline format strings but aren't](https://github.com/rust-lang/rust-clippy/issues/10195) (done in https://github.com/rust-lang/rust-clippy/pull/13410)
 * [ ] Improve float `Display` conversion (checking how [ryu](https://crates.io/crates/ryu) does it)
 * [ ] Add possibility to expand macro in rustdoc source code pages (add a button on the left of a line if there is a macro call)
 * [ ] [Conditionally derived traits using cfg_attr are not documented as being behind a feature flag](https://github.com/rust-lang/rust/issues/103300)
 * [ ] [rustdoc: Don't show two different types as the same thing in a single function](https://github.com/rust-lang/rust/issues/122673)
 * [ ] Improve `Display` implementation for integers (follow-up of https://github.com/rust-lang/rust/pull/133247)
 * [x] Sort item kinds in impl (first comes types, then consts and finally functions) (done in https://github.com/rust-lang/rust/pull/129471)
 * [x] Migrate <docs.rs> to askama
   * Lot of updates to [the askama crate](https://github.com/djc/askama/pulls/GuillaumeGomez)
   * Update docs.rs to use askama
   * Forked askama into [rinja](https://crates.io/crates/rinja)
   * Finished docs.rs migration (https://github.com/rust-lang/docs.rs/pull/2292)
 * [x] Finish rustc_codegen_gcc sync
 * [x] [extra scraped examples height was increased without noticed](https://github.com/rust-lang/rust/issues/130562)
 * [x] [Add tidy check for missing {# #} tag in rustdoc templates](https://github.com/rust-lang/rust/issues/130559)
