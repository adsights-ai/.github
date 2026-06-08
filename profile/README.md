# AdSights

<p align="center">
  <img src="https://www.adsights.ai/logo.png" alt="AdSights Logo" width="200"/>
</p>

<p align="center">
  <strong>AI-Powered Creative Analytics for Better Ad Performance</strong>
</p>

<p align="center">
  <a href="https://www.adsights.ai">Website</a> •
  <a href="https://www.adsights.ai/request-access">Request Access</a> •
  <a href="https://www.adsights.ai/frameworks">Frameworks</a> •
  <a href="https://www.adsights.ai/pricing">Pricing</a> •
  <a href="https://www.adsights.ai/blog">Blog</a> •
  <a href="https://www.adsights.ai/resources">Resources</a>
</p>

<p align="center">
  <a href="https://twitter.com/adsightsai"><img src="https://img.shields.io/twitter/follow/adsightsai?style=social" alt="Twitter Follow"></a>
  <a href="https://www.linkedin.com/company/adsights-ai/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue" alt="LinkedIn"></a>
  <a href="https://www.youtube.com/@AdSights"><img src="https://img.shields.io/badge/YouTube-Subscribe-red" alt="YouTube"></a>
  <a href="https://www.adsights.ai/frameworks/ads-framework"><img src="https://img.shields.io/badge/Framework-%40adsights--ai%2Fads--framework-7C3AED" alt="Ads Framework"></a>
</p>

---

## 🎯 About AdSights

AdSights is an AI-powered creative analytics platform that revolutionizes how advertisers optimize ad performance through data-driven insights, creative testing, and predictive modeling. We help marketers make smarter decisions that increase ROI and campaign effectiveness.

### What We Do

