# I build products. fast. from scratch.

### Things I have Shipped -  

**[GrowthCamel](https://growthcamel.xyz)** - Find what is working in your niche, then post it as you.  
A competitor's Instagram goes in and finished videos of you come out, in your own voice and face. It ingests up to 2,000 reels per handle across Instagram, TikTok and YouTube Shorts and ranks them against each account's own baseline instead of raw views, so a small account's breakout still surfaces. The voice is cloned from one audio sample and the video built from one photo. The AI's motion graphics are checked against placement rules before they render, and a single-pass composite cut peak memory by 58% with no lip-sync drift. When the text-to-speech vendor's speed setting turned out not to work, I re-paced the audio myself and rescaled the word timings so captions and lip-sync stayed aligned. Built from a playbook I used to grow an insta account past 300K.

**Pelorus .ai** - Pelorus is a continuous voyage optimization platform for merchant ships, covering container vessels, LNG carriers, and crude and product tankers.
It reads live NOAA marine forecasts along a vessel’s filed route and models how that specific hull will actually perform in those seas, accounting for speed loss, added resistance and fuel burn.
When a better track exists, it proposes one and prices the difference in fuel, CO2 and dollars against the voyage’s own bunker costs and charter terms.
Every recommendation shows the arithmetic behind it, and the platform stays silent when the saving is too small to be real.

**[EventDaddy](https://eventdaddy.ai)** - Eventdaddy is an operating system for B2B events. Conferences, trade shows and exhibitions are still run on six disconnected tools and a spreadsheet, and we collapse that into one system.
It covers the full lifecycle in a single product: branded registration pages, ticketing and checkout, an attendee CRM that persists across events, sub-second QR check-in with on-site badge printing, email campaigns and analytics.
The real work sits in transactional registration across multiple documents, dual payment gateways for international and India with per-tenant credentials encrypted at rest, signature-verified webhooks, and bulk imports on a worker queue that survives a crashed worker.

Otto, the built-in AI agent, can read event data and take action, but anything outward or irreversible such as sending a campaign, issuing a refund or deleting records is held behind an explicit human approval step rather than trusted to the model.

**[Motionabl](https://motionabl.com)** - Motionabl turns a plain-English description of a video into a finished, polished motion graphics video, with no editing software or timeline.
It works through 55 custom tools to generate voiceovers, sound effects, music and images, pick palettes and fonts, and check its own output by type-checking the code and rendering sample frames before you ever see it.

Every project is saved as its own GitHub repo, so users can refine the video by chatting ("make the intro faster", "swap the colors") and the agent edits the code instead of starting over.

Final videos render in parallel on AWS Lambda, and billing is metered in credits based on the actual AI and tool cost of each generation.

**[Warpbay](https://warpbay.com)** - AI workflows for exhibitions, and the whole event stack.  
Matchmaking, badges, WhatsApp campaigns and lead scanning; it raised $200k and grew to 1M+ visitors across 100+ in-person events. I scaled it for traffic spikes with Nginx and PM2 cluster mode and streamed 1000+ badge batches without memory spikes. I also built the schema-driven registration and payment form builder, the WhatsApp and email outreach console, and per-event ROI for organizers through MongoDB aggregation.

**[Superlinks](https://superlinks.ai)** - Create, launch and sell digital products with AI, no code.  
I built the live landing page editor, where every change appears instantly in a sandboxed preview with no rebuild or reload. Paid products stay locked behind signed access tokens until payment clears, and webhook-driven payments power sales tracking, refunds and split payouts across vendors. I also cut API calls by 20% with client-side memoization.

**[Findstartupideas](https://www.findstartupideas.com/)** - Acquired.  
It mined Reddit and Hacker News for real pain points and turned them into 1000+ ranked startup ideas with community voting and one-click landing page generation. Scrapers ran live on each user's search with deep thread traversal, and a self-hosted GPT model extracted, deduplicated and clustered the pain points in sub-second time.

**[Flickerdocs](https://flicker-docs.fly.dev/)** - A real-time collaborative editor with no server and no database.  
It runs peer-to-peer over WebRTC on a Logoot-family CRDT I built from scratch, following Shapiro 2011 and Preguiça 2009. Fractional identifiers keep concurrent inserts from ever renumbering the document, and per-peer version vectors give causal ordering. Operations are commutative, associative and idempotent, which gives strong eventual consistency.

**[Melo](https://www.trymelo.io/)** - An expense tracker that lives inside WhatsApp.  
Text it, voice note it or photograph a receipt, and it lands in a multi-currency ledger on the Meta Business API with no app and no login. Free-form messages are parsed into merchant, amount, currency and category in under a second. Voice notes go through Whisper into multi-entry extraction, so one clip can capture several expenses in several languages, and receipts go through Claude Vision into your own categories.

---

### stack

typescript · next.js · react · node.js · python · aws · mongodb · postgres · tailwind · docker

### ai

shipped into products: claude api · claude vision · whisper · self-hosted open-source LLMs · voice cloning · agentic workflows · E2B remote sandboxes

---

<p align="center">
  <a href="https://github.com/chinmay4o">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chinmay4o&theme=dark&layout=compact&hide_border=true&bg_color=000000&title_color=ffffff&text_color=999999" />
  </a>
</p>

---

<p align="center">
  <a href="https://x.com/chinmay4o">X</a> · <a href="mailto:chinmayinbox8@gmail.com">Email</a>
</p>
