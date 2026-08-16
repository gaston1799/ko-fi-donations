# Ko-fi Donations

Machine-updated public donation feed for the [Laptop upgrade fund](https://ko-fi.com/gaston1799).

**Schema:** [donations.json](donations.json) -> { goal: {title,target,currency}, donations: [{id,type,from,amount,currency,message,date,is_subscription_payment}] }.

This repo is updated automatically by the [ko-fi-webhook](https://github.com/gaston1799/kofi-webhook) service on every payment.