- **🎨 Creative Analytics**: Deep analysis of ad creative elements to understand what drives performance
- **📊 Performance Insights**: Real-time tracking and benchmarking across campaigns and platforms
- **🤖 AI-Powered Analysis**: Multi-modal understanding of video, image, and text content
- **📈 Predictive Modeling**: Forecast creative performance before launch
- **🔄 Creative Testing**: A/B testing framework with statistical significance
- **🎯 Optimization**: Data-driven recommendations for creative improvement
- **🎬 Programmatic Ad Production**: Code-defined, brand-consistent video ads in 12 platform formats (see [Ads Framework](#-adsights-ads-framework-new))

## 🚀 Key Features

- **Visual Ad Intelligence**: Advanced computer vision to analyze creative elements
- **Cross-Channel Analytics**: Unified insights across Facebook, Google, TikTok, and more
- **Competitive Benchmarking**: Compare your creatives against industry standards
- **Creative Performance Metrics**: Track CTR, engagement, conversions by creative element
- **Automated Insights**: AI-generated recommendations for creative optimization
- **ROI Tracking**: Connect creative performance to business outcomes

## 🛠️ Built With

- **[Next.js 16](https://nextjs.org)** — Modern React framework with App Router
- **[TypeScript](https://www.typescriptlang.org)** — Type-safe development
- **[TailwindCSS](https://tailwindcss.com)** — Utility-first styling
- **[Remotion](https://www.remotion.dev)** — Programmatic video for the Ads Framework
- **[Stripe](https://stripe.com)** — Checkout + automatic tax + dispute handling
- **[Vercel](https://vercel.com)** — Hosting, Postgres, KV rate limiting
- **[Postmark](https://postmarkapp.com)** — Transactional email (templates-as-code)
- **AI/ML Models** — Proprietary creative analysis algorithms
- **Analytics & Tracking** — Google Analytics 4, custom event tracking

## 💡 Use Cases

- **DTC brands** running 50+ ad variants per week across Meta + TikTok
- **Performance agencies** producing white-label creative at scale
- **App marketers** localizing ad packs across 12 platform formats
- **CTV / streaming buyers** needing broadcast-safe 1080p output
- **In-house creative teams** wanting brand-tokenized output without designer bottlenecks
- **Affiliate marketers** A/B testing concept variants programmatically

## 🌐 Our Ecosystem

### Products & Tools
- **[AdSights Platform](https://www.adsights.ai)** - Main analytics platform
- **[Frameworks Hub](https://www.adsights.ai/frameworks)** - Both agentic frameworks + their skills-only tiers (one-time purchase, lifetime updates)
- **[Ads Framework](https://www.adsights.ai/frameworks/ads-framework)** - Programmatic video ad production ($199 USD) · [Ads Skills for Claude](https://www.adsights.ai/frameworks/ads-skills) ($99, no-code)
- **[Email Framework](https://www.adsights.ai/frameworks/email-framework)** - Agentic lifecycle email production ($149 USD) · [Email Skills for Claude](https://www.adsights.ai/frameworks/email-skills) ($79, no-code)
- **[Resource Center](https://www.adsights.ai/resources)** - Free marketing guides and templates
- **[Interactive Tools](https://www.adsights.ai/resources/tools)** - Calculators, quizzes, and generators
- **[Blog](https://www.adsights.ai/blog)** - Marketing insights and best practices

### Community & Learning
- **[Marketing Glossary](https://www.adsights.ai/resources/glossary)** - Comprehensive marketing terms
- **[Metric Comparisons](https://www.adsights.ai/resources/comparisons)** - Side-by-side breakdowns (MER vs ROAS, Hold Rate vs ThruPlay, and more)
- **[Guides & Tutorials](https://www.adsights.ai/resources/guides)** - Step-by-step learning resources

## 🎬 AdSights Ads Framework (new)

The **[AdSights Ads Framework](https://www.adsights.ai/frameworks/ads-framework)** is a code-first, [Remotion](https://www.remotion.dev)-based ad production framework for teams that need to ship hundreds of brand-consistent variants without a designer in the loop for every one.

| Package | Description |
|---|---|
| `@adsights-ai/ads-framework` | Typed brand-token engine, 12-format registry with platform-specific safe-area insets, deterministic RNG, captions + voiceover modules |
| `@adsights-ai/ads-cli` | Render orchestrator — `ads render`, `render-all`, `list`, `generate-voiceover`, `snapshot`, `demo-render` |
| `@adsights-ai/ads-studio` | Remotion Studio host for interactive concept iteration |
| `create-adsights-ads` | One-command scaffolder — `npx create-adsights-ads@latest` |

**8 ad concepts × 12 platform formats** — product-showcase, before-after, testimonial-quote, sale-promo, talking-head-UGC, stat-reveal, comparison-vs, listicle. Each renders to social squares, stories, reels, TikTok, Pinterest, YouTube Shorts, YouTube pre-roll, X video, LinkedIn feed, and CTV-1080p with platform-specific safe-area insets.

📖 **[Read the Framework Docs →](https://www.adsights.ai/frameworks/ads-framework/setup)**

## 🛠️ Claude Code Skills

Twelve [Claude Code](https://claude.com/claude-code)-compatible skills ship with the Ads Framework — frontmatter-spec compliant, model-pinned, with allowed-tools allowlists:

| Skill | What it does |
|---|---|
| `/video-init` | Bootstrap a new ads project |
| `/ads-quickstart` | Guided first render in under 5 minutes |
| `/storyboard` | Concept → storyboard scenes |
| `/create-ad` | Build a new concept against the brand-token schema |
| `/create-ad-template` | Author a reusable template |
| `/multi-size-render` | Render one concept across all 12 platform formats |
| `/ads-copy` | Generate on-brand ad copy + captions |
| `/voiceover` | Script + synthesize voiceover audio |
| `/asset-pack` | Bundle assets with provenance + license tracking |
| `/video-review` | Fork to an `ads-reviewer` agent for QA |
| `/skill-bake` | Compile project rules into a custom skill |
| `remotion-best-practices` | Reference skill — full 36-rule Remotion docs |

The three skills marked *Portable* work standalone in any Claude Code workspace.

📖 **[Browse the Skills Catalog →](https://www.adsights.ai/frameworks/ads-framework/skills)**

## 📧 AdSights Email Framework (new)

The **[AdSights Email Framework](https://www.adsights.ai/frameworks/email-framework)** is the lifecycle-email counterpart to the Ads Framework — a [React Email](https://react.email)-based engine you drive with Claude Code to ship inbox-safe, on-brand lifecycle emails without hand-tuning Outlook HTML.

| Package | Description |
|---|---|
| `@adsights-ai/email-framework` | Brand-token-aware React Email components, a 4-client render matrix (Apple Mail, Gmail, Outlook/MSO, dark mode), inlined Outlook-safe HTML + plaintext alternatives |
| `@adsights-ai/email-cli` | Render orchestrator for the lifecycle template set |
| `create-adsights-email` | One-command scaffolder — `npx create-adsights-email@latest` |

**6 lifecycle templates** (welcome, promo, product-launch, abandoned-cart, newsletter, winback) × a 4-client render matrix, with **8 Claude Code skills + 1 review agent** for the full brief→rendered-email loop. **$149 USD** (one-time, lifetime updates) — or the no-code **[Email Skills for Claude](https://www.adsights.ai/frameworks/email-skills)** bundle at **$79**.

📖 **[Read the Email Framework Docs →](https://www.adsights.ai/frameworks/email-framework/setup)**

## 📚 Resources

Explore our growing collection of free resources:

- **Calculators**: ROI, budget, and performance calculators
- **Quizzes**: Test your marketing knowledge
- **Generators**: Creative brief and campaign planning tools
- **Templates**: Ready-to-use marketing frameworks
- **E-books**: In-depth guides on creative analytics

## 🤝 Connect With Us

Stay updated with the latest in creative analytics and advertising:

- **Website**: [adsights.ai](https://www.adsights.ai)
- **Twitter/X**: [@adsightsai](https://twitter.com/adsightsai)
- **LinkedIn**: [AdSights](https://www.linkedin.com/company/adsights-ai/)
- **YouTube**: [@AdSights](https://www.youtube.com/@AdSights)
- **TikTok**: [@adsightsai](https://tiktok.com/@adsightsai)
- **Medium**: [@adsights](https://medium.com/@adsights)
- **HuggingFace**: [AdSights](https://huggingface.co/AdSights)
- **Pinterest**: [adsightsai](https://pinterest.com/adsightsai/)
- **Trustpilot**: [Reviews](https://www.trustpilot.com/review/adsights.ai)
- **Product Hunt**: [AdSights Free Design Tools](https://www.producthunt.com/products/adsights-free-design-tools)

## 🎓 For Developers

Interested in building with us? Check out:
- **[GitHub](https://github.com/adsights-ai)** - Open source projects and contributions
- **[StackShare](https://stackshare.io/companies/adsights)** - Our tech stack
- **[Observable](https://observablehq.com/@adsights)** - Data visualization and analytics

## 📧 Get in Touch

- **Request Access**: [adsights.ai/request-access](https://www.adsights.ai/request-access)
- **Support**: support@adsights.ai
- **Business Inquiries**: team@adsights.ai
- **Buy the Ads Framework**: [adsights.ai/frameworks/ads-framework](https://www.adsights.ai/frameworks/ads-framework)

## 📄 Legal

- **[Terms of Service](https://www.adsights.ai/terms)**
- **[Privacy Policy](https://www.adsights.ai/privacy)**
- **[Data Privacy Agreement](https://www.adsights.ai/data-privacy-agreement)**

---

<p align="center">
  <sub>© 2026 AdSights. All rights reserved.</sub>
</p>

<p align="center">
  <sub>Made with ❤️ for marketers who want to make data-driven creative decisions</sub>
</p>
