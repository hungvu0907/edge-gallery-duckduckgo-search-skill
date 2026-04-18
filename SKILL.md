---
name: search-duckduckgo
description: Perform a web search using DuckDuckGo to find real-time information, news, or external references.
---

# Search DuckDuckGo

## Instructions

Call the `run_js` tool using `index.html` and a JSON string for `data` with the following field:
- **query**: Required. The exact search phrase or keywords to look up on the web (e.g., "latest Next.js release notes", "weather in Chatrapur today").

**Constraints:**
- Read through the returned snippets and synthesize the information to directly answer the user's prompt.
- Do not blindly list the raw search results unless explicitly asked to do so. Formulate a coherent response based on the facts provided in the summaries.
- If the top search results contradict each other or lack the specific answer, explicitly state that the search results were inconclusive.
- Always provide responses in the same language as the user's prompt. 
- If appropriate, cite the source by referencing the title or URL of the provided search results.
