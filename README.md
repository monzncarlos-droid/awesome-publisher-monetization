# Awesome Publisher Monetization

A curated list of tools, standards, and resources for web publisher monetization: ad revenue audits, ads.txt / supply-chain hygiene, header bidding, yield, consent, adblock recovery, agentic advertising, and account-safety monitoring. PRs welcome.

> Maintained by [Sulvo](https://sulvo.com). If you run a publisher site, start with the free [Publisher Revenue Audit](https://www.npmjs.com/package/publisher-revenue-audit-mcp) — one command, no login.

## Audits & revenue diagnostics

- [Publisher Revenue Audit (Sulvo)](https://github.com/Aratives/publisher-revenue-audit-mcp) — CLI + MCP server that scans a site for GAM/AdSense tag issues, ads.txt hygiene, CMP/consent gaps, viewability and layout risks. Free, no login.
- [adagents.json Studio (Sulvo)](https://github.com/Aratives/adagents-studio) — generate, validate, and check the AdCP `adagents.json` ("ads.txt for agents") declaration.

## Standards & protocols

- [IAB Tech Lab ads.txt](https://iabtechlab.com/ads-txt/) — authorized seller declaration.
- [IAB Tech Lab sellers.json / SupplyChain](https://iabtechlab.com/standards/sellers-json/) — supply-chain transparency.
- [Prebid.js](https://github.com/prebid/Prebid.js) — open-source header bidding; see the [price floors module](https://docs.prebid.org/dev-docs/modules/floors.html).
- [AdCP (Ad Context Protocol)](https://github.com/adcontextprotocol/adcp) — agentic advertising standard; `adagents.json`, media-buy tasks.
- [IAB Tech Lab AAMP](https://iabtechlab.com/standards/agentic-advertising-and-ai/) — agentic advertising management protocols.
- [RSL (Really Simple Licensing)](https://rslstandard.org/) — machine-readable AI-use licensing for content.

## Reference data & benchmarks

- [Coalition for Better Ads](https://www.betterads.org/) — ad experience standards (incl. the 30% mobile density rule).
- [eyeo Ad Blocking Report](https://eyeo.com/) — adblock usage research.

## Consent & privacy

- [Google-certified CMPs](https://support.google.com/admanager/answer/10113217) — required for EEA/UK traffic monetization.
- [IAB TCF](https://iabeurope.eu/transparency-consent-framework/) · [IAB GPP](https://iabtechlab.com/standards/gpp/)

## Contributing

Know a tool that belongs here? Open a PR with a one-line description and a link. Entries must be free to start and useful to publishers.
