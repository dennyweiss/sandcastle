---
"@ai-hero/sandcastle": patch
---

Add a hint to the `sequential-reviewer` and `simple-loop` implement prompts noting that the issue list is already filtered and discouraging an unfiltered re-query, so the agent is less likely to bypass the configured label filter when the list is empty.
