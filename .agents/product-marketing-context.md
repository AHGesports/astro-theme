# Product Marketing Context

*Last updated: 2026-03-30*

## Product Overview
**One-liner:** AI-powered browser automation platform for mass undetectable automation across infinite profiles.
**What it does:** Elyt lets individuals automate web tasks at scale using AI agents paired with anti-detect browsers. Users create realistic browser profiles, build multi-step workflows with AI nodes, and run them across hundreds of profiles simultaneously — with humanization technology that mimics real human behavior to avoid detection.
**Product category:** AI browser automation / anti-detection automation
**Product type:** B2C SaaS (cloud-based platform + downloadable desktop app via Tauri)
**Business model:** Subscription SaaS (pricing tiers TBD). Coopetition model — integrates with anti-detect providers (AdsPower, MoreLogin, GoLogin) via affiliate codes, with plans to launch own free anti-detect provider once user base is established.

## Target Audience
**Target companies:** Individual consumers, freelancers, solo entrepreneurs, small teams (B2C, not enterprise)
**Decision-makers:** The individual user — no buying committee, personal purchase decision
**Primary use case:** Automating repetitive browser tasks at scale across multiple profiles without getting detected or banned
**Jobs to be done:**
- Automate the same task across dozens/hundreds of browser profiles simultaneously
- Run browser automation on anti-bot-protected websites without detection
- Build complex multi-step automation workflows without coding
**Use cases:**
- Multi-account social media management and outreach (LinkedIn, Instagram, Twitter)
- Sneaker/ticket purchasing across multiple accounts
- Price monitoring and web scraping at scale
- Automated lead generation and personalized messaging
- Account farming and registration automation
- Cross-platform campaign management with scheduling

## Personas
| Persona | Cares about | Challenge | Value we promise |
|---------|-------------|-----------|------------------|
| **Botters** — Tech-savvy users running automation for competitive advantages (sneaker scalping, social media botting, account farming) | Undetectability, speed, multi-account scale | Getting banned/detected, managing many accounts manually | Run infinite undetectable bots with AI humanization — zero bans |
| **Web Scrapers** — Freelance developers and data analysts extracting web data at scale | Reliability, bypass blocks, API access | Sites blocking scrapers, unreliable extraction, IP bans | Reliable, unblockable data extraction paired with anti-detection |
| **Growth Hackers** — Solo marketers and entrepreneurs automating growth | Multi-platform reach, lead gen efficiency, ease of use | Manual social media management doesn't scale, spam detection kills campaigns | Scale outreach across platforms with AI agents that behave like humans |
| **Power Users** — Tech-savvy individuals and small business owners with advanced needs | Feature depth, customization, privacy, local deployment | Limited customization in existing tools, no advanced workflow capabilities | 100+ step workflows, custom AI models, MCP integrations, local deployment option |

## Problems & Pain Points
**Core problem:** Manual browser tasks don't scale, and existing automation tools get detected and banned by modern anti-bot systems.
**Why alternatives fall short:**
- browser-use.com, fellou.ai, skyvern.com offer AI browser automation but have NO anti-detection technology — automations get blocked on protected sites
- airtop.ai requires coding and isn't user-friendly for average users
- No competitor offers mass profile orchestration — users can only automate their own single browser
- No competitor offers a workflow system with scheduling for complex multi-step automation
- Anti-detect browsers (AdsPower, GoLogin, MoreLogin) handle fingerprinting but have no AI automation layer
**What it costs them:** Hours of manual work per day, lost accounts from bans, missed opportunities (sneaker drops, lead windows), revenue loss from blocked scraping
**Emotional tension:** Fear of account bans destroying months of work; frustration that existing tools force a choice between automation power and stealth; stress of manually managing dozens of accounts

## Competitive Landscape
**Direct:** browser-use.com, fellou.ai, skyvern.com — offer AI browser automation but lack anti-detection, mass profiles, and workflow systems
**Secondary:** AdsPower, MoreLogin, GoLogin — provide anti-detection browsers but no AI automation layer (coopetition partners: Elyt integrates with them AND competes long-term)
**Indirect:** Manual work, hiring VAs, basic scripting with Puppeteer/Playwright (no anti-detection, no AI intelligence, requires coding)

