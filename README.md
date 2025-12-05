# 🚀 Dev Resources Library

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GitHub Stars](https://img.shields.io/github/stars/fullsizemalt/dev-resources-library?style=social)](https://github.com/fullsizemalt/dev-resources-library/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/fullsizemalt/dev-resources-library)](https://github.com/fullsizemalt/dev-resources-library/commits/main)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> A curated living library of UI/animation libraries, data visualization tools, frameworks, and spec-driven development resources for rapid project evaluation and prototyping.

## 📚 Table of Contents

- [Overview](#overview)
- [Quick Start](#quick-start)
- [UI & Animation Libraries](#ui--animation-libraries)
- [Data Visualization](#data-visualization)
- [Frameworks & Core Tools](#frameworks--core-tools)
- [Spec-Driven Development](#spec-driven-development)
- [Agentic Workflows](#agentic-workflows)
- [Templates](#templates)
- [Contributing](#contributing)
- [Resources](#resources)

## 🎯 Overview

This repository serves as a comprehensive, living documentation system for evaluating and selecting the right tools for your next project. Whether you're building a data-rich dashboard, an animated marketing site, or a community platform, you'll find curated resources with real-world evaluation criteria.

### Why This Repository?

- **Save Time**: No more endless searches - find the right tool quickly
- **Make Informed Decisions**: Compare libraries side-by-side with clear criteria  
- **Stay Current**: Living documentation that evolves with the ecosystem
- **Learn Best Practices**: Agentic workflows and templates for rapid development
- **Community-Driven**: Contributions welcome to keep this resource valuable

## 🏃 Quick Start

### For Rapid Evaluation

1. Browse the [comparison tables](#ui--animation-libraries) for your use case
2. Check the [Quick Start Guide](docs/QUICKSTART.md) for setup tutorials
3. Use [templates](docs/TEMPLATES.md) to scaffold your project
4. Leverage [agentic workflows](docs/AGENTIC_WORKFLOWS.md) for AI-assisted development

### For Contributors

```bash
# Clone the repository
git clone https://github.com/fullsizemalt/dev-resources-library.git

# Navigate to the directory
cd dev-resources-library

# Check out contributing guidelines
cat CONTRIBUTING.md
```

## 🎨 UI & Animation Libraries

### Shadcn-Style Component Libraries

Perfect for building modern, accessible UIs with copy-paste components.

| Library | Description | Key Features | Best For |
|---------|-------------|--------------|----------|
| [Shadcn UI](https://ui.shadcn.com/) | Re-usable components built with Radix UI and Tailwind CSS | Copy-paste, Fully customizable, Accessible | Production apps, Design systems |
| [Magic UI](https://magicui.design/) | 50+ animated components with Framer Motion | Marquee, Terminal, Orbiting circles | Marketing sites, Portfolios |
| [Motion Primitives](https://motion-primitives.com/) | Animated buttons, cards, modals with Framer Motion | Page transitions, Micro-interactions | Interactive UIs |
| [Animate UI](https://animate-ui.com/) | Fully animated component library | TypeScript, Framer Motion integration | Modern web apps |
| [Cult UI](https://cultui.com/) | Accessible components with animations | Built-in micro-interactions | Full-stack apps |
| [React Bits](https://react-bits.dev/) | Unique text and background effects | Circular text, Glitch effects | Creative projects |

### Traditional UI Frameworks

| Framework | Language | Strengths | Use Cases |
|-----------|----------|-----------|--------|
| [Material UI (MUI)](https://mui.com/) | React | Material Design, Large ecosystem | Enterprise apps, Admin panels |
| [Chakra UI](https://chakra-ui.com/) | React | Developer experience, Accessibility | Rapid prototyping |
| [Ant Design](https://ant.design/) | React | Enterprise components, i18n | Data-heavy dashboards |
| [Mantine](https://mantine.dev/) | React | Highly customizable, 100+ hooks | Complex UIs |
| [Radix UI](https://www.radix-ui.com/) | React | Unstyled primitives, Accessible | Custom design systems |

**📖 [View detailed comparison →](docs/UI_LIBRARIES.md)**

## 📊 Data Visualization

### JavaScript Libraries

| Library | Type | Learning Curve | Best For |
|---------|------|----------------|----------|
| [D3.js](https://d3js.org/) | Low-level | High | Custom visualizations |
| [Plotly.js](https://plotly.com/javascript/) | High-level | Medium | Interactive dashboards, 3D charts |
| [ECharts](https://echarts.apache.org/) | High-level | Medium | Large datasets, Real-time |
| [Visx](https://airbnb.io/visx/) | React primitives | Medium | Custom React charts |
| [Nivo](https://nivo.rocks/) | React | Low | Beautiful animated charts |
| [Recharts](https://recharts.org/) | React | Low | Standard chart types |
| [Victory](https://formidable.com/open-source/victory/) | React | Low | Composable charts |

### Python Libraries

| Library | Best For | Output |
|---------|----------|--------|
| [Matplotlib](https://matplotlib.org/) | Publication-quality static plots | PNG, PDF, SVG |
| [Altair](https://altair-viz.github.io/) | Declarative statistical viz | Interactive HTML |
| [Plotly](https://plotly.com/python/) | Interactive dashboards | HTML, Dash apps |
| [Seaborn](https://seaborn.pydata.org/) | Statistical graphics | PNG, PDF |

**📖 [View detailed comparison →](docs/DATA_VIZ.md)**

## 🛠️ Frameworks & Core Tools

### Full-Stack Frameworks

- **Next.js** - React framework with SSR, SSG, and ISR
- **Remix** - Full-stack React framework with nested routing
- **SvelteKit** - Svelte framework with server-side rendering
- **Nuxt** - Vue.js framework with universal rendering

### Build Tools

- **Vite** - Next-generation frontend tooling
- **Turbopack** - Rust-powered bundler by Vercel
- **esbuild** - Extremely fast JavaScript bundler

### State Management

- **Zustand** - Small, fast, scalable state management
- **Jotai** - Primitive and flexible state for React
- **Redux Toolkit** - Official Redux toolkit
- **TanStack Query** - Data synchronization for React

**📖 [View full framework guide →](docs/FRAMEWORKS.md)**

## 📋 Spec-Driven Development

### Core Tools

#### GitHub Spec Kit
The leading open-source toolkit for spec-driven development.

```bash
# Install Specify CLI
npm install -g @github/specify-cli

# Initialize a new spec
specify init my-project
```

**Features:**
- Spec templates for breaking down projects
- AI agent-friendly task formats
- Progress tracking and validation
- Integration with GitHub Issues

#### Storybook
Document and develop UI components in isolation.

```bash
npx storybook@latest init
```

### Design System Documentation

- [Carbon Design System](https://carbondesignsystem.com/) (IBM)
- [Material Design 3](https://m3.material.io/) (Google)
- [Polaris](https://polaris.shopify.com/) (Shopify)
- [Lightning Design System](https://www.lightningdesignsystem.com/) (Salesforce)

**📖 [View spec-driven workflow →](docs/SPEC_DRIVEN.md)**

## 🤖 Agentic Workflows

Leverage AI agents for rapid development with these proven prompts and patterns.

### Quick Prompts

#### 🎨 UI Development
```
Create a responsive landing page using Shadcn UI components with:
- Hero section with animated gradient background
- Feature cards with hover effects  
- Pricing table with toggle for monthly/yearly
- Newsletter signup form with validation

Use Next.js, TypeScript, and Tailwind CSS.
```

#### 📊 Data Visualization
```
Build an interactive dashboard using Recharts that displays:
- Revenue trends (line chart)
- Category distribution (pie chart)
- User growth (area chart with gradient)
- Key metrics cards

Data source: PostgreSQL via Prisma. Add filtering by date range.
```

#### 🔧 Component Creation
```
Create a reusable Modal component following Shadcn patterns:
- Uses Radix UI Dialog primitive
- Supports multiple sizes (sm, md, lg, xl)
- Includes header, body, footer sections
- Accessible keyboard navigation
- TypeScript with proper prop types
```

**📖 [View full agentic workflow guide →](docs/AGENTIC_WORKFLOWS.md)**

## 📦 Templates

Ready-to-use project templates for common scenarios.

### Available Templates

- **[shadcn-starter](templates/shadcn-starter/)** - Next.js + Shadcn UI + TypeScript
- **[dashboard-template](templates/dashboard-template/)** - Admin dashboard with charts
- **[landing-page](templates/landing-page/)** - Marketing site with animations  
- **[saas-starter](templates/saas-starter/)** - Full SaaS boilerplate
- **[docs-site](templates/docs-site/)** - Documentation site with search

### Using Templates

```bash
# Clone specific template
git clone --depth 1 --filter=blob:none --sparse \
  https://github.com/fullsizemalt/dev-resources-library.git

cd dev-resources-library
git sparse-checkout set templates/shadcn-starter
```

**📖 [View all templates →](docs/TEMPLATES.md)**

## 🤝 Contributing

Contributions make this library valuable! Whether it's adding a new library, updating documentation, or sharing templates, we welcome your input.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-addition`)
3. Commit changes (`git commit -m 'Add amazing library'`)
4. Push to branch (`git push origin feature/amazing-addition`)
5. Open a Pull Request

### Contribution Guidelines

- Follow the [library evaluation template](.github/LIBRARY_TEMPLATE.md)
- Include comparison data and use cases
- Add screenshots where applicable
- Update the table of contents
- Test any code examples

**📖 [Read full contributing guide →](CONTRIBUTING.md)**

## 📚 Resources

### Community

- [Awesome Shadcn UI](https://github.com/birobirobiro/awesome-shadcn-ui)
- [Design Systems Repo](https://designsystemsrepo.com/)
- [Component Gallery](https://component.gallery/)

### Learning

- [Learn Spec-Driven Development](https://github.com/github/spec-kit/wiki)
- [React Patterns](https://reactpatterns.com/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)

### Tools

- [Can I Use](https://caniuse.com/) - Browser compatibility
- [Bundlephobia](https://bundlephobia.com/) - Package size analysis
- [Component Party](https://component-party.dev/) - Framework comparison

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Show Your Support

If this repository helped you, please consider giving it a star! It helps others discover these resources.

---

**Made with ❤️ by the community** | [Report Issue](https://github.com/fullsizemalt/dev-resources-library/issues) | [Request Feature](https://github.com/fullsizemalt/dev-resources-library/issues/new?template=feature_request.md)
