# 🪴 China AI Model Portal Guide

> For non-Chinese citizens & international developers · May 2026
> Covers 12 providers: Chat / Image / Video / Voice / Music / API / Coding / Agent / Docs

---

## How to use this guide

1. **Find your use case** — Each platform table has 9 rows: Chat, Image, Video, Voice, Music, API, Coding, Agent, Docs. Scan the feature column for what you need.
2. **Check international access** — Every section has a 🌍 **International Access** block with a ⭐ rating. Outside China? Start with ⭐ Simplest.
3. **Compare prices** — API pricing at the bottom of each table. See the [API Pricing Quick Reference](#-api-pricing-quick-reference) and coding plan subscriptions for cross-platform comparison.

## Key terms

| Term | What it means |
|------|---------------|
| **Token** | ~0.75 English words. Prices are per 1 million tokens (1M). A 1000-word article costs ~1.3K tokens. |
| **$0.14/M in / $0.28/M out** | $0.14 per 1M input tokens, $0.28 per 1M output tokens. Output costs more because the model generates new text. |
| **MoE** (Mixture of Experts) | Only a fraction of total parameters activate per query — faster inference, lower cost. |
| **Context window** | How much text the model can "remember" in one conversation. 200K ≈ 150K English words ≈ a long novel. |
| **2.5折 / 75% off** | Paying 25% of the list price. 2.5折 = 75% discount. |

## Where should I start?

| I want to... | Try this first |
|--------------|----------------|
| 💬 **Chat for free** | DeepSeek, Kimi, Qwen, Zhipu |
| 🔧 **Call API (cheapest)** | DeepSeek V4-Flash ($0.14/M), StepFun 3.5 Flash ($0.10/M) |
| 💻 **Vibe code / AI coding** | DeepSeek V4-Pro, Kimi K2.6, MiniMax M2.7 |
| 🖼 **Generate images** | Zhipu CogView-4, ByteDance Jimeng (Seedream) |
| 🎬 **Generate video** | Alibaba HappyHorse (#1 globally), MiniMax Hailuo, ByteDance Seedance |
| 🔊 **Voice / TTS** | iFlytek (best Chinese voice), MiniMax Speech 2.8 |
| 🎵 **AI music** | MiniMax Music 2.6 (only option among 12) |

---

## Before you start

Every platform handles international users differently. Some accept email sign-up. Others need a Chinese ID or +86 phone. Each section below has an **International Access** block so you know what to expect.

**Quick ranking (best to worst for international devs):**

1. DeepSeek — email sign-up, 5 min to first API call
2. Kimi/Moonshot — `kimi.com` accepts international phone/email
3. MiniMax — Google/GitHub OAuth at `minimax.io`
4. Xiaomi MiMo — English docs, OpenRouter available
5. Zhipu GLM — international phone accepted at `bigmodel.cn`
6. Tencent Hunyuan — passport verification works on Tencent Cloud Intl
7. Alibaba Qwen — passport verification on Alibaba Cloud Intl, multi-step
8. iFlytek Spark — international registration limited
9. ByteDance Volcano — country-dependent phone support, US blocked
10. Baidu ERNIE — three account systems, API effectively China-only
11. Ant Bailing — consumer products only, no public API yet
12. StepFun — open-source MoE models, strong coding value

---

## 🟪 DeepSeek

**Models**: V4-Pro (1.6T MoE) / V4-Flash (284B) / V3.2 / R1-0528 / Coder V2 (all open-source, MIT)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | V4-Pro / V4-Flash / V3.2 | https://chat.deepseek.com | Free |
| 🖼 Image | Not supported | — | — |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | Not supported | — | — |
| 🎵 Music | Not supported | — | — |
| 🔧 API | V4-Pro / V4-Flash / V3.2 / R1-0528 / Coder V2 | https://platform.deepseek.com/api_keys | V4-Flash $0.14/M in / $0.28/M out；V4-Pro list price $1.74/M in / $3.48/M out (75% off / 2.5折 at $0.435/$0.87, extended through 2026/05/31 23:59 Beijing Time) |
| 💻 Coding | No official Coding Plan — use API directly | — | — |
| 🤖 Agent | No official platform — build via Coze / n8n | — | — |
| 📖 Docs | — | https://api-docs.deepseek.com | — |

**🌍 International Access — ⭐ Simplest**

- Non-Chinese users: **email-only** registration in most regions. No phone required.
- Chat + API: same account. `chat.deepseek.com` and `platform.deepseek.com` share one login.
- API is OpenAI-compatible and also supports Anthropic API format — swap base URL only.

→ ~5 minutes from sign-up to first API call. The gold standard.

---

## 🟦 Zhipu · GLM (Z.ai)

**Models**: GLM-5.1 (agentic flagship, 200K context) / GLM-5 / GLM-4.7-Flash (free) / GLM-4.6V (vision) / CogView-4 (image) / CogVideo-4 (video)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | GLM-5.1 / GLM-5 / GLM-4.7-Flash | https://z.ai | Free |
| 🖼 Image | CogView-4 | https://open.bigmodel.cn | By token |
| 🎬 Video | CogVideo-4 | https://open.bigmodel.cn | By token |
| 🔊 Voice | GLM-TTS / GLM-ASR | https://open.bigmodel.cn | By token |
| 🎵 Music | Not supported | — | — |
| 🔧 API | GLM-5.1 / GLM-5 / GLM-4.7-Flash / GLM-4.6V / CogView / CogVideo | https://open.bigmodel.cn | GLM-5.1 ~$1.40/M in / ~$4.40/M out (prices raised Q1 2026, check console)；GLM-4.7-Flash free |
| 💻 Coding | GLM Coding Plan (same model as API above) | https://bigmodel.cn/glm-coding | Lite ¥49/mo, Pro ¥149/mo, Max ¥469/mo |
| 🤖 Agent | AutoGLM / GLM-PC / CogAgent-9B (open-source) | https://z.ai | — |
| 📖 Docs | — | https://open.bigmodel.cn/dev/api or https://docs.z.ai | — |

**🌍 International Access — ⭐⭐ Moderate**

- International phone numbers accepted for registration at `bigmodel.cn`
- New users get 20M free tokens
- GLM-5.1 supports autonomous work for up to 8 hours on a single task, targeting Claude Opus 4.6-level performance
- Note: Zhipu raised API prices ~83% in Q1 2026; GLM Coding Plan subscriptions also raised. Check the console for current rates.
- Full multimodal coverage: text, image generation, video generation, voice

---

## 🟦 Alibaba · Qwen (Tongyi Qianwen)

**Models**: Qwen3.5-Flash / Qwen3.5-Omni / Qwen3-Max / Qwen3.5-Plus / Qwen3-Coder
**Video**: HappyHorse 1.0 (unified Transformer, #1 on Artificial Analysis T2V leaderboard globally)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Qwen3.5-Flash / Qwen3-Max / Qwen3.5-Plus | https://tongyi.aliyun.com/qianwen | Free |
| 🖼 Image | Tongyi Wanxiang / Wan2.7-Image-Pro | https://tongyi.aliyun.com/wanxiang | By token |
| 🎬 Video | HappyHorse 1.0 (T2V / I2V / video editing, in beta) | https://bailian.console.alibabacloud.com | By token (API open) |
| 🔊 Voice | CosyVoice V3.5 / Qwen-ASR | https://bailian.console.alibabacloud.com | By token |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Qwen3.5-Flash / Qwen3.5-Omni / Qwen3-Max / Qwen3.5-Plus / Qwen3-Coder | https://bailian.console.alibabacloud.com | Qwen3-Max $0.36/M in (≤32K) / $1.43/M out；Qwen3.5-Plus $0.12/M in / $0.29/M out |
| 💻 Coding | Bailian Coding Plan (Pro) | https://bailian.console.aliyun.com | Pro ¥200/mo (Lite discontinued) |
| 🤖 Agent | Bailian console | https://bailian.console.alibabacloud.com | — |
| 📖 Docs | — | https://www.alibabacloud.com/help/en/model-studio | — |

**🌍 International Access — ⭐⭐⭐ Difficult**

- Use **Alibaba Cloud International** (`alibabacloud.com`), NOT `aliyun.com`
- Passport accepted for identity verification
- Three confusing domains: `qianwen.com` (chat alias) → `qwen.com` (blog, no service) → `bailian.console.alibabacloud.com` (real dev console)
- Qwen3-Max uses tiered pricing: ≤32K input is cheapest, costs rise for longer contexts
- New users get 100M+ free tokens across models (90-day validity)

→ Budget 15–30 min for setup. Verification may take 1–2 business days.

---

## 🟥 ByteDance · Doubao / Volcano Engine

**Models**: Seed 2.0 Pro / Seed 2.0 Code / Seed 2.0 Lite / Seedance 2.0 (video) / Doubao-pro

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Seed 2.0 Pro / Doubao-pro | https://www.doubao.com | Free (Douyin login) |
| 🖼 Image | Jimeng AI (Seedream 5.0 Lite) | https://jimeng.jianying.com | Free tier + paid |
| 🎬 Video | Seedance 2.0 (T2V + I2V + video editing) | https://jimeng.jianying.com | Jimeng subscription; API ~¥46/M tokens for T2V |
| 🔊 Voice | Doubao TTS / ASR | https://console.volcengine.com/ark | By token |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Seed 2.0 Pro / Seed 2.0 Code / Seedance 2.0 / Doubao-pro | https://console.volcengine.com/ark | Seed 2.0 Pro ~$0.44/M in / $2.21/M out (≤32K) |
| 💻 Coding | Ark Coding Plan (Seed 2.0 / MiniMax-M2.5 / Kimi-K2.5 / GLM-4.7 / DeepSeek-V3.2, Auto mode, API calls allowed) | https://console.volcengine.com/ark | Lite ¥40/mo, Pro ¥200/mo (intro ~¥9.9) |
| 🤖 Agent | Coze (international) | https://www.coze.com | Free + paid |
| 📖 Docs | — | https://www.volcengine.com/docs/82379 | — |

**🌍 International Access — ⭐⭐⭐⭐ Very difficult**

- **Country-dependent phone support.** US numbers confirmed blocked. Some other countries work.
- If blocked: ask Chinese colleague to register, or use temporary SMS service
- **Trae AI IDE** (`trae.ai`) and **Coze** (`coze.com`) work internationally
- Seedance 2.0 accessible via third-party platforms (WeShop AI, CometAPI)

---

## 🌊 MiniMax / Hailuo AI

**Models**: M2.7 (230B MoE, 10B active, "self-evolving") / Speech 2.8 / Music 2.6 / Hailuo 2.3 (video) / Hailuo 02

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | M2.7 / M2.5 | https://hailuoai.com | Free |
| 🖼 Image | M2.7 (multimodal understanding) | https://hailuoai.com | Free |
| 🎬 Video | Hailuo 2.3 / Hailuo 02 | https://hailuoai.com | Free tier + paid |
| 🔊 Voice | Speech 2.8 (emotional TTS, dialects, singing) | https://www.minimaxi.com/audio | By token |
| 🎵 Music | Music 2.6 (AI composition + arrangement) | https://www.minimaxi.com/audio | By token |
| 🔧 API | M2.7 / Speech 2.8 / Music 2.6 / Hailuo 2.3 | https://platform.minimax.io | M2.7 $0.30/M in / $1.20/M out |
| 💻 Coding | Token Plans (Starter / Plus / Max / Ultra) | https://platform.minimax.io | Starter ¥29/mo, Plus ¥49/mo, Max ¥119/mo, Ultra ¥899/mo |
| 🤖 Agent | MiniMax Agent | https://www.minimax.io/agent | — |
| 📖 Docs | — | https://platform.minimax.io/docs | — |

**🌍 International Access — ⭐⭐ Easy**

- **Google / GitHub OAuth login** at `platform.minimax.io` — no separate registration needed
- Always use `platform.minimax.io` (international), NOT `minimaxi.com` (China-only)
- M2.7 released March 2026: SWE-Pro 56.22%, strong coding model. OpenRouter and major providers available.
- Anthropic-compatible endpoint: `api.minimax.io/anthropic`
- Token subscription plans from $10/month bundling text, speech, image, video, and music

---

## 📱 Xiaomi · MiMo

**Models**: MiMo-V2.5-Pro (1T, 42B active, 1M context) / V2.5-Omni (full-modality) / V2.5-TTS / V2-Flash

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | V2.5-Pro / V2-Flash | https://aistudio.xiaomimimo.com | Free |
| 🖼 Image | V2.5-Omni (full-modality understanding) | https://aistudio.xiaomimimo.com | Free |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | V2.5-TTS (emotional TTS, dialects, singing) | https://platform.xiaomimimo.com | By token |
| 🎵 Music | Not supported | — | — |
| 🔧 API | V2.5-Pro / V2.5-Omni / V2.5-TTS / V2-Flash | https://platform.xiaomimimo.com | V2.5-Pro $0.40/M in / $2.00/M out |
| 💻 Coding | MiMo Token Plan | https://platform.xiaomimimo.com | from ¥39/mo (~$5.50/mo) |
| 🤖 Agent | MiMo Claw (OpenClaw / Cline / KiloCode compatible) | https://aistudio.xiaomimimo.com | — |
| 📖 Docs | — | https://platform.xiaomimimo.com/docs/en-US | — |

**🌍 International Access — ⭐⭐ Easy**

- Full English documentation available
- International phone numbers appear to be accepted
- OpenRouter carries all MiMo models (easiest path for international devs)
- OpenAI + Anthropic dual API protocol support
- ~1/5 the price of Claude at comparable tiers

---

## ⬜ Moonshot AI · Kimi

**Models**: Kimi K2.6 (1T MoE, 32B active, open weights, 256K context) / K2.5

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | K2.6 / K2.5 | https://www.kimi.com | Free |
| 🖼 Image | K2.6 (native multimodal: image+video+audio input understanding) | https://www.kimi.com | Free |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | K2.6 (audio input understanding) | https://www.kimi.com | Free |
| 🎵 Music | Not supported | — | — |
| 🔧 API | K2.6 / K2.5 | https://platform.kimi.ai | K2.6 $0.95/M in / $4.00/M out (cache miss)；K2.5 $0.60/M in / $3.00/M out |
| 💻 Coding | Andante / Moderato / Allegretto / Allegro | https://platform.kimi.ai | Andante ¥49/mo, Moderato ¥99/mo, Allegretto ¥199/mo, Allegro ¥699/mo |
| 🤖 Agent | Built-in Agent mode / Agent Swarm (300+ sub-agents, 1500+ tool calls) | https://www.kimi.com | — |
| 📖 Docs | — | https://platform.kimi.ai/docs | — |

**🌍 International Access — ⭐ Simplest**

- Always use `kimi.com` / `platform.kimi.ai` (global), NOT `.cn` domains (China-only)
- Accepts international phone numbers and email; chat + API share one account
- K2.6 released April 20, 2026 — open weights on Hugging Face (Modified MIT, commercial use allowed)
- K2.6 API is ~58% more expensive than K2.5 due to longer agent reasoning chains
- Agent Swarm: 300+ sub-agents, 5-day autonomous run supported

---

## 🟩 Tencent · Hunyuan / Yuanbao

**Models**: HY 3.0 / T1 / HY 2.0 (MoE 406B) / Image 3.0 / 3D 3.0

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | HY 3.0 / T1 / HY 2.0 | https://yuanbao.tencent.com | Free (WeChat/QQ login) |
| 🖼 Image | Hunyuan Image 3.0 | https://console.cloud.tencent.com/hunyuan | By token |
| 🎬 Video | In development (Hunyuan Video) | — | — |
| 🔊 Voice | Hunyuan TTS / ASR | https://console.cloud.tencent.com/hunyuan | By token |
| 🎵 Music | Not supported | — | — |
| 🔧 API | HY 3.0 / T1 / HY 2.0 / Image 3.0 / 3D 3.0 | https://console.cloud.tencent.com/hunyuan | By token, post-pay billing required |
| 💻 Coding | Coding Plan (HY 2.0 / GLM-5 / Kimi-K2.5 / MiniMax-M2.5, OpenClaw / Claude Code / Cline / Cursor compatible) | https://console.cloud.tencent.com/tokenhub/codingplan | Lite ¥40/mo, Pro ¥200/mo (intro pricing: ¥7.9 → ¥20 → ¥40) |
| 🤖 Agent | Tencent Yuanqi | https://yuanqi.tencent.com | — |
| 📖 Docs | — | https://cloud.tencent.com/document/product/1729 | — |

**🌍 International Access — ⭐⭐⭐ Moderate**

- Tencent Cloud International (`tencentcloud.com`) accepts **passport/driver's license/work permit**
- No Chinese ID needed. One document verifies up to 3 accounts.
- Chat (Yuanbao) is effectively China-only (requires WeChat/QQ)
- Hunyuan 3D API is the most internationally accessible Tencent AI product

---

## 🟧 iFlytek · Spark

**Models**: Spark V4.0 / Multimodal / TTS / ASR (industry-leading Chinese voice AI)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Spark V4.0 | https://xinghuo.xfyun.cn | Free |
| 🖼 Image | Spark Multimodal (understanding + generation) | https://xinghuo.xfyun.cn | By token |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | iFlytek TTS / ASR (best-in-class Chinese voice: emotional, dialect, multilingual) | https://global.xfyun.cn | By token / per-character |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Spark V4.0 / Multimodal / TTS / ASR | https://xinghuo.xfyun.cn/sparkapi | By token, free quota available |
| 💻 Coding | No official Coding Plan | — | — |
| 🤖 Agent | iFlytek Open Platform | https://www.xfyun.cn | — |
| 📖 Docs | — | https://global.xfyun.cn/doc | — |

**🌍 International Access — ⭐⭐⭐ Difficult**

- International registration limited — primarily a domestic Chinese platform
- Voice AI (TTS/ASR) is the strongest offering and available via the global site (`global.xfyun.cn`)
- Best Chinese voice synthesis in the industry; strong in education and office scenarios

---

## 🟧 Baidu · ERNIE (Wenxin Yiyan) / Qianfan

**Models**: ERNIE 5.1 Preview / ERNIE 5.0 / ERNIE X1 / ERNIE-Image (8B open-source)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | ERNIE 5.0 / 5.1 Preview / X1 | https://yiyan.baidu.com | Free |
| 🖼 Image | ERNIE-Image (8B open-source) | https://aistudio.baidu.com/ernieimage | By token |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | Baidu TTS / ASR | https://console.bce.baidu.com | By token |
| 🎵 Music | Not supported | — | — |
| 🔧 API | ERNIE 5.0 / X1 / Speed / Lite | https://console.bce.baidu.com/qianfan | By token；Auth: Key+Secret → access_token (30-day validity, extra step vs others) |
| 💻 Coding | Qianfan Coding Plan (GLM-5 / DeepSeek-V3.2 / Kimi-K2.5 / MiniMax-M2.5, Claude Code / OpenClaw / Cline compatible) | https://cloud.baidu.com/product/codingplan.html | Lite ¥40/mo, Pro ¥200/mo (intro ¥7.9, limited daily slots) |
| 🤖 Agent | Qianfan console | https://console.bce.baidu.com/qianfan | — |
| 📖 Docs | — | https://cloud.baidu.com/doc/WENXINWORKSHOP/s/Slfmc9dds | — |

**🌍 International Access — ⭐⭐⭐⭐⭐ Hardest**

- Three independent account systems, no cross-login
- API: Baidu Intelligent Cloud with Chinese real-name verification — **extremely difficult without Chinese ID**
- AI Studio: most accessible to international researchers, limited free model access

→ Best bet for international users: AI Studio for free model access. API path is effectively China-only.

---

## 💰 Ant Group · Bailing

**Models**: Ling-2.6-flash (released April 2026) / Bailing foundation model

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Ling-2.6-flash / Bailing foundation model | https://www.ant-ling.com | Free |
| 🖼 Image | Bailing multimodal | https://www.ant-ling.com | Free |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | Bailing TTS / ASR | https://www.ant-ling.com | Free |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Ling-2.6-flash (April 2026) | https://www.ant-ling.com (public API in progress) | TBA |
| 💻 Coding | No official Coding Plan | — | — |
| 🤖 Agent | Zhixiaobao / Alipay AI Pay (120M+ weekly txn) / Health AQ (100M+ users) | Alipay app | — |
| 📖 Docs | — | https://www.ant-ling.com | — |

**🌍 International Access — ⭐⭐⭐⭐⭐ Limited**

- Main site: [ant-ling.com](https://www.ant-ling.com) (English available)
- Consumer-product-first; Alipay ecosystem required for agent products
- Developer API in progress — watch for announcements

---

## 🔵 StepFun (阶跃星辰)

**Models**: Step 3.5 Flash (196B MoE, 11B active, open-source) / Step3 (321B MoE, 38B active, multimodal)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Step 3.5 Flash / Step3 | https://www.stepfun.com | Free |
| 🖼 Image | Step3 (multimodal vision understanding) | https://platform.stepfun.ai | By token |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | Not supported | — | — |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Step 3.5 Flash / Step3 | https://platform.stepfun.ai | Step 3.5 Flash $0.10/M in / $0.30/M out；Step3 $0.57/M in / $1.42/M out |
| 💻 Coding | Step Plan | https://platform.stepfun.ai | from ¥40/mo (~$5.50/mo) |
| 🤖 Agent | StepFun Open Platform | https://platform.stepfun.ai | — |
| 📖 Docs | — | https://platform.stepfun.ai/docs | — |

**🌍 International Access — ⭐⭐ Moderate**

- Registration with phone number at `platform.stepfun.ai`
- Step 3.5 Flash: open-source (196B total / 11B active), SWE-bench 74.4%, exceptional coding value at $0.10/M input
- Step3: multimodal flagship (321B / 38B active), accepts text and image inputs

---

## 📊 International Access Comparison

| Platform | Non-Chinese Phone OK? | No Chinese ID Needed? | Separate Chat/API Account? | Overall |
|----------|----------------------|----------------------|---------------------------|---------| 
| **DeepSeek** | ✅ Email-only in most regions | ✅ Yes | ❌ Same account | ⭐ Easiest |
| **Kimi / Moonshot** | ✅ Yes (use `kimi.com`) | ✅ Yes | ❌ Same account | ⭐ Easiest |
| **MiniMax** | ✅ Yes (Google/GitHub OAuth) | ✅ Yes | ❌ Separate (chat vs API) | ⭐⭐ Easy |
| **Xiaomi MiMo** | ✅ Likely | ✅ Yes | ❌ Same account | ⭐⭐ Easy |
| **Zhipu GLM** | ✅ International phone OK | ✅ Yes | ❌ Same account | ⭐⭐ Moderate |
| **Tencent Hunyuan** | ✅ Yes (intl. site) | ✅ Passport accepted | ❌ Separate (WeChat vs Cloud) | ⭐⭐⭐ Moderate |
| **Alibaba Qwen** | ✅ Yes (intl. Alibaba Cloud) | ✅ Passport accepted | ⚠️ Same but multi-step | ⭐⭐⭐ Difficult |
| **iFlytek Spark** | ⚠️ Limited international | ⚠️ Primarily domestic | ⚠️ Separate | ⭐⭐⭐ Difficult |
| **ByteDance Volcano** | ⚠️ Country-dependent (US blocked) | ⚠️ Chinese ID for payment | ❌ Separate (Douyin vs Volcano) | ⭐⭐⭐⭐ Very difficult |
| **Baidu ERNIE** | ⚠️ Partial (AI Studio) | ❌ Required for API | ❌ Three separate systems | ⭐⭐⭐⭐⭐ Hardest |
| **Ant Bailing** | ❌ Consumer-only | ❌ Alipay ecosystem | N/A (no public API) | ⭐⭐⭐⭐⭐ Unavailable |
| **StepFun** | ✅ International phone OK | ✅ Yes | ❌ Same account | ⭐⭐ Moderate |

---

## 📊 API Pricing Quick Reference

| Provider | Flagship Model | Input ($/1M tokens) | Output ($/1M tokens) | Notes |
|----------|---------------|---------------------|----------------------|-------|
| DeepSeek | V4-Pro | $1.74 (list) → $0.435 (75% off / 2.5折 through 5/31 23:59 Beijing Time) | $3.48 → $0.87 | Discount extended |
| DeepSeek | V4-Flash | $0.14 | $0.28 | Best value |
| Zhipu | GLM-5.1 | ~$1.40 | ~$4.40 | Raised Q1 2026 |
| Zhipu | GLM-4.7-Flash | Free | Free | — |
| Alibaba | Qwen3-Max | $0.36 (≤32K) | $1.43 | Tiered pricing |
| Alibaba | Qwen3.5-Plus | $0.12 | $0.29 | Budget option |
| MiniMax | M2.7 | $0.30 | $1.20 | Cached: $0.06/M |
| Xiaomi | V2.5-Pro | $0.40 | $2.00 | — |
| Kimi | K2.6 | $0.95 | $4.00 | +58% vs K2.5 |
| Kimi | K2.5 | $0.60 | $3.00 | Previous gen |
| StepFun | Step 3.5 Flash | $0.10 | $0.30 | Open-source MoE |
| StepFun | Step3 | $0.57 | $1.42 | Multimodal flagship |
| Baidu | ERNIE 5.0 | By token | By token | API China-only |
| iFlytek | Spark V4.0 | By token (free quota) | By token | — |

---

## 💡 Practical tips for international developers

1. **Start with DeepSeek or Kimi** — email sign-up, no friction, competitive pricing
2. **Google/GitHub OAuth** at MiniMax `platform.minimax.io` — no registration needed
3. **Passport verification works** on Tencent Cloud Intl and Alibaba Cloud Intl
4. **Open weights**: DeepSeek (MIT), Kimi K2.6 (Modified MIT, commercial OK), Qwen (Apache 2.0), Step 3.5 Flash (open-source)
5. **HappyHorse** (Alibaba) is #1 video generation globally — API available via Bailian
6. **MiniMax `.io`** and **Kimi `.com` / `.ai`** — always use the global domains, not `.cn`
7. **Volcano Engine is country-dependent** — US numbers blocked, try Coze (`coze.com`) as an alternative
8. **Kimi K2.6** raised API pricing ~58% on launch (April 2026) — factor this into agent cost estimates

---

*Maintained by: Wendy Chen · https://github.com/cwd1130/ModelGate*
*Data as of May 2026 — check each platform's official site for latest updates*
