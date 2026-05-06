# 🪴 China AI Model Portal Guide

> For non-Chinese citizens & international developers · May 2026
> Covers 12 providers: Chat / Image / Video / Voice / Music / API / Agent / Docs

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
| 🔧 API | V4-Pro / V4-Flash / V3.2 / R1-0528 / Coder V2 | https://platform.deepseek.com/api_keys | V4-Pro $1.74/M in / $3.48/M out；V4-Flash $0.14/M in / $0.28/M out |
| 🤖 Agent | No official platform — build via Coze / n8n | — | — |
| 📖 Docs | — | https://api-docs.deepseek.com | — |

**🌍 International Access — ⭐ Simplest**

- Non-Chinese users: **email-only** registration in most regions. No phone required.
- Chat + API: same account. `chat.deepseek.com` and `platform.deepseek.com` share one login.
- API is OpenAI-compatible — swap `api.openai.com` for `api.deepseek.com`.

→ ~5 minutes from sign-up to first API call. The gold standard.

---

## 🟦 Zhipu · GLM (Z.ai)

**Models**: GLM-5.1 (agentic flagship, 200K context) / GLM-5 / GLM-4.7-Flash (free) / GLM-4.6V (vision) / CogView-4 (image) / CogVideo-4 (video)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | GLM-5.1 / GLM-5 / GLM-4.7-Flash | https://z.ai / https://chatglm.cn | Free |
| 🖼 Image | CogView-4 | https://open.bigmodel.cn | Metered |
| 🎬 Video | CogVideo-4 | https://open.bigmodel.cn | Metered |
| 🔊 Voice | GLM-TTS / GLM-ASR | https://open.bigmodel.cn | Metered |
| 🎵 Music | Not supported | — | — |
| 🔧 API | GLM-5.1 / GLM-5 / GLM-4.7-Flash / GLM-4.6V / CogView / CogVideo | https://open.bigmodel.cn | GLM-5.1 $1.40/M in / $4.40/M out；GLM-4.7-Flash free |
| 🤖 Agent | AutoGLM / GLM-PC / CogAgent-9B (open-source) | https://z.ai | — |
| 📖 Docs | — | https://open.bigmodel.cn/dev/api | — |

**🌍 International Access — ⭐⭐ Moderate**

- International phone numbers accepted for registration at `bigmodel.cn`
- New users get 20M free tokens
- GLM-5.1 supports autonomous work for up to 8 hours on a single task
- Full multimodal coverage: text, image generation, video generation, voice
- Open-source Agent models available

---

## 🟦 Alibaba · Qwen (Tongyi Qianwen)

