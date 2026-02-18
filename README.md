# Sandbox as Tool
Agent runs locally/on your server, calls sandbox remotely for execution. Benefits: easy to update agent logic, API keys stay outside sandbox, cleaner separation of concerns.

---
# Architecture pattern (Image credit: Langchain)
In this pattern, the agent runs on your machine or server. When it needs to execute code, it calls a remote sandbox via API.
![Sandbox as tool](/Sanbox_as_tool.png)
