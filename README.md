# 📚 英语学习小助手

面向中文使用者的英语学习 Skill，由 Yuki 整理。提供英美音标、中文释义、双语例句、近反义表达、难词拼读提示和疑似拼写纠正。

## 选择使用方式

| 使用环境 | 使用方法 |
| --- | --- |
| 支持导入 SKILL.md 的 AI 工具 | 下载本仓库，按工具的技能导入说明导入 SKILL.md 或包含它的文件夹 |
| 豆包、DeepSeek 等普通聊天界面 | 打开 [PROMPT.md](PROMPT.md)，复制全文到新对话，再发送英语内容 |
| DeepSeek Harness | 在项目的 .dsh/skills/english-study/ 目录中放入 SKILL.md，按所用版本说明加载技能 |

GitHub 是分享和下载入口，不会让所有 AI 自动安装本技能。是否支持 ZIP、文件夹或链接导入，取决于具体产品和版本。未在豆包或 DeepSeek 普通聊天客户端验证原生安装能力；复制提示词也不等于永久安装。模型不同，输出效果可能不同。

## 快速体验

- 单词：meticulous
- 列表：resilient, reluctant, generous
- 句子：Her meticulous preparation made the transition seamless.
- 疑似误拼：meticulus

单词模式：每词提供中文释义、3 个双语例句、3 个类似表达及适用的反义表达。没有直接反义词时明确说明，不硬凑。
句子模式：保持原句，仅为较难词添加拼读提示和英美 IPA。“雅思 6.5 以上”是难度近似判断，不是官方逐词分级。

## 文件

- SKILL.md：标准技能入口，包含 name、description 和完整规则。
- PROMPT.md：无须安装、可直接粘贴的完整规则。
- README.md：使用说明。

无需 API 密钥，没有脚本和外部服务依赖。模型生成的音标和解释可能有误，遇到不确定读音应核对词典。

## 分享到 GitHub

新建名为 english-study 的 Public 仓库，将本文件夹中的 3 个文件上传到仓库根目录。请解压后上传，避免只上传 ZIP 而无法直接阅读规则。把仓库链接分享给朋友即可。

## 兼容性参考

- [豆包开放平台 Skill 接入指南](https://open.doubao.com/document/doubao-developer-guide/skill-integration-guide)：开发者接入流程，不等于普通聊天客户端的安装承诺。
- [DeepSeek Harness 官方技能文档](https://github.com/deepseek-ai/deepseek-harness/blob/master/docs/subsystems/skills.md)：文件夹技能与发现目录说明。

整理日期：2026-11-06。尚未进行各目标客户端的实际导入测试。
