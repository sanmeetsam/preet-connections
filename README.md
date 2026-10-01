# Preet’s Connections

Static Vercel dashboard. No cloud database or login. IndexedDB stores tracking in the current browser profile. Public prospects.json contains researched prospect details and drafted messages, but never private tracking notes. Noindex discourages indexing; this is not access control. GitHub repository is currently public.

## Daily updates
Append new, verified and unique prospects to prospects.json, five based in Dubai and five in the US. Each record needs id (LinkedIn slug), name, region (Dubai or US), niche, location, linkedin (canonical https://www.linkedin.com/in/... URL), source (verified offer page), offer, reason, scoutedAt (YYYY-MM-DD Dubai date), message. Preserve all prior prospects. Bump updatedAt. GitHub commits trigger the linked Vercel deployment. The dashboard merges new IDs only, preserving existing tracking and message edits.

## Setup
Open the production dashboard URL on Preet’s laptop in a normal browser window. Bookmark this exact hostname and use the same profile. Initial data imports automatically. Do not use per-deployment preview URLs, which have separate browser storage. Export a JSON backup weekly and before clearing browser data. Import merges records by id, applying backup tracking to matching people and preserving other records.

Prospects are sourced from public LinkedIn information and offer pages. They are leads, not confirmation of willingness to buy marketing services. Preet’s experience is grounded in the supplied 2026 launch, ads, copywriting and funnel portfolios. Avoid unverified personalisation and performance guarantees.
