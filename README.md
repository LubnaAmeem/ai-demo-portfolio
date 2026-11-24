# AI Demo Portfolio — LubnaAmeem

This portfolio is a curated index of third-party open-source projects for customer demos. These are **not** my own original work. Each project keeps its original author, licence, and branding. Forking / customising is allowed only under that project's licence.

> How to use: share this repo link with a customer. Each row links to the original project. For a forked copy, replace the original link with the fork link under `LubnaAmeem/`.

## AI — Chatbots, Media & Content

### Most demanding AI chatbots
- [open-webui/open-webui](https://github.com/open-webui/open-webui) — Self-hosted ChatGPT-style chat UI with RAG, web search, image/voice. ~159,400 stars. Licence: BSD-3-Clause with branding clause — do not strip branding.
- [LibreChat-AI/LibreChat](https://github.com/LibreChat-AI/LibreChat) — Multi-provider ChatGPT clone with agents, MCP, multi-user auth, file/RAG. ~47,500 stars. Licence: MIT — keep licence notice. Cleanest MIT chatbot pick.

### Text-to-Image & Social Graphic Generation
- [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI) — Node-graph engine for Stable Diffusion / Flux / video / 3D / audio. ~148,000 stars. Licence: GPL-3.0 — distributing a modified version must stay GPL-3.0. Model weights have their own licences.

### AI Product Photography & Background Replacement
- [danielgatis/rembg](https://github.com/danielgatis/rembg) — Removes image backgrounds via CLI / Python / HTTP / Docker. ~25,600 stars. Licence: MIT (code). Caution: default BRIA RMBG-2.0 weights need a paid BRIA agreement for commercial use — use `birefnet-general` (MIT) or `u2net` / `isnet-general-use` for client demos.

### Image-to-Video & Automated Short-Form Reels
- [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) — Topic/keyword → finished HD short video: LLM script, stock/AI footage, voiceover, subtitles, music, 9:16/16:9/1:1. ~145,000 stars. Licence: MIT. Note: mainly topic→video with stock footage, not pure image→video.

### Talking Avatar & Lip-Sync Video Generation
- [OpenTalker/SadTalker](https://github.com/OpenTalker/SadTalker) — One portrait photo + audio → talking-head video. ~14,200 stars. Licence: Apache-2.0. Flag: last push 26 Jun 2024 — stale. More maintained alternative: `KwaiVGI/LivePortrait` (~19,500 stars, MIT).

### Multimodal Vision Inspection, Receipt OCR & Screenshot Analysis
- [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) — OCR toolkit: receipts, invoices, tables, screenshots, PDFs → structured text/data, 100+ languages. ~93,100 stars. Licence: Apache-2.0.

### Voice Note Transcription, Translation & Audio Dubbing
- [liuzhao1225/YouDub-webui](https://github.com/liuzhao1225/YouDub-webui) — WebUI for video dubbing: Whisper recognition, subtitle translation, voice cloning, audio mixing. ~5,900 stars. Licence: Apache-2.0.

### Podcast & Long-Form Video Clipping with Auto-Captions
- [ghost1412/shortsflow](https://github.com/ghost1412/shortsflow) — Self-hosted Opus Clip alternative: long podcast/interview → scored, captioned 9:16 Shorts. ~11–18 stars. Licence: MIT. Flag: very new/small community — demo for feature fit, not popularity.

### Dynamic Banner & Thumbnail Creation from Blog/News URLs
- [BahaaShk/ai-thumbnail-generator](https://github.com/BahaaShk/ai-thumbnail-generator) — Full-stack app generating YouTube thumbnails with FLUX. Licence: MIT. Gap: it takes a title, not a blog/news URL — a small URL-fetch → title/summary step would need to be added.

### AI CRM
- [twentyhq/twenty](https://github.com/twentyhq/twenty) — Modern open-source CRM, “open alternative to Salesforce, designed for AI”. ~55,000–60,000 stars. Licence: AGPL-3.0 — hosting it as a service for others triggers source-sharing duties.

### AI Accounts / Finance
- [frappe/erpnext](https://github.com/frappe/erpnext) — Full open-source ERP: accounting, invoicing, bank reconciliation, P&L / balance sheet, stock, sales, projects. ~42,000 stars. Licence: GPL-3.0.

## Industries

### Shipping & Logistics
- [fleetbase/fleetbase](https://github.com/fleetbase/fleetbase) — Modular logistics / supply-chain OS: dispatch, fleet, live tracking, orders, warehousing, finance. ~4,700 stars. Licence: AGPL-3.0 — hosting a modified version for customers triggers source-sharing; a commercial licence is offered for proprietary / white-label use.

### Medical Clinic
- [openemr/openemr](https://github.com/openemr/openemr) — Most popular open-source EHR + practice management: patient records, scheduling, e-prescribing, billing, FHIR. ~5,600 stars. Licence: GPL-3.0. Warning: patient data — software alone is not HIPAA / privacy compliant. Do not load real patient data into a demo.

### Inventory / Stock
- [inventree/InvenTree](https://github.com/inventree/InvenTree) — Open-source inventory system: stock control, part tracking, purchase orders, barcodes, REST API + plugins. ~7,900 stars. Licence: MIT — safest pick in this batch for customising / handing over.

### Hospital Management System
- [ictinnovations/ICTHospital](https://github.com/ictinnovations/ICTHospital) — Hospital system: OPD, appointments, admissions, beds/wards, lab, radiology, pharmacy, billing. ~127 stars. Licence: GPL-3.0. Flag: small community, README says core works but screens are new and not yet proven in production. Change the shipped admin password (`123456`) before any demo with data.

### Patient Management System
- [openmrs/openmrs-core](https://github.com/openmrs/openmrs-core) — Patient-centred EMR platform: longitudinal patient records, encounters, diagnoses, observations. ~2,000 stars. Licence: MPL-2.0 with Healthcare Disclaimer. Flag: this is a platform, not a single turnkey app — a usable demo needs the Reference Application distro / Docker Compose, plus local configuration. Same patient-data warning as OpenEMR.

### School Management System
- [yungifez/skuul](https://github.com/yungifez/skuul) — Multi-school system: students, campuses, attendance, gradebooks, timetables, fees, family portal. ~484 stars. Licence: MIT. Flag: V3 is a rewrite; V2 → V3 upgrade can lose data — install a fresh V3 release tag for a demo.

### Email Automation
- [mautic/mautic](https://github.com/mautic/mautic) — Marketing / email automation: contacts, segments, visual campaign builder, emails, landing pages, forms, lead scoring. ~10,800 stars. Licence: GPL-3.0. Note: it does not send mail itself — needs SMTP / email API + cron jobs.

### WhatsApp Chatbot
- [evolution-foundation/evolution-api](https://github.com/evolution-foundation/evolution-api) — Self-hosted WhatsApp REST API: multi-instance, messages, webhooks, integrations with Chatwoot, Typebot, n8n, OpenAI/Dify. ~10,100 stars. Licence: Apache-2.0 with brand-protection conditions. Warning: Baileys / WhatsApp Web path is unofficial and can risk a ban / ToS issue. For a customer demo, prefer the official Meta Cloud API path it also supports.

### Forex Prediction Chatbot / Trading Bot
- [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) — Multi-agent LLM trading framework: analyst, bull/bear researcher, trader, risk team and portfolio manager debate a ticker and return a decision. ~123,500 stars. Licence: Apache-2.0. Warning — do not present as guaranteed profit: README says research only, not financial / investment / trading advice. Final step is a simulated exchange, not a live broker.

## Licence summary

Safest for customer-facing demo / custom handover: LibreChat (MIT), rembg (MIT code, with model caveat), MoneyPrinterTurbo (MIT), PaddleOCR (Apache-2.0), YouDub-webui (Apache-2.0), shortsflow (MIT), ai-thumbnail-generator (MIT), InvenTree (MIT), Skuul (MIT), TradingAgents (Apache-2.0), Evolution API (Apache-2.0 + brand conditions).

Flagged / copyleft: Open WebUI (BSD + branding), ComfyUI (GPL), Twenty (AGPL), ERPNext (GPL), SadTalker (stale), Fleetbase (AGPL), OpenEMR (GPL), ICTHospital (GPL), Mautic (GPL), OpenMRS (MPL + Healthcare Disclaimer).

Before any fork is shown to a customer: keep the original licence/attribution, do not remove branding where required, and check model-weight / WhatsApp / broker terms separately from code licences.

Star counts are approx. snapshots from GitHub / web search on 24 Nov 2026.
