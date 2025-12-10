# Test Cloud Agents

该仓库用于验证 Cursor Cloud Agent 的协作流程。

在 Cursor 客户端使用 Cloud Agent 时，Git remote 必须使用原始链接，如果因为 SSH 别名把远程改成自定义域名，就会连接不上。网页端 Cloud Agent 直接访问 GitHub 账号数据，因此不存在这个问题。

## 已知限制

- **无法将 Cursor 配置为默认 Reviewer**：经过测试，目前无法通过 CODEOWNERS 或其他方式将 Cursor 配置成 PR 的默认 review 人员。
