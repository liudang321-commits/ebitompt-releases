# eBitompt 更新分发仓库

本仓库**只存放 eBitompt 的更新产物**，不包含源码。

| 文件 | 用途 |
|---|---|
| `eBitompt-Setup-<version>.exe` | 安装包 |
| `eBitompt-Portable-<version>.exe` | 便携版 |
| `eBitompt-Setup-<version>.exe.blockmap` | 增量更新块映射 |
| `latest.yml` | 更新清单，客户端据此判断是否有新版本 |

## 为什么单独开一个仓库

eBitompt 桌面客户端需要以**匿名**身份读取更新清单才能检查更新——客户端不持有任何凭据。
GitHub 对私有仓库的匿名请求一律返回 404，因此更新产物必须托管在公开仓库；
而源码仓库继续保持私有。

**请不要在这里提交源码。** 这里只放产物。

## 下载

前往 [Releases](../../releases/latest) 获取最新版本。

---

*This repository hosts release artifacts only. The source code is not public.*
