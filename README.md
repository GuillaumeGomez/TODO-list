# TODO-list

 * [ ] Make [unescape functions](https://github.com/rust-lang/rust/blob/master/compiler/rustc_lexer/src/unescape.rs) available through `proc-macro` crate
 * [ ] Make crates.io work without JS
 * [ ] Finish rustc_codegen_gcc sync
 * [ ] Improve integration of rustc_codegen_gcc into the Rust compiler
   * [Add support for downloading libgccjit.so file](https://github.com/rust-lang/rust/pull/124353)
 * [ ] https://github.com/rust-lang/rust/issues/126638
 * [ ] https://github.com/rust-lang/rust/issues/67533 (https://github.com/rust-lang/rust/pull/128780)
 * [ ] https://github.com/rust-lang/rust/issues/50784

## Finished

 * [x] Migrate <docs.rs> to askama
   * Lot of updates to [the askama crate](https://github.com/djc/askama/pulls/GuillaumeGomez)
   * Update docs.rs to use askama
   * Forked askama into [rinja](https://crates.io/crates/rinja)
   * Finished docs.rs migration (https://github.com/rust-lang/docs.rs/pull/2292)
