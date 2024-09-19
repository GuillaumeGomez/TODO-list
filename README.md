# TODO-list

 * [ ] Make [unescape functions](https://github.com/rust-lang/rust/blob/master/compiler/rustc_lexer/src/unescape.rs) available through `proc-macro` crate
 * [ ] Make crates.io work without JS
 * [ ] Finish rustc_codegen_gcc sync
 * [ ] Improve integration of rustc_codegen_gcc into the Rust compiler
   * [Add support for building gcc and libgccjit](https://github.com/rust-lang/rust/pull/125419)
   * Add support for `backend = "gcc"` in `config.toml`
   * Run rustc tests with GCC backend in rustc's CI
 * [ ] https://github.com/rust-lang/rust/issues/126638
 * [ ] https://github.com/rust-lang/rust/issues/67533 (https://github.com/rust-lang/rust/pull/128780)
 * [ ] https://github.com/rust-lang/rust/issues/50784
 * [ ] [extra scraped examples height was increased without noticed](https://github.com/rust-lang/rust/issues/130562)
 * [ ] [Cargo doc --examples doesn't pick up default features or report failure](https://github.com/rust-lang/rust/issues/130560)
 * [ ] [Add tidy check for missing {# #} tag in rustdoc templates](https://github.com/rust-lang/rust/issues/130559)
 * [ ] [rustdoc: make linking to examples easier and detect dead links](https://github.com/rust-lang/rust/issues/130493)
 * [ ] [warn on strings that look like inline format strings but aren't](https://github.com/rust-lang/rust-clippy/issues/10195) (done in https://github.com/rust-lang/rust-clippy/pull/13410)
 * [x] Sort item kinds in impl (first comes types, then consts and finally functions) (done in https://github.com/rust-lang/rust/pull/129471)
 * [x] Migrate <docs.rs> to askama
   * Lot of updates to [the askama crate](https://github.com/djc/askama/pulls/GuillaumeGomez)
   * Update docs.rs to use askama
   * Forked askama into [rinja](https://crates.io/crates/rinja)
   * Finished docs.rs migration (https://github.com/rust-lang/docs.rs/pull/2292)
