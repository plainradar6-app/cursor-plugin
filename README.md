# Plainradar for Cursor

Live news search for Cursor's agent. Ask what is new about a company, person, topic or event, and the agent gets
the stories published in the last 24 hours (or up to 7 days back), each with its headline, link, source,
publication time, a short summary and the number of sources covering it.

- **Only recent news.** News sites and blogs are read at the moment of the call.
- **Duplicates are grouped.** A wire story republished by twenty outlets comes back as one story with "20 sources".
- **Relevance is checked first.** Each story is verified against the question before the agent sees it.
- **45 languages**, plain-language filters ("skip opinion pieces") and an optional short briefing.

The plugin adds one remote MCP server, `https://plainradar.com/mcp`, with one read-only tool, `search_news`.

## Setup

1. Install the plugin from the Cursor Marketplace.
2. The first time the agent uses it, Cursor asks you to sign in. A Plainradar page opens: log in, or enter your
   email to get a free account with 50 search credits, then press **Allow**.

No API key or configuration is needed. Each new search uses one credit; further pages of the same search and
filters are included. More credits can be bought at [plainradar.com](https://plainradar.com).

## Example prompts

- "What's new in artificial intelligence today? Group the stories by company and link the sources."
- "What happened in space exploration this week? Skip opinion pieces."
- "What are French news outlets writing about artificial intelligence today?"

## Links

- Documentation: https://plainradar.com/blog/news-mcp-server-for-ai-agents
- Privacy policy: https://plainradar.com/privacy
- Support: https://plainradar.com/#contact

## License

MIT (this repository holds the plugin's manifest only; the Plainradar service has its own
[terms](https://plainradar.com/terms)).
