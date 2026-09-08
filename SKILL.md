# 一键 Codex 英文转中文界面

> 让 Codex++ 这类英文 AI 编程客户端的界面、菜单、错误提示、状态信息全部转为中文。

## 它能做什么

- 自动识别客户端的 UI 字符串文件（`.json` / `.js` / `.po` / `.strings`）
- 用 AI 批量翻译为中文，保留占位符与技术术语
- 生成可一键应用的 patch 文件，原文+译文对照
- 支持回滚（备份原文件，应用前自动创建 `.bak`）

## 一句话定位

给英文恐惧症的程序员用：装上它，再不用查字典。

## 使用流程

1. 指定 Codex++ 的安装目录（一般是 `C:\Users\<你>\AppData\Local\Programs\codex`）
2. 选「扫描 → 生成 patch → 应用」三步式
3. 重启客户端，UI 全变中文

## 适用/不适用

- ✅ 适用：客户端 UI 文本、菜单项、按钮文案、提示语
- ❌ 不适用：代码注释、变量名、API 响应（这些保持英文更稳定）

## 版本

- v1.0.1

## 上游仓库

源码、字典、patch 模板：https://github.com/Hk3845030/codex-portable-zh-cn

详细使用说明见：https://skillhub.cn/skills/codex-portable-zh-cn

## License

MIT
