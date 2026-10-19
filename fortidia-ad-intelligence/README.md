# Fortidia Ad Intelligence

A Next.js dashboard starter for researching competitor and franchise recruitment advertising.

## Run locally

```bash
npm install
npm run dev
```

## Deploy to Vercel

1. Extract the project and push its contents to a GitHub repository.
2. In Vercel, choose **Add New → Project**, import the repository and deploy. Next.js is detected automatically.
3. Open the deployed URL.

## Included

- Overview dashboard, watchlist and competitor management
- LinkedIn Ad Library and Google Ads Transparency Centre source links
- Add and search verified advert observations; filter by brand, market and category
- Dedicated franchise recruitment view
- CSV export, report preview, weekly email preference form
- Responsive layout

## Important limitations

This is a functional **front-end starter**, not a live data ingestion or email delivery service. Records, competitors and email preferences are stored in the current browser's localStorage. They are not shared across devices or users. No weekly emails are sent. The watchlist consists of suggested research targets, not observed adverts.

For production, implement authentication, persistent database (e.g. Vercel Postgres-compatible provider), server-side verified observation ingestion, approved data access for the two advertising transparency libraries, Vercel Cron, and an email provider such as Resend. Do not scrape these platforms in breach of their access terms. Avoid exposing email recipients or API keys in client code.
