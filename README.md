# Constella for macOS

Constella 是面向学生的本机信息整理工具，汇集已连接来源中的信息、作业和课程安排，并提供搜索与 Agent 辅助整理。

此仓库仅用于安装包、版本说明和更新元数据。它不包含个人数据库、账号、聊天、Cookie、凭据或开发交接记录，也不代表项目源码已按开源许可发布。

## 下载

- [Constella 0.3.2 Preview · Apple Silicon](https://github.com/gewenyuan123/constella-releases/releases/download/v0.3.2/Constella-0.3.2-AppleSilicon-macOS27.zip)
- [所有版本与校验和](https://github.com/gewenyuan123/constella-releases/releases)

当前支持 Apple 芯片，要求 macOS 27 或更新系统。这是预览测试版，未完成所有来源的跨设备验收。

## 安装与升级

1. 下载并解压ZIP，把 Constella.app 拖到“应用程序”。
2. 升级前按 Cmd+Q 完全退出旧版，再由 Finder 替换 App。
3. 数据保存在每台 Mac 的 `~/Library/Application Support/Constella/`，替换App不会重建数据库。请勿删除该目录。
4. 首次使用在“连接”完成目标电脑上的正常登录。已登录的其它浏览器或客户端不一定与Constella共享会话。

当前为 ad-hoc 签名，未做 Developer ID 签名或公证。macOS可能要求在“隐私与安全性”中允许打开；不要关闭系统保护。

## 本地 AI 与 Harness

Qwen3.5 9B 权重不在安装包中。“设置 → Agent”提供配套模型下载链接及本机导入，约5.6GB，导入时建议预留12GB空间。模型按需启动，无需日常终端命令。当前图片附件仅提取文字，不能当成完整视觉理解。

DeepSeek Harness 需在该Mac单独安装并完成账号或官方API配置。凭据由其官方运行时处理，Constella不要求把API Key粘贴到聊天中。

## 更新

0.3.2起可在应用菜单或“设置 → 关于与更新”检查新版本。应用运行时默认每天最多自动检查一次，可关闭。检查仅请求本仓库的公开版本JSON；下载及替换安装需用户确认，不会静默安装或修改个人数据。旧版本需要先手动安装一次0.3.2。

## 当前边界

微信自动取钥、ClassIn新机初始化等仍未完成，不应将预览包视为全部来源已接通。Qwen权重导入、来源登录与采集需在目标设备验证；没有MacBook真实账号验收的完成承诺。仅支持每台Mac独立保存数据，尚无双机数据库同步。

第三方许可在App菜单“第三方许可…”中提供。请勿在公开仓库上传日志、聊天、Cookie、数据库或学校账号截图。数据处理范围见 [PRIVACY.md](PRIVACY.md)。
