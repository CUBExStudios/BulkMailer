# 📧 Bulk Mailer  
### **Open-source alternative to Mailchimp / Brevo / Sendinblue**

A modern, self-hostable email marketing platform that lets you send campaigns, create automations, manage subscribers, and track analytics - 100% open source.

Part of the **OpenGrowthStack**.

---

# 🌟 Features

### 📨 Campaigns
- Drag-and-drop email builder  
- HTML templates  
- Bulk campaign sending  
- Smart scheduling  
- A/B testing  

### 👥 Lists & Subscribers
- Import subscribers (CSV)  
- Tags & segmentation  
- Custom fields  
- GDPR-compliant features  
- Subscription pages + unsubscribe pages  

### ⚙ Automations
- Welcome sequences  
- Drip email campaigns  
- Trigger-based flows  

### 📊 Analytics
- Opens  
- Clicks  
- Bounces  
- Unsubscribes  
- Geolocation (optional)  

### 🌐 Integrations
- SMTP (Sendgrid, Amazon SES, Mailgun, Postmark)  
- Webhooks  
- API for developers  

---

# 🏗 Tech Stack

| Function | Tech |
|----------|------|
| Backend | Python FastAPI or Node.js |
| Frontend | React + Tailwind |
| Worker Queue | Redis / RabbitMQ |
| Email Sending | SMTP / API Provider |
| DB | PostgreSQL |
| Deployment | Docker |

---

# 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/OpenGrowthStack/bulk-mailer.git
cd bulk-mailer
