# Agent handoff

1. This public repository is only a discovery entry point. It is not the source of operational authority.
2. Via an already-authorized private runtime/Cloudflare connector, locate the private D1 `settings` record with key `agent_handoff_sop_v2`. This is the current handoff navigation SOP; do not copy its contents into public GitHub.
3. Follow that private SOP to enter the authorized DMM runtime and CT101. CT101 SQLite owns Discovery, AI review, Like and Comment task states. GitHub is **not** the article queue or private datastore.
4. Verify the live system, current permissions, and actual results before taking action. Use the CT101 task queue: unfinished Discovery review first, then Comment candidates from verified Likes. Quota-limited Gemini reviews remain parked for later processing or other authorized AI reviewers.
5. Keep runtime identifiers, topology, secrets, SOP details, approvals and interaction history private. Do not use public GitHub Issues to relay private state.
6. Never revive archived publication paths. If D1/private runtime access is unavailable, stop and report that limitation; do not guess endpoints.
7. Follow the internal authorization boundaries; use authenticated readback after external writes and never blindly repeat ambiguous actions.
