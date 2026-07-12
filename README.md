# TowkAI OS 頭家

**TowkAI** plays on **“towkay” — boss in Hokkien**.

It is a gamified pixel-art AI agent IDE for **One-Person Companies (OPCs)**: one place to see what every AI agent is doing, track progress and updates, inspect real outputs, and intervene when needed.

## Core MVP loop

**Observe → inspect → understand → intervene → approve**

- **Observe:** see every project and agent status from one screen
- **Inspect:** open an agent to view its objective, plan, current step, activity and artifacts
- **Understand:** see progress, priority, ETA, blockers and recent updates
- **Intervene:** pause, resume, reprioritise, change the task, unblock or send to review
- **Approve:** preview a real artifact, approve it or request revision

## Submission-ready features

### First-time clarity
- automatic quick tour
- guided end-to-end demo
- “MVP in 10 seconds” explanation
- map legend and next-best-action card
- explicit “click to inspect” labels

### Functional agent IDE
- responsive Agent Inspector drawer
- Overview, Plan, Activity, Artifacts and Controls tabs
- detailed task plans and current-step highlighting
- real artifact previews, copy, approval and revision flow
- project filtering that changes the active workspace
- visible Founder Attention queue for blockers and approvals

### Real data connector
- connect any public GitHub repository
- load real repository metadata and recent commits
- inject live repository activity into the Builder agent
- preview the connected repository as an artifact

### Gamified pixel world
- agents move according to real status
- task parcel moves to the selected agent
- animated monitors and support bot
- Hawker Centre, Trading Floor and Gardens by the Bay skins
- XP, quests, achievements and approval effects

## Demo flow

1. Open the app and run the Guided Demo.
2. Click an agent or `OPEN DETAILS`.
3. Open the **Plan**, **Activity** and **Artifacts** tabs.
4. Preview an artifact and request revision or approve it.
5. Resolve a blocked agent from Founder Attention.
6. Connect `defipaca/towkAI` through the public GitHub connector.
7. Show the Builder agent populated with real commit activity.

## Architecture

Hackathon MVP:
- static HTML, CSS and JavaScript
- no build step
- deterministic agent simulation for reliable judging
- public GitHub API integration for real repository activity

Production path:
- connect Codex, Claude Code, research agents and workflow platforms
- ingest live agent events through adapters/webhooks
- persist memory, artifacts and approvals
- add permissions, cost controls and team governance

## Built for

BUIDL_OPC_SG_0712 — Singapore, July 12, 2026.
