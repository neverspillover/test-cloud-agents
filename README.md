# Test Cloud Agents

该仓库用于验证 Cursor Cloud Agent 的协作流程。

在 Cursor 客户端使用 Cloud Agent 时，Git remote 必须保持原始连接（默认的 `origin` 指向 GitHub）；如果因为 SSH 别名把远程改成自定义域名，就会连接不上。网页端 Cloud Agent 不会遇到这个问题。
