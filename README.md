# Hi, I'm Pushpendra 👋

Staff-level frontend engineer with ~12 years of building web products. I work on frontend architecture: component systems, monorepos, performance and accessibility. I also lead teams and build AI-powered product experiences.

- 🏗️ Led the frontend for a conversational assistant: streaming bot responses, rich action cards, in-chat webviews for web, Teams and Slack, and bot-to-human handoff
- 🧩 Moved a fork-a-new-copy component culture to one shared library: deprecated and removed v1/v2/v3 duplicates, and built an MCP-based Figma-to-code pipeline that reuses it
- ⚙️ Migrated Webpack 4 → 5 with codemods and cut tech debt by ~75%
- 👥 Managed pods of 5–6 engineers for 5+ years (hiring, reviews, promotions) and kept ~80% of the original team through my tenure

## 🚀 What I'm building

| Project | What it is | Under the hood |
|---|---|---|
| [**BecauseILiked**](https://becauseiliked.com) | Tell it what you loved *and why*; get films, shows, books and games back with a reason each one fits | Next.js, Supabase + pgvector, embeddings + RAG with streaming LLM explanations, ~13.8k-title catalog |
| [**Thumbline**](https://thumbline.app) · [repo](https://github.com/tad-bit-better/thumbline) | Upload a song clip, get fingerstyle / arpeggio / flamenco right-hand sheets at three skill levels, with playback | Nx monorepo, audio processing to notation |
| [**VitalDelta**](https://vitaldelta.app) · [repo](https://github.com/tad-bit-better/vitaldelta) | Turns lab reports into trend charts, so you can show your doctor how your numbers move over time | Local-first: reports never leave your device; Chart.js |

## 🌍 Open source

I mostly contribute accessibility and interaction fixes to UI libraries, each with a root cause, tests and a reproduction. Some of my recent contributions include -

- **[Zag.js](https://github.com/chakra-ui/zag)**, merged:
  - ToC auto-scroll no longer interrupts the smooth scroll to a heading ([#3542](https://github.com/chakra-ui/zag/pull/3542))
  - Splitter `aria-orientation` now matches the separator ([#3553](https://github.com/chakra-ui/zag/pull/3553))
  - Password input visibility toggle: dropped a misleading `aria-expanded`, and the maintainer extended it with keyboard access ([#3555](https://github.com/chakra-ui/zag/pull/3555))
- **[Material UI](https://github.com/mui/material-ui)**: keep focus when `loading` is set on Button / IconButton ([#49540](https://github.com/mui/material-ui/pull/49540)). Referenced in MUI's WCAG 2.2 conformance work for IconButton.
- **[File Viewer](https://github.com/flyfish-dev/file-viewer)**: reported toolbar buttons losing keyboard focus, with root cause and fix options ([#419](https://github.com/flyfish-dev/file-viewer/issues/419)). Fixed in 3.3.0 along the approach I proposed.
- **[Storybook](https://github.com/storybookjs/storybook)**: reported the sidebar search using the outdated ARIA 1.1 combobox pattern, with a tested fix ([#37030](https://github.com/storybookjs/storybook/issues/37030)).

## 🛠️ Stack

**Core:** TypeScript · React · Next.js · Nx monorepos · GraphQL · Storybook
**Styling:** styled-components / Emotion · Sass / CSS Modules · Tailwind
**Testing:** Playwright · Vitest / Jest · axe
**AI & data:** embeddings · RAG · pgvector · Supabase · Postgres
**Also:** Node.js · Webpack / Vite · enterprise SSO (SAML / OIDC)

## 💬 Talk to me about

Frontend architecture at scale, design systems and component APIs, accessibility (WAI-ARIA / WCAG), monorepos, and building AI features that feel good to use.

## 🔗 Connect

[Portfolio](https://www.pushpendra.dev/) · [LinkedIn](https://www.linkedin.com/in/pushpendrayadav2011/) · pushpendra.y2011@gmail.com
