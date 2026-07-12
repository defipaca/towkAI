# TowkAI OS 頭家

**A pixel-art MVP for seeing what your AI agents are doing, tracking their progress, and controlling them from one place.**

## What this product is

TowkAI OS is a **gamified AI agent IDE**.

Its core job is simple:

> Help a founder see all active AI agents across projects, understand what each one is doing, and step in when needed.

Instead of jumping between chats, automation tools and dashboards, the founder gets one control room.

## What the MVP demonstrates

This MVP is designed to be understandable in seconds.

### Core MVP promise
- **See all agents in one place**
- **Track live status and progress**
- **Read recent updates from each agent**
- **Know what needs your attention**
- **Pause, redirect, unblock or approve work**

### How the interface works
- **Left sidebar:** what the product is, projects, and AI agent roster
- **Center map:** pixel-art operations world where agents move based on current activity
- **Right inspector:** selected agent’s task, progress, output, and recent updates
- **Bottom feed:** recent system and agent activity
- **Founder Attention panel:** blocked or approval-waiting work

## First-time user clarity features

To make the MVP easy for judges and first-time users, it includes:

- a **“What you are building”** starter panel
- a **Welcome / Quick Tour popup** on first load
- a **“MVP in 10 seconds”** explainer card
- a **“How to read this”** legend on the map
- visible status labels for every agent

## Agent behaviors in the demo

The pixel agents are not random decoration.

They move based on agent state:

- **Running** → move to the relevant work room
- **Needs Review** → move to Founder Review
- **Blocked** → stay at review with a blocker bubble
- **Done** → move to Ops / Memory
- **Idle** → move out of the active workflow

## Scene skins

The same operating system can be viewed with different Singapore-flavoured skins:

- **Hawker Centre**
- **Trading Floor**
- **Gardens by the Bay**

These are aesthetic skins over the same operational model.

## Demo flow

1. Open the app
2. Let the quick-tour popup explain the concept
3. Click **Run Live Demo**
4. Click different agents in the roster or map
5. Show how the right inspector explains exactly what each agent is doing
6. Resolve items in **Founder Attention**

## Architecture

Hackathon MVP:

- static HTML, CSS and JavaScript
- zero dependencies
- no API key required
- deterministic simulated updates for reliable demos

Production direction:

- connect real agent runtimes and APIs
- ingest real status, progress and agent logs
- persist task history and agent memory
- support messaging and approvals between founder and agents
- add multi-user and permission controls

## Why it matters

The main bottleneck for AI-powered one-person companies is not just access to agents.
It is **visibility, confidence and control**.

TowkAI OS solves that by making the invisible visible.

## Built for

BUIDL_OPC_SG_0712 — Singapore, July 12, 2026.
