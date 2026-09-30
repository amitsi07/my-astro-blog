# Astro Blog CMS

> Production-grade Astro Blog with Sveltia CMS and Cloudflare Pages deployment.

## Architecture
- **CMS**: [Sveltia CMS](https://github.com/sveltia/sveltia-cms) (Git-based headless CMS located at `/admin`)
- **Hosting**: Cloudflare Pages (Free, global edge CDN caching)
- **Content**: Markdown & Frontmatter in `src/content/blog/`

## Deployment to Cloudflare Pages
1. Go to [Cloudflare Dashboard - Pages](https://dash.cloudflare.com/?to=/:account/pages/new).
2. Click **Connect to Git** and select `Amitsi07/my-astro-blog`.
3. Set **Build command**: `npm run build` and **Build output directory**: `dist`.
4. Click **Save and Deploy**.

## Managing Content with Sveltia CMS
Once deployed, open `https://my-astro-blog.pages.dev/admin` in your browser to publish articles directly!
