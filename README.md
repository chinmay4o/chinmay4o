# I build products. Fast. From scratch.

**Pelorus. ai** - Continuous voyage optimization for merchant ships: container vessels, LNG carriers, and crude and product tankers.
It reads live NOAA marine forecasts along a vessel's filed route and models how that specific hull will perform in those seas: speed loss, added resistance and fuel burn. When a better track exists, it proposes one and prices the difference in fuel, CO2 and dollars against the voyage's own bunker costs and charter terms. Every recommendation shows its arithmetic, and it stays silent when the saving is too small to be real.

**[Warpbay](https://warpbay.com)** · AI workflows for trade shows: matchmaking, badges, WhatsApp campaigns and lead scanning.
Grew to 1M+ visitors across 100+ trade shows. I scaled it for traffic spikes with Nginx and PM2 cluster mode and streamed 1,000+ badge batches without memory spikes. I also built the schema-driven registration and payment form builder, the WhatsApp and email outreach console, and per-event ROI for organizers through MongoDB aggregation.

**[GrowthCamel](https://growthcamel.xyz)** · Find what's working in your niche, then post it as you.
A competitor's Instagram goes in; finished videos of you come out, in your own voice and face. It ranks up to 2,000 reels per handle across Instagram, TikTok and YouTube Shorts against each account's own baseline, so a small account's breakout still surfaces. The voice is cloned from one audio sample and the video built from one photo. A single-pass composite cut peak memory by 58% with no lip-sync drift. Built from a playbook I used to grow an Instagram account past 300K.

**[Motionabl](https://motionabl.com)** · Plain English in, finished motion graphics video out. No editor, no timeline.
The agent uses 55 custom tools to generate voiceovers, sound effects, music and images and to pick palettes and fonts, then type-checks its own code and renders sample frames before you see anything. Every project is its own GitHub repo, so you refine by chatting ("make the intro faster") and the agent edits the code instead of starting over. Final videos render in parallel on AWS Lambda, and billing is metered in credits from the real AI and tool cost of each generation.

**[Flicker Docs](https://flicker-docs.fly.dev/)** · Real-time collaborative editor with no server and no database.
It runs peer-to-peer over WebRTC, built on a Logoot-family CRDT following Shapiro 2011 and Preguiça 2009. Fractional identifiers keep concurrent inserts from ever renumbering the document, and per-peer version vectors give causal ordering. Operations are commutative, associative and idempotent, which gives strong eventual consistency across every peer.

**[EventDaddy](https://eventdaddy.ai)** · An operating system for B2B events, replacing six disconnected tools and a spreadsheet.
Branded registration, ticketing and checkout, an attendee CRM that persists across events, sub-second QR check-in with on-site badge printing, campaigns and analytics. Underneath: transactional registration across multiple documents, dual payment gateways for India and international with per-tenant credentials encrypted at rest, signature-verified webhooks, and bulk imports on a worker queue that survives a crashed worker. Otto, its AI agent, takes action, but anything irreversible waits for human approval.

**[FindStartupIdeas](https://www.findstartupideas.com/)** · Real pain points from Reddit and Hacker News, turned into startup ideas. Acquired.
Scrapers ran live on each user's search with deep thread traversal, and a self-hosted GPT model extracted, deduplicated and clustered the pain points in under a second. The result was 1,000+ ranked startup ideas with community voting and one-click landing page generation.

**[Superlinks](https://superlinks.ai)** · Create, launch and sell digital products with AI, no code.
I built the live landing page editor, where every change appears instantly in a sandboxed preview with no rebuild or reload. Paid products stay locked behind signed access tokens until payment clears, and webhook-driven payments power sales tracking, refunds and split payouts across vendors. I also cut API calls by 20% with client-side memoization.

**[Melo](https://www.trymelo.io/)** · An expense tracker that lives inside WhatsApp. No app, no login.
Text it, voice note it or photograph a receipt, and it lands in a multi-currency ledger on the Meta Business API. Free-form messages are parsed into merchant, amount, currency and category in under a second. Voice notes go through Whisper into multi-entry extraction, so one clip can log several expenses in several languages, and receipts go through Claude Vision into your own categories.

---

**Stack:** TypeScript · Next.js · React · Node.js · Python · AWS · MongoDB · Postgres · Docker

**AI in production:** Claude API · Claude Vision · Whisper · self-hosted LLMs · voice cloning · agentic workflows · E2B sandboxes

---

<p align="center">
  <a href="https://x.com/chinmay4o">X</a> · <a href="mailto:chinmayinbox8@gmail.com">Email</a>
</p>
