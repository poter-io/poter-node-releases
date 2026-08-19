# Poter Node Releases

Poter Node (headless relay / gateway / pin service) 预编译二进制发布仓库。

桌面端 SSH 部署从 `https://github.com/poter-io/poter-node-releases/releases/download/v{版本}/poter-node_linux-{arch}` 下载二进制,资产命名必须保持:

| 资产名 | 架构 |
|---|---|
| `poter-node_darwin-aarch64` | macOS Apple Silicon |
| `poter-node_darwin-x86_64` | macOS Intel |
| `poter-node_linux-aarch64` | Linux arm64 (glibc) |
| `poter-node_linux-x86_64` | Linux amd64 (glibc) |

每个二进制附带同名 `.sha256` 校验文件(`<hash>  <文件名>` 格式)。

源码仓库: [big-tengu/Poter-v2](https://github.com/big-tengu/Poter-v2)
