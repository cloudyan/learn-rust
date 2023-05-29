# learn-rust

学习 rust

- [rust 官网](https://www.rust-lang.org/)
  - [官方中文站](https://www.rust-lang.org/zh-CN)
- [官方在线工具](https://play.rust-lang.org/)
- [标准库](https://doc.rust-lang.org/std/index.html)
- cargo: Rust 包管理器[cargo 手册](https://doc.rust-lang.org/cargo/index.html)
- rustc: Rust 编译器，[rustc 选项](https://doc.rust-lang.org/rustc/index.html)
- `rustup doc`
  - [Rust 程序设计语言-book](https://doc.rust-lang.org/book/)
  - [RustDoc 手册](https://doc.rust-lang.org/rustdoc/index.html)
  - [rust cli 命令行手册](https://rust-cli.github.io/book/index.html)
  - [Rust WebAssembly 手册](https://rustwasm.github.io/docs/book/)
  - [通过例子学 Rust](https://doc.rust-lang.org/stable/rust-by-example/)

## hello

```rust
rustc --version
// 卸载
rustup self uninstall

// hello.ts
fn main() {
  println!("Hello, world!");
}

// 编译
rustc main.rs
```
