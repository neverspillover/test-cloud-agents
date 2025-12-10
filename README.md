# Test Cloud Agents

该仓库用于验证 Cursor Cloud Agent 的协作流程。

在 Cursor 客户端使用 Cloud Agent 时，本地 Git remote 应保持原始连接（如默认的 `origin` 指向 GitHub）。若因 SSH 别名将远程改成自定义域名，Cloud Agent 会识别失败并无法连接；网页端 Cloud Agent 没有这个限制。
