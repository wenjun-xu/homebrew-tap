# TokenFlow Homebrew Tap

GitHub Copilot CLI 本地只读 Token 用量 Dashboard 的安装源。

```bash
brew install wenjun-xu/tap/tokenflow
tokenflow start
tokenflow stop
```

v0.2.0 预发布改用 TS + Bun 独立程序：按 Mac 架构下载一个预编译包，
无需安装 Python、Node.js 或 Bun，不在本机编译。升级或卸载前先执行 `tokenflow stop`。

需要 macOS 14+ 及可验证的 sandbox-exec 文件写入隔离。Apple Silicon 和 Rosetta 下的
x64 程序已在本机合成数据验收；原生 Intel Mac 及其他 macOS 版本仍待验收。
GitHub 下载仍受内网和代理策略影响；本项目未提供内网镜像。

源码、完整说明与发布包：[wenjun-xu/TokenFlow](https://github.com/wenjun-xu/TokenFlow)。
