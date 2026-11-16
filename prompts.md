# Web Analytics MCP Server: prompts to copy

Paste these into Claude, Claude Code or Cursor once the server is set up with `SEMUST_MCP_TOOLSETS=metrik`. If you have several Semust projects, name the one you mean, or the assistant will ask. Dates are worked out for you; say "last 30 days" or "last month".

## Right now

- How many people are on the site right now, and on which pages?
- Compare today's visitors by channel with yesterday.
- Is the tracking script installed and reporting?

## Traffic

- How did visitors, visits and bounce rate change this month versus last month?
- Which day did my traffic drop in the last 30 days?
- Show the top pages for visitors on phones.
- Which UTM campaigns brought the most visits this week?

## Funnels and paths

- Where is the biggest drop in /products → /cart → /checkout?
- What page sequence do homepage visitors follow most often?
- How many people go from /pricing to /signup?

## Events and goals

- Did form submissions drop this month compared to last month?
- Which goals convert best, and at what rate?
- Did outbound link clicks change this week compared with last week?

## Revenue

- Which channels sold my best-selling products in the last 30 days?
- Break down revenue by country and by device.

## Speed and usage

- Which 10 pages have the worst 75th percentile LCP?
- Which devices and browsers have the worst INP?
- How many billable events have I used this month?

Setup and the full tool list are in the [README](README.md).
