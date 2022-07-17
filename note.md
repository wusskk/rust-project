# Rust Note
## Chapter-1

### 下载Rust
* Linux or macOS：
``` bash
# Linux or macOS
curl http://sh.rustup.rs -sSf | sh
```
* Windows：去官网下载。

* 查看版本：
``` bash
rustc --version
```

* 更新与卸载
``` bash
# 更新
rustc update

# 卸载
rustup self uninstall
```
### 编译与运行
``` bash
# 编译
rustc main.rs

# 运行
./main.rs
```

### Cargo
Cargo是Rust工具链中内置的构建系统及包管理器。
``` bash
# 编译以及构建可执行程序
cargo build

# 仅编译，不生成可执行程序，主要用于检查能否通过编译
cargo check

# 构建并运行
cargo run

# 发布项目时选择Release模式，进行代码优化
cargo build --release
