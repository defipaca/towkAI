# Towkay 頭家

**A gamified command centre for running a one-person company like a Singapore hawker centre.**

Every stall is an AI agent. You are the towkay.

## Demo

Open `index.html` locally, or deploy this repository directly to Vercel, Netlify, GitHub Pages, or Cloudflare Pages. No build step and no API key are required.

## What the MVP demonstrates

- One business goal becomes four typed work chits.
- Specialist stalls “cook” work in parallel:
  - **Market Intelligence** — inspired by Flywheel
  - **BD Outreach** — inspired by Dealmaiker
  - **Growth Loops** — inspired by Rocketo
  - **Diagnostic Funnel** — inspired by IgnAIte
- All outputs return to a human approval counter.
- The towkay can **Chop & Serve** or **Send Back** with feedback.
- Every dispatch, completion, revision and approval appears in an append-only ledger.

## Why it matters

The bottleneck for a one-person company is not access to agents. It is the ability to understand, coordinate and trust them. Towkay replaces scattered chats and opaque logs with a spatial, game-like interface built around human judgment.

## Architecture

This hackathon MVP is a dependency-free static web app:

- HTML/CSS/JavaScript only
- Simulated specialist-agent execution for reliable judging and offline demos
- Responsive UI
- No external services or secrets

The production path is to connect each stall to real agent workflows and APIs, persist tasks and memory, and allow third-party agents to be installed as stalls.

## Business model

1. SaaS subscription by active stalls and monthly orders
2. Usage-based agent execution
3. Revenue share from a third-party stall marketplace
4. Premium first-party workflow integrations
5. White-label orchestration and audit layer for agencies and micro-teams

## Built for

BUIDL_OPC_SG_0712 — Singapore, July 12, 2026.
