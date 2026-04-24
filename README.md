# Awesome Claude Code Skills

> Claude Code 最实用的 Skills / Agents / Plugins 精选合集，按场景分类，带安装命令，复制即用。
>
> 50+ 精选 | 按场景分类 | 带推荐等级 | 持续更新

---

## 这个仓库是什么

Claude Code 的 Skill 生态爆发了，但好东西散落在 GitHub、skills.sh、lobehub 各处，找起来费劲。

这个仓库帮你**筛过一遍**：

- 只收有实际价值的 skill，不收凑数的
- 按使用场景分类，不按作者堆
- 标注推荐等级：`必装` > `强推` > `好用` > `可选`
- 每个都带一键安装命令

**怎么安装 Skill：**

```bash
# 通用安装方式
npx skills add <作者>/<仓库>@<skill名>

# 例子
npx skills add vercel-labs/agent-skills@web-design-guidelines

# 查看已安装
npx skills list
```

---

## 目录

- [必装 Top 10](#必装-top-10)
- [设计 / UI](#设计--ui)
- [前端开发](#前端开发)
- [动效 / 视频](#动效--视频)
- [营销 / SEO](#营销--seo)
- [代码质量](#代码质量)
- [工作流 / 方法论](#工作流--方法论)
- [无障碍](#无障碍)
- [合集 / 导航站](#合集--导航站)
- [怎么选 Skill](#怎么选-skill)

---

## 必装 Top 10

不管你做什么方向，这 10 个装了不亏。

| # | Skill | 作者 | 一句话 | 安装 |
|---|-------|------|--------|------|
| 1 | [**Frontend Design**](https://github.com/anthropics/claude-code/tree/main/plugins/frontend-design) | Anthropic | 官方出品，让 UI 不像 AI 生成的 | `npx skills add anthropics/skills@frontend-design` |
| 2 | [**Context7**](https://skills.sh/context7/skills/context7) | intellectronica | 上下文窗口内实时拉 API 文档，不用再贴链接 | `npx skills add intellectronica/agent-skills@context7` |
| 3 | [**Web Design Guidelines**](https://skills.sh/vercel-labs/agent-skills/web-design-guidelines) | Vercel Labs | 对照 100+ 最佳实践审查你的 UI | `npx skills add vercel-labs/agent-skills@web-design-guidelines` |
| 4 | [**UI-UX-Pro-Max**](https://skills.sh/nextlevelbuilder/ui-ux-pro-max-skill/ui-ux-pro-max) | Next Level Builder | 视觉层级 x 色彩心理学 x 交互模式 | `npx skills add nextlevelbuilder/ui-ux-pro-max-skill@ui-ux-pro-max` |
| 5 | [**Emil Kowalski's Skill**](https://skills.sh/emilkowalski/skill) | Emil Kowalski | 设计 + 动效 + 代码 + 性能，全栈审美 | `npx skills add emilkowalski/skill` |
| 6 | [**Superpowers**](https://github.com/obra/superpowers) | obra | TDD / 并行 Agent / 代码审查 / Git 工作流 | `npx skills add obra/superpowers` |
| 7 | [**shadcn/ui**](https://github.com/shadcn/ui) | shadcn | 官方组件管理 + 表单 + 预览 | `npx skills add shadcn/ui@shadcn` |
| 8 | [**Remotion**](https://github.com/remotion-dev/skills) | Remotion | React 驱动的视频生成，30+ 规则 | `npx skills add remotion-dev/skills@remotion-best-practices` |
| 9 | [**Tailwind CSS**](https://skills.sh/hairyf/skills/tailwindcss) | hairyf | Tailwind v4 完整支持 | `npx skills add hairyf/skills@tailwindcss` |
| 10 | [**Find Skills**](https://skills.sh/vercel-labs/skills/find-skills) | Vercel Labs | 让 Agent 自己发现和安装新 Skill | `npx skills add vercel-labs/skills@find-skills` |

---

## 设计 / UI

让 AI 出的设计不再有「模板感」。

| Skill | 作者 | 推荐 | 一句话 | 安装 |
|-------|------|------|--------|------|
| [Frontend Design](https://github.com/anthropics/claude-code/tree/main/plugins/frontend-design) | Anthropic | 必装 | 官方设计系统哲学，大胆配色 + 有辨识度的字体 + 有意图的动效 | `npx skills add anthropics/skills@frontend-design` |
| [UI-UX-Pro-Max](https://skills.sh/nextlevelbuilder/ui-ux-pro-max-skill/ui-ux-pro-max) | Next Level Builder | 必装 | 视觉层级 x 色彩心理学 x 交互模式，出图质量显著提升 | `npx skills add nextlevelbuilder/ui-ux-pro-max-skill@ui-ux-pro-max` |
| [Emil Kowalski's Skill](https://skills.sh/emilkowalski/skill) | Emil Kowalski | 必装 | 来自 Sonner / Vaul 作者的设计 + 动效 + 代码实践 | `npx skills add emilkowalski/skill` |
| [Web Design Guidelines](https://skills.sh/vercel-labs/agent-skills/web-design-guidelines) | Vercel Labs | 必装 | 对照 100+ 最佳实践审查 UI，找出细节问题 | `npx skills add vercel-labs/agent-skills@web-design-guidelines` |
| [Make Interfaces Feel Better](https://skills.sh/jakubkrehel/make-interfaces-feel-better) | Jakub Krehel | 强推 | 对齐 / 阴影 / 间距 / 圆角的细节打磨 | `npx skills add jakubkrehel/make-interfaces-feel-better` |
| [Figma Designer](https://github.com/anthropics/claude-code) | Anthropic | 好用 | Claude 进入 Figma 高级设计师思维模式 | `npx claude skills add figma` |
| [Theme Factory](https://github.com/anthropics/claude-code) | Anthropic | 好用 | 10 套配色 + 字体主题，套用到任意 artifact | `npx claude skills add theme-factory` |
| [Brand Guidelines](https://github.com/anthropics/claude-code) | Anthropic | 好用 | Anthropic 官方品牌规范（色 / 字 / 视觉） | `npx claude skills add brand-guidelines` |
| [Canvas Design](https://github.com/anthropics/claude-code) | Anthropic | 好用 | 生成海报 / 插画，输出 PNG / PDF | `npx claude skills add canvas-design` |
| [SuperKit UI/UX](https://skillsmp.com/skills/pixel-process-ug-superkit-agents-templates-skills-ui-ux-pro-max-skill-md) | Pixel Process UG | 好用 | 50+ 风格 / 97 色板 / 57 字体配对 | `npx skills add Pixel-Process-UG/superkit-agents` |
| [TypeUI Design Skills](https://www.typeui.sh/design-skills) | TypeUI | 可选 | 手工 skill 文件，复现特定视觉风格 | `npx typeui.sh pull [name]` |
| [Design.md Generator](https://github.com/google-labs-code/stitch-skills) | Google Labs | 好用 | 分析项目 → 自动生成 DESIGN.md 设计规范 | `npx skills add google-labs-code/stitch-skills@design-md` |
| [Brainstorming](https://github.com/obra/superpowers) | obra | 强推 | 验证设计方案后才允许写代码，防止 AI 乱写 | `npx skills add obra/superpowers@brainstorming` |

---

## 前端开发

组件库、框架支持、开发效率。

| Skill | 作者 | 推荐 | 一句话 | 安装 |
|-------|------|------|--------|------|
| [shadcn/ui](https://github.com/shadcn/ui) | shadcn | 必装 | 官方组件管理 + 表单 + 预览 | `npx skills add shadcn/ui@shadcn` |
| [Context7](https://skills.sh/context7/skills/context7) | intellectronica | 必装 | 上下文窗口内实时拉准确 API 文档 | `npx skills add intellectronica/agent-skills@context7` |
| [Tailwind CSS](https://skills.sh/hairyf/skills/tailwindcss) | hairyf | 必装 | Tailwind CSS v4 完整支持 | `npx skills add hairyf/skills@tailwindcss` |
| [Tailwind Design System](https://skills.sh/wshobson/agents/tailwind-design-system) | WS Hobson | 强推 | CSS-first 设计系统 + OKLCH 色彩 | `npx skills add wshobson/agents@tailwind-design-system` |
| [Find Skills](https://skills.sh/vercel-labs/skills/find-skills) | Vercel Labs | 强推 | 让 Agent 自己发现和安装新 Skill | `npx skills add vercel-labs/skills@find-skills` |
| [React Best Practices](https://github.com/vercel-labs/agent-skills) | Vercel Labs | 强推 | 45 条 React/Next.js 性能优化规则 | `npx skills add vercel-labs/agent-skills@react-best-practices` |
| [Ralph Loop](https://github.com/frankbria/ralph-claude-code) | Frank Bria | 好用 | 多小时自主编码 Agent，适合长任务 | `npx skills add frankbria/ralph-claude-code` |

---

## 动效 / 视频

让页面动起来，或者直接生成视频。

| Skill | 作者 | 推荐 | 一句话 | 安装 |
|-------|------|------|--------|------|
| [Remotion](https://github.com/remotion-dev/skills) | Remotion | 必装 | React 驱动的视频生成，30+ 规则，3D / 图表 / 参数化内容 | `npx skills add remotion-dev/skills@remotion-best-practices` |
| [Motion (Framer Motion)](https://skills.sh/jezweb/claude-skills/motion) | Jezweb | 强推 | React 动画：手势 / 滚动 / 弹性 / 布局 | `npx skills add jezweb/claude-skills@motion` |
| [Animation Systems](https://lobehub.com/skills/guilhermemarketing-gui-marketing-skills-animation-systems) | Guilherme | 强推 | Stripe / Linear / Apple 级别网页动效 | `npx skills add guilhermemarketing/gui-marketing-skills@animation-systems` |
| [AI Video Generation](https://github.com/inferen-sh/skills) | inference.sh | 好用 | 40+ AI 视频模型（Veo / Wan / Grok） | `npx skills add inferen-sh/skills@ai-video-generation` |
| [Nano Banana 2](https://github.com/inferen-sh/skills) | inference.sh | 好用 | Gemini 文字转图 / 图片编辑，4K 输出 | `npx skills add inferen-sh/skills@nano-banana-2` |

---

## 营销 / SEO

从 SEO 审查到文案撰写到定价策略。

| Skill | 作者 | 推荐 | 一句话 | 安装 |
|-------|------|------|--------|------|
| [SEO Audit](https://github.com/coreyhaines31/marketingskills) | Corey Haines | 强推 | 五优先级 SEO 全面审查框架 | `npx skills add coreyhaines31/marketingskills@seo-audit` |
| [Copywriting](https://github.com/coreyhaines31/marketingskills) | Corey Haines | 强推 | 主页 / 落地页 / 定价页转化文案 | `npx skills add coreyhaines31/marketingskills@copywriting` |
| [Product Marketing Context](https://github.com/coreyhaines31/marketingskills) | Corey Haines | 好用 | 产品定位 / 人群 / 竞品 / 品牌声音 | `npx skills add coreyhaines31/marketingskills@product-marketing-context` |
| [Pricing Strategy](https://github.com/coreyhaines31/marketingskills) | Corey Haines | 好用 | SaaS 定价设计与竞品对比框架 | `npx skills add coreyhaines31/marketingskills@pricing-strategy` |
| [Twitter Automation](https://github.com/inferen-sh/skills) | inference.sh | 可选 | 推文 / 点赞 / 转推 / DM，9 个命令 | `npx skills add inferen-sh/skills@twitter-automation` |

---

## 代码质量

代码审查、测试、调试。

| Skill | 作者 | 推荐 | 一句话 | 安装 |
|-------|------|------|--------|------|
| [Superpowers](https://github.com/obra/superpowers) | obra | 必装 | TDD / 并行 Agent / 代码审查 / Git 工作流，一套全有 | `npx skills add obra/superpowers` |
| [Code Review](https://skills.sh/supercent-io/skills-template/code-review) | Supercent | 强推 | 自动代码审查（注释 / 测试 / 类型 / 质量） | `npx skills add supercent-io/skills-template@code-review` |

---

## 工作流 / 方法论

改变 Claude Code 的工作方式。

| Skill | 作者 | 推荐 | 一句话 | 安装 |
|-------|------|------|--------|------|
| [Superpowers - TDD](https://github.com/obra/superpowers) | obra | 必装 | 强制测试驱动开发：写测试 → 实现 → 重构 | `npx skills add obra/superpowers@test-driven-development` |
| [Superpowers - Parallel Agents](https://github.com/obra/superpowers) | obra | 强推 | 多个子 Agent 并行执行独立任务 | `npx skills add obra/superpowers@dispatching-parallel-agents` |
| [Superpowers - Plan Mode](https://github.com/obra/superpowers) | obra | 强推 | 先规划再执行，防止 AI 乱改代码 | `npx skills add obra/superpowers@writing-plans` |
| [Superpowers - Git Worktrees](https://github.com/obra/superpowers) | obra | 好用 | 隔离工作区，不影响主分支 | `npx skills add obra/superpowers@using-git-worktrees` |

---

## 无障碍

| Skill | 作者 | 推荐 | 一句话 | 安装 |
|-------|------|------|--------|------|
| [Web Accessibility](https://skills.sh/supercent-io/skills-template/web-accessibility) | Supercent | 好用 | 对比度 / 键盘导航 / 语义结构检查 | `npx skills add supercent-io/skills-template@web-accessibility` |

---

## 合集 / 导航站

不知道该装什么？先看这些合集。

| 资源 | 说明 | 链接 |
|------|------|------|
| **Awesome Agent Skills** | VoltAgent 维护，549+ skills，分类最全 | [GitHub](https://github.com/VoltAgent/awesome-agent-skills) |
| **Awesome Claude Code Toolkit** | Rohit Ghumare 维护，135 agents + 35 skills | [GitHub](https://github.com/rohitg00/awesome-claude-code-toolkit) |
| **Awesome Claude Code** | hesreallyhim 维护，skills + hooks + 命令 | [GitHub](https://github.com/hesreallyhim/awesome-claude-code) |
| **skills.sh** | Vercel 出的 Skill 包管理器和浏览站 | [skills.sh](https://skills.sh) |
| **LobeHub Skills** | 232+ skills 的可视化浏览 | [lobehub.com/skills](https://lobehub.com/skills) |
| **hotkeys.design** | 设计师向的 Skill 导航站 | [hotkeys.design](https://hotkeys.design) |
| **awesomeskills.dev** | 跨平台 Agent Skill 目录 | [awesomeskills.dev](https://awesomeskills.dev) |
| **Skills宝 (skilery.com)** | 国内 AI 技能市场，一站式搜索安装 Claude Code/OpenCode 等多平台 | [skilery.com](https://skilery.com) |

---

## 怎么选 Skill

装太多 Skill 反而会让 Claude Code 变慢或行为混乱。建议：

**第一步：装 3 个基础 Skill**

```bash
# 设计质量
npx skills add anthropics/skills@frontend-design

# 代码质量
npx skills add obra/superpowers

# 文档查询
npx skills add intellectronica/agent-skills@context7
```

**第二步：按你的方向加 1-2 个**

| 你的方向 | 加这个 |
|---------|--------|
| 做 UI / 前端 | UI-UX-Pro-Max + Emil Kowalski |
| 做视频 | Remotion |
| 做营销页 | SEO Audit + Copywriting |
| 做组件库 | shadcn/ui + Tailwind CSS |

**第三步：用 Find Skills 让 Agent 自己找**

```bash
npx skills add vercel-labs/skills@find-skills
```

装完之后 Claude 遇到新需求会自动搜索和安装合适的 Skill。

---

## 关于作者

**Ian (伊恩)** — 产品设计师 / 一人公司实践者 / AI Builder

用 AI 团队打造一人公司。

- X/Twitter: [@ianneo_ai](https://x.com/ianneo_ai)
- 网站: [ianneo.xyz](https://ianneo.xyz)
- 微信: 17855813746
- 邮箱: hello.neoc@gmail.com

> **🚀 正在开启：内容创作丨AI 工作流围观营，欢迎来玩！** 加微信了解详情。

---

## 其他资源

- [obsidian-ai-second-brain](https://github.com/helloianneo/obsidian-ai-second-brain) — Obsidian + Claude AI 个人知识库搭建指南
- [claude-code-handbook](https://github.com/helloianneo/claude-code-handbook) — Claude Code 高阶使用手册
- [ai-skill](https://github.com/anomalyco/ai-skill) — AI 技能发现与管理系统

---

## 贡献

发现好用的 Skill 但这里没收？欢迎提 [Issue](https://github.com/helloianneo/awesome-claude-code-skills/issues) 或 PR。

收录标准：
- 有实际使用价值（不是 demo）
- 能正常安装
- 有人在用（GitHub stars > 10 或明确的用户反馈）

觉得有用？Star 一下方便后续更新时收到通知。

---

## License

[MIT](LICENSE)
