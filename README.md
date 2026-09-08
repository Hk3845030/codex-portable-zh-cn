# 一键 Codex 英文转中文界面

[![version](https://img.shields.io/badge/version-1.0.1-2563eb)](https://skillhub.cn/skills/codex-portable-zh-cn)
[![downloads](https://img.shields.io/badge/downloads-50%2B-2fbf8f)](https://skillhub.cn/skills/codex-portable-zh-cn)
[![platform](https://img.shields.io/badge/platform-SkillHub-5b8ff9)](https://skillhub.cn/skills/codex-portable-zh-cn)
[![license](https://img.shields.io/badge/license-MIT-22c55e)](./LICENSE)

> 让 Codex++ 这类英文 AI 编程客户端的界面、菜单、错误提示、状态信息全部变成中文。

> [!IMPORTANT]
> **本仓库是技能索引与说明页，代码与安装包不在 GitHub。**
> 完整可用的技能包请在 SkillHub 获取（一键安装，自动跟随版本更新）：
>
> 👉 **https://skillhub.cn/skills/codex-portable-zh-cn**

---

## 3 秒判断：这是不是你要的

| 如果你正遇到 | 这个技能替你做的事 |
|---|---|
| 客户端全英文，每次都要查字典 | 批量翻译 UI 字符串为中文 |
| 担心翻译把占位符搞坏 | 自动保留 `%s`、`{}` 等占位符与技术术语 |
| 怕改坏回不去 | 应用前自动备份 `.bak`，支持一键回滚 |
| 只想看中文，代码还是英文 | 只翻 UI 文本，不动代码逻辑 |

**一句话定位**：给英文恐惧症的程序员用 —— 装上它，再不用查字典。

---

## 核心能力

- **自动扫描** —— 识别客户端 UI 字符串文件（`.json` / `.js` / `.po` / `.strings`）
- **AI 批量翻译** —— 保留占位符与技术术语，不会把 `{{count}}` 翻坏
- **生成 patch** —— 原文 + 译文对照，可逐条审阅再应用
- **可回滚** —— 应用前自动创建 `.bak` 备份
- **三步式流程** —— 扫描 → 生成 patch → 应用

---

## 三步上手

1. 指定 Codex++ 的安装目录（一般是 `C:\Users\<你>\AppData\Local\Programs\codex`）
2. 走「扫描 → 生成 patch → 应用」三步
3. 重启客户端，UI 全变中文

---

## 适用 / 不适用

- ✅ **适用**：客户端 UI 文本、菜单项、按钮文案、提示语
- ❌ **不适用**：代码注释、变量名、API 响应（这些保持英文更稳定）

---

## 安装（唯一入口）

技能的运行脚本、字典与后续更新都托管在 SkillHub，那里是唯一的安装来源。

### 👉 [在 SkillHub 安装「一键 Codex 英文转中文界面」](https://skillhub.cn/skills/codex-portable-zh-cn)

安装后在工作台搜索 `codex-portable-zh-cn` 即可调用。

---

## 常见问题

**Q：为什么 GitHub 上找不到源码？**
A：本仓库只做索引与说明（见下方「关于这个仓库」）。可运行的技能包统一在 SkillHub 分发，避免你 clone 到一个跑不起来的旧快照。

**Q：会把我的代码注释也翻译掉吗？**
A：不会。只处理 UI 文本，代码注释、变量名、API 响应一律不动。

**Q：翻译错了能还原吗？**
A：能。应用前会自动生成 `.bak` 备份文件，随时回滚。

---

## 关于这个仓库

这个仓库只做两件事：

1. **门牌** —— 让你在 GitHub 或搜索引擎里能找到这个技能
2. **展示窗** —— 让你在看代码之前，就能判断它值不值得装

技能本体（脚本、字典、patch 模板与更新）全部在 SkillHub，保证你装到的永远是最新版。

- SkillHub 主页：https://skillhub.cn/skills/codex-portable-zh-cn
- 问题反馈：请在 SkillHub 技能页留言

## License

[MIT](./LICENSE)
