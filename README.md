# TokenFlow Homebrew Tap

GitHub Copilot CLI 本地只读 Token 用量 Dashboard 的安装源。

```bash
brew install wenjun-xu/tap/tokenflow
tokenflow start
```

v0.2.2 预发布提供按 Mac 架构下载的独立程序，无需安装 Python、Node.js 或 Bun，不在用户机器上编译。
本版本增加单次调用与工具详情、完整轮次折线图、紧凑页面布局，以及每 15 秒更新的首页。
自动更新保留筛选草稿、分页和滚动位置，后台和交互时暂停。

已安装用户升级：

```bash
tokenflow stop
brew update
brew upgrade wenjun-xu/tap/tokenflow
tokenflow --version
tokenflow start
```

升级或卸载前请先执行 `tokenflow stop`。需要 macOS 14+ 及可验证的 sandbox-exec 文件写入隔离。
Apple Silicon 和 Rosetta 下的 x64 程序已以合成数据验收；原生 Intel Mac 及其他 macOS 版本仍待验收。
真实会话、数据库和日志不上传。GitHub 下载仍受内网和代理策略影响；本项目未提供内网镜像。

源码、完整说明与发布包：[wenjun-xu/TokenFlow](https://github.com/wenjun-xu/TokenFlow)。
