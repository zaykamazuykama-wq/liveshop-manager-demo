# liveshop-manager-demo — legacy dubbing prototype

Despite the repository name, the current code tree is a **Mongolian dubbing / speaker-voice prototype**, not the canonical Live Shop / Borlo application.

The repository contains reusable dubbing UI and pipeline modules such as:

- `components/dubbing/*`
- `components/speaker-voice/*`
- `lib/dubbing/*`
- `lib/mongolian-voices.ts`
- `lib/voice-matching.ts`

## Canonical destinations

- Dubbing app: `zaykamazuykama-wq/mongol-dub-genie`
- Voice/API service: `zaykamazuykama-wq/mongolian-voice-api`
- Live sales product: `zaykamazuykama-wq/borlo-live-sales-assistant`

Do not add new work here. Useful dubbing modules should be migrated selectively to the canonical dubbing app; unrelated starter/UI duplication should be discarded after validation.

Tracking: `zaykamazuykama-wq/ai-orchestrator#57`
