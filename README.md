# ModelGate

> Language: **EN** | [中文](README_CN.md)

---

## The Problem

You type **"Tongyi Qianwen API"** into a search engine.

Three results come back: `qianwen.com`, `qwen.com`, `bailian.aliyun.com` — three completely different domains, all claiming to be the same product.

You click the first one. It's a chat page. There's a text box, some suggested prompts, but no API Key in sight. No developer settings. Nothing.

You try the second. Model introduction. Blog posts. Benchmark charts. Still no API Key.

The third one? That's the real developer console. But it's buried under an Alibaba Cloud subdomain — a separate account system, a separate login flow, and a UI that looks like it belongs to a different company entirely.

Fifteen minutes later, you're one of the lucky ones. You found it.

**This isn't just Alibaba.** Baidu splits chat, API, and AI Studio across three independent accounts with no cross-login. ByteDance's Doubao chat and Volcano Engine API sit in two different corporate universes. Tencent's Hunyuan chat uses WeChat login while the API requires a separate Tencent Cloud account. MiniMax has four — four — different account systems for chat, API, international API, and character roleplay.

Every developer who tries Chinese LLMs hits this wall. Every single one.

---

## What ModelGate Does

ModelGate is a hand-curated, one-page index of the actual URLs you need — chat, API Key, API docs, agent, coding, and multimodal — for each major Chinese LLM provider. No blog posts, no marketing landing pages, no wrong turns.

Each entry also maps out the **account system** behind the platform, because finding the right URL is only half the battle.

---

## Guides

- **[China AI Model Portal Guide](guide/China-AI-Model-Portal-Guide.md)** (English) — For non-Chinese citizens. Shows which platforms accept international sign-up and which require a Chinese ID or mainland phone number.
- **[中国主流大模型入口导航](guide/中国主流大模型入口导航.md)** (简体中文) — For Chinese citizens. Covers 实名认证 rules and domestic account registration.

---

## Covered Platforms

| Provider | Models | Chat | API | Coding | Multimodal |
|----------|--------|------|-----|--------|------------|
| DeepSeek | V4-Pro / V4-Flash / V3.2 / R1-0528 | ✅ | ✅ | ✅ | — |
| Zhipu · GLM (Z.ai) | GLM-5.1 / GLM-5 / GLM-4.7 / CogView / CogVideo | ✅ | ✅ | ✅ | ✅ |
| Alibaba · Qwen | Qwen3.5 / Qwen3-Max / Plus / Coder / Omni / HappyHorse | ✅ | ✅ | ✅ | ✅ |
| ByteDance · Doubao / Volcano | Seed 2.0 Pro / Doubao-pro / Seedance 2.0 | ✅ | ✅ | ✅ | ✅ |
| MiniMax / Hailuo | M2.7 / Speech 2.8 / Music 2.6 / Hailuo 2.3 | ✅ | ✅ | ✅ | ✅ |
| Xiaomi · MiMo | V2.5-Pro / V2.5-Omni / V2.5-TTS / V2-Flash | ✅ | ✅ | ✅ | ✅ |
| Moonshot AI · Kimi | K2.6 / K2.5 | ✅ | ✅ | ✅ | — |
| Tencent · Hunyuan / Yuanbao | HY 3.0 / T1 / HY 2.0 / Image 3.0 / 3D 3.0 | ✅ | ✅ | ✅ | ✅ |
| iFlytek · Spark | Spark V4.0 / TTS / ASR | ✅ | ✅ | — | ✅ |
| Baidu · ERNIE / Qianfan | ERNIE 5.0 / X1 / Speed / Lite | ✅ | ✅ | — | ✅ |
| Ant Group · Bailing | Ling-2.6-flash / Bailing | ✅ | ⏳ | — | ✅ |
| StepFun | Step 3.5 Flash / Step3 (321B MoE) | ✅ | ✅ | ✅ | ✅ |

---

*Data as of May 2026 — verify on each platform's official site for the latest.*
