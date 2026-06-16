# AgentFleet

**Parallel AI Agent Fleets that ship while you sleep.**

Hierarchical agent orchestration platform inspired by Cursor's internal system. One fleet manager + hundreds of child agents with monitoring, auto-restart, and human escalation.

[GitHub](https://github.com/jckniffin-blip/AgentFleet) • [Join Waitlist](#) • [Demo](#)

## ✨ Features
- Hierarchical Fleet Manager (supervisor + workers)
- Automatic health checks & restarts
- Task distribution & result aggregation
- Cost controls + Slack/PagerDuty alerts
- Parallel execution (10–1000+ agents)
- Built for Cursor, Claude, Grok, and OpenAI agents

## Quick Start

```bash
# Clone
git clone https://github.com/jckniffin-blip/AgentFleet.git
cd AgentFleet

# Backend
cd backend
uv sync
uv run main.py

# Frontend
cd ../frontend
npm install
npm run dev
