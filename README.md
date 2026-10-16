# Awesome-CSS-Frameworks

# Top CSS Frameworks Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Utility-First Styling, Component Libraries & Design Systems*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **CSS Frameworks**. These tools enable developers to build responsive, maintainable user interfaces—from utility-first systems that generate only the CSS you use to component libraries that ship pre-built UI elements out of the box.

**Examples** include Tailwind CSS, Bootstrap, Bulma, Foundation, Material-UI, Chakra UI, Ant Design, Semantic UI, PureCSS, and UIkit (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, utility-first styling, and open component systems—ideal for frontend developers, design engineers, and organizations seeking transparent, vendor-independent styling infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Tailwind Plus](https://tailwindcss.com/plus)**  
  **Premium component library and templates for Tailwind CSS** — the commercial companion to Tailwind CSS. Features **500+ professionally designed UI components**, **full website templates**, and **access to the Tailwind team's design expertise**. **Note**: Closed to new customers as of the Shopify acquisition (September 2026) — existing customers retain access, but the paid tier is no longer available for purchase .

- **[Bootstrap Themes](https://themes.getbootstrap.com/)**  
  **Official premium themes for Bootstrap** — commercial themes built by the Bootstrap team and verified partners. Features **responsive designs**, **documentation**, and **support**.

## Open-Source GitHub Projects

- **[Bootstrap](https://github.com/twbs/bootstrap)**  
  **The most popular HTML, CSS, and JavaScript framework for developing responsive, mobile-first projects on the web** (MIT) — **174,000+ GitHub stars** and **22.4 million weekly npm downloads** . **The safe, predictable choice** — every frontend developer knows Bootstrap, every component is battle-tested, and the documentation is among the best in open source . **Version 5** dropped jQuery, added **CSS custom properties for theming**, introduced a **utility API**, and added **RTL support**. **Strengths**: **pre-built components** (navbar, modals, carousels, accordions, tooltips, offcanvas), **speed-to-market** for admin dashboards and internal tools, and **53 KB gzipped** (CSS + JS) . **Weakness**: the recognizable "Bootstrap look" requires significant CSS overrides to escape . **The reference implementation for component-based CSS frameworks**.

- **[Tailwind CSS](https://github.com/tailwindlabs/tailwindcss)**  
  **A utility-first CSS framework for rapidly building custom user interfaces** (MIT) — **97,789 GitHub stars** and **163 million weekly npm downloads** . **The default choice for new web projects in 2026** — **51% usage in State of CSS 2025** . **Version 4** replaced JavaScript-based configuration with a **CSS-native engine** (`@theme` directives), **dropped PostCSS**, and introduced the **Oxide (Rust) engine** delivering **~5× faster full builds** and **~100× faster incremental builds** . **Key advantage**: the engine only generates CSS for classes found in source files, resulting in **production bundles of 6-12 KB** — versus Bootstrap's 30 KB+ where you ship styles for components you never touch . **Ecosystem**: **shadcn/ui** (copy-paste components), **DaisyUI** (semantic class names), **Headless UI** (accessible unstyled components), **tailwind-merge** (deterministic class conflict resolution), **CVA** (typed variant API) . **The reference implementation for utility-first CSS**.

- **[Bulma](https://github.com/jgthms/bulma)**  
  **Modern CSS framework based on Flexbox** (MIT) — **50,000+ GitHub stars** . **The zero-JavaScript choice** — provides Bootstrap-like components with modern Flexbox layouts but ships **no JavaScript**. Every interactive behavior (dropdowns, modals, tabs) is your responsibility . **Best for**: projects using React, Vue, or any framework where you want full control over interactive behavior.

- **[Foundation](https://github.com/foundation/foundation-sites)**  
  **The most advanced responsive front-end framework in the world** (MIT) — **29,000+ GitHub stars**. **The enterprise choice** — used by Facebook, eBay, Mozilla, and Adobe. Features **responsive grid**, **motion UI**, **email framework**, and **extensive component library**. **Moderate learning curve** but **extensive components** .

- **[Material-UI (MUI)](https://github.com/mui/material-ui)**  
  **React components for faster and easier web development** (MIT) — **the most popular React component library**. Implements **Google's Material Design** with **extensive theming capabilities**, **CSS-in-JS styling**, and **accessible components**. **Best for**: React applications wanting a complete, opinionated design system.

- **[Chakra UI](https://github.com/chakra-ui/chakra-ui)**  
  **Simple, modular and accessible component library for React** (MIT) — **the developer-experience choice**. Features **style props for rapid styling**, **built-in dark mode**, **accessible components by default**, and **theme customization via design tokens**. **Best for**: teams wanting a flexible, accessible React component library with excellent DX.

- **[Ant Design](https://github.com/ant-design/ant-design)**  
  **An enterprise-class UI design language and React UI library** (MIT) — **the enterprise React choice** from Alibaba. Features **60+ components**, **internationalization support**, **theme customization**, and **TypeScript definitions**. **Best for**: enterprise React applications, especially those targeting Chinese markets.

- **[PureCSS](https://github.com/pure-css/pure)**  
  **A set of small, responsive CSS modules** (BSD-3-Clause) — **24,000+ GitHub stars**. **The minimalist choice** — **~3.5 KB gzipped** for the full framework. Features **grid**, **forms**, **menus**, and **tables** without any JavaScript . **Best for**: projects wanting minimal CSS footprint with essential components.

- **[UIkit](https://github.com/uikit/uikit)**  
  **A lightweight and modular front-end framework** (MIT) — **18,000+ GitHub stars**. Features **50+ components**, **JavaScript components**, and **~31 KB gzipped CSS + 53 KB JS** . **Best for**: teams wanting a comprehensive component framework with moderate footprint.

### Additional Strong Open-Source Options

- **[Pico CSS](https://github.com/picocss/pico)** — **Minimal CSS Framework for semantic HTML** (MIT) — **13,700+ GitHub stars** . **The classless choice** — style semantic HTML elements without adding classes. **Best for**: quick prototypes, Markdown-generated sites, and minimal CSS footprint.
- **[DaisyUI](https://github.com/saadeghi/daisyui)** — **The most popular component library for Tailwind CSS** (MIT). **Adds semantic class names on top of Tailwind utilities** — `btn`, `card`, `modal` instead of composing 20 utilities . **Best for**: teams wanting Tailwind's power with pre-built component class names.
- **[shadcn/ui](https://github.com/shadcn-ui/ui)** — **Beautifully designed components you can copy and paste into your apps** (MIT). **The copy-paste model** — Radix UI primitives + Tailwind styling, owned by you, not a dependency . **Most popular React kit 2024-2025** .
- **[Milligram](https://github.com/milligram/milligram)** — **A minimalist CSS framework** (MIT) — **10,200+ GitHub stars** and **~2.3 KB gzipped** . **The smallest full-featured choice**.
- **[Skeleton](https://github.com/dhg/Skeleton)** — **A dead simple, responsive boilerplate** (MIT) — **19,000+ GitHub stars** and **~2.7 KB gzipped** . **Grid + typography only**.
- **[Water.css](https://github.com/kognise/water.css)** — **A drop-in collection of CSS styles to make simple websites just a little nicer** (MIT) — **8,400+ GitHub stars** . **No classes needed** — style semantic HTML automatically.
- **[Spectre.css](https://github.com/picturepan2/spectre)** — **A lightweight, responsive and modern CSS framework** (MIT) — **11,300+ GitHub stars** .
- Community **n8n** workflows for design token synchronization and CSS build automation.

**Frameworks for building custom systems**: Combine **Tailwind CSS** for utility-first styling with **shadcn/ui** for accessible React components, **DaisyUI** for semantic class names, **Headless UI** for unstyled interactive primitives, and **Style Dictionary** for design token transformation—creating a comprehensive modern CSS stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CSS frameworks must respect licensing terms, especially when bundling with commercial applications. **MIT and BSD licenses are permissive**; **GPL and AGPL require source disclosure** for derivative works.
- **The utility-first vs. component-based distinction drives adoption.** **Tailwind CSS** (utility-first) is the default for new projects in 2026 with **51% usage in State of CSS 2025** . **Bootstrap** (component-based) remains the most widely deployed with **74.8% CSS framework market share** . **Choose based on whether you want design freedom or speed-to-market** .
- **Bootstrap's dominance is declining but still substantial.** Market share dropped from **75.3% in October 2025 to 74.8% in October 2026** — a slow but steady erosion . Tailwind grew from **1.3% to 1.8%** in the same period . **Bootstrap remains the safe, predictable choice for enterprise and internal tools** .
- **Bundle size matters more than ever.** **Tailwind produces 6-12 KB** gzipped for typical apps . **Bootstrap ships 53 KB** (CSS + JS) . **PureCSS is 3.5 KB** . **The difference compounds on mobile networks** — every kilobyte affects load time and user experience.
- **The CSS-in-JS landscape has shifted.** **Runtime CSS-in-JS (styled-components, Emotion) is no longer recommended for new RSC projects** — they are incompatible with React Server Components and carry runtime costs . **Zero-runtime CSS-in-TS (vanilla-extract, StyleX, Panda CSS) is the modern alternative** .
- **Tailwind v4 requires modern browsers.** **Safari 16.4+, Chrome 111+, Firefox 128+** — the `@property` and `color-mix()` features it relies on are baseline in these versions . **If you must support pre-2023 browsers, stay on Tailwind v3** .
- Self-hosted open-source solutions require proper build configuration, design token management, and ongoing maintenance. **Frameworks are starting points** — invest in your design system and component conventions.

---

**Made for frontend developers, design engineers, and organizations building transparent CSS solutions.**  
Let's make CSS Frameworks more open, data-driven, and maintainable.
