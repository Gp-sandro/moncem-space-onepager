# Moncem one-pager

Static site for `moncem.space`.

## Files

- `index.html` - main one-page landing site
- `styles.css` - shared visual system
- `privacy.html` - public privacy policy URL for App Store Connect
- `support.html` - public support URL for App Store Connect

## Recommended URLs

- `https://moncem.space`
- `https://moncem.space/privacy.html` or route it as `https://moncem.space/privacy`
- `https://moncem.space/support.html` or route it as `https://moncem.space/support`

## Fastest hosting path

Use Cloudflare Pages, Netlify, or Vercel and deploy this folder as a static site.

For Cloudflare Pages:

1. Put this folder in a GitHub repo.
2. Cloudflare Dashboard -> Workers & Pages -> Create -> Pages.
3. Connect GitHub.
4. Build command: leave empty.
5. Output directory: `/`.
6. Add custom domain: `moncem.space`.

## App Store Connect values

- Privacy Policy URL: `https://moncem.space/privacy`
- Support URL: `https://moncem.space/support`
- Marketing URL: `https://moncem.space`

## Manual follow-up

Replace the beta mailto form with a real form when you pick an email/waitlist tool.
Good options: Tally, Fillout, ConvertKit, Buttondown, Beehiiv, or a tiny Supabase Edge Function.
