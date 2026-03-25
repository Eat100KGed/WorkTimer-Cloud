# WorkTimer Cloud · 工时记录

> 单文件 HTML 工时打卡工具，支持 GitHub Gist 云端同步。

## 功能特性

- 上下班打卡，自动计算当日工时
- 支持夏季 / 冬季不同标准工时
- 历史记录查询 + 月度日历视图
- 拍摄 / 剪辑项目管理
- **云端同步**：通过 GitHub Gist API 跨设备同步数据

## 云端同步使用方式

1. 前往 [GitHub Settings → Tokens](https://github.com/settings/tokens/new?scopes=gist&description=WorkTimer) 生成一个勾选 `gist` 权限的 Personal Access Token
2. 在页面底部「☁ 云端同步」面板粘贴 Token
3. Gist ID 留空自动创建，或粘贴已有 Gist ID 绑定
4. 点击「🔗 连接云端」完成配置
5. 后续可手动上传 / 下载，或点击「🔄 自动同步」进行合并同步

## 文件说明

| 文件 | 说明 |
|------|------|
| `WorkTimer-Cloud.html` | 完整的单文件应用，直接用浏览器打开即可使用 |

## 数据安全

- Token 仅保存在本地 `localStorage`，不会上传到任何第三方
- 数据保存在你自己的 GitHub 账号私有 Gist 中
