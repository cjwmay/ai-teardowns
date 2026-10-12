# AI Teardowns · AI 产品每日拆解

> 每天 10 分钟，拆一个真实 AI 产品的一个交互。
> 10 minutes a day, one real AI product interaction.

## The fixed framework · 固定三问

Every teardown answers the same three questions — the raw material of "AI judgment":

1. **Trust calibration 做得怎么样？** — How does the product express certainty/uncertainty? Numeric confidence? Draft-like visuals? Interaction cost?
2. **Graceful degradation 在哪？** — When the model is uncertain, offline, or fails: what does it degrade into? Shorter? Silent? Fallback? Does the core task break?
3. **人有没有 override 的机会？** — Can the human accept / dismiss / edit, at what granularity, at what cost, and when?

每个拆解都回答同一个三问 —— "AI 判断力"的原材料，直接服务作品集 AI Hub 面试 deep-dive。

## 结构 · Structure

- `index.html` — roadmap 首页：每天一张卡片
- `teardowns/day-N-<slug>/index.html` — 每一拆，中英双语（右上角可切换）
- 每课固定格式：今天拆什么 → 三问 → 设计师 takeaway → 🎙️ 面试怎么讲 / How to say it in an interview

## 本地预览 · Preview locally

```bash
npm install
npm run dev
```

或在 StackBlitz 打开（GitHub 每次 push 后自动同步）：

`stackblitz.com/github/cjwmay/ai-teardowns`
