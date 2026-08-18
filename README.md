I build recruiting-operations software: the systems around the ATS that make hiring actually run — ingestion, analytics, automation, and AI access with the permission model enforced. The five repositories pinned below are working systems, each cut public from production code with tenant data replaced by shaped fixtures. Every one verifies from a fresh clone: install, test, build, no credentials.

- **[riddy](https://github.com/sam-vangelos/riddy)** — Cursor for dirty ATS data: a deterministic workflow-debt engine for recruiting operations.
- **[long-horizon-sourcing-agent](https://github.com/sam-vangelos/long-horizon-sourcing-agent)** — multi-hour governed browser runs over LinkedIn Recruiter and the GitHub API, with crash-safe canonical state and a post-run learning loop.
- **[Rosie](https://github.com/sam-vangelos/Rosie)** — few-shot resume ranking over live ATS pipelines: rubric generation, revealed-preference calibration, and three model runtimes behind one byte-locked contract.
- **[recruiting-analytics-platform](https://github.com/sam-vangelos/recruiting-analytics-platform)** — Greenhouse-to-Postgres ELT, SLA sweeps, identity resolution, and permit-gated Google Workspace automation, gated by an AST architecture checker and a mutation corpus.
- **[greenhouse-mcp](https://github.com/sam-vangelos/greenhouse-mcp)** — scoped MCP servers for Greenhouse: per-user permission enforcement on every read, paired preview/apply writes, and an evidence-gated rollout.

<!-- pinned: the five portfolio repositories above -->
