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
  中文介绍
集梦通信 (Jimeng.live) 是领先的出海通信基础设施提供商。我们为跨境电商、游戏出海、Web3 平台以及跨国企业提供高到达率的全球双向短信接口与纯正美国 P2P 实体号码服务。

🌟 核心优势
🇺🇸 美国 P2P 专线与 10DLC 合规：提供 100% 真实美国本地号码，支持高频 P2P 短信收发。全面兼容北美 10DLC 商业报备规范，极大降低拦截率，保障出海营销与通知的送达。

🌍 全球 200+ 国家双向触达：无论您的用户在世界的哪个角落，我们都能提供极速的 OTP 验证码 下发、物流通知以及双向互动回复支持。

⚡ 极简 API 快速集成：毫秒级响应的 RESTful 标准接口。提供详尽的开发文档，最快 10 分钟即可完成联调上线。

💡 核心应用场景 (Use Cases)
Web3 & Crypto (加密货币与 Web3): 快速可靠的全球用户身份验证 (KYC) 与登录 OTP 发送。

Cross-border E-commerce (跨境电商): 订单确认、物流状态实时通知、节日精准营销推送。

Social Apps (出海社交应用): 真实美国号码分配，支持应用内的高频用户私信互动机制。

🔗 Get Started / 立即接入
Register & Get API Key: Visit www.jimeng.live

Customer Support / 商务与技术支持: Contact us on Telegram @qtz123456
