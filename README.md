# pramod-kunwar-portfolio — deployed output

Source: https://pramod-kunwar-portfolio.vercel.app (Vercel project `pramodkunwar`, team `acme-acad`)
Pulled: 2026-07-30

## What's in here

This is the **rendered/compiled output actually served in production** — not the
original Next.js/TypeScript source repo. The Vercel MCP tools available to me
(list_projects, get_project, list_deployments, get_runtime_logs,
web_fetch_vercel_url, etc.) don't include an endpoint to download a
deployment's source file tree, and this Vercel project has no Git repository
connected that I could find — so this is the closest thing to "the code" I can
pull through the API.

- `index.html` — server-rendered homepage markup
- `research.html` — server-rendered `/research` page markup
- `_next/static/css/44a9315034601bbc.css` — the full compiled Tailwind CSS bundle
- `_next/static/chunks/app/page-6e1b4c82f7185906.js` — the compiled JS bundle for
  the homepage (minified, but readable — contains the `BlogCard`, `ContactForm`,
  `Reveal`, and `SkillsDiagram` components, plus the Supabase client init)

Not included: the dozens of other webpack chunks (framework/vendor bundles),
font files, and images (`photo.svg`, `og-cover.png`) — say the word if you want
those pulled too.

## What this tells us about the original project

- Framework: Next.js (App Router), React
- Styling: Tailwind CSS
- Backend: Supabase (`gqocryomablqgtqmkqkn.supabase.co` — public anon key only,
  no secrets exposed)
- Content: contact form, `/research` article explorer (currently empty), skills
  diagram, project cards

## Getting the real source instead

If you still have this on your machine, or can find the repo on your GitHub
account, that will always be a better source than this reconstruction —
the actual `.tsx` components, not minified JS. If you find the repo name,
I can pull it straight from GitHub and zip/push that properly.

## Pushing to GitHub

I don't currently have a connected GitHub account with write access in this
conversation, so I can't push commits on your behalf yet. If you want this
pushed to a new repo, either:
1. Connect a GitHub integration/connector, or
2. Give me a personal access token (repo-scope) I can use for this session.

Once one of those is in place, I can create a repo and push this content (or,
better, the real source if we can locate it).
