# Basetrip (basetrip)
Basetrip is a travel intelligence platform providing APIs for country and city data, travel phrases, safety ratings, visa requirements, cost of living estimates, and health advisories. Designed to help travel apps, booking platforms, and trip planning tools differentiate their products and improve traveler experiences.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/basetrip/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cities, Countries, Health, Safety, Travel, Visa

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-04-19

## APIs

### Basetrip API
Travel intelligence API providing country details, city data, travel phrases, safety ratings, visa requirements, cost estimates, and health advisories.

**Human URL:** [https://www.thebasetrip.com/en/documentation/v3](https://www.thebasetrip.com/en/documentation/v3)

#### Properties

- [Documentation](https://www.thebasetrip.com/en/documentation/v3)
- [OpenAPI](openapi/basetrip-api-openapi.yml)

## Common Properties

- [Website](https://www.thebasetrip.com/)
- [Documentation](https://www.thebasetrip.com/en/documentation/v3)
- [Sign Up](https://www.thebasetrip.com/en/sign_up)
- [Pricing](https://www.thebasetrip.com/en/pricing)

## Features

| Name | Description |
|------|-------------|
| Country Data | Country names, slugs, alpha-2 codes, capital, currency, languages, population, and timezone. |
| City Data | City names, slugs, geographic coordinates, and timezone information per country. |
| Travel Phrases | Language phrases for travel in English, French, German, Italian, and Spanish. |
| Safety Ratings | Country safety ratings and travel advisory levels from 1 (normal) to 4 (do not travel). |
| Cost Estimates | Daily budget estimates for budget, mid-range, and luxury traveler tiers. |
| Visa Requirements | Visa requirement lookup by passport country and destination country. |
| Health Advisories | Vaccination requirements, health risks, drinking water safety, and medical facility ratings. |

## Use Cases

| Name | Description |
|------|-------------|
| Travel App Integration | Embed country and city intelligence directly into travel booking apps. |
| Trip Planning Tools | Provide travelers with safety, cost, and visa information before booking. |
| Destination Guides | Power destination content with live data on safety, costs, and health. |
| Travel Risk Assessment | Assess travel risk using safety ratings and health advisories for corporate travel. |
| Language Assistance | Surface travel phrases in destination language for traveler communication tools. |

## Artifacts

### OpenAPI

- [Basetrip API](openapi/basetrip-api-openapi.yml)

### JSON-LD

- [Basetrip JSON-LD Context](json-ld/basetrip-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Basetrip API](capabilities/shared/basetrip-api.yaml) — 9 key operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Travel Intelligence](capabilities/travel-intelligence.yaml) | Basetrip | 7 | Travel App Developer, Trip Planner, Travel Content Publisher |

## Vocabulary

- [Basetrip Vocabulary](vocabulary/basetrip-vocabulary.yaml) — 7 resources, 2 actions, 1 workflow, 3 personas

## Rules

- [Basetrip Spectral Rules](rules/basetrip-spectral-rules.yml) — 15 rules enforcing API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
