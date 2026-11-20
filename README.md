# Awesome-Android-APK-Launchers-Emulation-Setup

# Awesome AI Website Builder & Landing Page Generator 🌟

> **Top AI Website Builder Landing Page Generator (Opensource)**  
> A curated list of the best AI-powered website builders and landing page generators — with a strong focus on **open-source** and self-hostable alternatives.  
> 🌟 **Star if you like it!** 🌟

AI website builders and landing page generators let you go from a simple prompt or description to a fully designed, responsive site (or conversion-focused landing page) in minutes. Commercial tools like Durable, 10Web, Framer AI, and others dominate the hosted space, but a growing ecosystem of open-source projects gives you full control, no vendor lock-in, and the ability to run locally or self-host.

This list prioritizes **open-source GitHub projects** while keeping SaaS/hosted platforms clearly separated.

## Table of Contents

- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS / Hosted Platforms

These are popular commercial AI website builders and landing page generators (closed-source / hosted):

- **[Durable](https://durable.co/)** — Generates a complete business website + CRM + invoicing in under 60 seconds. Ideal for local service businesses and solopreneurs.
- **[10Web](https://10web.io/)** — AI website builder built on WordPress + Elementor. Can recreate sites from a URL or prompt and hosts on Google Cloud with performance optimization.
- **[Framer AI](https://www.framer.com/)** — Design-first AI website builder with a powerful visual canvas, advanced animations, and CMS. Excellent for designers who want pixel-perfect control.
- **[Wix Studio AI](https://www.wix.com/studio)** — AI-assisted website creation inside the Wix ecosystem (ADI + Studio tools). Strong for beginners and full marketing sites.
- **[Hostinger AI Website Builder](https://www.hostinger.com/)** — Fast AI site generation tightly integrated with Hostinger hosting.
- **[Dorik AI](https://dorik.com/)** — AI website & landing page builder focused on speed and simplicity.
- **[Relume](https://www.relume.io/)** — AI-powered component library and site structure generator that works great with Figma → Webflow/Framer workflows.
- **[TeleportHQ](https://teleporthq.io/)** — AI-assisted visual development platform with code export.
- **[B12](https://www.b12.io/)** — AI website builder aimed at professional services (lawyers, consultants, agencies) with built-in marketing tools.
- **[CodeDesign.ai](https://codedesign.ai/)** — AI website & landing page generator with clean code export options.

## Open-Source GitHub Projects

Open-source alternatives and tools you can self-host, run locally, or extend. These range from full visual AI builders to prompt-to-landing-page generators and developer-focused frameworks.

### Full AI Website / App Builders

- **[buildingopen/openpage](https://github.com/buildingopen/openpage)**  
  Open-source website builder with a Framer-like visual drag-and-drop editor + AI site generation (Gemini). JSON-first architecture (single source of truth). Self-hosted alternative to Framer / Lovable / v0. Built with React 19, TypeScript, Tailwind CSS v4. MIT.

- **[stackblitz-labs/bolt.diy](https://github.com/stackblitz-labs/bolt.diy)**  
  The popular open-source version of Bolt.new. Prompt → full-stack web apps & sites in the browser using WebContainers. Supports 20+ LLM providers (OpenAI, Anthropic, Gemini, Groq, Ollama, local models, etc.). Live preview, terminal, code editor, one-click deploy. Extremely active (~20k+ stars). MIT.

- **[webstudio-is/webstudio](https://github.com/webstudio-is/webstudio)**  
  Advanced open-source visual website builder (strong Webflow/Framer alternative). Full CSS control, components, CMS connections, animations. AI support via MCP (agents can build/edit projects) + separate Inception design exploration tool. AGPL core. Self-hostable + hosted option.

### AI Landing Page Generators

- **[zinedkaloc/aipage.dev](https://github.com/zinedkaloc/aipage.dev)** (and forks such as jeus0522/AI-Landing-Page-Generator)  
  Classic open-source AI landing page generator. Describe your page → get clean HTML + Tailwind CSS. Simple, fast, and still widely forked/used. MIT.

- **[keyflowcoreg/pageforge](https://github.com/keyflowcoreg/pageforge)**  
  AI landing page generator powered by Gemini 2.0 Flash. Multiple template styles, live responsive preview, export as Next.js or standalone HTML.

- **[alexar76/aicom-landing](https://github.com/alexar76/aicom-landing)**  
  One-prompt → self-contained HTML landing page in ~30–60 seconds. 20 style presets. Fully self-hosted, supports OpenAI / Ollama / DeepSeek. MIT. Perfect for rapid MVPs and A/B testing.

- **[Cybrarist/InstantLand](https://github.com/Cybrarist/InstantLand)**  
  Open-source landing page / marketing site builder with GrapeJS visual editor, A/B testing, custom forms, and campaign tools. Self-hostable (PHP/Laravel stack).

### Other Notable Open-Source Tools & Templates

- **[HugoBlox/hugo-theme-saas-landing-page](https://github.com/HugoBlox/hugo-theme-saas-landing-page)**  
  Markdown-first SaaS landing page system. AI can generate the content; you own clean Markdown files. Extremely fast, free hosting forever (static). Great for developers who hate React maintenance.

- **[RayVelez27/instalanding.ai](https://github.com/RayVelez27/instalanding.ai)**  
  Library of premium single-file HTML landing pages + motion components. No frameworks, no build step. Designed for humans *and* AI coding agents (includes one-shot prompts).

- **[ln-dev7/landing-pages](https://github.com/ln-dev7/landing-pages)**  
  Collection of distinctive, personality-rich open-source landing pages built with Next.js + Tailwind + shadcn/ui.

- **[all-in-aigc/pagen-ai-landing-page-template](https://github.com/all-in-aigc/pagen-ai-landing-page-template)**  
  Clean Next.js + shadcn/ui AI landing page template generated by Pagen AI. Easy to customize.

- **GrapesJS-based builders** and related projects (search “grapesjs landing” or “grapesjs page builder”) — the foundational open-source visual page builder that many self-hosted tools build upon.

- Additional emerging projects worth watching: various multi-agent SEO landing page systems, local Ollama-powered generators, and visual editors that integrate with agents via MCP.

> **Tip**: Many of the strongest open-source options today are either (1) visual builders with AI/MCP support (OpenPage, Webstudio) or (2) full prompt-to-app environments you can self-host (bolt.diy). For pure marketing landing pages, the simpler HTML/Tailwind generators are often the fastest path.

## How to Contribute

Contributions are welcome and encouraged!

1. Fork the repository
2. Add a new tool under the appropriate section (keep SaaS and Open-Source strictly separate)
3. Use the same format: **Name** — short description + key features + license/link
4. Prefer actively maintained projects with clear documentation
5. Submit a Pull Request

Please keep descriptions neutral and factual. Open-source projects are the primary focus of this list.

## Disclaimer

This is a community-curated list for informational purposes only.  
Inclusion does not constitute an endorsement. Always review licenses, privacy policies, pricing, and security practices before using any tool (especially when handling customer data or deploying to production).  

Some “open-source” projects may have dual licensing, proprietary components, or require paid API keys for AI features. Check the actual LICENSE file and documentation.

---

**Made with ❤️ for the open-source community**  
If this list helped you, please ⭐ the repo!
# Awesome-Android-APK-Launchers-Emulation-Setup

##### Top Algorithmic Trading & Automated Crypto Execution Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Strategy Backtesting, Automated Execution & Self-Hosted Trading Engines*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Algorithmic Trading & Automated Crypto Execution**. These tools help traders and developers automate strategy execution, backtest ideas against historical data, and manage live trading across crypto exchanges and traditional brokers—covering everything from visual no-code builders to institutional-grade execution engines.

**Examples** include QuantConnect, Alpaca, MetaTrader, TradingView, NinjaTrader, Freqtrade, Hummingbot, and Jesse (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted crypto trading bots, open-source backtesting frameworks, and community-driven execution engines—ideal for developers seeking full control over strategy logic and avoiding monthly subscription fees that compound over time. The open-source landscape is genuinely mature: **Freqtrade** leads with 56k+ stars and active weekly development , **Hummingbot** covers market making and arbitrage across 40+ CEX/DEX , and **Jesse** offers an advanced Python framework for systematic strategies .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[QuantConnect](https://www.quantconnect.com/)**  
  Cloud-based algorithmic trading platform with **Lean engine**, supporting equities, futures, options, and crypto. Offers backtesting, live trading, and data subscriptions. The **Lean engine is open-source** (Apache-2.0) with 31k+ stars and active development [citation:1].

- **[Alpaca](https://alpaca.markets/)**  
  Commission-free API-first brokerage for stocks, ETFs, and crypto. Provides **paper trading** and live execution APIs. **Official MCP server** (MIT) enables trading via LLM tools and IDEs [citation:11].

- **[MetaTrader (MT4/MT5)](https://www.metatrader5.com/)**  
  Industry-standard platform for forex and CFD algorithmic trading. Uses MQL4/MQL5 for expert advisors. Widely supported by brokers globally.

- **[TradingView](https://www.tradingview.com/)**  
  Charting platform with **Pine Script** for strategy development and alerts. Webhook integration enables automated execution through third-party bots.

- **[NinjaTrader](https://ninjatrader.com/)**  
  Futures and forex trading platform with C#-based strategy development, backtesting, and automated execution.

- **[3Commas](https://3commas.io/)**  
  Cloud crypto trading bot platform. **Starter: $15/mo annual** (spot only, 5 DCA + 2 grid bots); **Pro: $38/mo annual** (futures, unlimited exchange accounts, SmartTrade) [citation:3]. Free plan allows limited backtesting only.

- **[Bitsgap](https://bitsgap.com/)**  
  Cloud crypto trading bots with **COMBO (DCA + grid) strategy** and **leveraged futures grid** support on Binance, Bybit, and OKX. **Basic: $23/mo annual**; **Pro: $119/mo annual** [citation:3][citation:14].

## Open-Source GitHub Projects

- **[Freqtrade](https://github.com/freqtrade/freqtrade)**  
  **Free, open-source crypto trading bot** with **56,911 GitHub stars**—the most popular in the category [citation:7][citation:12]. Python-based with a large strategy library, Telegram integration, backtesting, hyperopt, and live trading across major exchanges. **Active weekly development** [citation:7].

- **[Hummingbot](https://github.com/hummingbot/hummingbot)**  
  **Open-source market making and arbitrage platform** with **40+ CEX/DEX integrations** [citation:14]. Covers strategies no other retail-accessible platform offers: cross-exchange arbitrage, AMM liquidity provision, and market making. **Zero monthly cost**, but requires **4–8 hours setup** and CLI comfort [citation:14]. Recommended capital: **$1,000+** for arbitrage viability [citation:14].

- **[Jesse](https://github.com/jesse-ai/jesse)**  
  **Advanced crypto trading bot framework** in Python with **8,805 stars** and active development [citation:7]. Designed for systematic strategies with backtesting, optimization, and live execution.

- **[Lean (QuantConnect)](https://github.com/QuantConnect/Lean)**  
  **Open-source algorithmic trading engine** by QuantConnect, **C#** with **31,254 stars** and active development [citation:1]. Powers the QuantConnect cloud platform; supports multi-asset backtesting and live trading. Apache-2.0 licensed.

- **[vn.py](https://github.com/vnpy/vnpy)**  
  **China's most popular open-source quant trading platform** with **19k+ stars** [citation:6]. Python-based modular architecture supporting domestic Chinese exchanges and futures/options trading. Includes CTA strategies, algorithmic trading, and graphical interface.

- **[Backtrader](https://github.com/mementum/backtrader)**  
  **Popular Python backtesting framework** with **10k+ stars** [citation:6]. Event-driven architecture, intuitive API, supports multiple data sources and brokers. **Community activity has slowed** (last meaningful push 2024) [citation:1].

- **[roboquant](https://github.com/roboquant/roboquant)**  
  **Free Python algo-trading platform** (Apache-2.0) with fast backtesting, live trading, AI/ML strategies, and multi-asset support (stocks, options, forex, crypto) [citation:5]. Integrates with IBKR, Alpaca, and crypto exchanges.

### Additional Strong Open-Source Options

- **[hftbacktest](https://github.com/nkaz001/hftbacktest)** (5k+ stars) — High-frequency trading backtesting accounting for limit orders, queue position, and latency [citation:12].
- **[ccxt](https://github.com/ccxt/ccxt)** (44k+ stars) — Unified trading API for 100+ crypto exchanges; the foundational library many bots build upon [citation:7].
- **[passivbot](https://github.com/enarjord/passivbot)** (2k+ stars) — Grid trading bot running on Bybit, Bitget, OKX, GateIO, Binance, Kucoin, WEEX, and Hyperliquid [citation:7].
- **[CryptoSignal](https://github.com/CryptoSignal/CryptoSignal)** (5k+ stars) — Technical analysis and signal bot; **last updated July 2024**—verify maintenance before use [citation:7].

**Frameworks for building custom systems**: Combine **ccxt** for exchange connectivity, **Backtrader** or **Jesse** for strategy backtesting, and **Freqtrade** or **Hummingbot** for live execution. For AI-driven strategies, **roboquant** provides PyTorch/SB3 integration [citation:5].

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Algorithmic trading involves **substantial risk of loss**; automated execution can amplify losses during volatile markets. Never deploy capital you cannot afford to lose. Backtest results do not guarantee future performance.
- **Open-source trading bots require technical expertise and ongoing maintenance.** **Hummingbot** needs 4–8 hours setup and $1,000+ capital for viable arbitrage—small-scale profitability is limited [citation:14]. **Backtrader** has slowed development (last meaningful push 2024) [citation:1]. **CryptoSignal** last updated July 2024—verify before relying on it [citation:7]. **Commercial platforms charge monthly fees that compound**: 3Commas Pro at $38/mo annual for futures [citation:3], Bitsgap Pro at $119/mo annual [citation:3]. **API key security is critical**—use trade-only keys without withdrawal permissions. Validate strategy logic, exchange compatibility, and maintenance status before committing real capital.

---

**Made for algorithmic traders, quantitative developers, and teams building automated execution infrastructure.**  
Let's make algorithmic trading more open, auditable, and risk-aware.
# Awesome-Android-APK-Launchers-Emulation-Setup

<FollowUp>
If you'd like to refine this `README.md` further, let me know:
* **Specific platform niches** to expand (e.g., Linux Waydroid scripts & ARM translation tools, Docker CI/CD Android images, or AI-driven Android ADB agents)
* **Metadata badges or comparison tables** (e.g., host OS support like Linux/Windows/macOS, architecture like `x86_64`/`arm64`, GPU acceleration, or license type)
* **Support & Sponsor footer snippet** added directly to the bottom of the file
</FollowUp>
# Awesome-Android-APK-Launchers-Emulation-Setup

<FollowUp>
If you'd like to refine this `README.md` further, let me know:
* **Specific platform niches** to expand (e.g., Linux Waydroid scripts & ARM translation tools, Docker CI/CD Android images, or AI-driven Android ADB agents)
* **Metadata badges or comparison tables** (e.g., host OS support like Linux/Windows/macOS, architecture like `x86_64`/`arm64`, GPU acceleration, or license type)
* **Support & Sponsor footer snippet** added directly to the bottom of the file
</FollowUp>
# Awesome-Android-APK-Launchers-Emulation-Setup

<FollowUp>
If you'd like to refine this `README.md` further, let me know:
* **Specific platform niches** to expand (e.g., Linux Waydroid scripts & ARM translation tools, Docker CI/CD Android images, or AI-driven Android ADB agents)
* **Metadata badges or comparison tables** (e.g., host OS support like Linux/Windows/macOS, architecture like `x86_64`/`arm64`, GPU acceleration, or license type)
* **Support & Sponsor footer snippet** added directly to the bottom of the file
</FollowUp>
# Awesome-Android-APK-Launchers-Emulation-Setup

