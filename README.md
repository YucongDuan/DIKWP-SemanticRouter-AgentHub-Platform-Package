# DIKWP SemanticRouter AgentHub Platform Package

A concrete platform delivery package for DIKWP-based content semantic routing, agent-hub/proxy coordination, group semantic collaboration, and cognitive interaction among agents.

## Quick start

1. Open `prototype/index.html` in a browser.
2. Run `python src/semantic_router_demo.py` to generate `data/sample_route_log.json`.
3. Review `docs/01_DIKWP_SemanticRouter_Platform_Blueprint.docx` first.
4. Use `DIKWP_SemanticRouter_Policy_Matrix.xlsx` to maintain agent registry, route policies, score formulas, evidence, claims and benchmark results.

## Core idea

Every user request, agent message, tool result and external event is transformed into a DIKWP Semantic Packet before routing. The platform chooses agents according to semantic layer, evidence need, purpose boundary, risk grade, permission, trust score, cost and latency. It records each decision in a replayable audit bundle.

## Key folders

- `docs/`: platform blueprint, PRD, protocol, governance, implementation, use cases and integration guide.
- `prototype/`: offline browser demo.
- `api/`: OpenAPI draft.
- `schemas/`: JSON Schemas.
- `templates/`: reusable markdown and CSV templates.
- `src/`: offline routing demo.
- `data/`: sample agents, tasks and route logs.
- `adapters/`: MCP, A2A and LangGraph integration notes.
