# Securify — Block All Countries Except Mockup

Interactive HTML prototype for marketing and product review.

## Live demo

**https://connectotp.github.io/securify-block-except-mockup/**

## Design spec (Notion)

**https://app.notion.com/p/37b8f7302dae81318c49c0b31eb12865**

Full design document under Securify → Feature Catalog. Includes user stories, plan gating, Layout A/B comparison, interaction flows, copy, and marketing messaging.

## What to review

Use the **prototype controls** at the top of the mockup page:

| Control | Options |
|---------|---------|
| **Layout** | Option A — Separate card / Option B — Unified picker |
| **Plan** | Free / Pro / Advanced / Growth |
| **Preset** | Empty, US only, US+CA, Active except mode |

### Layout A — Separate card

- Dedicated "Block All Countries Except" card below the map
- Multi-select country search with chips
- Single **Block except** button
- PRO+ badge and upgrade CTA for Free users

### Layout B — Unified picker

- Single country search box with two action buttons:
  - **Restrict selected countries** → blocklist behavior
  - **Restrict all except selected** → except mode (PRO+ only)

### Shared states

- Confirmation modal before applying except mode
- Active-state green banner with Edit / Switch to blocklist
- Inverted map legend in except mode
- Marketing review checklist at page bottom

## Marketing review checklist

1. Which layout do you prefer? (A vs B)
2. Is the confirmation modal copy clear?
3. Is the upgrade CTA compelling for Free users?
4. Are button labels clear enough? (Option B)
5. Any messaging changes for App Store / help docs?
6. Does the active-state summary communicate the policy clearly?

Leave feedback as comments on the [Notion design spec](https://app.notion.com/p/37b8f7302dae81318c49c0b31eb12865).

## Local preview

```bash
cd docs/mockups/securify-block-except-mockup
npx serve . -p 3456
# Open http://localhost:3456/
```

## Share message for marketing head

> Hi — we've prepared a design package for the new **Block All Countries Except** feature on the Block Countries page. Please review:
>
> - **Design spec:** https://app.notion.com/p/37b8f7302dae81318c49c0b31eb12865
> - **Interactive mockup:** https://connectotp.github.io/securify-block-except-mockup/
>
> Use the layout toggle at the top of the mockup to compare Option A (separate card) vs Option B (unified picker with two buttons). Toggle the plan to Free to see the upgrade CTA. Comments welcome directly on the Notion page.
