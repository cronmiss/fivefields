Five fields, one line, and nobody notices when it stops running.

I'm building [cronmiss](https://cronmiss.com): tell it when a scheduled job should run, and it emails you when that run doesn't happen. It's aimed at Vercel Cron, Cloudflare Cron Triggers, GitHub Actions schedules and Supabase pg_cron.

I also write up why serverless crons fail, one platform at a time:

- [Vercel cron job not running? 10 causes and how to check](https://cronmiss.com/guides/vercel-cron-job-not-running/)
- [Cloudflare cron trigger not running? 9 causes to check](https://cronmiss.com/guides/cloudflare-cron-trigger-not-running/)
- [GitHub Actions schedule not running? 9 causes to check](https://cronmiss.com/guides/github-actions-schedule-not-running/) (with real data: a 5-minute schedule GitHub ran 3 times in 23 hours)
- [Supabase cron job not running? 8 causes to check](https://cronmiss.com/guides/supabase-cron-job-not-running/)
- [Railway](https://cronmiss.com/guides/railway-cron-job-not-running/) · [Render](https://cronmiss.com/guides/render-cron-job-not-running/) · [Fly.io](https://cronmiss.com/guides/fly-io-cron-job-not-running/)

Code: [cronmiss on npm](https://www.npmjs.com/package/cronmiss) · [cronmiss on PyPI](https://pypi.org/project/cronmiss/) · [canary](https://github.com/cronmiss/canary)
