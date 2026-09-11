# Binnacle — Yacht Broker Dashboard Prototype

An interactive, fully client-side prototype of a KPI dashboard built for yacht sales
brokers — response times, listing sync across marketplaces, deal pipeline, and every
buyer channel (WhatsApp, SMS, call, website, Instagram, email, AI-driven website
visitor identification, and an AI sales rep) in one screen.

**[View the live demo](https://claude.ai/code/artifact/688c7656-8d56-4592-afc0-c63f6fc3c2cb)** · or open `index.html` directly in a browser — no build step, no dependencies.

## What this is

A sales/pitch prototype, not a production app. All data shown is sample data,
clearly labeled as such in the UI. It exists to demonstrate what the real product —
built on top of an n8n automation layer feeding a Supabase/Cloudflare backend — would
show a yacht brokerage once it's live.

## Features demonstrated

- **KPI strip** — inquiries caught, commission protected, listings needing attention (reactive, click-through)
- **Sold Yacht Cleanup** — flags listings still showing live on a marketplace after they sold, with a working "Mark fixed" action
- **Listings & pipeline** — a sortable table and funnel, with full listing detail pages (specs, description, features, per-platform status, performance)
- **Deal pipeline** — a color-coded Kanban view by stage
- **Response speed** — average first-reply time by listing platform
- **Inquiries by channel** — eight channels (WhatsApp, SMS, Call, Website, Instagram, Email, Website Visitor Deanonymization, AI SDR), each with a real drill-through to individual conversations
- **AI draft, human approve** — every outbound message the AI drafts is shown as an editable suggestion; nothing sends without an explicit approval click
- **Full localization** — English, French, Spanish, and Italian, toggle in the header, persisted per browser

## Stack

Single self-contained HTML file. Vanilla JavaScript (no framework, no build step),
hand-tuned CSS with light/dark theme support, Google Fonts (Fraunces, Public Sans,
IBM Plex Mono). Nothing to install — clone and open `index.html`.

## License

Proprietary — built for and owned by Aimamoth. Not for reuse or redistribution.