## Differentiation
**Key differentiators:**
- **Mass AI browser automation** — automate across infinite profiles, not just one browser (competitors can't do this)
- **Anti-detection technology pairing** — integrated with AdsPower, MoreLogin, GoLogin for unblockable automation on protected sites
- **AI humanization (AIHumanizer)** — first-in-world solution: realistic mouse movements, typing patterns with human errors, behavioral mimicry that passes bot detection
- **Workflow system** — visual node-based builder for complex multi-step automation with scheduling, branching, and chaining (not just single-prompt execution)
**How we do it differently:** Three-tier architecture (web frontend + Node.js orchestrator + Python automation engine with Playwright + Browser-Use + Humanizer) that connects to anti-detect browser APIs for profile management while adding AI intelligence and human-like behavior on top.
**Why that's better:** Users get the stealth of anti-detect browsers PLUS the intelligence of AI automation PLUS the scale of mass profile orchestration — no other tool combines all three.
**Why customers choose us:** "I can automate anything on any website across hundreds of accounts and never get banned" — that combination doesn't exist elsewhere.

## Objections
| Objection | Response |
|-----------|----------|
| "How is this different from browser-use or similar AI automation tools?" | Those tools automate a single browser. Elyt automates across infinite profiles with anti-detection and workflows — it's mass orchestration, not single-browser automation. |
| "I already use AdsPower/GoLogin — why do I need this?" | Those handle fingerprinting. Elyt adds the AI brain: automated actions, workflows, scheduling, and humanization that makes your profiles behave like real humans. |
| "Will this actually avoid detection?" | AIHumanizer generates realistic mouse paths, typing patterns with human errors, and behavioral randomization. Combined with anti-detect browser fingerprinting, this is the most complete stealth stack available. |

**Anti-persona:** Enterprise IT teams looking for RPA-style process automation within their own corporate systems (they need tools like UiPath/Automation Anywhere, not anti-detection). Also: users who need to automate a single personal browser task once — Elyt is overkill for one-off tasks.

## Switching Dynamics
**Push:** Current tools get detected and accounts get banned; single-browser automation doesn't scale; manual multi-account management is exhausting; existing scrapers get blocked
**Pull:** Mass automation across infinite profiles; anti-detection that actually works; AI that behaves like a human; visual workflow builder anyone can use; scheduling for hands-off operation
**Habit:** Users already invested in learning their current anti-detect browser; existing scripts and workflows in Puppeteer/Playwright; familiarity with current tool's UI
**Anxiety:** "Will migration break my existing setup?"; "Is the AI actually reliable enough?"; "What if Elyt gets shut down?"; learning curve concerns

## Customer Language
**How they describe the problem:**
- "I keep getting my accounts banned no matter what anti-detect browser I use"
- "I can automate one browser but I need to run the same thing across 50 profiles"
- "Every scraper I try gets blocked after a few hours"
- "I'm spending 4 hours a day just doing the same thing on different accounts"
- "browser-use is cool but it doesn't work on sites with bot detection"
- "I need something that works on LinkedIn/Instagram without getting flagged"
- "Managing 20+ accounts manually is killing me"
**How they describe us:**
- "It's like browser-use but it actually works on protected sites"
- "Anti-detect browser + AI automation in one tool"
- "I set up the workflow once and it runs across all my profiles"
- "The humanization is insane — my accounts haven't been flagged once"
**Words to use:** automation, profiles, workflows, undetectable, anti-detection, AI agents, humanization, mass automation, stealth, scale, scheduling, browser automation, AI-powered
**Words to avoid:** bot/botting (too negative in public marketing), scraping (legal risk in ads), hacking (even "growth hacking" is risky in paid channels), exploit, bypass, crack, abuse
**Glossary:**
| Term | Meaning |
|------|---------|
| Profile | A browser identity with unique fingerprint, persona data, and anti-detection configuration |
| AI Agent | An AI-powered browser automation instance that executes tasks within a profile |
| Workflow | A multi-step automation sequence built from connected AI nodes |
| AIHumanizer | Elyt's proprietary technology that generates human-like mouse movements, typing, and behavior |
| Node | A single step in a workflow, configured with its own action, prompt, and browser settings |
| MCP | Model Context Protocol — allows AI agents to access custom data sources and functions |
| Anti-detect browser | Third-party browser (AdsPower, MoreLogin, GoLogin) that spoofs browser fingerprints |

## Brand Voice
**Tone:** Confident and technical, but not intimidating. Direct, not hype-driven. Avoids generic SaaS marketing language.
**Style:** Results-oriented, show-don't-tell. Lead with what users can DO, not abstract benefits. Use specific numbers and scenarios over vague promises.
**Personality:** Technical authority, approachable expertise, community-minded, builder mentality, power-user energy

## Proof Points
**Metrics (capability-based, pre-launch):**
- Works on any website — including LinkedIn, Instagram, Twitter, e-commerce platforms, and sites with aggressive bot detection
- Compatible with 3 major anti-detect providers (AdsPower, MoreLogin, GoLogin)
- Supports 10+ AI model providers (OpenAI, Claude, Gemini, Groq, Ollama, and more)
- 100+ steps per workflow node for complex automation sequences
- Parallel execution across unlimited browser profiles
- High success rates with repeatable results at low cost per automation
**Customers:**
- Pre-launch for B2C. Currently serving enterprise customers with custom engagements. No public logos yet.
**Testimonials:**
- None available yet (pre-launch). Plan to collect from early B2C adopters and beta testers post-launch.
**Value themes:**
| Theme | Proof |
|-------|-------|
| Automate any website | Works on protected sites that block every other automation tool — anti-detection + AI humanization stack |
| Mass scale | Run the same workflow across unlimited profiles in parallel — not limited to one browser |
| No-code power | Visual workflow builder with AI nodes — describe what you want in plain English, no programming |
| Unbeatable stealth | AIHumanizer: AI-generated mouse movements, typing with human errors, behavioral randomization |
| Flexibility | 10+ AI providers, custom MCPs, works with your existing anti-detect browser, cloud or local deployment |
| Affordable at scale | Bring your own anti-detect browser and AI keys — Elyt orchestrates cheaply on top |

## Goals
**Business goal:** Launch B2C SaaS, acquire paying individual users at scale, establish market authority in AI browser automation
**Conversion action:** Free trial signup (immediate access, no credit card)
**Current stage:** Pre-launch for B2C. Enterprise customers on custom pricing. No public metrics yet.
**Pricing:** Enterprise-only with custom pricing currently. B2C subscription tiers TBD for launch.
