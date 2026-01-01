# Typed Ant LSP

Typed Ant LSP 是一个基于 Rust 的语言服务器协议（LSP）实现，旨在为开发者提供高效、可靠的代码编辑支持。

## 项目结构

```
typed_ant_lsp/
├── Cargo.toml          # 项目根目录的 Cargo 配置文件
├── src/                # 主程序代码目录
│   └── main.rs         # 主入口文件
├── lsp_backend/        # LSP 后端实现
│   ├── Cargo.toml      # 后端模块的 Cargo 配置文件
│   └── src/            # 后端模块代码目录
│       ├── lib.rs      # 后端库的主要实现
│       └── utils.rs    # 工具函数模块
└── target/             # 编译输出目录
```

## 功能

- 提供语言服务器协议支持
- 代码解析与分析

## 构建与运行

### 环境要求

- Rust 编译器（建议使用最新稳定版）
- Cargo 构建工具

### 构建项目

在项目根目录下运行以下命令以构建项目：

```bash
cargo build --release
```

### 运行项目

需要注意的是，本项目并不能直接执行。推荐搭配 VSCode 使用

## 贡献

欢迎对本项目提出建议或贡献代码。请确保在提交代码前运行所有测试并通过。
(这项目有毛测试)

## 许可证

本项目采用 MIT 许可证。详情请参阅 [LICENSE](LICENSE) 文件。