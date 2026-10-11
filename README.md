# Growex dashboard

Set `NEXT_PUBLIC_API_URL` to the deployed API URL (for example, `https://api.growexmedia.in/api`), run `npm install`, then `npm run dev`. It runs at `http://localhost:3001` locally.

For Cloudflare Workers, configure `NEXT_PUBLIC_API_URL` as a **Build variable** and run `npm run deploy`. Attach `admin.growexmedia.in` as a custom domain, then protect it with Cloudflare Access before sharing it. This UI has no application-level authentication yet.
d
