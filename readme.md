# Gurmad AI Business Operator — prototype

Responsive, single-page HTML prototype for the Gurmad AI Business Operator concept.

## Current features
- Overview dashboard with lead/task counts
- Local lead and task management (browser localStorage)
- AI Assistant demo with deterministic local templates
- Marketing copy draft generator (template-based)
- Proposal draft builder
- Responsive desktop/mobile navigation

## Important limitations
This is a front-end prototype, not a production SaaS yet. It does not include authentication, shared database, live AI API, file uploads, billing, real social posting, email/WhatsApp delivery, audit logging, or server-side authorization. Starter records are illustrative. Do not store sensitive customer information in this prototype.

## Netlify deployment
The project needs to be uploaded to or connected with the Netlify site `gurmad-ai-business-operator` before a deploy can be created. The Netlify connector available in this environment can create and inspect sites, but does not expose a source upload/deploy or `agents:create` operation. Once a Git repository is connected, use the Netlify CLI/agent runner to deploy a preview and continue implementation.

For a static preview, publish this directory as the site root; no build command is required.
