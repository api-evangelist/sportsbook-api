# Sportsbook API

Sportsbook API provides real-time sports betting odds data from major US sportsbooks including FanDuel, DraftKings, BetMGM, Kalshi, theScore, Fanatics, BetRivers, Polymarket, Bovada, and BetOnline. The API aggregates spreads, moneylines, totals, halves, quarters, player props, and futures for NFL, NBA, MLB, NHL, NCAA football, NCAA basketball, and soccer leagues. Includes tools to identify positive expected value (+EV) bets, arbitrage opportunities, and middling situations. Odds update once per minute.

**URL:** [https://sportsbookapi.com/](https://sportsbookapi.com/)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Sports Betting, Odds, Sports Data, Gambling

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-02

## APIs

### Sportsbook API

Real-time sports betting odds aggregator from 10+ major US sportsbooks covering NFL, NBA, MLB, NHL, NCAA, and soccer with spread, moneyline, total, and prop markets plus arbitrage and +EV detection.

**Human URL:** [https://sportsbookapi.com/](https://sportsbookapi.com/)

**Base URL:** `https://api.sportsbookapi.com`

#### Tags

Sports Betting, Odds, NFL, NBA, MLB, NHL, Soccer, Arbitrage, Expected Value

#### Properties

- [Documentation](https://sportsbookapi.com/documentation/)
- [OpenAPI](openapi/sportsbook-api-openapi.yml)
- [Pricing](https://sportsbookapi.com/pricing/)

## Common Properties

- [Website](https://sportsbookapi.com/)
- [Portal](https://sportsbookapi.com/documentation/)
- [Pricing](https://sportsbookapi.com/pricing/)

## Artifacts

### OpenAPI

- [Sportsbook API OpenAPI](openapi/sportsbook-api-openapi.yml) — REST API specification for odds, arbitrage, and betting analysis endpoints

### Spectral Rules

- [Sportsbook API Rules](rules/sportsbook-api-rules.yml) — Spectral ruleset enforcing Sportsbook API conventions

### JSON Schema

- [Odds Schema](json-schema/sportsbook-api-odds-schema.json) — Schema for odds response data
- [Arbitrage Schema](json-schema/sportsbook-api-arbitrage-schema.json) — Schema for arbitrage opportunity data

### JSON Structure

- [Odds Structure](json-structure/sportsbook-api-odds-structure.json) — Structure documentation for odds, arbitrage, and betting analysis data

### JSON-LD

- [Sportsbook API Context](json-ld/sportsbook-api-context.jsonld) — JSON-LD context for sports betting data

### Examples

- [Get Odds Example](examples/sportsbook-api-get-odds-example.json) — Example for retrieving NFL odds from multiple sportsbooks
- [Get Arbitrage Example](examples/sportsbook-api-get-arbitrage-example.json) — Example for finding arbitrage opportunities

### Vocabulary

- [Sportsbook API Vocabulary](vocabulary/sportsbook-api-vocabulary.yml) — Domain vocabulary for sports betting terminology

### Capabilities

#### Shared Definitions
- [Sportsbook API](capabilities/shared/sportsbook-api.yaml) — Per-API capability definition

#### Workflow Capabilities
- [Betting Analysis](capabilities/betting-analysis.yaml) — Odds comparison, arbitrage, +EV, and middle detection workflow

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
