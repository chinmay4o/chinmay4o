# I build products. fast. from scratch.

CTO at Warpbay (raised $200k). Head of Product at Motionabl. Built and sold FindStartupIdeas.

### now building

**[GrowthCamel](https://growthcamel.xyz)** - Find what is working in your niche, then post it as you.  
A competitor's Instagram goes in and finished videos of you come out, in your own voice and face. It ingests up to 2,000 reels per handle across Instagram, TikTok and YouTube Shorts and ranks them against each account's own baseline instead of raw views, so a small account's breakout still surfaces. The voice is cloned from one audio sample and the video built from one photo. The AI's motion graphics are checked against placement rules before they render, and a single-pass composite cut peak memory by 58% with no lip-sync drift. When the text-to-speech vendor's speed setting turned out not to work, I re-paced the audio myself and rescaled the word timings so captions and lip-sync stayed aligned. Built from a playbook I used to grow an insta account past 300K.

**Pelorus .ai** - Voyage optimization for merchant ships.  
Pelorus reads live NOAA weather and wave forecasts, estimates fuel burn for the specific hull, and prices every candidate route in dollars. It ranks on total cost rather than time, and it accounts for carbon charges and compliance (EU ETS, FuelEU, CII) alongside fuel. Its first $1,298 saving turned out to be sampling noise: the route's own cost moved $5,180 when only the sampling resolution changed. Better interpolation and denser grids cut that to $405, which made a $34,803 recommendation clear the noise by 86x. It now refuses any recommendation it cannot resolve, won't run on climatology, and never fills gaps with silent defaults. It's backed by 343 test modules.

**[EventDaddy](https://eventdaddy.ai)** - AI-native operating system for B2B trade shows.  
Registration, check-in, badge printing, exhibitor and sponsor onboarding and marketing live in one platform, and organizers run the whole show by talking to it. Background jobs run on a MongoDB queue with heartbeat leases, so a crashed worker's job is picked up by another. The agent is bounded to a fixed number of rounds, and anything it can't undo, like a mass send or a refund, waits for a human. The model is told the action is pending.

### before that

**[Motionabl](https://motionabl.com)** - AI video generation and motion graphics.  
You describe a scene and it builds the video. I was Product Head at Motionabl, based out of Paris. I made a coding-agent SDK built for one laptop work for many users, restoring each session from the database per request. AI-written code is type-checked and linted in parallel, then opened in a real browser at five frames before every render to catch errors that only appear mid-video. As agent runs outgrew platform limits I moved from Vercel's 300s cap to 800s and then to Railway, and moved bundling into sandboxes after it ran out of memory.

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
