# WorkerDesk

[English](#english) | [中文](#中文)

---

## English

### 📌 Introduction
**WorkerDesk** is a **serverless helpdesk system** built with **Cloudflare Workers** and **D1 Database**.  
It allows small businesses and teams to **collect feedback, manage support requests, and embed a ticket form** directly into websites or applications.  
Thanks to Cloudflare’s free tier, it runs at **virtually zero cost** while remaining reliable and scalable.

---

### ✨ Features
- 🛠️ **Serverless & Scalable** – Powered by Cloudflare Workers, no server maintenance needed.  
- 💸 **Zero Cost** – Fits within Cloudflare’s monthly free quota.  
- 🧩 **Embeddable** – Drop-in widget for websites or apps.  
- 🔒 **Reliable** – Runs on Cloudflare’s global edge network.  
- 📊 **Persistent Storage** – Ticket data stored securely in D1 Database.  

---

### 🚀 Getting Started

#### Prerequisites
- [Cloudflare account](https://dash.cloudflare.com/)  
- [Wrangler CLI](https://developers.cloudflare.com/workers/wrangler/)  

#### Installation
```bash
# Clone repository
git clone https://github.com/your-username/workerdesk.git
cd workerdesk

# Configure Cloudflare
wrangler login
wrangler d1 create workerdesk-db

# Deploy
wrangler publish
```

#### Usage
	•	Embed the provided script in your website/app.
	•	Users submit feedback or support requests via the form.
	•	Tickets are stored in D1 Database, accessible via API or dashboard.

---

### 🗺️ Roadmap
	•	Admin dashboard for managing tickets
	•	Email/Slack notifications
	•	Multi-language support
	•	Analytics & reporting
	
---

## 中文

### 📌 简介

WorkerDesk 是一个基于 Cloudflare Workers 与 D1 数据库 构建的 无服务器工单系统。
它帮助中小企业和团队 收集用户反馈、管理支持请求，并可将工单表单直接嵌入到网站或应用中。
借助 Cloudflare 免费额度，该系统能以 几乎零成本 运行，同时具备高可靠性与可扩展性。

---

### ✨ 功能
	•	🛠️ 无服务器 & 可扩展 —— 基于 Cloudflare Workers，无需服务器维护。
	•	💸 几乎零成本 —— 运行在 Cloudflare 每月的免费配额内。
	•	🧩 可嵌入 —— 简单集成到任何网页或应用。
	•	🔒 可靠安全 —— 依托 Cloudflare 全球边缘网络。
	•	📊 持久存储 —— 工单数据安全保存于 D1 数据库。

---

### 🚀 快速开始

#### 环境要求
	•	Cloudflare 账号
	•	Wrangler CLI

#### 安装
```bash
# 克隆仓库
git clone https://github.com/your-username/workerdesk.git
cd workerdesk

# 配置 Cloudflare
wrangler login
wrangler d1 create workerdesk-db

# 部署
wrangler publish
```

#### 使用方法
	•	在网站或应用中嵌入提供的脚本。
	•	用户可通过表单提交反馈或支持请求。
	•	工单将保存到 D1 数据库，可通过 API 或后台管理。

---

### 🗺️ 计划
	•	管理工单的后台面板
	•	邮件 / Slack 通知
	•	多语言支持
	•	数据分析与报表

---
