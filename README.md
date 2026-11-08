# LinkClipper Monetization

Pricing and the business model. Everything here is subordinate to the product law (README of `linkclipper`): **if it requires an account, it's a redesign** — and its twin: **no selling data, ever.**

## Principles

1. **The core stays free, offline, and accountless.** Monetization can never paywall save/replay/search — that would betray local-first and poison every trust surface (CWS listing, privacy policy, word of mouth).
2. **Users pay for infra and leverage, not for features already on their device.** Storage/bandwidth (hosted sync, public board pages) is a real cost — that's where price belongs first.
3. **No ads. No tracking pixels. No "free tier with analytics".** Ads in a tool people trust with their reading list is self-defeating; this is written to outlive discussion.
4. **Solo-friendly first:** pricing must be simple before discovery exists (Phase C); revisit when data exists.

## Model under evaluation (Decision point: Phase C gate)

| Tier | What | Notes |
|---|---|---|
| Free | Everything local: boards, tags, search, reader, playback, in-page saves, sync to your own Supabase | forever |
| Pro | Hosted sync across devices · public board pages at scale · (Phase D) collab invites · priority support | pays for hosting + moderation load; target self-sustaining, not VC-shaped |
| Patron (optional) | GitHub Sponsors tier, no product difference beyond early previews | exists only because some users ask to support before needing Pro |

Pricing numbers deliberately TBD: set them from real server costs at Phase C, publish the math (margin transparency builds the same trust the privacy posture does).

## What money funds (in order)

1. Managed Supabase/Postgres for hosted sync & share links
2. Moderation tooling the moment public boards exist (see `Knowledgebase/design/social-backend.md`)
3. Security review before Phase C (external, scoped to extension + backend)

## Explicit bans

- Selling/giving/anonymizing-shipping any user data. (Privacy policy already commits to this.)
- Feature-gating via referrer-wall activation checks that phone home per-use.
- Crypto tokens, "AI credits", leaderboards-for-payment.
