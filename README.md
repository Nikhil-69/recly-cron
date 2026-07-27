# recly-cron

Scheduler for [Recly](https://recly-web.vercel.app): a GitHub Actions cron pings the
mail send-batch endpoint every ~10 minutes so queued cold mails go out in small,
Gmail-safe batches through the day. Endpoint + secret are stored as Actions secrets.
