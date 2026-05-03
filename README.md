# US House of Representatives

The United States House of Representatives is one of the two chambers of the United States Congress, with the other being the Senate. Its main function is to pass federal legislation, which must then be approved by the Senate before it can become law. The House also has the power to impeach government officials, including the President, and to initiate revenue-related bills. Congressional data is made available through the Congress.gov API, a REST API maintained by the Library of Congress that provides access to bills, members, committees, amendments, nominations, and treaties.

**URL:** [https://www.house.gov](https://www.house.gov)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

`Federal Government` `Legislation` `Congress` `Legislative Data` `Bills` `Members` `Committees`

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-03

## APIs

| API | Description |
|-----|-------------|
| [Congress.gov API](https://www.loc.gov/apis/additional-apis/congress-dot-gov-api/) | Official REST API for congressional data - bills, members, committees, nominations |
| [ProPublica Congress API](https://projects.propublica.org/api-docs/congress-api/) | Third-party API with voting records, member profiles, and legislative activity |

## OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [Congress.gov API](openapi/congress-gov-api-openapi.yml) | OpenAPI 3.0 spec for Congress.gov v3 API |

## Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [Congress.gov API Rules](rules/congress-gov-api-rules.yml) | Spectral rules for Congress.gov API conventions |

## Naftiko Capabilities

### Workflow Capabilities

| Capability | Description |
|------------|-------------|
| [Legislative Research](capabilities/legislative-research.yaml) | Congressional bill tracking, member research, and committee monitoring |

### Shared API Definitions

| Shared Definition | Description |
|-------------------|-------------|
| [Congress.gov API](capabilities/shared/congress-gov-api.yaml) | Shared definition for Congress.gov API |

## JSON Schema

| Schema | Description |
|--------|-------------|
| [Bill Schema](json-schema/congress-gov-bill-schema.json) | Schema for congressional bills |
| [Member Schema](json-schema/congress-gov-member-schema.json) | Schema for members of Congress |

## JSON Structure

| Structure | Description |
|-----------|-------------|
| [Bill Structure](json-structure/congress-gov-bill-structure.json) | Field documentation for congressional bills |

## JSON-LD

| Context | Description |
|---------|-------------|
| [Congress Context](json-ld/us-house-of-representatives-context.jsonld) | Linked data context for congressional data |

## Examples

| Example | Description |
|---------|-------------|
| [List Bills Example](examples/congress-gov-list-bills-example.json) | Example response listing congressional bills |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [Congress Vocabulary](vocabulary/us-house-of-representatives-vocabulary.yml) | Domain vocabulary for legislation and congressional process |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
