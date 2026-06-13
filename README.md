# Open Exchange Rates

Foreign exchange rates REST API providing historical and real-time currency exchange data for 200+ currencies with hourly updates and USD as the default base currency. Trusted by over 100,000 organizations globally, Open Exchange Rates has delivered reliable forex data since 2011 with historical coverage back to January 1, 1999.

**Website:** [https://openexchangerates.org](https://openexchangerates.org)

**Documentation:** [https://docs.openexchangerates.org](https://docs.openexchangerates.org/reference/api-introduction)

**Pricing:** [https://openexchangerates.org/signup](https://openexchangerates.org/signup)

**Status:** [https://status.openexchangerates.org](https://status.openexchangerates.org)

**GitHub:** [https://github.com/openexchangerates](https://github.com/openexchangerates)

## APIs

- **Open Exchange Rates API** — RESTful JSON API delivering live and historical foreign exchange rates for 200+ world and digital currencies.

## Plans

| Plan | Monthly | Requests/Month | Update Frequency |
|------|---------|----------------|-----------------|
| Forever Free | $0 | 1,000 | Hourly |
| Developer | $12 | 10,000 | Hourly |
| Enterprise | $47 | 100,000 | 30 minutes |
| Unlimited | $97 | Unlimited | 5 minutes |
| VIP | Custom | Unlimited | Second-level |

Annual plans include two months free. Non-profit and educational discounts of 20% are available.

## Authentication

Requests are authenticated via an `app_id` query parameter obtained from your Account Dashboard after signing up.

```
GET https://openexchangerates.org/api/latest.json?app_id=YOUR_APP_ID
```

## About This Repository

This repository contains an [APIs.json](https://apisjson.org) profile for Open Exchange Rates, maintained by [API Evangelist](https://apievangelist.com).
