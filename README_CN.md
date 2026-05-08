# 🪴 ModelGate

<p align="center">
  <img alt="Platforms" src="https://img.shields.io/badge/platforms-12-blue?style=flat-square">
  <img alt="Updated" src="https://img.shields.io/badge/data-May%202026-green?style=flat-square">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square">
  <img alt="PRs" src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square">
</p>

> **别再迷路了。直接开干。** 中国 12 家主流大模型平台，每个功能只放一个链接——就是那个真正能用的。没有软文，没有营销落地页，没有错误转向。

---

## 痛点

你搜**"通义千问 API"**，出来三个域名——`qianwen.com`、`qwen.com`、`bailian.aliyun.com`——看起来都像官方。第一个是聊天页，翻遍找不到 API Key。第二个是技术博客。第三个才是真正的开发者控制台，藏在阿里云子域名下面。

**每家国产大模型平台都这样。** 百度把聊天、API、AI Studio 拆成三套独立账号。字节的豆包和火山方舟分属两个企业体系。腾讯聊天用微信登录，API 要另开腾讯云账号。MiniMax 有四套不互通的登录系统。

每个想用国产大模型做开发的工程师，都在这里撞过墙。

## ModelGate 做什么

一份手动维护的**直链索引**。覆盖 **12 家主流国产大模型厂商**，每个功能维度只放那个能用的链接。

**每个平台包含：**

| 维度 | 你能得到什么 |
|------|------------|
| 💬 **聊天** | 直接打开就能聊的对话入口 |
| 🔧 **API** | API Key 申请页——不是博客，不是落地页 |
| 💻 **Coding** | Coding Plan 订阅方案和 IDE 集成说明 |
| 📖 **文档** | 官方 API 开发文档 |
| 🤖 **Agent** | Agent 平台和框架入口 |
| 🖼 🎬 🔊 🎵 | 图像、视频、语音、音乐生成入口 |

**不止链接——还有账号体系的坑：**
- ⚠️ **账号体系梳理**——哪家手机号注册就行，哪家要实名认证，哪家聊天和 API 是两套账号
- 💰 **API 价格速查表**——12 家平台 ¥/百万 Token 横向对比
- 📋 **Coding Plan 订阅对比**——从 ¥29/月到 ¥899/月，各档位一目了然

---

## 指南目录

| 指南 | 适合谁 | 包含内容 |
|------|--------|---------|
| **[中国主流大模型入口导航](guide/中国主流大模型入口导航.md)** | 中国开发者 / 刚接触 AI | 实名认证规则 · 人民币价格速查 · Coding Plan 对比 · 新手快速选择表 |
| **[China AI Model Portal Guide](guide/China-AI-Model-Portal-Guide.md)** | International developers | ⭐ access difficulty · USD pricing · sign-up methods · quick-pick table |

---

## 覆盖平台

| 厂商 | 旗舰模型 | 聊天 | API | 编程 | 多模态 |
|------|---------|------|-----|------|--------|
| **DeepSeek** | V4-Pro / V4-Flash / V3.2 / R1-0528 | ✅ | ✅ | ✅ | — |
| **智谱 · GLM** | GLM-5.1 / GLM-5 / GLM-4.7 / CogView / CogVideo | ✅ | ✅ | ✅ | ✅ |
| **阿里 · 通义 Qwen** | Qwen3.5 / Qwen3-Max / Plus / Coder / Omni / HappyHorse | ✅ | ✅ | ✅ | ✅ |
| **字节 · 火山方舟** | Seed 2.0 Pro / Doubao-pro / Seedance 2.0 | ✅ | ✅ | ✅ | ✅ |
| **MiniMax / 海螺** | M2.7 / Speech 2.8 / Music 2.6 / Hailuo 2.3 | ✅ | ✅ | ✅ | ✅ |
| **小米 · MiMo** | V2.5-Pro / V2.5-Omni / V2.5-TTS / V2-Flash | ✅ | ✅ | ✅ | ✅ |
| **月之暗面 · Kimi** | K2.6 / K2.5 | ✅ | ✅ | ✅ | — |
| **腾讯 · 混元** | HY 3.0 / T1 / HY 2.0 / Image 3.0 / 3D 3.0 | ✅ | ✅ | ✅ | ✅ |
| **科大讯飞 · 星火** | 星火 V4.0 / TTS / ASR | ✅ | ✅ | — | ✅ |
| **百度 · 文心** | ERNIE 5.1 / ERNIE 5.0 / X1 / Speed / Lite | ✅ | ✅ | ✅ | ✅ |
| **蚂蚁 · 百灵** | Ling-2.6-flash / Bailing | ✅ | ⏳ | — | ✅ |
| **阶跃 · StepFun** | Step 3.5 Flash / Step3 (321B MoE) | ✅ | ✅ | ✅ | ✅ |

---

## 快速开始

1. **选你的指南**——国内用户看 [中文版](guide/中国主流大模型入口导航.md)，海外开发者看 [English](guide/China-AI-Model-Portal-Guide.md)
2. **用决策表**——每个指南开头都有"不知道该从哪家开始？"，按你的需求直接推荐
3. **点链接开干**——表格里每个链接都是直达入口，没有弯弯绕绕

---

## 参与贡献

发现链接失效？价格过时？有新模型发布？欢迎提 PR。

- 平台数据在 `guide/` 目录——中英文各一份
- 更新时**两份文件一起改**，保持同步
- 价格换算汇率：**1 USD = 6.8 CNY**
- 术语规范：**"按token"** 而非 "按量"；**"2.5折 / 75% off"** 而非 "75折"

---

*维护者：[Wendy Chen](https://github.com/cwd1130) · 数据截至 2026 年 5 月*
