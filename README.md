# all_deck

Private collection of research presentation decks.

Each subfolder contains an `index.html` that is auto-deployed to Cloudflare Pages.

## Decks

| Folder | Topic | URL Path |
| --- | --- | --- |
| `Anthropic_OpenAI_JV_research/` | Anthropic & OpenAI × PE JV mentor call deck | `/Anthropic_OpenAI_JV_research/` |

## Workflow

1. Add a new folder under root: `{topic_name}/index.html`
2. `git add . && git commit -m "add: {topic}" && git push`
3. Cloudflare Pages auto-deploys; share URL `https://<site>.pages.dev/{topic_name}/`
