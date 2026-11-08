# OMNICORE — Command Center Prototype

A high-fidelity, interactive AI Business Operating System prototype. Frontend-only **demo** built with React, Vite, Recharts and Lucide. All metrics, business events, agent responses and workflow runs are simulated; there are no connected bank accounts, payment systems, AI model APIs or real enterprise integrations.

## Run

```bash
npm install
npm run dev
npm run build
```

## Prototype interactions

- Overview with financial analysis, activity, approvals and an AI command entry point
- AI Workforce with agent detail panels and simulated agent runs
- Core Intelligence with insights and charts
- Workflows with simulated execution and activity trail
- Businesses workspace and context switching
- Command center with scripted intent-based demo replies
- Search/action palette (⌘K or Ctrl+K)
- Dismiss/approve tasks, activity logging and demo preferences in local storage

## Production architecture (not implemented)

Add authenticated multi-tenant access, role-based permissions, audit trail, Postgres persistence, agent queue/workflow engine, read-only provider OAuth connections, API approval and execution layer, observability, robust data controls, tests, and compliance review before using real business systems. Avoid relying on browser-based demo state for security or actual business processing.
