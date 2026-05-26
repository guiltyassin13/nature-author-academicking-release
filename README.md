# nature作者学术中 Release

这个公开仓库只用于发布 Zotero 插件安装包和自动更新文件。

当前推荐版本：3.5.21-recent-zero-backfill

## 文件说明

- 
ature-author-academic-center.xpi：当前最新插件安装包
- update.json：Zotero 自动更新配置
- update-beta.json：备用自动更新配置

## 安装与更新

首次安装时，在 Zotero 里进入：

工具 -> 插件 -> 齿轮 -> Install Plugin From File...

然后选择 
ature-author-academic-center.xpi。

已经安装 3.5.x 的用户，可以在 Zotero 插件管理器里点击：

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

## v3.5.21 更新内容

- 修复日期偏移问题，避免把昨天算错日期
- 支持最多补最近 30 天缺失的 0 分钟历史记录
- 保持稳定策略：不启用后台半小时同步，不做重型历史批量回填