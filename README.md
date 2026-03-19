# 🌍 Jimeng.live API | Global 2-Way SMS & US P2P SMS
**集梦通信 - 专为出海与全球化业务打造的顶级短信网关接口**

[![Official Website](https://img.shields.io/badge/Website-jimeng.live-blue?style=for-the-badge&logo=google-chrome)](https://www.jimeng.live)
[![Telegram Support](https://img.shields.io/badge/Telegram-@qtz123456-0088cc?style=for-the-badge&logo=telegram)](https://t.me/qtz123456)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](#)

[**English**](#english-introduction) | [**中文介绍**](#中文介绍)

---

## English Introduction

**Jimeng.live** provides enterprise-grade SMS API solutions designed for cross-border e-commerce, Web3 projects, and global applications. We specialize in high-delivery-rate global messaging and authentic US local numbers.

### 🌟 Key Features

* 🇺🇸 **Authentic US P2P SMS**: Get real US local numbers supporting high-frequency Person-to-Person (P2P) interactions. Fully compliant with US Carrier **10DLC** regulations to ensure maximum inbox delivery and prevent carrier blocking.
* 🌍 **Global 2-Way Coverage**: Reach users in over 200 countries and regions. Seamlessly deliver **OTP (One-Time Passwords)**, transactional alerts, and marketing campaigns with two-way reply capabilities.
* ⚡ **Developer-Friendly API**: Ultra-low latency RESTful API. Easy to integrate with your existing CRM, App, or Web3 infrastructure in minutes.

### 🚀 Quick Start (cURL)

```bash
curl -X POST [https://api.jimeng.live/v1/sms/send](https://api.jimeng.live/v1/sms/send) \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "to": "+1234567890",
    "from": "+1098765432",
    "text": "Hello! Your OTP is 8899. Powered by Jimeng.live",
    "type": "otp"
  }'
