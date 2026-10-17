# Market Monitoring & Telegram Approval Workflows

A modular n8n automation project for collecting market data, tracking candidate events, coordinating Telegram review, and following outcomes.

## Purpose

Market monitoring requires repeated collection and follow-up. This project organizes those tasks into separate workflows, with Google Sheets storing records and Telegram providing notifications and review interactions.

## Workflow architecture

| Module | Responsibility |
| --- | --- |
| Watchlist refresh | Prepare a market watchlist using CoinGecko and Binance information. |
| Market-event scanner | Retrieve candle data, analyze candidate events, and write event records. |
| Telegram approval handling | Coordinate review decisions and publication-related status checks. |
| Outcome monitoring | Revisit pending events or signals and record evaluated outcomes. |
| Performance reporting | Prepare summaries from recorded events and results. |
| Health and error monitoring | Check workflow execution health and send operational alerts. |

## Tools

n8n, HTTP APIs, JavaScript workflow steps, Google Sheets, Telegram, Binance, and CoinGecko.

## Operating scope

The project has been developed as a multi-workflow system. Its documented handoff scope is private-admin delivery and shadow evaluation, with public-channel publication disabled. Approval and publishing-related components should not be read as a claim that public publishing is enabled.

This repository presents the automation architecture. It does not establish profitable trading performance or validated financial predictions. Live reliability and outcome metrics require dated execution records.

## What this project demonstrates

- Coordinating scheduled workflows around shared records.
- Connecting external APIs to Telegram and Google Sheets.
- Separating candidate detection, review, follow-up, and reporting.
- Adding health checks and a dedicated error-alert workflow.

## Reviewing the implementation

Workflow screenshots document the structure. A reproducible release should include sanitized workflow exports, configuration instructions, and a recorded end-to-end demonstration. Screenshots alone do not establish runtime behavior.

Before publishing exports or execution data, remove credentials, private endpoints, personal identifiers, and customer data.

## Related work

[AI-assisted news curation and publishing](https://github.com/mrasoolghd10-glitch/ai-crypto-news-automation) · [LinkedIn](https://www.linkedin.com/in/mohammad-rasool-gholami/)
