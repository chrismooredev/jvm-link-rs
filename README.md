# jvm-link

Simple crate to link to a JNI-capable JVM.

Should work on Windows, Linux, and macOS

Adapted from code from the `jni` crate.

This crate is intended for use as a dependency for binary executable crates, or as a dev-dependency for tests in libraries.

If you are getting linkage errors, please ensure the following is in your `lib.rs`/`main.rs` file.
```rust
extern crate jvm_link;
```
