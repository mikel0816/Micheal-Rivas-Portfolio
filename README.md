[README.md](https://github.com/user-attachments/files/27853071/README.md)
# Michael Rivas — Automation Specialist Portfolio

A personal portfolio website showcasing no-code automation projects built with n8n, Make.com, and Groq AI.

---

## 🚀 Projects Featured

### 1. 📊 AI Weekly Sales Report Bot
**Tools:** n8n · Google Sheets · Groq AI · Gmail

Automatically pulls weekly sales data from Google Sheets, sends it to an AI model that writes a plain-English business summary, and delivers it to the store owner's inbox every Monday at 8am. Zero manual work required.

**Flow:** Schedule Trigger → Google Sheets → Groq AI → Gmail

---

### 2. 💆 Glow Skin Derma Booking Bot
**Tools:** n8n · Telegram · Groq AI

AI-powered Telegram bot named "Sofia" that handles end-to-end appointment booking for a skin clinic. Greets customers, shows services, collects name and phone number, confirms booking — 24/7 with no human involvement.

**Flow:** Customer messages → Sofia greets → Collects details → Confirms booking

---

### 3. 🏠 Real Estate Leads Automation
**Tools:** Make.com · Groq AI · Gmail

Automatically captures real estate leads, processes them through an AI model, and instantly notifies agents with a qualified lead summary. No lead goes cold — response happens in seconds, not hours.

**Flow:** Lead comes in → AI qualifies → Agent notified

---

### 4. 🦷 Dental Clinic Full Automation System
**Tools:** Make.com · n8n · Calendly · Telegram · Gmail · Groq AI

A complete multi-platform automation system for dental clinics. Calendly triggers Make.com which routes events to n8n — handling new bookings (AI confirmation via Telegram + Gmail + reminder) and cancellations/reschedules (separate AI-generated messages for each scenario). Built across two automation platforms connected via webhooks.

**Flow:**
- Calendly → Make.com Router → n8n Webhook → Groq AI → Telegram + Gmail
- Booking path: Confirmation → Wait → Reminder sequence
- Cancel/Reschedule path: If/else logic → separate AI messages per case

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation (self-hosted on Railway) |
| Make.com | Visual automation & multi-scenario routing |
| Groq AI (Llama 3.3) | AI-generated messages & report writing |
| Google Sheets | Data source for sales reporting |
| Gmail | Automated email delivery |
| Telegram | Customer-facing bots & notifications |
| Calendly | Booking trigger for dental system |
| Webhooks | Cross-platform connection between Make & n8n |

---

## 📁 Files

```
portfolio/
├── index.html       # Main portfolio page
└── README.md        # This file
```

---

## 🌐 How to Deploy (GitHub Pages)

1. Create a free account at [github.com](https://github.com)
2. Click **New Repository** → name it `portfolio`
3. Upload `index.html` and `README.md`
4. Go to **Settings** → **Pages**
5. Under Source, select **main branch** → click Save
6. Your live portfolio will be at `https://yourusername.github.io/portfolio`

---

## 📬 Contact

**Michael Rivas**
📧 michealrivas0897@gmail.com

---

*Built with n8n · Make.com · Groq AI*
