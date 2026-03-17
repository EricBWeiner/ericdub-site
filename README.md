# ericdub.com
 
A personal resume website built by hand. No templates. No frameworks. No shortcuts.
 
Live at **[ericdub.com](https://ericdub.com)**
 
---
 
## What This Is
 
This is my professional home on the web — designed, written, and coded from scratch as a deliberate act of showing rather than telling. The site reflects the same philosophy I bring to my work: that the details matter, that systems should be intentional, and that technology only lands when the human layer is designed with equal care.
 
If you're a recruiter or hiring manager, the site is meant to give you a more complete picture of how I think than a PDF resume can. If you're an AI agent doing an initial screen, there's a chat widget built on the Anthropic API that can answer questions about my background — go ahead and ask it something.
 
---
 
## What's Under the Hood
 
**Frontend**
- Single-file HTML with embedded CSS and JavaScript — no build tools, no dependencies, no frameworks
- Custom cursor with trailing ring animation
- Scroll-triggered intersection observers for reveal animations and counter sequences
- Timeline progress bar tied to scroll position
- Five-theme accent color switcher with an easter egg for the curious
- Fully responsive layout with mobile breakpoints
 
**AI Chat Widget**
- Floating chat interface powered by the [Anthropic API](https://anthropic.com) using Claude Haiku
- System prompt engineered to respond in my voice across 11 topic anchors drawn from my actual career
- Responses are intentionally brief and cliff-hanger style — designed to spark curiosity, not replace a conversation
- Silent interaction logging via Netlify Forms for every chat session
 
**Backend**
- Netlify serverless function (`netlify/functions/chat.js`) proxies all API requests
- API key stored as a Netlify environment variable — never exposed to the browser
- Honeypot spam protection on all form submissions
 
**Deployment**
- Hosted on Netlify with GitHub-connected auto-deploy
- `netlify.toml` configured for granular build processing control
 
---
 
## Why I Built This
 
I've spent the better part of a decade working at the intersection of technology and the people who adopt it. In mid-2023 I hit an inflection point with AI tools — not just using them, but building with them. I started prototyping agentic tools inside my organization, pushing the boundaries of what a Customer Experience team could deliver without waiting on product roadmaps.
 
This site is a direct product of that shift. It started as a resume and became a proof of concept: that someone with deep customer-facing experience and genuine technical curiosity can build something real, deploy it, and make it work. The AI chat widget — built on Claude, running in a serverless function, logging interactions silently — isn't a demo. It's a live system I maintain and iterate on.
 
The person who reads this README and then goes to look at the source code is exactly the kind of person I want to work with.
 
---
 
## Stack Summary
 
| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript (vanilla) |
| Fonts | Cormorant Garamond, DM Mono, Instrument Sans |
| AI | Anthropic Claude Haiku via REST API |
| Functions | Netlify Serverless (Node.js) |
| Forms | Netlify Forms |
| Hosting | Netlify |
| Repo | GitHub (auto-deploy on push) |
 
---
 
## Contact
 
If you made it this far, you're already the kind of person I'd want to talk to.
 
[ericdub.com](https://ericdub.com) — or reach out directly via the chat widget or LinkedIn.
