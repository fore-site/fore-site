# 👋 Hi, I'm Oluwaseun!
Backend developer/AI Engineer building with python and everything.

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)](https://github.com/fore-site) [![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white&style=for-the-badge)](https://github.com/fore-site) [![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=for-the-badge)](https://github.com/fore-site) [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=for-the-badge)](https://github.com/fore-site)

---

## Selected work

### [PyCurb](https://github.com/fore-site/pycurb): rate limiting for Python web apps

A framework-agnostic rate-limiting library.

- 5 algorithms, in-memory or Redis storage, sync and async support, dynamic rule updates and composite multi-tier limits.
- Atomic distributed limiting using Redis Lua scripts, with adapters for FastAPI, Flask and Django.
- CI/CD with GitHub Actions and conditional deployment controls, so only tested changes ship.
- **Result:** benchmarked at 25,000+ requests/second with sub-millisecond latency. I estimate it cut endpoint integration time by about 80%.

### [Metrika](https://github.com/fore-site/metrika): web analytics platform

Turns raw site visits into daily reports.

- Event ingestion with bot filtering and location enrichment.
- Daily aggregation of page views, referrers, countries, regions, cities, devices, browsers and operating systems.
- Timezone-aware stats and session metrics: bounce rate, views per visit and duration.
- REST reporting endpoints with Swagger docs, plus a Prometheus metrics dashboard.

### [Tiber](https://github.com/fore-site/tiber): intelligent notification delivery (in development)

Decides when a message should go out, how urgent it is.

- Event-driven on RabbitMQ, with retries, dead-lettering, idempotent processing and provider failover.

### [Pulp](https://github.com/fore-site/pulp): comic and manga store

An e-commerce platform on Django, PostgreSQL and Redis.

- Removed N+1 query patterns on a catalog of 100K+ SKUs.
- **Result:** response time down from about 2.3s to 78ms through query optimization, indexing and Redis caching.
- Paystack payments with webhook testing and transaction-reference verification.

## Smaller projects

- [Twitter/X content scheduler](https://github.com/fore-site/twitter-content-scheduler): a REST API for scheduling tweets.
- [Gmail reply bot](https://github.com/fore-site/gmail-reply-bot): auto-replies to emails with a keyword in the subject, using the Gmail API and Gemini 2.5 Flash.
- [Keep/Cut](https://github.com/fore-site/keep-cut): keep 4, cut 4 for movies, TV and anime.

## Toolbox

| | |
|---|---|
| **Languages** | Python, TypeScript, SQL, Bash |
| **Backend** | Django, FastAPI, Express |
| **Data** | PostgreSQL, SQLite, Redis |
| **Async and queues** | RabbitMQ, Celery, Python-RQ, Redis Queue |
| **Infrastructure** | Docker, GitHub Actions, Prometheus, k6 |
| **Learning now** | scikit-learn, PyTorch |


## Contact

Email: ogunsanu17@gmail.com | X: [@fore_site](https://twitter.com/fore_site)
