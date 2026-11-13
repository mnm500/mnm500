# Michael Marrujo

AI Strategist at Container Supply Company, a metal and plastic container manufacturer, and founder of Theron Digital, an AI consulting practice for owner-operated businesses in Southern California.

I build with Claude Code. I find where an operation loses time or data, design the system that fixes it, and ship it into daily use with the people who run it.

Most of my work lives in my employer's private repos: **about 3,000 commits across 15 repos since May 2026, 16 systems deployed, 13 in regular use.**

## Production systems at Container Supply

| System | What changed |
|---|---|
| **Order acknowledgement system** | Replaced a paper and Microsoft Access process. Every order in the system gets four timestamped sign-offs, and 1 in 4 is caught and corrected before production. |
| **Maintenance management (CMMS)**, co-built with one colleague | Took the repair log from empty to about 800 tickets in six months. Required for the plant's SQF food-safety certification. |
| **Plastics operations app** | Replaced an 11-tab spreadsheet retyped every morning. Calculates every rate instead of trusting typed ones, and found scrap under-reported nearly sixfold. |
| **Sage 100 to BigQuery warehouse** | Made ERP data queryable across departments. Refreshed several times a day, with clean full loads on 95% of days. |
| **AR visibility agent** | Routes each overdue invoice to the salesperson who owns the account, 15 days sooner than before. Code computes every figure; AI only writes the wording. |
| **CFO dashboard and monthly AI report** | The dashboard replaced manual Excel pulls. The monthly report runs Claude Sonnet for trends, Claude Opus for recommendations, a fact-check stage, and an AI reviewer that has held the report twice for real errors. |
| **AI Use Policy and Systems Register** | Wrote the policy the Owner and CFO signed, and built the app that enforces it: 31 systems registered, 17 owned by other departments, each checked quarterly. |
| **Bug triage agents** (pilot) | Three agents triage reports from every app into tracked issues: 47 reports, 18 issues, 15 closed. No agent can merge code or send an email on its own. |

## Theron Digital

Built weekly profit and loss by crew and property for a $5M landscape services business, to guide pricing and staffing.

## How I build

- **Right model for the job.** Opus for judgment, Sonnet for execution, plain code wherever arithmetic will do.
- **AI never takes an irreversible step alone.** The safeguard is removing the ability, not writing an instruction.
- **"Not available" beats an invented number.**
- **Run old and new side by side** before switching anything off.
- **Mock it first, put it in front of a real user second, build third.**

## Public work

- [**roomsense**](https://github.com/mnm500/roomsense): a Claude Code skill that teaches interior design while designing a room you actually live in.

## Stack

Claude Code (Opus, Sonnet) · Python · JavaScript / TypeScript · SQL · React · Google Apps Script · Cloudflare Workers, Pages and D1 · BigQuery · Sage 100 over ODBC · GitHub Actions

## Contact

[therondigital.com](https://therondigital.com) · [LinkedIn](https://www.linkedin.com/in/mmarrujo3)
