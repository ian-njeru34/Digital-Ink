# Digital Ink — beginner starter

This is a simple, no-build website that can be hosted on Vercel from GitHub and uses Supabase for enquiry storage.

## Files
- `index.html` — public website
- `style.css` — design
- `config.js` — Supabase URL/key
- `admin.html` — starter enquiry viewer
- `supabase.sql` — database setup

## IMPORTANT SECURITY
Use only the Supabase browser-safe ANON/PUBLISHABLE key in `config.js`. NEVER use a service_role/secret key.

The included public admin page is a starter only. Before using it with real customer data, add Supabase Auth and an authenticated admin policy.

## Quick setup
1. Create a Supabase project.
2. Open SQL Editor and run `supabase.sql`.
3. Copy Project URL and the browser-safe anon/publishable key.
4. Paste them into `config.js`.
5. Create a GitHub repository and upload all files.
6. Import the GitHub repository into Vercel.
7. Deploy.
8. Open your Vercel URL and test the enquiry form.

## Customize
Replace "Digital Ink" with your company name in `index.html` and `admin.html`.
Change the prices and services in the Pricing section.
