---
api_specs:
- filename: euroref-dev-alerts-api-openapi.yml
  format: yaml
  label: Euroref Alerts API
  slug: euroref-dev-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-alerts-api-openapi.yml
- filename: euroref-dev-answers-api-openapi.yml
  format: yaml
  label: Euroref Answers API
  slug: euroref-dev-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-answers-api-openapi.yml
- filename: euroref-dev-certified-api-openapi.yml
  format: yaml
  label: Euroref Certified API
  slug: euroref-dev-certified-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-certified-api-openapi.yml
- filename: euroref-dev-discovery-api-openapi.yml
  format: yaml
  label: Euroref Discovery API
  slug: euroref-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-discovery-api-openapi.yml
- filename: euroref-dev-free-api-openapi.yml
  format: yaml
  label: Euroref Free API
  slug: euroref-dev-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-free-api-openapi.yml
- filename: euroref-dev-jobs-api-openapi.yml
  format: yaml
  label: Euroref Jobs API
  slug: euroref-dev-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-jobs-api-openapi.yml
- filename: euroref-dev-keys-api-openapi.yml
  format: yaml
  label: Euroref Keys API
  slug: euroref-dev-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-keys-api-openapi.yml
- filename: euroref-dev-reference-data-api-openapi.yml
  format: yaml
  label: Euroref Reference data API
  slug: euroref-dev-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-reference-data-api-openapi.yml
- filename: euroref-dev-x402-sellers-api-openapi.yml
  format: yaml
  label: Euroref x402 sellers API
  slug: euroref-dev-x402-sellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-x402-sellers-api-openapi.yml
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
    period: null
    text: We may update these terms; the date above records the current version.
  effective_date: Last updated 9 October 2026
  governing_law:
    jurisdiction: Republic of South Africa
    text: These terms are governed by the laws of the Republic of South Africa.
  liability_cap:
    text: 3L Group Consulting (PTY) LTD’s total liability arising out of or relating to the Service is limited to the amount you paid for the Service in the three months preceding the claim.
  permitted_use:
  - summary: Using data within own product or workflow
    text: Using the data within your own product or workflow is expressly permitted.
  prohibited_use:
  - summary: Bulk redistribution as competing dataset
    text: Do not resell or redistribute bulk extracts of the data as a competing dataset.
  - summary: Circumventing payment or limits
    text: Do not attempt to circumvent payment, rate limits or access controls.
  - summary: Degrading availability for others
    text: Do not use the Service in a way that degrades availability for others.
  rate_or_usage_limits_referenced:
    text: A free key carries a daily allowance of 50 calls on the computed answer endpoints, reset at 00:00 UTC
  redistribution:
    stance: conditional
    text: Do not resell or redistribute bulk extracts of the data as a competing dataset.
  termination_notice:
    period: null
    text: You can cancel at any time, with effect from the end of the month you have paid for, and the key stops when a renewal is not paid.
layer: terms_of_service
layer_version: 0.1.0
layout: terms
method: harvested
model: claude-haiku-5-5
name: Euroref
provenance_date: '2026-11-09'
provider_name: Euroref
provider_slug: euroref-dev
slug: euroref-dev-terms-of-service
source_date: '2026-11-09'
source_filename: euroref-dev-terms-of-service.yml
source_heading: Terms of Service
source_page: https://euroref.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nterms_of_service: 0.1.0\nprovider: Euroref\naid: euroref-dev\nurl: https://euroref.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\neffective_date: Last updated 9 October 2026\npermitted_use:\n- summary: Using data within own product or workflow\n  text: Using the data within your own product or workflow is expressly permitted.\nprohibited_use:\n- summary: Bulk redistribution as competing dataset\n  text: Do not resell or redistribute bulk extracts of the data as a competing dataset.\n- summary: Circumventing payment or limits\n  text: Do not attempt to circumvent payment, rate limits or access controls.\n- summary: Degrading availability for others\n\
  \  text: Do not use the Service in a way that degrades availability for others.\ncaching:\n  stance: unstated\n  max_duration: null\n  text: null\nredistribution:\n  stance: conditional\n  text: Do not resell or redistribute bulk extracts of the data as a competing dataset.\nattribution:\n  required: null\n  text: null\ngoverning_law:\n  jurisdiction: Republic of South Africa\n  text: These terms are governed by the laws of the Republic of South Africa.\nliability_cap:\n  text: 3L Group Consulting (PTY) LTD’s total liability arising out of or relating to the Service is limited to\n    the amount you paid for the Service in the three months preceding the claim.\ntermination_notice:\n  period: null\n  text: You can cancel at any time, with effect from the end of the month you have paid for, and the key stops when\n    a renewal is not paid.\nchange_notice:\n  period: null\n  text: We may update these terms; the date above records the current version.\nrate_or_usage_limits_referenced:\n \
  \ text: A free key carries a daily allowance of 50 calls on the computed answer endpoints, reset at 00:00 UTC\n"
source_yaml_url: https://artifacts.apis.io/euroref-dev/terms/euroref-dev-terms-of-service.yml
stated_fields:
- permitted_use
- prohibited_use
- redistribution
- governing_law
- liability_cap
- termination_notice
- change_notice
- rate_or_usage_limits_referenced
summary_line: 10 quoted statements, read from Euroref's own page on 2026-11-09.
synthetic: false
tags:
- Reference Data
- Government
- Europe
- API
- Open Data
---
