## 🚢 Host-ship 自动续期（GitHub Actions，纯 HTTP 单账号版）

### 🔐 Secrets 配置说明

| Secret 名称   | 是否必填 | 说明 |
|---------------|----------|------|
| API_KEY       | ✅ 必填* | 面板 Client API key（`ptlc_` 开头）。*无则走备链 |
| SERVER_ID     | ✅ 必填  | 服务器 UUID（面板服务器页面 URL 里那串 `xxxxxxxx-xxxx-...`） |
| COOKIE        | ❌ 可选  | 备链用，格式 `remember_web_...=xxx; jexactyl_session=yyy`（F12 → Application → Cookies → panel.host-ship.com） |
| EMAIL         | ❌ 可选  | 通知备注名 |
| TG_BOT_TOKEN  | ❌ 可选  | Telegram Bot Token |
| TG_CHAT_ID    | ❌ 可选  | Telegram Chat ID |


## ⚠️ 免责声明

仅供学习了解；遵守相关法律法规，作者不对不当行为负责。
