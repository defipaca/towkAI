# TowkAI OS 頭家

**A pixel-art MVP for seeing, controlling and coordinating AI agents across projects.**

TowkAI OS is designed to be understood quickly by a judge or founder:

- the **left sidebar** explains what the product is and lists active projects
- the **center map** shows where agents are working
- the **right inspector** shows what a selected agent is doing and how to control it
- the **bottom review queue** is where the founder approves or sends back outputs

In short: **one founder, many projects, many agents, one control screen.**

## What the MVP is for

TowkAI OS is a command centre for a one-person company. It helps a solo founder:

1. switch between projects
2. dispatch missions to specialist AI agents
3. watch work happen across functional zones
4. inspect each agent's task and status
5. approve or reject outputs before anything ships

## MVP features

- **Multi-project workspace:** Flywheel, Dealmaiker, Rocketo and IgnAIte are example projects.
- **Agent process list:** specialist agents appear as live worker processes.
- **Pixel-art control map:** agents visibly move between research, build, growth, ops and founder review zones.
- **Founder controls:** pause, stop, reassign, approve and update an agent's task.
- **Mission orchestration:** a single business goal is decomposed across multiple agents.
- **Approval queue:** outputs wait for a founder to CHOP or SEND BACK.
- **Event console:** a live stream shows what the system is doing.
- **Scene skins:** users can switch the background between **Hawker Centre**, **Trading Floor**, and **Gardens by the Bay** to reflect different Singapore operating vibes.

## Why it is easy to understand

This MVP deliberately includes:

- a **"What this app does"** panel
- a **"MVP in 10 seconds"** explainer card
- a **"How to read this"** legend on the map
- a visible **current project** card
- a visible **current mission** card

These reduce ambiguity so a judge can immediately understand what the product is doing.

## Demo usage

Open `index.html` locally or deploy the repository directly to Vercel, Netlify, GitHub Pages or Cloudflare Pages. No build step and no API key are required.

Recommended demo flow:

1. explain the product in one sentence: “This is an operating system for a one-person company.”
2. click a different project in the sidebar
3. switch scene skins to show Hawker / Trading Floor / Gardens
4. click **RUN DEMO**
5. click an agent to inspect it
6. CHOP or SEND BACK an output in the approval queue

## Why it matters

The bottleneck for a one-person company is not just access to AI. It is **control, visibility and trust**.

Today, founders use scattered chats, automations and tools. TowkAI OS gives them one visual control plane for projects, agents, work status and approvals.

## Architecture

Hackathon MVP:

- static HTML, CSS and JavaScript
- no dependencies
- responsive single-page app
- deterministic simulation for reliable judging

Production path:

- connect real agent runtimes and APIs
- persist project memory and task history
- support real approvals and handoffs
- add cost controls and observability
- allow installable third-party agent modules

## Business model

1. SaaS subscriptions by projects, active agents and monthly executions
2. usage-based pricing for orchestration and model calls
3. marketplace revenue share from third-party agents and skills
4. premium first-party GTM, research, BD and ops modules
5. white-label control planes for agencies and micro-teams

## Built for

BUIDL_OPC_SG_0712 — Singapore, July 12, 2026.

## Pitch and submission assets

- `SUBMISSION.md` — paste-ready OpenArena submission copy
- `PITCH.md` — 30-second and 60-second pitch scripts, demo flow and judge Q&A
- `SCREENSHOT_GUIDE.md` — exact screenshots, captions and recording sequence
