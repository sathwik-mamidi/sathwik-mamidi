# Sathwik Mamidi

**Technical founder. CTO at Akisto.**

I build AI systems for work where mistakes are expensive.

For a decade I have taken products from first idea to production, across applied AI, developer infrastructure, identity, and real-time systems. In every company I have owned the technical foundation, from the first architecture decision to production.

## Now

**Akisto**, CTO. An AI supplier coordinator for manufacturers. Supplier email threads mix several orders, answer half the question, and move dates without saying so; Akisto turns them into traceable facts, a consistent state for every order, and follow-up that happens on time. I lead architecture and engineering: a typed platform with a canonical data model, durable workflows, tenant isolation, and a full audit trail.

TypeScript, React, PostgreSQL, Temporal, AWS. In development, pilot secured.

## Track record

| Years | Company | Role | What it was |
|---|---|---|---|
| 2026 | **Akisto** | CTO | AI supplier coordination for manufacturers. Moving the product from automation and spreadsheets to a durable, auditable platform. |
| 2025–26 | **Scrute** | Founder and CTO | AI review for commercial real estate documents. Title commitments reconciled against surveys, plans checked against building-code rules, every finding tied to its page. [Demos](https://scrute.ai) |
| 2025 | **Commentrix** | Founder | Automated play-by-play for sports footage. Proved the pipeline end to end, then chose not to pursue a market that was too narrow. [Source](https://github.com/sathwik-mamidi/commentrix) |
| 2025 | **Aiditor** | Founder | A conversational editor for image, audio, and video. Shipped the full product and learned where natural language holds as an interface, and where it breaks. [Source](https://github.com/sathwik-mamidi/aiditor) |
| 2023–24 | **Authnest** | Founder | A separate email identity for sign-ups, one-time codes, and notifications. Set aside to focus fully on Scrute. [Source](https://github.com/sathwik-mamidi/authnest) |
| 2017–23 | **Independent products** | Founder | Consumer products, multiplayer games, and SaaS, each designed, built, and operated end to end: OnlyOnePremium, SlowAndSteady, Rank Race, SV Hunt, Links Browser, Favs.bio, Vowalls. |

## Selected engineering

**[Aftlog](https://github.com/sathwik-mamidi/aftlog)**: a flight recorder for AI coding agents. A local Rust daemon records every command and file change, separates the agent's work from what was already there, and produces a readable report with a conservative, backup-first revert plan. *Rust, Git, filesystem watchers.*

**[Scrute](https://scrute.ai)**: document review that cites its sources. Title and survey parsing run in parallel and are reconciled together; plan details from a vision model are checked by explicit TypeScript rules; findings carry the rule, observed and required values, and page references. *TypeScript, NestJS, PostgreSQL, Gemini.*

**[Aiditor](https://github.com/sathwik-mamidi/aiditor)**: conversation as the control surface for media. The model plans the edit as Python, a dedicated container executes it, and failures feed back into the next attempt. *Python, FastAPI, Gemini, Docker, FFmpeg.*

**[Everby](https://github.com/sathwik-mamidi/Everby)**: a native macOS accountability companion. Layered memory with distinct lifetimes, check-ins timed to the person's actual day, and personal state that stays on the machine. *Swift, AppKit, Keychain, tool calling.*

## Range

- **Real-time systems.** [SlowAndSteady.io](https://github.com/sathwik-mamidi/slowandsteady.io), a zero-player multiplayer race that drew 30,000 hits in one night, and [SlowAndSteady 2](https://github.com/sathwik-mamidi/slowandsteady.xyz), a shared economy where giving creates power. WebSockets, Redis, Unity.
- **Multimodal pipelines.** [Commentrix](https://github.com/sathwik-mamidi/commentrix) samples footage, writes timestamped commentary, and aligns narration and subtitles to the source timeline.
- **Identity and email.** [Authnest](https://github.com/sathwik-mamidi/authnest), [SES Email Ingestion](https://github.com/sathwik-mamidi/ses-email-ingestion-lambda), and an [OAuth Flow Tester](https://github.com/sathwik-mamidi/oauth-flow-tester) for proving authorization-code and OIDC flows in isolation.
- **Browser automation at scale.** Twish, a visual index of one million websites captured by parallel Puppeteer workers on EC2, and the [Ad Network Scanner](https://github.com/sathwik-mamidi/ad-network-scanner).
- **Explainable decisions.** The [Logistics Trust Console](https://github.com/sathwik-mamidi/logistics-trust-console), carrier due diligence that refuses to hide its reasons.

More: [Open Order](https://github.com/sathwik-mamidi/open-order), [Voice Chat Widget](https://github.com/sathwik-mamidi/voice-chat-widget), [Prompt Page Builder](https://github.com/sathwik-mamidi/prompt-page-builder), [WhoCan](https://github.com/sathwik-mamidi/whocan), [AI Wallpaper Batcher](https://github.com/sathwik-mamidi/ai-wallpaper-batcher), [OnlyOnePremium](https://github.com/sathwik-mamidi/onlyonepremium).

## How I build

**Start where the work actually happens.** Before any architecture, learn how the job is done today: the spreadsheets, the email threads, the workarounds.

**Let models interpret. Let rules decide.** Models read messy input well. Commitments, state, and money belong to deterministic code, with a person able to step in.

**Show the evidence, and plan the undo.** A finding, score, or automated action is incomplete without a source someone can inspect and a way back if it is wrong.

**Earn every piece of complexity.** Use the smallest architecture that tells the truth.

## Contact

Working on a difficult problem in a domain you know deeply? I would like to hear about it.

[sathwikmamidi.com](https://sathwikmamidi.com) · [hi@sathwikmamidi.com](mailto:hi@sathwikmamidi.com) · [LinkedIn](https://www.linkedin.com/in/sathwik-mamidi/) · [X](https://x.com/sathwik_mamidi)
