# nature作者学术中 Release

这个公开仓库只用于发布 Zotero 插件安装包和自动更新文件。

当前推荐版本：3.6.1

## 文件说明

- nature-author-academic-center.xpi：当前最新插件安装包
- update.json：Zotero 自动更新配置
- update-beta.json：备用自动更新配置

## 安装与更新

首次安装时，在 Zotero 里进入：

工具 -> 插件 -> 齿轮 -> Install Plugin From File...

然后选择 nature-author-academic-center.xpi。

已经安装旧版本的用户，可以在 Zotero 插件管理器里点击：

齿轮 -> Check for Updates

## 隐私说明

这个公开仓库不保存：

- Supabase URL
- Supabase anon / publishable key
- 用户阅读时间数据
- 用户头像
- 排行榜数据
- 点赞、点踩、留言数据

用户数据保存在你配置的 Supabase 项目里，不在 GitHub 里。

## v3.6.1 更新内容

- 同一个安装包同时兼容 Zotero 9 和 Zotero 10.0.x
- 功能、同步规则、账号关联和数据库结构与 v3.6.0 保持一致

## v3.6.0 更新内容

- 新增“我的账号”，支持在新设备恢复同一身份
- 阅读时间改为账号总时间与多设备增量累加，避免设备之间互相覆盖
- 新增 Zotero 账号轻量关联，同一 Zotero 账号在多台设备上共享阅读快照，避免重复累计
- 优化同步反馈与排行榜刷新流程，区分“立即同步”和“刷新小组数据”
- 历史状态增加当天最多阅读文献
- 新增八月“学术气象台”月报，并保留六月、七月历史月报
- 月报入口升级为最新报告与历史月份组合菜单
- 优化过去七天历史卡片、长标题布局和互动刷新
