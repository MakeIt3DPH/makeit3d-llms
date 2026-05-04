# Make It 3D Philippines — AI Knowledge Base

This repository hosts the AI/LLM discovery files for [Make It 3D Philippines](https://www.makeit3dph.com), the Philippines' authorized distributor for premium 3D printers, dental resins, and 3D scanners.

## Files

- **[`llms.txt`](./llms.txt)** — Concise overview following the [llms.txt standard](https://llmstxt.org). Lists brands, collections, featured products, and blog index.
- **[`llms-full.txt`](./llms-full.txt)** — Comprehensive knowledge base with full product specs, brand stories, use case guides, pricing, compatibility reference, and FAQ.
- **[`index.html`](./index.html)** — Landing page for human visitors who land on the subdomain root.
- **`CNAME`** — Custom domain configuration for GitHub Pages (`llms.makeit3dph.com`).

## Live URLs

Once GitHub Pages is enabled and the subdomain is configured:

- https://llms.makeit3dph.com/llms.txt
- https://llms.makeit3dph.com/llms-full.txt

## How to update

1. Edit `llms.txt` or `llms-full.txt` directly on GitHub (web editor) or commit changes via Git.
2. GitHub Pages auto-deploys within 1-2 minutes.
3. No CDN cache busting needed — browsers and AI crawlers will pick up the latest version.

When updating, also:
- Update product/collection lists if the Shopify catalog changes
- Refresh blog post entries when new articles publish
- Update pricing when promotions change
- Refresh the "Last Updated" line at the bottom of each file

## Cross-reference

The llms.txt file references the llms-full.txt file via:
```
For complete product specs, FAQ, use case guides, and detailed brand information,
see the full knowledge base at https://llms.makeit3dph.com/llms-full.txt
```

If the subdomain ever changes, update the cross-reference URL in `llms.txt` to match.

## Related

- Main store: https://www.makeit3dph.com
- Contact: info@m3dsolutions.com | (02) 8800 8853

---

*This repository is for AI agents, LLMs, and search engines. Human shoppers, please visit [makeit3dph.com](https://www.makeit3dph.com).*