**Models**: Qwen3.5-Flash / Qwen3.5-Omni / Qwen3-Max / Qwen3-Plus / Qwen3-Coder
**Video**: HappyHorse 1.0 (15B, unified Transformer, #1 on Artificial Analysis T2V leaderboard)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Qwen3.5-Flash / Qwen3-Max / Qwen3-Plus | https://tongyi.aliyun.com/qianwen | Free |
| 🖼 Image | Tongyi Wanxiang | https://tongyi.aliyun.com/wanxiang | Metered |
| 🎬 Video | HappyHorse 1.0 (beta) | Not yet public API | TBA |
| 🔊 Voice | Qwen-TTS / Qwen-ASR | https://bailian.console.alibabacloud.com | Metered |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Qwen3.5-Flash / Qwen3.5-Omni / Qwen3-Max / Qwen3-Plus / Qwen3-Coder | https://bailian.console.alibabacloud.com | Qwen3-Plus $0.28/M in / $1.12/M out |
| 🤖 Agent | Bailian console | https://bailian.console.alibabacloud.com | — |
| 📖 Docs | — | https://www.alibabacloud.com/help/en/model-studio | — |

**🌍 International Access — ⭐⭐⭐ Difficult**

- Use **Alibaba Cloud International** (`alibabacloud.com`), NOT `aliyun.com`
- Passport accepted for identity verification
- Three confusing domains: `qianwen.com` (chat alias) → `qwen.com` (blog, no service) → `bailian.console.alibabacloud.com` (real dev console)
- HappyHorse is the #1 video generation model globally, currently in beta

→ Budget 15–30 min for setup. Verification may take 1–2 business days.

---

## 🟥 ByteDance · Doubao / Volcano Engine

**Models**: Seed 2.0 Pro / Seed 2.0 Code / Seedance 2.0 (video) / Doubao-pro

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Seed 2.0 Pro / Doubao-pro | https://www.doubao.com | Free (Douyin login) |
| 🖼 Image | Jimeng AI | https://jimeng.jianying.com | Free tier + paid |
| 🎬 Video | Seedance 2.0 (text-to-video + image-to-video) | https://jimeng.jianying.com | Jimeng subscription |
| 🔊 Voice | Doubao TTS / ASR | https://console.volcengine.com/ark | Metered |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Seed 2.0 Pro / Seed 2.0 Code / Seedance 2.0 / Doubao-pro | https://console.volcengine.com/ark | Metered |
| 🤖 Agent | Coze (international) | https://www.coze.com | Free + paid |
| 📖 Docs | — | https://www.volcengine.com/docs/82379 | — |

**🌍 International Access — ⭐⭐⭐⭐ Very difficult**

- **Country-dependent phone support.** US numbers confirmed blocked. Some other countries work.
- If blocked: ask Chinese colleague to register, or use temporary SMS service
- **Trae AI IDE** (`trae.ai`) and **Coze** (`coze.com`) work internationally
- Seedance 2.0 accessible via third-party platforms (WeShop AI, CometAPI)

---

## 🌊 MiniMax / Hailuo AI

**Models**: M2.7 (230B MoE) / Speech 2.8 / Music 2.6 / Hailuo 2.3 (video) / Hailuo 02

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | M2.7 / M2.5 | https://hailuoai.com | Free |
| 🖼 Image | M2.7 (multimodal understanding) | https://hailuoai.com | Free |
| 🎬 Video | Hailuo 2.3 / Hailuo 02 | https://hailuoai.com | Free tier + paid |
| 🔊 Voice | Speech 2.8 (emotional TTS, dialects, singing) | https://www.minimaxi.com/audio | Metered |
| 🎵 Music | Music 2.6 (AI composition + arrangement) | https://www.minimaxi.com/audio | Metered |
| 🔧 API | M2.7 / Speech 2.8 / Music 2.6 / Hailuo 2.3 | https://platform.minimax.io | M2.7 $0.30/M in / $1.20/M out |
| 🤖 Agent | MiniMax Agent | https://www.minimax.io/agent | — |
| 📖 Docs | — | https://platform.minimax.io/docs | — |

**🌍 International Access — ⭐⭐ Easy**

- **Google / GitHub OAuth login** at `platform.minimax.io` — no separate registration needed
- Always use `platform.minimax.io` (international), NOT `minimaxi.com` (China-only)
- M2.7 SWE-Pro 56.22%, strong coding model. Anthropic-compatible endpoint: `api.minimax.io/anthropic`

---

## 📱 Xiaomi · MiMo

**Models**: MiMo-V2.5-Pro (1T, 42B active, 1M context) / V2.5-Omni (full-modality) / V2.5-TTS / V2-Flash

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | V2.5-Pro / V2-Flash | https://aistudio.xiaomimimo.com | Free |
| 🖼 Image | V2.5-Omni (full-modality understanding) | https://aistudio.xiaomimimo.com | Free |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | V2.5-TTS (emotional TTS, dialects, singing) | https://platform.xiaomimimo.com | Metered |
| 🎵 Music | Not supported | — | — |
| 🔧 API | V2.5-Pro / V2.5-Omni / V2.5-TTS / V2-Flash | https://platform.xiaomimimo.com | V2.5-Pro $0.40/M in / $2.00/M out；Token Plan from ~$5.50/mo |
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

**Models**: Kimi K2.6 (1T MoE, 32B active) / K2.5 — K2 series is the only actively maintained family

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | K2.6 / K2.5 | https://www.kimi.com | Free |
| 🖼 Image | K2.6 (native multimodal: image+video+audio input understanding) | https://www.kimi.com | Free |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | K2.6 (audio input understanding) | https://www.kimi.com | Free |
| 🎵 Music | Not supported | — | — |
| 🔧 API | K2.6 / K2.5 | https://platform.kimi.ai | K2.6 $0.60/M in / $2.40/M out |
| 🤖 Agent | Built-in Agent mode / Agent Swarm (300+ sub-agents) | https://www.kimi.com | — |
| 📖 Docs | — | https://platform.kimi.ai/docs | — |

**🌍 International Access — ⭐ Simplest**

- Always use `kimi.com` / `platform.kimi.ai` (global), NOT `.cn` domains (China-only)
- Accepts international phone numbers and email
- Chat + API: same account
- K2.6 open weights on Hugging Face (Modified MIT, commercial use allowed)
- Agent Swarm supports 300+ sub-agents, 4000+ coordinated steps

---

## 🟩 Tencent · Hunyuan / Yuanbao

**Models**: HY 3.0 / T1 / HY 2.0 (MoE 406B) / Image 3.0 / 3D 3.0

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | HY 3.0 / T1 / HY 2.0 | https://yuanbao.tencent.com | Free (WeChat/QQ login) |
| 🖼 Image | Hunyuan Image 3.0 | https://console.cloud.tencent.com/hunyuan | Metered |
| 🎬 Video | In development (Hunyuan Video) | — | — |
| 🔊 Voice | Hunyuan TTS / ASR | https://console.cloud.tencent.com/hunyuan | Metered |
| 🎵 Music | Not supported | — | — |
| 🔧 API | HY 3.0 / T1 / HY 2.0 / Image 3.0 / 3D 3.0 | https://console.cloud.tencent.com/hunyuan | Metered, post-pay billing required |
| 🤖 Agent | Tencent Yuanqi | https://yuanqi.tencent.com | — |
| 📖 Docs | — | https://cloud.tencent.com/document/product/1729 | — |

**🌍 International Access — ⭐⭐⭐ Moderate**

- Tencent Cloud International (`tencentcloud.com`) accepts **passport/driver's license/work permit**
- No Chinese ID needed. One document verifies up to 3 accounts.
- Chat (Yuanbao) is effectively China-only (requires WeChat/QQ)
- Hunyuan 3D API going global — most internationally accessible Tencent AI product

---

## 🟧 iFlytek · Spark

**Models**: Spark V4.0 / Multimodal / TTS / ASR (industry-leading Chinese voice AI)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Spark V4.0 | https://xinghuo.xfyun.cn | Free |
| 🖼 Image | Spark Multimodal (understanding + generation) | https://xinghuo.xfyun.cn | Metered |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | iFlytek TTS / ASR (best-in-class Chinese voice: emotional, dialect, multilingual) | https://global.xfyun.cn | Metered / per-character |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Spark V4.0 / Multimodal / TTS / ASR | https://xinghuo.xfyun.cn/sparkapi | Metered, free quota available |
| 🤖 Agent | iFlytek Open Platform | https://www.xfyun.cn | — |
| 📖 Docs | — | https://global.xfyun.cn/doc | — |

**🌍 International Access — ⭐⭐⭐ Difficult**

- International registration limited — primarily a domestic Chinese platform
- Voice AI (TTS/ASR) is the strongest offering and available via the global site (`global.xfyun.cn`)
- Best Chinese voice synthesis in the industry
- Focus on education, office, and voice scenarios

---

## 🟧 Baidu · ERNIE (Wenxin Yiyan) / Qianfan

**Models**: ERNIE 5.1 Preview / ERNIE 5.0 (2.4T unified multimodal) / ERNIE X1 / ERNIE-Image (8B open-source)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | ERNIE 5.0 / 5.1 Preview / X1 | https://yiyan.baidu.com | Free |
| 🖼 Image | ERNIE-Image (8B open-source) | https://aistudio.baidu.com/ernieimage | Metered |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | Baidu TTS / ASR | https://console.bce.baidu.com | Metered |
| 🎵 Music | Not supported | — | — |
| 🔧 API | ERNIE 5.0 / X1 / Speed / Lite | https://console.bce.baidu.com/qianfan | Metered；Auth: Key+Secret → access_token (30-day validity, extra step vs others) |
| 🤖 Agent | Qianfan console | https://console.bce.baidu.com/qianfan | — |
| 📖 Docs | — | https://cloud.baidu.com/doc/WENXINWORKSHOP | — |

**🌍 International Access — ⭐⭐⭐⭐⭐ Hardest**

- Three independent account systems, no cross-login
- Chat: Baidu account (international phone possible)
- API: Baidu Intelligent Cloud with Chinese real-name verification — **extremely difficult without Chinese ID**
- AI Studio: third account, most accessible to international researchers, limited free model access

→ Best bet for international users: AI Studio for free model access. API path is effectively China-only.

---

## 💰 Ant Group · Bailing

**Models**: Ling-2.6-flash (released April 2026) / Bailing foundation model

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Ling-2.6-flash / Bailing foundation model | https://www.ant-ling.com/zh/ | Free |
| 🖼 Image | Bailing multimodal | https://www.ant-ling.com/zh/ | Free |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | Bailing TTS / ASR | https://www.ant-ling.com/zh/ | Free |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Ling-2.6-flash (April 2026) | https://www.ant-ling.com/zh/ (currently consumer-product-first; public API in progress) | TBA |
| 🤖 Agent | Zhixiaobao / Alipay AI Pay (120M+ weekly txn) / Health AQ (100M+ users) | Alipay app | — |
| 📖 Docs | — | https://www.ant-ling.com/zh/ | — |

**🌍 International Access — ⭐⭐⭐⭐⭐ Limited**

- Main site: [ant-ling.com](https://www.ant-ling.com/zh/), Ant Group's LLM platform
- Currently consumer-product-first (Zhixiaobao, AI Pay, Health AQ within Alipay ecosystem)
- Developer API is in progress — watch for announcements
- Alipay account may be required for full access

---

## 🔵 StepFun (阶跃星辰)

**Models**: Step 3.5 Flash (196B MoE, 11B active, open-source) / Step3 (321B MoE, 38B active, multimodal reasoning)

| Feature | Model | URL | Pricing |
|---------|-------|-----|---------|
| 💬 Chat | Step 3.5 Flash / Step3 | https://www.stepfun.com | Free |
| 🖼 Image | Step3 (multimodal vision understanding) | https://platform.stepfun.ai | Metered |
| 🎬 Video | Not supported | — | — |
| 🔊 Voice | Not supported | — | — |
| 🎵 Music | Not supported | — | — |
| 🔧 API | Step 3.5 Flash / Step3 | https://platform.stepfun.ai | Step 3.5 Flash $0.10/M in / $0.30/M out；Monthly plans from ~$5.50/mo |
| 🤖 Agent | StepFun Open Platform | https://platform.stepfun.ai | — |
| 📖 Docs | — | https://platform.stepfun.ai/docs | — |

**🌍 International Access — ⭐⭐ Moderate**

- Registration with phone number at `platform.stepfun.ai`
- Step 3.5 Flash is open-source (MoE, 196B total / 11B active) — strong reasoning and coding at low cost
- Step3 is the multimodal flagship (321B / 38B active) with vision-language capabilities
- "Super Search Agent" that aggregates 80+ foundation models for search decomposition and result synthesis
- Suitable as an end-user tool, not a developer platform
- No international-specific offering or API

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

| Provider | Flagship Model | Input ($/1M tokens) | Output ($/1M tokens) |
|----------|---------------|---------------------|----------------------|
| DeepSeek | V4-Pro | $1.74 | $3.48 |
| DeepSeek | V4-Flash | $0.14 | $0.28 |
| Zhipu | GLM-5.1 | $1.40 | $4.40 |
| Zhipu | GLM-4.7-Flash | Free | Free |
| Alibaba | Qwen3-Plus | $0.28 | $1.12 |
| MiniMax | M2.7 | $0.30 | $1.20 |
| Xiaomi | V2.5-Pro | $0.40 | $2.00 |
| Kimi | K2.6 | $0.60 | $2.40 |
| Baidu | ERNIE 5.0 | Metered | Metered |
| StepFun | Step 3.5 Flash | $0.10 | $0.30 |
| iFlytek | Spark V4.0 | Metered (free quota) | Metered |

---

## 💡 Practical tips for international developers

1. **Start with DeepSeek or Kimi** — email sign-up, no friction, competitive pricing
2. **Google/GitHub OAuth** at MiniMax `platform.minimax.io` — no registration needed
3. **Passport verification works** on Tencent Cloud Intl and Alibaba Cloud Intl
4. **Open weights**: DeepSeek (MIT), Kimi K2.6 (Modified MIT), Qwen (Apache 2.0)
5. **HappyHorse** (Alibaba) is #1 video generation globally — API coming soon
6. **MiniMax `.io`** and **Kimi `.ai`** — always use the global domains, not `.com`/`.cn`
7. **Volcano Engine is country-dependent** — check before giving up

---

*Maintained by: Wendy Chen · https://github.com/cwd1130/ModelGate*
*Data as of May 2026 — check each platform's official site for latest updates*
