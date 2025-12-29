

##  1. Internal Infrastructure Costs 
These estimates are based on 2025 API rates for a restaurant doing standard volume.

| Component | Tier 1: Starter (Small) | Tier 2: Business (Large) | Logic & Unit Economics |
| :--- | :--- | :--- | :--- |
| **Monthly Order Vol.** | **Up to 1,000 Orders** | **Up to 6,000 Orders** | Scaling based on traffic. |
| **AWS EC2 (n8n)** | $20.00 | $35.00 | Tier 2 requires higher RAM/vCPU. |
| **OpenAI GPT-4o mini** | $15.00 | $85.00 | 10+ msgs/order + RAG search. |
| **Twilio WhatsApp API** | $45.00 | $210.00 | $0.005/msg + Meta session fees. |
| **OpenAI Whisper** | $10.00 | $50.00 | Voice note processing (30s cap). |
| **Google Sheets** | $0.00 | $0.00 | Free tier usage. |
| **TOTAL MONTHLY COST** | **~$90.00** | **~$380.00** | ** Break-even Point.** |



##  2. Service Pricing (What we charge)
Maintaining  a healthy **50-60% margin** to ensure business sustainability.

| Plan Feature | Tier 1: Starter | Tier 2: Business |
| :--- | :--- | :--- |
| **Setup Fee (One-time)** | **$350** | **$800** |
| **Monthly Subscription** | **$180 / month** | **$750 / month** |
| **Primary Channel** | WhatsApp OR Web Chat | WhatsApp AND Web Chat |
| **Audit Ledger** | Basic | **Advanced Rider Audit** |
| **Support** | Email Support | Priority WhatsApp Support |
| **Over-limit Fee** | $0.15 per order | $0.10 per order |



