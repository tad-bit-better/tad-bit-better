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

I contribute to UI libraries, state managers, routers and design tools: accessibility, correctness and API work, each with a root cause, a failing test and a reproduction.

**Merged**

- **[react-resizable-panels](https://github.com/bvaughn/react-resizable-panels)**: `vh` / `vw` / `em` panel sizes now resolve against the panel's own window, so popouts and iframes size correctly ([#777](https://github.com/bvaughn/react-resizable-panels/pull/777), released in 4.15.2)
- **[Zag.js](https://github.com/chakra-ui/zag)**:
  - ToC auto-scroll no longer interrupts the smooth scroll to a heading ([#3542](https://github.com/chakra-ui/zag/pull/3542))
  - Splitter `aria-orientation` now matches the separator ([#3553](https://github.com/chakra-ui/zag/pull/3553))
  - Password input visibility toggle: dropped a misleading `aria-expanded`, and the maintainer extended it with keyboard access ([#3555](https://github.com/chakra-ui/zag/pull/3555))
  - Steps: `aria-current` moved from the item wrapper to the tab ([#3529](https://github.com/chakra-ui/zag/pull/3529))
- **[Ark UI](https://github.com/chakra-ui/ark)**: `Field.Root readOnly` now makes FileUpload read-only, across React, Solid, Vue and Svelte ([#4234](https://github.com/chakra-ui/ark/pull/4234))
- **[Matita](https://github.com/matita-dev/icons)**:
  - `--matita-grain` CSS dial for the pencil texture, from solid lines to full paper grain ([#29](https://github.com/matita-dev/icons/pull/29), ships in 0.5.0)
  - Icons with an `aria-label`, `aria-labelledby` or `role` are no longer `aria-hidden` ([#28](https://github.com/matita-dev/icons/pull/28))
- **[File Viewer](https://github.com/flyfish-dev/file-viewer)**: reported toolbar buttons losing keyboard focus, with root cause and fix options ([#419](https://github.com/flyfish-dev/file-viewer/issues/419)). Fixed in 3.3.0 along the approach I proposed.

**In review**

- **[Jotai](https://github.com/pmndrs/jotai)**: `freezeAtom` no longer crashes on circular references or typed arrays; the maintainer opened the PR from my branch ([#3383](https://github.com/pmndrs/jotai/pull/3383))
- **[Excalidraw](https://github.com/excalidraw/excalidraw)**: links to other sites (`//host`, look-alike hosts) no longer open in the editor's tab ([#12482](https://github.com/excalidraw/excalidraw/pull/12482))
- **[TanStack Router](https://github.com/TanStack/router)**: `createMemoryHistory` ignored `initialIndex: 0` and started on the last entry ([#8828](https://github.com/TanStack/router/pull/8828))
- **[Floating UI](https://github.com/floating-ui/floating-ui)**: typeahead skipped the first item after a key with no match ([#3536](https://github.com/floating-ui/floating-ui/pull/3536)); reported items with duplicate labels being unreachable ([#3538](https://github.com/floating-ui/floating-ui/issues/3538))
- **[Matita](https://github.com/matita-dev/icons)**: a `rough` option, from today's pencil to crayon-rough, planned with the maintainer for 0.6.0 ([#22](https://github.com/matita-dev/icons/issues/22))
- **[Material UI](https://github.com/mui/material-ui)**: keep focus when `loading` is set on Button / IconButton ([#49540](https://github.com/mui/material-ui/pull/49540)), now part of a wider discussion on how loading buttons should behave
- **[Oat](https://github.com/knadh/oat)**: dropdown no longer steals focus from an element clicked outside the menu ([#192](https://github.com/knadh/oat/pull/192))
- **[Storybook](https://github.com/storybookjs/storybook)**: reported the sidebar search using the outdated ARIA 1.1 combobox pattern, with a tested fix ([#37030](https://github.com/storybookjs/storybook/issues/37030))

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
