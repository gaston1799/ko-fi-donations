# Ko-fi Donations

Machine-updated public donation feed for the [Laptop upgrade fund](https://ko-fi.com/gaston1799).

**Schema:** [donations.json](donations.json) -> { goal: {title,target,currency}, donations: [{id,source,type,from,amount,currency,message,date,is_subscription_payment}] }.

- `source`: `"kofi"` (Ko-fi webhooks) or `"github"` (GitHub Sponsors webhooks)
- `type`: `Donation | Subscription | Shop Order | Commission | Sponsorship`
- `amount`: numeric, in `currency` (GitHub Sponsors amounts are USD from `tier.monthly_price_in_cents`)

This repo is updated automatically by the [ko-fi-webhook](https://github.com/gaston1799/kofi-webhook) service on every payment.
