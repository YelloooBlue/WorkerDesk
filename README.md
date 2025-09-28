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
