# AI Content Automation

> 一周社媒内容，机器替你写。 / A full week of social content, on autopilot.

[![Live Site](https://img.shields.io/badge/Live-evophysics.ai%2Faica-7c3aed)](https://evophysics.ai/aica)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Stack](https://img.shields.io/badge/Stack-HTML%20%2B%20Vanilla%20CSS-orange)](#tech-stack)

---

## English

### What is this?

A single-page **landing site** for an AI-driven content automation service.
The product itself is a subscription that delivers a full week of social media
content (Twitter/X, LinkedIn, Instagram) every Monday morning — fully written,
formatted, hashtagged, and ready to schedule.

This repo contains only the marketing page. The actual content generation
pipeline lives behind the scenes and is exposed to customers via email and
WeChat after onboarding.

### Features

- **Weekly drop** — every Monday, a full week of posts lands in your inbox.
- **Templated production** — content is generated from a curated prompt
  template stack tuned per niche and voice, not generic AI slop.
- **Cross-platform format** — Twitter/X, LinkedIn, and Instagram ready;
  each post ships with hook, body, hashtags, and CTA.
- **Built-in calendar** — delivered as a plain weekly calendar so you can
  batch-schedule in 10 minutes.

### Tech stack

- **HTML5** — single file, semantic structure, no bundler.
- **Vanilla CSS** — embedded `<style>` block, dark theme, no framework.
- **No JavaScript** — static page, zero runtime dependencies.
- **No build step** — what you see in `index.html` is what gets deployed.

### Deployment

- Hosted on **Cloudflare Pages**.
- Direct upload from `main` branch; no CI required.
- Custom domain points to a path under the EvoPhysics umbrella site.

### Part of the EvoPhysics content matrix

This landing page is a sub-product of the
[EvoPhysics content platform](https://github.com/EvoPhysics/evophysics-website).
It shares the design language and analytics stack with the parent site,
and feeds qualified leads into the EvoPhysics tool suite.

### License

MIT — see [LICENSE](LICENSE).

---

## 中文

### 这是什么？

一个**单页落地站**，为 AI 内容自动化服务做销售转化。
产品本体是一项订阅服务：每周一早上，自动把**一周的社媒内容**
（Twitter/X、LinkedIn、Instagram）写好、格式化、配好 hashtag，
直接送到用户邮箱。

这个仓库只承载**销售页**。真正的内容生成流水线在后台，
订阅用户通过邮件 + 微信 onboarding 接入，看不到代码。

### 功能

- **每周一投递** — 一觉醒来，一周 7 条内容已经在邮箱里。
- **模板化生产** — 基于按行业 / 语调调过的 prompt 模板栈批量生成，
  不是"通用 AI 口水文"。
- **跨平台适配** — Twitter/X、LinkedIn、Instagram 一次给齐，
  每条都带 hook、正文、hashtag、CTA。
- **自带日历** — 以"周历"形式交付，10 分钟批量排程。

### 技术栈

- **HTML5** — 单文件，语义化结构，无打包工具。
- **Vanilla CSS** — 内嵌 `<style>`，深色主题，无任何 CSS 框架。
- **零 JavaScript** — 纯静态页，运行时零依赖。
- **零构建步骤** — `index.html` 里写什么，部署出去就是什么。

### 部署

- 托管在 **Cloudflare Pages**。
- 直接从 `main` 分支拉取，无需 CI。
- 自定义域名指向 EvoPhysics 主站下的子路径。

### 商业化定位

本落地站是 [EvoPhysics 内容平台](https://github.com/EvoPhysics/evophysics-website)
旗下**子产品**之一，与主站共用设计语言与数据埋点，
并把高意向线索回流到 EvoPhysics 工具套件。

### License

MIT — 见 [LICENSE](LICENSE)。

---

## Related

- 🌐 EvoPhysics 主站 / Parent site: [EvoPhysics/evophysics-website](https://github.com/EvoPhysics/evophysics-website)
- 📧 联系 / Contact: gu@evophysics.ai
- © 2026 GuYuEngineer
