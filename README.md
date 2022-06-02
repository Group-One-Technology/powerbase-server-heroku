# Powerbase

[Powerbase](https://trypowerbase.com) is the missing bridge to the worlds most trusted relational database.

## Pre-requisites

- [AWS RDS](https://aws.amazon.com/rds/free/) - A PostgreSQL instance is needed so that Powerbase will be able to create databases and roles. Note: Amazon RDS has a free tier.
- SMTP Service - The SMTP is used for sending emails to users. Note: You may want to try out [Postmark](https://postmarkapp.com/)'s free trial.

Checkout [our documentation](https://powerbase.notaku.site/Deploying-Powerbase-to-Heroku-Vercel-c3f24a07f9c84929a625faa971961984) on details to get you up and running.

## Deploying Powerbase Server on Heroku

You can checkout Powerbase by deploying it on [Heroku](https://heroku.com). This uses free tier add-ons in running the app so that you can **deploy Powerbase for free**. The ff services are used:
- PostgreSQL
- Redis
- Bonsai Elasticsearch
- Pusher Channel

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

For production or long-term use of Powerbase, we recommend some upgrades to avoid the limitation of Heroku's free tier. You can read more at [our documentation](https://powerbase.notaku.site/Deploying-Powerbase-to-Heroku-Vercel-c3f24a07f9c84929a625faa971961984)

