# Agnes 2.0 Flash BYOK 接入教程（免费）

在 Cursor 中接入免费的 Agnes 2.0 Flash 模型。

## 步骤

1. 注册 Agnes AI 账号获取 API Key
2. 在 Cursor 设置中添加自定义模型
3. 配置如下：

```json
{
  "cursor.byok.endpoint": "https://apihub.agnes-ai.com/v1",
  "cursor.byok.model": "agnes-2.0-flash",
  "cursor.byok.apiKey": "your-agnes-key"
}
```

> 完全免费！无需任何费用。
