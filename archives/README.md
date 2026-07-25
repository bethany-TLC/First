# Claude Brain

Personal archive of LLM conversation exports.

## Contents

- `claude-export/` — Claude.ai data export (conversations, projects, memories, account info), exported 2026-07-25.
  - `claude-export/conversations/` — each Claude conversation split into its own JSON file (named `<date>_<title-slug>_<uuid8>.json`), with `_index.json` listing all of them.
- `chatgpt-export/` — ChatGPT chat exports, added 2026-07-25.
  - `chatgpt-export/conversations/` — every ChatGPT conversation (1,010 total) split into its own JSON file (named `<date>_<title-slug>_<id8>.json`), with `_index.json` listing all of them. Attachments referenced within these chats (images, PDFs, videos, docs) were intentionally not imported to keep this repo focused on conversation text.
  - `chatgpt-export/chat-1.txt` through `chat-25.*` — earlier ad-hoc uploads (screenshots/pasted snippets) from before the full export was available.
