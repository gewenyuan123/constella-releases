# 数据与更新检查

- 每台设备的数据库、会话与日志位于该设备的 Application Support 中，不随公开安装包分发。
- 更新检查只读取 `raw.githubusercontent.com/gewenyuan123/constella-releases/main/releases/preview.json`。请求包含普通网络连接信息及Constella版本标识，不附加账号、Cookie、API Key、聊天或数据库内容。
- 当前更新检查不自动下载或运行安装程序。下载来自本仓库GitHub Releases，公开版本文件包含大小及SHA-256校验值。
- 本地Qwen推理留在本机。云端Harness会处理用户输入及获准的受限结构摘要/课表；不代表所有内容都留在本机，也不代表所有Agent都可获得私人原文。附件发送仍受应用内确认约束。
- 来源连接与采集按已实现能力执行，只读来源；不发送消息、提交作业、点赞、关注或删除来源记录。同步会更新Constella的本地缓存。
- 公开发行仓库不接收私人诊断资料。需要反馈时请仅描述版本、错误类别及操作步骤，并先遮盖私人信息。
