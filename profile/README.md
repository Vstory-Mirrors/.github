# Vstory-Mirrors

> 上游开源项目的公开镜像，用于归档与提交历史检索。全部为 fork，不改动上游代码。

## LSPosed 主链

| 仓库 | 说明 |
| --- | --- |
| [LSPosed](https://github.com/Vstory-Mirrors/LSPosed) | LSPosed Framework |
| [LSPlant](https://github.com/Vstory-Mirrors/LSPlant) | ART 运行时 hook 框架 |
| [LSPlt](https://github.com/Vstory-Mirrors/LSPlt) | Android 平台的简单 PLT hook |
| [LSParanoid](https://github.com/Vstory-Mirrors/LSParanoid) | 应用字符串混淆器 |
| [LSPlugin](https://github.com/Vstory-Mirrors/LSPlugin) | 插件模块 |
| [AndroidHiddenApiBypass](https://github.com/Vstory-Mirrors/AndroidHiddenApiBypass) | LSPass：绕过非 SDK 接口限制 |
| [DexBuilder](https://github.com/Vstory-Mirrors/DexBuilder) | 用 C++ 生成 dex 文件 |
| [dexsql-release](https://github.com/Vstory-Mirrors/dexsql-release) | 用 SQL 查询 Android 的 apk / dex 文件 |

## libxposed

| 仓库 | 说明 |
| --- | --- |
| [libxposed-api](https://github.com/Vstory-Mirrors/libxposed-api) | libxposed 接口定义 |
| [libxposed-helper](https://github.com/Vstory-Mirrors/libxposed-helper) | 配套辅助库 |
| [libxposed-service](https://github.com/Vstory-Mirrors/libxposed-service) | 服务端实现 |
| [libxposed-example](https://github.com/Vstory-Mirrors/libxposed-example) | 示例模块 |

## 相邻项目

| 仓库 | 说明 |
| --- | --- |
| [YukiHook](https://github.com/Vstory-Mirrors/YukiHook) | 现代的 hook API 与 Xposed 模块方案（上游现名 `HighCapable/YukiHook`） |
| [miuix](https://github.com/Vstory-Mirrors/miuix) | Compose Multiplatform UI 库（镜像停在 `v0.9.4`） |
| [Notice](https://github.com/Vstory-Mirrors/Notice) | LSPosed 通知拦截模块：按规则过滤系统通知 |
| [io.mo.mnblocker](https://github.com/Vstory-Mirrors/io.mo.mnblocker) | 基于正则匹配与通知渠道管理的垃圾通知拦截模块 |

## 文档

| 仓库 | 说明 |
| --- | --- |
| [LSPosed-wiki](https://github.com/Vstory-Mirrors/LSPosed-wiki) | LSPosed 官方 Wiki 镜像（wiki 仓库无法 fork，为独立镜像） |

## 自动巡检

`.github/workflows/upstream-sync-check.yml` 每天 09:17（UTC+8）比对上面列出的镜像与上游默认分支的 HEAD：有落后就开出带 `upstream-sync` 标签的 issue 并持续更新同一页，全部同步后自动关闭。

## 关于

- 提交历史与上游完全一致，可直接用于 `git log`、`blame`、`diff` 检索
- 不接受 PR 与 issue，改动请提交到对应上游仓库
- 上游若删除仓库，fork 会自动转为独立仓库，内容与历史不受影响
