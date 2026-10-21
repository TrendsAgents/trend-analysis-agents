<div align="center">

<a href="https://trendsagents.com/?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents"><img src="https://trendsagents.com/brand/trendsagents.com/logo.png" width="80" height="80" alt="Trends Agents logo"></a>

# Trends Agents: AI trend analysis for Claude, Cursor and ChatGPT

AI agents for trend analysis and trend forecasting. Each agent takes a live board (Google Trends, TikTok, YouTube, Reddit, Amazon and 15 more), then checks growth and history to tell a spike from a trend that lasts.

[![Free plan](https://img.shields.io/badge/Free-100%20requests/month-2ea44f?style=for-the-badge)](https://trendsagents.com/pricing?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents)
[![MCP](https://img.shields.io/badge/MCP-remote%2C%20OAuth-6E56CF?style=for-the-badge)](https://trendsagents.com/docs?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents)
[![License: MIT](https://img.shields.io/badge/License-MIT-555555?style=for-the-badge)](LICENSE)

**[Website](https://trendsagents.com/?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents)** · **[Get started free](https://trendsagents.com/account?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents)** · [Docs](https://trendsagents.com/docs?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) · [Pricing](https://trendsagents.com/pricing?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) · [All agents](https://trendsagents.com/data-sources?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents)

</div>

```
You: Something is trending on YouTube. Should I make a video about it?

Claude: (YouTube agent: reads YouTube Trending, then YouTube search growth for the title)
        Film, wait, or skip, with the growth numbers behind the call...
```

## Connect in 10 seconds

Pick your app. Every button opens it with Trends Agents already filled in. Claude and ChatGPT sign you in with your Trends Agents account, so there is no API key to copy.

<p align="center">
  <a href="https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=Trends%20Agents&connectorUrl=https%3A%2F%2Ftrendsagents.com%2Fmcp"><img src="https://img.shields.io/badge/Add%20to-Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Add to Claude"></a>
  <a href="https://chatgpt.com/plugins#settings/Connectors?create-connector=true&redirectAfter=%2Fplugins"><img src="https://img.shields.io/badge/Add%20to-ChatGPT-10A37F?style=for-the-badge&logo=openai&logoColor=white" alt="Add to ChatGPT"></a>
  <a href="https://cursor.com/en/install-mcp?name=trendsagents&config=eyJ1cmwiOiAiaHR0cHM6Ly90cmVuZHNhZ2VudHMuY29tL21jcCJ9"><img src="https://img.shields.io/badge/Add%20to-Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white" alt="Add to Cursor"></a>
  <a href="https://insiders.vscode.dev/redirect/mcp/install?name=trendsagents&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A//trendsagents.com/mcp%22%7D"><img src="https://img.shields.io/badge/Add%20to-VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Add to VS Code"></a>
</p>

| App | After you click |
|---|---|
| **Claude** | The connector name and URL are prefilled. Confirm, sign in to Trends Agents, approve access. |
| **ChatGPT** | Turn on Developer mode under Settings → Security and login. Name it `Trends Agents`, URL `https://trendsagents.com/mcp`, choose OAuth, sign in. |
| **Cursor** | Approve the install. Sign in to Trends Agents when Cursor asks. |
| **VS Code** | Approve the install. Open Chat in Agent mode and enable the Trends Agents tools. |

**Server URL:** `https://trendsagents.com/mcp`

**Every coding agent at once** (Cursor, Claude Code, VS Code, Windsurf and more, detected automatically):

```bash
npx add-mcp https://trendsagents.com/mcp
```

Then ask: `Using Trends Agents, what's trending on Google right now?`

<details>
<summary><b>Claude Code</b></summary>

```bash
claude mcp add --transport http trendsagents https://trendsagents.com/mcp
```

</details>

<details>
<summary><b>Grok</b></summary>

In Grok, open Connectors, choose **New Connector**, then **Custom**, and paste `https://trendsagents.com/mcp`. Sign in to Trends Agents when asked. Menu names can differ slightly per plan.

</details>

<details>
<summary><b>Any other MCP client</b></summary>

Add a remote MCP server (streamable HTTP) with the URL `https://trendsagents.com/mcp` and sign in when prompted. Prefer an API key? [Get a free key](https://trendsagents.com/account?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents): the account page has buttons for Cursor and VS Code with your key already included.

</details>

Full setup for every app: [trendsagents.com/docs](https://trendsagents.com/docs?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents).

## What you can ask

- Is "protein coffee" a lasting trend or a spike?
- Which TikTok hashtags are memes and which are staying tags?
- Is this Amazon best seller actually searched, or only a chart hit?
- Compare pandas and polars downloads on PyPI over 12 months.
- Is the game at the top of Steam a weekend spike or still played?

Tip: start with "Using Trends Agents" so your AI uses these tools instead of a web search.

## 20 trend agents

Each agent starts from a live board, then checks growth or history to answer one question.

| Agent | Answers |
|---|---|
| [Google Trends agent](https://trendsagents.com/google-trends-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Spike versus lasting demand |
| [Google Shopping agent](https://trendsagents.com/google-shopping-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Shopping demand versus browsing |
| [YouTube trending agent](https://trendsagents.com/youtube-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Film, wait, or skip |
| [TikTok hashtags agent](https://trendsagents.com/tiktok-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Meme versus staying tag |
| [Reddit Hot agent](https://trendsagents.com/reddit-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Subreddit growth behind a hot post |
| [Amazon Best Sellers agent](https://trendsagents.com/amazon-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Chart hit versus searched product |
| [Wikipedia pageviews agent](https://trendsagents.com/wikipedia-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | News burst versus a page people keep opening |
| [Google News agent](https://trendsagents.com/news-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | News volume and sentiment on a headline |
| [Google Play agent](https://trendsagents.com/app-downloads-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Chart position versus installs |
| [App Store agent](https://trendsagents.com/app-store-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Top Free versus Top Paid |
| [npm downloads agent](https://trendsagents.com/npm-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Package growth versus a rival |
| [Steam Charts agent](https://trendsagents.com/steam-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Weekend spike versus a game people still play |
| [PyPI stats agent](https://trendsagents.com/pypi-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Python package growth, e.g. pandas versus polars |
| [X trending agent](https://trendsagents.com/twitter-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Trending topic versus search growth |
| [Spotify podcasts agent](https://trendsagents.com/spotify-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Chart versus people searching the show |
| [GitHub trending agent](https://trendsagents.com/github-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Trending repo versus package downloads |
| [IMDb MOVIEmeter agent](https://trendsagents.com/imdb-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Popularity versus searches for the title |
| [Open Library agent](https://trendsagents.com/open-library-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Trending book versus search and page views |
| [Most visited websites agent](https://trendsagents.com/websites-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Traffic rank versus branded search |
| [Substack agent](https://trendsagents.com/substack-agent?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents) | Leaderboard versus searches for the newsletter |

## Tools

Three read-only tools. Your AI picks the right one from your question.

| Tool | Use when | Needs a keyword? |
|---|---|---|
| `get_top_trends` | What is ranking on a platform right now | No |
| `get_growth` | Percent change over 7D to 5Y, several windows and sources in one call | Yes |
| `get_time_series` | Up to 5 years of history for one keyword on one source | Yes |

<details>
<summary><b>Keyword sources</b> for <code>get_time_series</code> and <code>get_growth</code></summary>

| `source` | Signal | `keyword` |
|---|---|---|
| `google search` | Google search volume | Any phrase |
| `google images` | Image search volume | Any phrase |
| `google news` | News-tab search volume | Any phrase |
| `google shopping` | Shopping-tab search volume | Any phrase |
| `youtube` | YouTube search volume | Any phrase |
| `tiktok` | Hashtag volume | Hashtag or topic, no # |
| `reddit` | Subreddit attention | Subreddit name, no r/ |
| `amazon` | Product search volume | Product or category |
| `wikipedia` | Page views | Article title |
| `news volume` | News mention volume | Any phrase |
| `news sentiment` | News tone | Any phrase |
| `app downloads` | Android downloads | Play bundle id, e.g. com.openai.chatgpt |
| `app rankings` | Android chart position | Play bundle id |
| `npm` | Weekly npm downloads | Exact package name |
| `steam` | Concurrent players | Game display name |
| `python` | PyPI downloads | Exact project name |

</details>

## Free and paid

| Plan | Requests a month | Price |
|---|---|---|
| Free | 100 | $0 |
| Starter | 1,000 | $19 / month |
| Pro | 5,000 | $49 / month |
| Business | 25,000 | $199 / month |

Every plan has every source. Annual billing saves 20%. Only successful calls count. [Get started free](https://trendsagents.com/account?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents): email and an 8-digit code, no password, no credit card.

## FAQ

**Trend vs fad: how do I tell?**  
A fad spikes and falls back within weeks. A trend keeps growing over months. Each agent checks both: the short window (7D, 1M) against the long one (12M, 5Y).

**What is AI trend analysis?**  
An AI assistant reads live trend boards and growth data for you, then explains what is rising and whether it lasts. These agents give Claude, Cursor and ChatGPT that data through MCP.

**Which platforms are covered?**  
Google Trends, Google Shopping, Google News, YouTube, TikTok, Reddit, X, Amazon, Wikipedia, Google Play, App Store, npm, PyPI, Steam, Spotify, GitHub, IMDb, Open Library, Substack and the most visited websites.

**Is it free?**  
Yes. The free plan has 100 requests a month with every source. No credit card.

## Links

- Website: [trendsagents.com](https://trendsagents.com/?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents)
- Get started free: [trendsagents.com/account](https://trendsagents.com/account?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents)
- Docs and setup for every app: [trendsagents.com/docs](https://trendsagents.com/docs?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents)
- Pricing: [trendsagents.com/pricing](https://trendsagents.com/pricing?utm_source=github&utm_medium=readme&utm_campaign=trend-analysis-agents)
- For AI agents: [trendsagents.com/llms.txt](https://trendsagents.com/llms.txt)
- Support: hello@trendsagents.com

## License

MIT for the contents of this repository. Use of the hosted service follows the [terms of service](https://trendsagents.com/terms).
