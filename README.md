# Awesome-Ui-Design-System

# Top UI Design System Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Design Tokens, Component Libraries & Self-Hosted Design System Platforms*  
**Last updated: October 2026**

This repository tracks notable **commercial design system platforms** and **open-source projects** that help teams build, document, and maintain consistent user interfaces — from design token management and component libraries to documentation sites and AI-ready design systems.

**Examples** include Salesforce Lightning Design System, Figma, Zeroheight, Storybook, Supernova, Backlight, Adobe XD, Knapsack, Specify, and Tokens Studio (the category leaders).

**Open-source emphasis**: UI design systems are one of the strongest open-source domains. **Astryx** from Meta brings 150+ accessible components with agent-ready CLI and MCP tooling . **shadcn/ui** delivers copy-paste component architecture that developers own completely . **Storybook** remains the standard for component development and documentation . **Penpot** provides a fully open-source design platform with design tokens and AI workflows . **OpenDesigner** generates complete design systems from AI interviews with DTCG tokens . **Ilse** validates code against design systems with AI-powered insights . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Figma](https://www.figma.com/)**  
  **The industry-standard design platform** — component libraries, variables, and Dev Mode for design-to-code handoff . **The design source of truth for most product teams** . **Best for design collaboration and component management** .

- **[Zeroheight](https://zeroheight.com/)**  
  **Design system documentation platform** — connects Figma and Storybook to create a single source of truth . **~$49/editor/month** for polished, client-facing docs . **Best for external-facing design system documentation** .

- **[Supernova](https://www.supernova.io/)**  
  **Design system platform** — documentation, token management, and automation . **Paid $20+/editor/month** . **Best for end-to-end design system management** .

- **[Backlight](https://backlight.dev/)**  
  **Design system platform** — documentation, component playground, and token management . **Paid $39+/editor/month** . **Best for integrated design system workflows** .

- **[Tokens Studio](https://tokens.studio/)**  
  **Design token management for Figma** — apply, manage, and sync design tokens from Figma to code . **Paid $3+/month** . **Best for token management in Figma** .

- **[Specify](https://specifyapp.com/)**  
  **Design token automation** — centralizes tokens from various sources . **Paid $39+/month** . **Best for automated token workflows** .

- **[Knapsack](https://knapsack.cloud/)**  
  **Design system platform** — connects design and code workflows . **Best for enterprise design system orchestration** .

- **[Salesforce Lightning Design System](https://www.lightningdesignsystem.com/)**  
  **Salesforce's design system** — components, patterns, and guidelines for Salesforce applications . **Best for Salesforce developers** .

## Open-Source GitHub Projects

### Component Libraries & Design Systems

- **[Astryx (Meta)](https://github.com/facebook/astryx)**  
  **Meta's open-source React design system built for people and AI agents**, MIT licensed . **150+ accessible components** with brand-level theming, dark mode, and ready-to-ship templates . **Built on React 19+ and StyleX** — no build plugin required, pre-built CSS with typed React components . **CLI with swizzle command** — eject any component's full source into your project to own and customize . **MCP tooling** for AI assistant integration . **No styling lock-in** — override with Tailwind, CSS modules, or plain CSS via `className` . **Powers 13,000+ apps inside Meta** . **Best for comprehensive React design systems with AI-ready tooling** .

- **[shadcn/ui](https://github.com/shadcn-ui/ui)**  
  **Copy-paste component architecture**, MIT licensed . **Components are copied into your project, not installed as a dependency** — full ownership and customization . **Built on Radix UI and Tailwind CSS** . **The most popular modern React component collection** . **Best for developers wanting complete control over components** .

- **[Material Components](https://github.com/material-components/material-components-web)**  
  **Google's Material Design implementation**, Apache-2.0 licensed with **1.1k+ GitHub stars** . **Web, Android, and iOS implementations** . **The reference implementation for Material Design** . **Best for Material Design applications** .

- **[IBM Carbon](https://github.com/ibm/carbon-components)**  
  **IBM's open-source design system**, Apache-2.0 licensed with **6.2k+ GitHub stars** . **React, Angular, Vue, and Svelte components** . **IBM Design Language implementation** . **Best for enterprise applications** .

- **[GitHub Primer](https://github.com/primer/)**  
  **GitHub's design system**, MIT licensed . **React components, CSS, and design guidelines** . **Powers GitHub's interface** . **Best for GitHub-style applications** .

- **[Chakra UI](https://github.com/chakra-ui/chakra-ui)**  
  **Simple, modular, and accessible React components**, MIT licensed with **40k+ GitHub stars** . **The most popular accessible React component library** . **Best for React applications needing accessibility** .

- **[Evergreen (Segment)](https://github.com/segmentio/evergreen)**  
  **React UI framework from Segment**, MIT licensed with **12k+ GitHub stars** . **Enterprise-grade components** . **Best for enterprise React applications** .

- **[GOV.UK Design System](https://github.com/alphagov/govuk-design-system)**  
  **UK government design system**, MIT licensed with **631+ GitHub stars** . **Accessible, tested components for public services** . **Best for government and public sector applications** .

### Design System Documentation & Tooling

- **[Storybook](https://github.com/storybookjs/storybook)**  
  **The standard for component development and documentation**, MIT licensed . **Build components in isolation, write stories, generate docs automatically** . **Visual testing with Chromatic, interaction testing, and Figma integration** . **Free and open-source** . **Best for front-end engineering teams** .

- **[Penpot](https://github.com/penpot/penpot)**  
  **The open-source design platform**, open-source . **Design as code** — Inspect Mode generates CSS, HTML, SVG code . **W3C design tokens** for design systems at scale . **Penpot MCP Server** for AI agent access to structured design context . **Self-hosted with Docker, Docker Compose, or Kubernetes** . **Best for open-source design collaboration** .

- **[OpenDesigner](https://github.com/ckryptickunal/OpenDesigner)**  
  **Open-source AI design system builder**, open-source . **Load into Claude, ChatGPT, Codex, or Cursor** — interviews you, recommends sourced defaults . **Writes DTCG design tokens, CSS, Tailwind, Figma variables, DESIGN.md, and decision log** with WCAG 2.2 checks . **Built on 352 cited Decision Cards and 25 benchmarked design systems** . **Best for AI-assisted design system creation** .

- **[Ilse](https://github.com/iversondantas/ilse)**  
  **Design quality validator for JSX/TSX projects**, MIT licensed . **Validates against YOUR design system** — not generic rules . **Detects hardcoded tokens, accessibility issues, visual inconsistencies** . **AI-powered insights** for visual hierarchy and semantic issues . **Works with or without design system** . **Skill for Claude Code and MCP server** . **Best for validating code against design systems** .

- **[monkey-doc](https://github.com/monkey-doc/monkey-doc)**  
  **Narrative-first documentation tool**, MIT licensed . **Beautiful alternative to Storybook** — product guides + storytelling . **Built with Vite, React, and MDX** . **Best for product documentation beyond components** .

- **[StoryLite](https://github.com/storylite/storylite)**  
  **Lightweight alternative to Storybook**, open-source . **Supports HTML, React, Preact, Svelte, Vue, and Solid component stories** . **Best for lightweight component documentation** .

### Design Token Tools

- **[Tokens Studio](https://github.com/tokens-studio/figma-plugin)**  
  **Design token management for Figma** — open-source plugin . **Apply, manage, and sync design tokens** . **Best for token management in Figma** .

- **[@bdelanghe/brand-tools](https://socket.dev/npm/package/@bdelanghe/brand-tools)**  
  **Design-system analysis tooling**, open-source . **Token coverage** — every colour in the surface is a token, not a literal . **Content string validation** and **accessibility contrast pairings** . **Page meta checks** . **Best for CI-based design system validation** .

### Additional Strong Open-Source Options

- **Design System Awesome List** — Curated list of open-source design systems including Audi UI, Skyscanner Backpack, Palantir Blueprint, Seek Braid, and more .
- **Radix UI** — Unstyled, accessible components for React .
- **Tailwind UI** — Component library from Tailwind CSS creators (paid) .
- **Panda CSS** — CSS-in-JS with type-safe styles .
- **Histoire** — Storybook alternative for Vite .
- **Baseweb (Uber)** — Uber's design system components .
- **Fluent UI (Microsoft)** — Microsoft's cross-platform design system with 14k+ stars .
- **Geist UI** — Vercel's design system with 3.4k+ stars .
- **ParsiUX** — Persian/RTL design system engine with visual regression for AI coding assistants .

**Frameworks for building custom UI design system solutions**: Combine **Astryx** for comprehensive React design system with 150+ components and agent-ready tooling . Use **shadcn/ui** for copy-paste components with complete ownership . Deploy **Storybook** for component development and documentation . Choose **Penpot** for open-source design collaboration with design tokens . Integrate **OpenDesigner** for AI-assisted design system generation . Use **Ilse** for validating code against your design system . Choose **Tokens Studio** for Figma token management . Note that true enterprise design system platforms with managed documentation, token automation, and external-facing portals (Zeroheight, Supernova, Knapsack) remain primarily commercial territory; open-source stacks provide strong component libraries, documentation tools, and token management foundations that require integration for complete design system operations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Design system platforms handle brand assets and component libraries that may be proprietary. Self-hosted solutions require proper security hardening, access controls, and compliance with licensing requirements.
- **License considerations**: Astryx uses MIT , shadcn/ui uses MIT , Storybook uses MIT , Penpot is open-source , OpenDesigner is open-source , and Ilse uses MIT . Verify licensing against your use case before committing.
- **Design systems require governance** — components, tokens, and documentation must be maintained and versioned. Without ownership and review processes, design systems drift and lose adoption .
- **AI-ready design systems are emerging** — Astryx, OpenDesigner, and Penpot all provide MCP tooling for AI agent integration, enabling agents to build with the same design constraints as humans .
- The open-source ecosystem provides strong component libraries, documentation tools, and token management foundations, but **managed documentation, token automation, and external-facing portals** remain primarily commercial offerings.

---

**Made for design system engineers, front-end architects, and organizations seeking design system sovereignty.**  
Let's make UI design systems more open, transparent, and consistent.
