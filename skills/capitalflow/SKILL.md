---
name: capitalflow
description: Use when the user asks about Tel Aviv Stock Exchange (TASE) securities, prices, indices, MAYA filings and report summaries, earnings, or their CapitalFlow watchlist and holdings.
---

# CapitalFlow

CapitalFlow tools give read-only access to Tel Aviv Stock Exchange data. They never change anything.

- Find a security first (search by Hebrew or English name, or the security number), then fetch its page data, prices, reports and summaries.
- Report summaries are produced automatically from the MAYA filing and can contain errors. Quote the figures with their period, and tell the user to confirm material numbers in the original filing.
- Prices can be delayed. Say when the data was last updated if the answer depends on it.
- The user's own lists (watchlist, holdings) are only that user's. Never guess another user's data.
- This is information, not investment advice. Do not recommend buying or selling.
- Requests are rate limited. Prefer one well-aimed call over many; narrow queries by date or security when a result is truncated.
- Access is by invitation. If sign-in says the account has no permission, tell the user to ask CapitalFlow for access.
