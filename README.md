# 终端神器速查表 · Terminal Superpowers

[![Stars](https://img.shields.io/github/stars/Ezra-Zhao/terminal-superpowers-cheatsheet?style=social)](https://github.com/Ezra-Zhao/terminal-superpowers-cheatsheet/stargazers) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE) ![Languages](https://img.shields.io/badge/languages-3-blue)

Support & more: [GitHub Sponsors](https://github.com/sponsors/Ezra-Zhao) · [Gumroad — templates & workbooks I use](https://ezraflow28.gumroad.com) · [Ko-fi](https://ko-fi.com/ezra777zhao)


> 🌍 [Español](README.es.md) · [Português](README.pt.md)

一份**一页纸**的 2026 年终端效率工具速查表：14 个真正值得装的工具，每个条目只讲四件事——**它是干什么的、一条安装命令、一条上手命令、适用场景标签**。不灌水，不凑数。

## 面向谁

运维工程师、后端开发者，以及每天活在终端里的你。如果你还在用裸 `cd`、`ls`、`cat`、`grep` 干活，这张表能让你每天省下半小时。

## 怎么用

1. 直接看 **[CHEATSHEET.md](CHEATSHEET.md)** ——速查表正文，中英双语开发者都无压力。
2. 先装"新手包"，一条命令搞定常用项（macOS / Homebrew）：
   ```bash
   brew install zoxide fzf fd ripgrep eza bat starship lazygit tldr btop tmux zellij
   ```
   Debian/Ubuntu 用户注意三处坑：`fd` 装完二进制叫 `fdfind`、`bat` 叫 `batcat`（可自己 alias 回来）；`eza` 不在默认源里，需加第三方源。别照着上面的名字直接 apt。
3. 每个工具先跑一遍"试一试"那条命令，五分钟就知道它值不值得留。

## 收录了什么

| 分类 | 工具 |
|---|---|
| 🆕 2026 新贵 | cmux（为 AI 编程智能体而生的终端）、yoinks（终端里下载各平台视频） |
| 🧭 导航与搜索 | zoxide（智能 cd）、fzf（模糊搜索）、fd（find 替代）、ripgrep（grep 替代） |
| 🖥️ 终端复用与提示符 | tmux（经典终端复用）、zellij（现代终端工作区）、starship（智能提示符） |
| 📄 文件查看 | eza（ls 替代）、bat（cat 替代） |
| 🛠️ 开发提效 | lazygit（git 可视化操作）、tldr（命令速查） |
| 📊 监控 | btop（资源监控） |

所有官网 / GitHub 链接都经过核实，安装命令均为真实可用。

## 为什么是这 14 个

- **2026 新贵**：cmux、yoinks 是今年在 GitHub 上冒头的新工具，解决的是 AI 编程时代的新问题。
- **常青神器**：其余 12 个是经年验证的经典，每一个都替代了一个难用的 Unix 老命令，且快得多、好看得多。

## 欢迎 PR

发现更好的工具、命令写错了、翻译不到位——欢迎提 Pull Request。新增条目请保持统一格式（功能 / 安装 / 上手 / 标签），**提交前请核实链接真实有效**。

## 📚 更多速查表

同一作者的其他速查表，同样有中/西/葡三语版本：

- [FFmpeg 命令速查表](https://github.com/Ezra-Zhao/ffmpeg-cheatsheet) — 28 条音视频处理命令
- [Git 实战速查表](https://github.com/Ezra-Zhao/git-cheatsheet) — 30 条日常+救命命令
- [Docker 命令速查表](https://github.com/Ezra-Zhao/docker-cheatsheet) — 28 条容器命令
- [curl 命令速查表](https://github.com/Ezra-Zhao/curl-cheatsheet) — 29 条 API 调试命令
- [正则表达式速查表](https://github.com/Ezra-Zhao/regex-cheatsheet) — 30 条实战正则模式
- [jq 命令速查表](https://github.com/Ezra-Zhao/jq-cheatsheet) — 30 条 JSON 处理 filter
- [Adobe 免费替代速查表](https://github.com/Ezra-Zhao/adobe-free-alternatives-cheatsheet) — 16 个 Adobe 免费替代品
- [退订省钱速查表](https://github.com/Ezra-Zhao/desubscribe-cheatsheet) — 10 组退订替代，年省约 $1,260

## License

MIT © 2026 Guangyi Zhao，详见 [LICENSE](LICENSE)。
