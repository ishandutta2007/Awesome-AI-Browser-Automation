# Awesome-AI-Browser-Automation

## Top AI Browser Automation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Cloud Browsers, AI Web Agents, Playwright/Puppeteer Infrastructure, Computer-Use Agents & Headless Browser APIs*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Browser Automation**. These tools provide hosted browsers, AI-driven act/extract agents, and infrastructure so LLMs and agents can navigate the web, fill forms, and extract data reliably at scale.



**Examples** include Browserbase, Stagehand, Steel.dev, Browserless, Hyperbrowser, Anchor Browser Automation, Playwright Cloud, Scrapfly Browser API, ZenRows Browser, and FetchFox (the category leaders).



**Open-source emphasis**: Browser automation has excellent open foundations. **Playwright**, **browser-use**, **Stagehand** (open SDK), **Puppeteer**, and **Playwright MCP** power most AI browser agents. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Browserbase](https://www.browserbase.com/)**  

  Cloud browser infrastructure for AI agents—session management, stealth, and scale; tightly integrated with the Stagehand open SDK.



- **[Stagehand](https://www.stagehand.dev/)**  

  AI browser automation SDK (open-source core) with natural-language act/extract/observe on top of Playwright; often paired with Browserbase for production.



- **[Steel.dev, Hyperbrowser, Browserless](https://steel.dev/)**  

  Hosted headless browser APIs and session platforms for scraping, testing, and agent workloads.



- **[Scrapfly Browser API, ZenRows Browser](https://scrapfly.io/)**  

  Browser and anti-bot oriented APIs for reliable rendering and extraction when sites block simple scrapers.



- **[Playwright Cloud, Anchor, FetchFox](https://www.browserbase.com/)**  

  Additional managed Playwright/browser automation and AI browser-use style services for developers and agents.



- **[Other commercial AI browser platforms](https://www.browserbase.com/)**  

  Further providers of cloud browsers, computer-use APIs, and agent-ready browser infrastructure.



## Open-Source GitHub Projects



- **[Playwright (Microsoft)](https://github.com/microsoft/playwright)**  

  Leading open-source browser automation library—Chromium, Firefox, WebKit; the standard foundation for most AI and classic browser scripts.



- **[browser-use](https://github.com/browser-use/browser-use)**  

  Highly popular open-source AI browser agent library (Python)—LLM-driven navigation and task completion on real websites; major community for agentic web automation.



- **[Stagehand (open SDK)](https://github.com/browserbase/stagehand)**  

  Open-source AI browser automation framework—natural-language actions mixed with Playwright code, self-healing patterns, and agent workflows (MIT); runs local or on Browserbase.



- **[Playwright MCP](https://github.com/microsoft/playwright-mcp)**  

  Open Model Context Protocol server exposing Playwright capabilities to AI coding agents for test generation and browser control.



- **[Puppeteer](https://github.com/puppeteer/puppeteer)**  

  Open Chrome/Chromium automation library widely used for scraping, PDFs, and headless workflows.



- **[Skyvern & vision-based agents](https://github.com/Skyvern-AI/skyvern)**  

  Open projects using vision + LLM for browser tasks on unfamiliar UIs without brittle selectors.



- **[Selenium](https://github.com/SeleniumHQ/selenium)**  

  Long-standing open WebDriver standard and tooling, still used in enterprise test and automation stacks.



- **[Self-hosted browser grids](https://github.com/browserless/browserless)**  

  Open components and Docker images for running browser pools (Browserless has open editions/approaches) for team infrastructure.



### Additional Strong Open-Source Options



- **Classic automation**: Playwright (preferred) or Puppeteer/Selenium for deterministic scripts.

- **AI agents**: browser-use (Python) and Stagehand (TypeScript) for LLM-driven browsing.

- **Agent tooling**: Playwright MCP for IDE/agent integration.

- **Vision agents**: Skyvern-style approaches when DOM selectors fail.

- **Composable stacks**: Playwright/Stagehand + optional cloud browser (Browserbase etc.) + LLM for hybrid cost/reliability.

- Commercial platforms still lead in stealth, multi-region sessions, and zero-ops scale.



**Frameworks for building custom systems**:  

**Playwright** + **Stagehand** or **browser-use** are the core open stack for AI browser automation.  

Add **Playwright MCP** for agent IDEs.  

Commercial cloud browsers (Browserbase, Steel, Browserless, Hyperbrowser, etc.) provide isolation, scale, and anti-bot resilience.  

Many teams develop with local Playwright/Stagehand/browser-use and deploy sessions on hosted browser infrastructure. Fully open stacks work well for trusted sites and internal tools; hostile public sites often need commercial browser/proxy layers.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Browser automation can violate website terms of service and trigger legal or blocking responses. Only automate sites you own or have permission to access. Respect robots.txt, rate limits, and privacy laws.

- AI browser agents can take unintended actions. Use allowlists, sandboxes, and human approval for sensitive accounts. Open-source tools require you to secure credentials and infrastructure; commercial platforms shift some operational risk to the vendor.



---



**Made for AI agent builders, automation engineers, and teams shipping web-using products.**  

Let's keep AI browser automation open and capable—through Playwright, Stagehand, browser-use, and complementary commercial cloud browsers.
