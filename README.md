# Granola (granola)

Granola is an AI notepad for back-to-back meetings. It captures audio directly from the user's computer (no meeting bot), enhances handwritten notes with AI, and supports post-meeting tasks like follow-up drafting, action item extraction, and chat over the transcript. Works across Zoom, Google Meet, Webex, Microsoft Teams, and Slack. Granola exposes a public Granola API (Business and Enterprise plans) for programmatic access to notes, transcripts, and folders, plus an MCP server for conversational AI clients. Webhooks are on the roadmap; Zapier covers event-style automation today.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/granola/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/granola/refs/heads/main/apis.yml)

## Tags

- AI
- Meeting Notes
- Transcription
- Productivity
- API
- MCP
- Zapier
- Business
- Enterprise

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Granola Desktop & Mobile App

Consumer desktop app (macOS / Windows) and iPhone app that records meeting audio locally, enhances notes with AI, and supports customizable templates for different meeting types.

- **Human URL:** [https://www.granola.ai/](https://www.granola.ai/)
- **Base URL:** `https://www.granola.ai`

#### Tags

- Consumer
- Desktop
- Mobile
- Templates

#### Properties

- [Product Page](https://www.granola.ai/)
- [Integrations Guide](https://www.granola.ai/blog/granola-integrations-complete-guide-connecting-meeting-tools)
- [Postman Collection](collections/granola.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/granola.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Granola Public API

REST API for programmatic access to meeting notes, transcripts, AI summaries, and folders. Authentication is Bearer token using API keys prefixed with `grn_`, created in Settings → Connectors → API keys. Requires Business or Enterprise plan. Endpoints include GET /notes, GET /notes/{id}, and GET /folders. Rate limits are 25 requests burst / 5 requests per second sustained. Webhooks are on the roadmap; current pattern is polling.

- **Human URL:** [https://docs.granola.ai/help-center/sharing/integrations/granola-api](https://docs.granola.ai/help-center/sharing/integrations/granola-api)
- **Base URL:** `https://public-api.granola.ai/v1`

#### Tags

- REST
- API Key
- Bearer Token
- Notes
- Transcripts
- Folders

#### Properties

- [Documentation](https://docs.granola.ai/introduction)
- [A P I Docs](https://docs.granola.ai/help-center/sharing/integrations/granola-api)
- [Docs Index](https://docs.granola.ai/llms.txt)
- [Launch Announcement](https://www.createwith.com/tool/granola/updates/granola-launches-api-to-connect-meeting-notes-with-ai-agents-and-external-tools)
- [Postman Collection](collections/granola.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/granola.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Granola Zapier Integration

Zapier integration for event-style automation connecting Granola to 8,000+ apps. Useful for webhook-like patterns until Granola ships native webhooks.

- **Human URL:** [https://zapier.com/apps/granola/integrations](https://zapier.com/apps/granola/integrations)
- **Base URL:** `https://zapier.com`

#### Tags

- Zapier
- Automation
- Webhooks
- Integration

#### Properties

- [Zapier App](https://zapier.com/apps/granola/integrations)
- [Webhook Connector](https://zapier.com/apps/granola/integrations/webhook)
- [Postman Collection](collections/granola.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/granola.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/granola-ai)
- [Website](https://www.granola.ai/)
- [Documentation](https://docs.granola.ai/introduction)
- [A P I Docs](https://docs.granola.ai/help-center/sharing/integrations/granola-api)
- [Blog](https://www.granola.ai/blog)
- [Plans](plans/granola-plans-pricing.yml)
- [Rate Limits](rate-limits/granola-rate-limits.yml)
- [Fin Ops](finops/granola-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
