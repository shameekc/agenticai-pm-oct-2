# Agent-driven Automation in Products
**Institute of Product Leadership · Cohort ICAIPM2026F · Saturdays, 3:00–6:00 PM IST**
Prof. Shameek Chakravarty

| Session | Date | Theme | Materials |
|---|---|---|---|
| 1 | 24 Oct | Foundations, the AI-native PRD, first agent builds | [`session1/`](session1/) |
| 2 | 31 Oct | MCP, planning, multi-agent systems, the eval problem | [`session2/`](session2/) |
| 3 | 7 Nov | Eval harness, guardrails, token economics, HITL, capstone scoping | Added before Session 3 |
| 4 | 14 Nov | Capstone presentations | |

New materials are added to this repo before each session. Pull (or re-download) before every class.

## Start Here

1. **Read the case:** [`case-study/wren-cx-case-study.md`](case-study/wren-cx-case-study.md). Wren CX is the running case for the course.
2. **Optional:** [`case-study/industry-variant-cards.md`](case-study/industry-variant-cards.md) shows the same case in five other industries, if you want to play around.
3. **Open today's handbook:** [`session2/Session2_Student_Handbook.md`](session2/Session2_Student_Handbook.md) (earlier: [Session 1](session1/Session1_Student_Handbook.md)). We work through it together in class, and every prompt is in it, ready to paste.

## What's Here

| Folder | Contents |
|---|---|
| `case-study/` | The Wren CX case + optional industry variant cards |
| `sample_data/` | Support tickets (`wren_tickets.json`), the simulated CRM (`crm_orders.json`), the golden dataset (`golden_dataset.csv`) and inputs for the PM workflows (`pm_workflow_inputs/`) |
| `mcp-server/` | The Wren mock MCP server (ticket inbox + CRM) for Session 2. Python 3 standard library, nothing to install |
| `templates/` | The Agent Opportunity Canvas (blank) and a filled example for Wren CX |
| `session1/` | The Session 1 handbook |
| `session2/` | The Session 2 handbook and two short decks (`Build_With_A_Coding_Agent_Deck.html`, `Evals_Deck.html`): download and open in a browser |

## Tools

- **Google Antigravity** is the main build tool for the course. If it isn't working on the day, run the handbook prompts in any LLM chat (Claude, ChatGPT, Gemini).
- **Agentic AI Lab:** https://agentic-ai-lab-rho.vercel.app. Browser simulations of each concept on the same Wren case. The handbook links to the right lab at the right point. No login needed.

## Before Session 2 (Sat 31 Oct, 3:00 PM) — connect MCP

Pull this repo, then take 5 minutes before class:

1. Install Python 3 if you don't have it. Step-by-step for Mac and Windows: https://agentic-ai-lab-rho.vercel.app/setup
2. Register the Wren MCP server: follow [`mcp-server/README.md`](mcp-server/README.md).
3. Ask the agent: *"List the tools on the wren MCP server."* You should see 4 tools.

If it won't connect, don't worry: the handbook has simulated tool outputs so you can follow along.

## Homework

- **Homework 1** (team, problem and canvas) and **Homework 2** (individual Agent Teardown): section 10 of the Session 1 handbook.
- **Homework 3** (team, Capstone Canvas v2), due **Thu 5 Nov, 11:59 PM IST**: section 8 of the Session 2 handbook.
