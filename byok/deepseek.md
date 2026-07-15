# DeepSeek V4 Pro BYOK 接入教程

在 Cursor 中配置自己的 DeepSeek API，降低使用成本。

## 步骤

1. 注册 DeepSeek 账号并获取 API Key
2. 在 Cursor 设置中添加自定义模型
3. 配置如下：

```json
{
  "cursor.byok.endpoint": "https://api.deepseek.com",
  "cursor.byok.model": "deepseek-v4-pro", 
  "cursor.byok.apiKey": "your-deepseek-key"
}
```

> 💡 推荐使用[此链接注册 Cursor](https://cursor.com/referral?code=8JPEAJD2ITJV)
