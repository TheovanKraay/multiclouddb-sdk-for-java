---
description: Recall relevant memories from previous coding sessions
agent: agent
tools:
  - runInTerminal
argument-hint: Enter your question or topic to search memory for
---

Run the following command in the terminal to search persistent memory, using the user's message as the search query:

```
.github\skills\repo-memory\.venv\Scripts\python.exe .github/skills/repo-memory/scripts/memory_cli.py recall "$PROMPT" --top-k 5
```

Use the returned memories to inform your response. These contain decisions, preferences, and conventions from previous coding sessions.
