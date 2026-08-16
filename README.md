# n8n Automations 🤖

**16 production-ready automation workflows** — built with n8n and Groq AI (Replacable by other AI) to handle real business operations: authentication, customer communication, document processing, and lead generation. No manual babysitting required.

Every workflow below is live, tested, and built to the same standard: **trigger → validate → process → branch → respond.** Error paths are handled, not ignored.

---

## 🔐 Authentication Suite

| # | Workflow | What it does |
|---|---|---|
| 1 | **Register** | Signup with duplicate-checking + auto OTP dispatch via email |
| 2 | **Verify OTP** | Time-boxed code validation with expiry enforcement |
| 3 | **Login** | Credential check + verification-status gating |
| 4 | **Forgot / Reset Password** | Full self-service password recovery flow |

## 🤖 AI Communication & Support

| # | Workflow | What it does |
|---|---|---|
| 5 | **AI Email Responder** | Classifies inbound Gmail, drafts replies for genuine inquiries only |
| 6 | **Smart Lead Responder** | Lead-qualification variant of the email engine |
| 7 | **WhatsApp Chat Bot** | Real-time AI conversation over WhatsApp via Evolution API |
| 8 | **Order Notifier + Support Bot** | Sends order updates, auto-answers common questions, escalates the rest to a human |
| 9 | **AI Appointment Booking Bot** | Parses natural-language requests on Telegram, checks live calendar availability, books automatically |

## 📄 Document & Content Intelligence

| # | Workflow | What it does |
|---|---|---|
| 10 | **PDF Summarizer** | Watches a Drive folder, extracts text, delivers structured AI summaries to Google Docs |
| 11 | **Invoice Appender** | Reads PDF invoices, extracts line-item data, logs to Google Sheets |
| 12 | **YT Study Notes** | Turns any YouTube URL into organized study notes in Google Docs |
| 13 | **Daily AI News Digest** | Scheduled news aggregation with editorial-quality Telegram briefings |

## 📈 Growth & Ops

| # | Workflow | What it does |
|---|---|---|
| 14 | **Idea Generator** | Form-triggered content ideation — Twitter-ready output on demand |
| 15 | **Lead Gen Bot** | Enriches raw leads with AI-generated outreach angles, logs to sheet |

## 🧪 Reference

| # | Workflow | What it does |
|---|---|---|
| 16 | **Webhook Test Integration** | Minimal scaffold for clean webhook → external (Python) integration handoff |

---

## Why work with this stack

- **No code required to run** — every workflow is a self-contained n8n import
- **Real error handling** — failure paths return clean, structured responses instead of silent breaks
- **Credential-isolated** — API keys live in n8n's encrypted credential store, not hardcoded in the workflow
- **Built to hand off** — readable node names, logical branching, documented triggers

**Stack:** n8n · Groq (Llama 3.3) · Google Workspace · Telegram · Gmail · WhatsApp

*Want one of these adapted to your business? Every workflow here can be customized to your data, your stack, and your process.*
