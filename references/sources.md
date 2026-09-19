# 来源、改写与边界

本文件记录随包内容的来源方向，方便维护者核对；它不是用户每次都要阅读的课程页。

## 文内来源编号

FAQ 和课程页中的编号是维护用的短标记，不代表外部统计或权威等级。回答时只在确实使用了对应依据时引用；“教学设计”“产品假设”等没有编号的判断，不要包装成外部事实。

| 编号 | 对应依据 | 用途与边界 |
|---|---|---|
| L01 | 本地 `AI小白入门四步法`、`references/learning-map.md` | 从真实任务起步、先做后学；属于胖叔课程整理，不是通用学习排名 |
| L02 | 本地 `提示词三原则：简洁、框架、迭代`、`references/prompt-and-context.md` | 需求表达、提示词和反馈迭代 |
| L03 | 本地 `从工具到落地五步法`、WorkBuddy 课程与案例、`references/lessons/` | 从场景到输入输出、最小功能和验收 |
| S01 | Replit Effective prompting | 目标、上下文、分步构建和迭代的公开通用原则 |
| S02 | Replit Introduction to AI | 模型、Agent、人的验收责任等公开通用解释 |
| S03 | Replit Context management | 文件、截图、上下文保留和交接的公开通用原则 |
| S04 | Lovable FAQ | 小步构建、调查错误、版本恢复和密钥边界的产品文档示例 |
| S05 | 本 Skill 的附件读取验收设计 | 用原文页/段落核对“确实读到”，不是第三方产品承诺 |
| S06 | 本 Skill 的分享验收设计 | 另一设备或独立环境验证，不把本机可用说成已发布 |
| S07 | 本 Skill 的应用测试设计 | 正常、空白、错误输入、刷新和重复操作的检查建议 |
| S08 | Agent Skills Overview | Skill 目录、渐进式加载和可复用能力的公开说明 |
| S09 | Agent Skills best practices | Skill 范围、按需加载和第三方安全审查的公开原则 |
| U01 | 用户当前提供的文件、截图、报错、界面和实际结果 | 任务事实证据；必须以当前材料核对，不能由文件名或经验替代 |
| C01 | 当前产物的实际打开、运行和功能复测 | 只有完成相应检查，才能说已验证 |
| C02 | 关键事实回到原文或独立输入核对 | 不能用模型自查替代外部证据 |

## 胖叔本地课程与知识库

- 《Ai时代必修课.pptx》：AI 基础、提示词、Agent、Skill、MCP、API、RAG、知识库和应用搭建主线。前轮完成图片型幻灯片 OCR 与抽查；本 Skill 使用提炼后的教学表达，不在包内捆绑原始 PPT。
- `AI小白入门四步法`：从真实任务、模型/工具选择、Skill 复用到知识积累的路径。
- `提示词三原则：简洁、框架、迭代`：将需求组织为背景/任务/结果，再根据结果迭代。
- `从工具到落地五步法`：场景、重复动作、输入输出、最小功能、交付形式。
- WorkBuddy 课程与案例：输入材料、处理动作、可编辑产物、验收和安全边界。
- `Codex+Image2 PPT生产流程`：内容结构、视觉表达、可编辑交付与逐页验收。
- Codex 零基础课程：从工具可用、配置、规则、Skill、闭环演练到业务复用；具体平台步骤需按当前版本核验。

这些内容来自用户电脑的本地材料和已有综合页。读取路径不代表公开包拥有原始课件、截图或第三方教程的再分发权。随包练习和示范已经重新组织；虚构示例不能当成真实学员案例。

## 公开参考

- [Agent Skills Overview](https://agentskills.io/home)：Skill 目录、渐进式加载与可复用能力的公开说明。查阅日期：2026-09-19。
- [Replit Effective prompting](https://docs.replit.com/learn/effective-prompting)：明确目标、分步构建、提供上下文、调试和迭代。查阅日期：2026-09-19。
- [Replit Introduction to AI](https://docs.replit.com/learn/foundations/introduction-to-ai)：模型、上下文、Agent 与人的验收责任。查阅日期：2026-09-19。
- [Replit Context management](https://docs.replit.com/learn/foundations/context-management)：相关上下文、文件/截图/日志和新对话交接。查阅日期：2026-09-19。
- [Lovable FAQ](https://docs.lovable.dev/introduction/faq)：小步开始、错误调查、版本恢复、密钥与发布的产品文档示例。查阅日期：2026-09-19；只采纳稳定原则，不复制其套餐或按钮承诺。
- [Agent Skills best practices](https://docs.replit.com/learn/agent-skills)：Skill 范围、按需加载和第三方安全审查。查阅日期：2026-09-19。
- [Ask HN: Prompt engineering for beginner-friendly code](https://news.ycombinator.com/item?id=41983440)：一个社区提问样本，观察“扩展代码后难理解和越改越坏”的问题，不代表统计频率或统一答案。查阅日期：2026-09-19。

公开文档的版本、产品能力、价格和平台入口会变化。工具教学需在实际使用时核验，不把查阅日的页面当永久事实。公开参考只作为通用原则和边界依据，不自动允许重新分发其文字。

## xyskill

[xyaz1313/xyskill](https://github.com/xyaz1313/xyskill) 仅作为统一入口、问题分流、连续学习和反馈检查站的产品设计参考。本包没有复制其原子知识库、脚本、云端搜索或业务内容。若未来加入其受 CC BY-NC 4.0 覆盖的具体内容，需保留署名、许可链接、修改说明并重新检查商业边界。

## 事实边界

- “胖叔经验”只指用户明确提供或本地课程中明确归属于胖叔的方法，不把模型补充冒充作者经历。
- 工具卡的“安装已验证”和“代表性任务已验证”必须由实际记录支持；搜索到名称或阅读 README 不算验证。
- 模型、费用、按钮、兼容平台和效果数字是易变事实；无法核验时写明未知或待核验。
- 用户的文件、截图和学习记录默认只服务当前任务；未经同意不转成公开案例或上传到外部服务。
