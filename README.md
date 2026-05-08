# 🪴 ModelGate

<p align="center">
  <img alt="Platforms" src="https://img.shields.io/badge/platforms-12-blue?style=flat-square">
  <img alt="Updated" src="https://img.shields.io/badge/data-May%202026-green?style=flat-square">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square">
  <img alt="PRs" src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square">
</p>

> **Stop searching. Start building.** One page maps every major Chinese LLM platform to the right URL — chat, API key, docs, coding plan, agent, multimodal. No marketing pages. No wrong turns.

---

## The Problem

You search **"Tongyi Qianwen API"**. Three domains come back — `qianwen.com`, `qwen.com`, `bailian.aliyun.com` — all claiming to be the same product. One is a chat page with no API key in sight. Another is a blog. Only the third is the real developer console, buried under an Alibaba Cloud subdomain.

**This is every Chinese LLM platform.** Baidu splits chat, API, and AI Studio across three independent accounts. ByteDance's Doubao and Volcano Engine live in two different corporate universes. Tencent's chat uses WeChat login while the API needs a separate cloud account. MiniMax has four different login systems.

Every developer who tries Chinese LLMs hits this wall.

## The Solution

ModelGate is a hand-curated, one-page reference. For each of **12 major Chinese LLM platforms**, we list exactly one URL per feature — the one that actually works.

**Each platform entry includes:**

| Dimension | What you get |
|-----------|-------------|
| 💬 **Chat** | Direct link to the chat interface — start talking immediately |
| 🔧 **API** | API key signup page — not a blog, not a landing page |
| 💻 **Coding** | Coding plan subscriptions with IDE integrations |
| 📖 **Docs** | Official API documentation |
| 🤖 **Agent** | Agent platforms and frameworks |
| 🖼 🎬 🔊 🎵 | Image, video, voice, and music generation |

**Beyond links — account system intel:**
- 🌍 **International access ratings** (⭐ to ⭐⭐⭐⭐⭐) — which platforms accept email, Google OAuth, international phone, and which require a Chinese ID
- 💰 **API pricing in one table** — cross-compare $ per 1M tokens across all 12 platforms
- 📋 **Coding plan subscription breakdown** — who offers what, from ¥29/mo to ¥899/mo

---

## Guides

| Guide | Audience | Content |
|-------|----------|---------|
| **[China AI Model Portal Guide](guide/China-AI-Model-Portal-Guide.md)** | International developers | ⭐ access difficulty per platform · USD pricing · passport vs phone vs email sign-up · quick-pick decision table |
| **[中国主流大模型入口导航](guide/中国主流大模型入口导航.md)** | 中国开发者 / 刚接触 AI | 实名认证规则 · 人民币价格速查 · Coding Plan 订阅对比 · 新手快速选择表 |

---

## Covered Platforms

| Provider | Flagship Models | Chat | API | Coding | Multimodal |
|----------|----------------|------|-----|--------|------------|
| **DeepSeek** | V4-Pro / V4-Flash / V3.2 / R1-0528 | ✅ | ✅ | ✅ | — |
| **Zhipu · GLM** | GLM-5.1 / GLM-5 / GLM-4.7 / CogView / CogVideo | ✅ | ✅ | ✅ | ✅ |
| **Alibaba · Qwen** | Qwen3.5 / Qwen3-Max / Plus / Coder / Omni / HappyHorse | ✅ | ✅ | ✅ | ✅ |
| **ByteDance · Volcano** | Seed 2.0 Pro / Doubao-pro / Seedance 2.0 | ✅ | ✅ | ✅ | ✅ |
| **MiniMax / Hailuo** | M2.7 / Speech 2.8 / Music 2.6 / Hailuo 2.3 | ✅ | ✅ | ✅ | ✅ |
| **Xiaomi · MiMo** | V2.5-Pro / V2.5-Omni / V2.5-TTS / V2-Flash | ✅ | ✅ | ✅ | ✅ |
| **Moonshot AI · Kimi** | K2.6 / K2.5 | ✅ | ✅ | ✅ | — |
| **Tencent · Hunyuan** | HY 3.0 / T1 / HY 2.0 / Image 3.0 / 3D 3.0 | ✅ | ✅ | ✅ | ✅ |
| **iFlytek · Spark** | Spark V4.0 / TTS / ASR | ✅ | ✅ | — | ✅ |
| **Baidu · ERNIE** | ERNIE 5.1 / ERNIE 5.0 / X1 / Speed / Lite | ✅ | ✅ | ✅ | ✅ |
| **Ant Group · Bailing** | Ling-2.6-flash / Bailing | ✅ | ⏳ | — | ✅ |
| **StepFun** | Step 3.5 Flash / Step3 (321B MoE) | ✅ | ✅ | ✅ | ✅ |

---

## Getting Started

1. **Pick your guide** — [English](guide/China-AI-Model-Portal-Guide.md) for international access info, [中文](guide/中国主流大模型入口导航.md) for domestic registration
2. **Use the decision table** — each guide opens with "Where should I start?" — pick your use case, get a recommendation
3. **Follow the links** — every URL in the tables goes directly to the real page, not a marketing site

---

## Contributing

Found a broken link? Outdated pricing? New model release? PRs are welcome.

- Platform data lives in `guide/` — one file per language
- Keep English and Chinese versions **in sync** — update both together
- Exchange rate for price conversions: **1 USD = 6.8 CNY**
- Terminology: **"By token"** not "Metered"; **"2.5折 / 75% off"** not "75折"

---

*Maintained by [Wendy Chen](https://github.com/cwd1130) · Data as of May 2026*
