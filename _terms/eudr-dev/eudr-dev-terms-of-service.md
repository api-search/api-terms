---
api_specs:
- filename: eudr-dev-a2a-api-openapi.yml
  format: yaml
  label: eudr.dev A2a API
  slug: eudr-dev-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-a2a-api-openapi.yml
- filename: eudr-dev-agent-api-openapi.yml
  format: yaml
  label: eudr.dev Agent API
  slug: eudr-dev-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-agent-api-openapi.yml
- filename: eudr-dev-discovery-api-openapi.yml
  format: yaml
  label: eudr.dev Discovery API
  slug: eudr-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-discovery-api-openapi.yml
- filename: eudr-dev-engineer-api-openapi.yml
  format: yaml
  label: eudr.dev Engineer API
  slug: eudr-dev-engineer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-engineer-api-openapi.yml
- filename: eudr-dev-ops-api-openapi.yml
  format: yaml
  label: eudr.dev Ops API
  slug: eudr-dev-ops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-ops-api-openapi.yml
- filename: eudr-dev-public-api-openapi.yml
  format: yaml
  label: eudr.dev Public API
  slug: eudr-dev-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-public-api-openapi.yml
- filename: eudr-dev-reference-api-openapi.yml
  format: yaml
  label: eudr.dev Reference API
  slug: eudr-dev-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-reference-api-openapi.yml
claim_count: 10
description: ''
doc:
  attribution:
    required: null
    text: null
  caching:
    max_duration: null
    stance: unstated
    text: null
  change_notice:
    period: at least 30 days' notice
    text: The Provider may amend these Terms on at least 30 days' notice.
  effective_date: Last reviewed 2026-09-30
  governing_law:
    jurisdiction: India (State of Jharkhand)
    text: These Terms are governed by the law of India , specifically the laws applicable in the State of Jharkhand
  liability_cap:
    text: the Provider's aggregate liability under or in connection with these Terms is capped at the fees the Customer paid for the hosted service in the 12 months preceding the event giving rise to the claim .
  permitted_use:
  - summary: Use by operators and authorised agents under EUDR
    text: The hosted service is offered for use by operators within the meaning of Reg. 2023/1115 Art. 2(15) and their authorised agents under Art. 6 of the Regulation.
  prohibited_use:
  - summary: No scraping or extracting third-party data
    text: The Customer will not scrape the service, attempt to extract third-party data, or use it to enumerate accounts.
  - summary: No abusive load; respect rate limits
    text: The Customer will not impose an abusive load — automated callers must respect the published rate limits
  - summary: No false Due Diligence Statements
    text: The Customer will not use the service to file a Due Diligence Statement the Customer knows or ought to know to be false.
  - summary: No submitting non-attestation document to TRACES as DDS
    text: the Customer must not submit that document to TRACES as a DDS.
  rate_or_usage_limits_referenced:
    text: automated callers must respect the published rate limits (5 magic links per email per hour, 30 per IP per hour; per-org API quotas as documented in the dashboard)
  redistribution:
    stance: unstated
    text: null
  termination_notice:
    period: null
    text: A Customer who does not accept an amendment may terminate the subscription with effect from the date the amendment would otherwise take effect.
layer: terms_of_service
layer_version: 0.1.0
layout: terms
method: harvested
model: claude-haiku-5-5
name: eudr.dev
provenance_date: '2026-11-09'
provider_name: eudr.dev
provider_slug: eudr-dev
slug: eudr-dev-terms-of-service
source_date: '2026-11-09'
source_filename: eudr-dev-terms-of-service.yml
source_heading: Terms of Service
source_page: https://eudr.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nterms_of_service: 0.1.0\nprovider: eudr.dev\naid: eudr-dev\nurl: https://eudr.dev/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\neffective_date: Last reviewed 2026-09-30\npermitted_use:\n- summary: Use by operators and authorised agents under EUDR\n  text: The hosted service is offered for use by operators within the meaning of Reg. 2023/1115 Art. 2(15) and their\n    authorised agents under Art. 6 of the Regulation.\nprohibited_use:\n- summary: No scraping or extracting third-party data\n  text: The Customer will not scrape the service, attempt to extract third-party data, or use it to enumerate accounts.\n- summary: No abusive load; respect rate\
  \ limits\n  text: The Customer will not impose an abusive load — automated callers must respect the published rate limits\n- summary: No false Due Diligence Statements\n  text: The Customer will not use the service to file a Due Diligence Statement the Customer knows or ought to know\n    to be false.\n- summary: No submitting non-attestation document to TRACES as DDS\n  text: the Customer must not submit that document to TRACES as a DDS.\ncaching:\n  stance: unstated\n  max_duration: null\n  text: null\nredistribution:\n  stance: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ngoverning_law:\n  jurisdiction: India (State of Jharkhand)\n  text: These Terms are governed by the law of India , specifically the laws applicable in the State of Jharkhand\nliability_cap:\n  text: the Provider's aggregate liability under or in connection with these Terms is capped at the fees the Customer\n    paid for the hosted service in the 12 months preceding the event giving rise to\
  \ the claim .\ntermination_notice:\n  period: null\n  text: A Customer who does not accept an amendment may terminate the subscription with effect from the date the\n    amendment would otherwise take effect.\nchange_notice:\n  period: at least 30 days' notice\n  text: The Provider may amend these Terms on at least 30 days' notice.\nrate_or_usage_limits_referenced:\n  text: automated callers must respect the published rate limits (5 magic links per email per hour, 30 per IP per\n    hour; per-org API quotas as documented in the dashboard)\n"
source_yaml_url: https://artifacts.apis.io/eudr-dev/terms/eudr-dev-terms-of-service.yml
stated_fields:
- permitted_use
- prohibited_use
- governing_law
- liability_cap
- termination_notice
- change_notice
- rate_or_usage_limits_referenced
summary_line: 10 quoted statements, read from eudr.dev's own page on 2026-11-09.
synthetic: false
tags:
- EU Deforestation
- Compliance
- Agriculture
- AI
- Environmental
---
