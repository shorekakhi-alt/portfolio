# Shore Kakhidze — Portfolio

Personal portfolio for Shore Kakhidze, Project Manager. A single HTML file using Tailwind CSS via CDN, published with GitHub Pages.

| Path | What it is |
| --- | --- |
| `index.html` | The live site (Kanban design): ticket hero, CV timeline, award-winning campaigns, client logos, contact form |
| `images/` | Photos, campaign boards and client logos used by the site |
| `drafts/` | The two alternative designs (Notebook, Midnight) and the picker page. Not published (see `_config.yml`) |

## Publishing (GitHub Pages)

Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `claude/affectionate-lamport-70nqr4`, folder `/ (root)`. The site goes live at https://shorekakhi-alt.github.io/portfolio/ and redeploys on every push to that branch.

## Before publishing

Replace the placeholder content (search each file):

- `href="#"` on the LinkedIn / Instagram / TikTok links → your profile URLs
- `hello@shorekakhidze.com` → your real email
- Stats (years, projects, on-time %, people led, budget) and the example projects → your real numbers and work
- Photo placeholders in `v1-notebook.html` (the "SK" polaroid) → an `<img>` of you

## Contact form

Tickets are sent to shorekakhi@gmail.com through [FormSubmit](https://formsubmit.co) — no account or server needed. The very first ticket triggers a one-time activation email from FormSubmit to that inbox; click its confirm link and every ticket after that arrives automatically. The form only works once the site is hosted (or opened in a normal browser), not inside sandboxed previews.
