# Preet’s Connections

Static Vercel dashboard. No cloud database or login. IndexedDB stores tracking in the current browser profile. Public prospects.json contains researched prospect details and drafted messages, but never private tracking notes. Noindex discourages indexing; this is not access control. GitHub repository is currently public.

## Daily updates
Append new, verified and unique prospects to prospects.json, five based in Dubai and five in the US. Each record needs id (LinkedIn slug), name, region (Dubai or US), niche, location, linkedin (canonical https://www.linkedin.com/in/... URL), source (verified offer page), offer, reason, scoutedAt (YYYY-MM-DD Dubai date), message. Preserve all prior prospects. Bump updatedAt. GitHub commits trigger the linked Vercel deployment. The dashboard merges new IDs only, preserving existing tracking and message edits.

## Setup
Open the production dashboard URL on Preet’s laptop in a normal browser window. Bookmark this exact hostname and use the same profile. Initial data imports automatically. Do not use per-deployment preview URLs, which have separate browser storage. Export a JSON backup weekly and before clearing browser data. Import merges records by id, applying backup tracking to matching people and preserving other records.

Prospects are sourced from public LinkedIn information and offer pages. They are leads, not confirmation of willingness to buy marketing services. Preet’s experience is grounded in the supplied 2026 launch, ads, copywriting and funnel portfolios. Avoid unverified personalisation and performance guarantees.

## Instagram tab
Instagram prospects are in instagram-prospects.json, with schemaVersion:1, updatedAt and prospects. Records use id: ig-HANDLE, platform: Instagram, instagram: canonical HTTPS profile URL with trailing slash, handle, name, region, niche, location, source, offer, reason, scoutedAt and message. Default status: To contact; statuses: To contact, Following, Message sent, Replied, Follow-up, Closed. Include notes and followUp as empty strings in public feed. Append five verified Dubai and five US Instagram profiles, in addition to LinkedIn. Prefer new people across channels and mark overlaps in reason. Instagram drafts are first-contact DMs, with no claim of prior engagement. Existing records without platform are LinkedIn. Backups include both platforms and old LinkedIn backups remain compatible.
