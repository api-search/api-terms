---
api_specs:
- filename: coldstate-ai-auth-api-openapi.yml
  format: yaml
  label: ColdState Auth API
  slug: coldstate-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-auth-api-openapi.yml
- filename: coldstate-ai-billing-api-openapi.yml
  format: yaml
  label: ColdState Billing API
  slug: coldstate-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-billing-api-openapi.yml
- filename: coldstate-ai-indexes-api-openapi.yml
  format: yaml
  label: ColdState Indexes API
  slug: coldstate-ai-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-indexes-api-openapi.yml
- filename: coldstate-ai-knowledge-api-openapi.yml
  format: yaml
  label: ColdState Knowledge API
  slug: coldstate-ai-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-knowledge-api-openapi.yml
- filename: coldstate-ai-mcp-api-openapi.yml
  format: yaml
  label: ColdState MCP API
  slug: coldstate-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-mcp-api-openapi.yml
- filename: coldstate-ai-meta-api-openapi.yml
  format: yaml
  label: ColdState Meta API
  slug: coldstate-ai-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-meta-api-openapi.yml
- filename: coldstate-ai-search-api-openapi.yml
  format: yaml
  label: ColdState Search API
  slug: coldstate-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-search-api-openapi.yml
- filename: coldstate-ai-usage-api-openapi.yml
  format: yaml
  label: ColdState Usage API
  slug: coldstate-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-usage-api-openapi.yml
claim_count: 11
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
    period: 30 days
    text: Material changes will be communicated via email or dashboard notice at least 30 days before taking effect.
  effective_date: 'Last updated: March 7, 2026'
  governing_law:
    jurisdiction: Ohio, United States
    text: These Terms are governed by the laws of the State of Ohio, United States, without regard to conflict-of-law provisions.
  liability_cap:
    text: Our total liability for any claim arising from the Service shall not exceed the amount you paid us in the 12 months preceding the claim.
  permitted_use:
  - summary: Use of the API under these Terms
    text: By creating an account or using the ColdState Services API ("Service"), you agree to these Terms of Service ("Terms").
  prohibited_use:
  - summary: Reselling or redistributing the Service
    text: Resell or redistribute the Service without written authorization
  - summary: Reverse engineering
    text: Reverse-engineer, decompile, or disassemble any part of the Service
  - summary: Automated account creation or fraudulent usage
    text: Use automated systems to create accounts or generate fraudulent usage
  - summary: Circumventing rate limits
    text: Attempt to circumvent rate limits, usage quotas, or security measures
  rate_or_usage_limits_referenced:
    text: Each tier has specific rate limits (requests per minute, burst limits per second) and monthly query quotas.
  redistribution:
    stance: prohibited
    text: Resell or redistribute the Service without written authorization
  termination_notice:
    period: null
    text: We may suspend or terminate your account for violation of these Terms, with notice when practical.
layer: terms_of_service
layer_version: 0.1.0
layout: terms
method: harvested
model: claude-haiku-5-5
name: ColdState
provenance_date: '2026-11-09'
provider_name: ColdState
provider_slug: coldstate-ai
slug: coldstate-ai-terms-of-service
source_date: '2026-11-09'
source_filename: coldstate-ai-terms-of-service.yml
source_heading: Terms of Service
source_page: https://services.coldstate.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nterms_of_service: 0.1.0\nprovider: ColdState\naid: coldstate-ai\nurl: https://services.coldstate.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\neffective_date: 'Last updated: March 7, 2026'\npermitted_use:\n- summary: Use of the API under these Terms\n  text: By creating an account or using the ColdState Services API (\"Service\"), you agree to these Terms of Service\n    (\"Terms\").\nprohibited_use:\n- summary: Reselling or redistributing the Service\n  text: Resell or redistribute the Service without written authorization\n- summary: Reverse engineering\n  text: Reverse-engineer, decompile, or disassemble any part of the Service\n- summary: Automated\
  \ account creation or fraudulent usage\n  text: Use automated systems to create accounts or generate fraudulent usage\n- summary: Circumventing rate limits\n  text: Attempt to circumvent rate limits, usage quotas, or security measures\ncaching:\n  stance: unstated\n  max_duration: null\n  text: null\nredistribution:\n  stance: prohibited\n  text: Resell or redistribute the Service without written authorization\nattribution:\n  required: null\n  text: null\ngoverning_law:\n  jurisdiction: Ohio, United States\n  text: These Terms are governed by the laws of the State of Ohio, United States, without regard to conflict-of-law\n    provisions.\nliability_cap:\n  text: Our total liability for any claim arising from the Service shall not exceed the amount you paid us in the\n    12 months preceding the claim.\ntermination_notice:\n  period: null\n  text: We may suspend or terminate your account for violation of these Terms, with notice when practical.\nchange_notice:\n  period: 30 days\n  text:\
  \ Material changes will be communicated via email or dashboard notice at least 30 days before taking effect.\nrate_or_usage_limits_referenced:\n  text: Each tier has specific rate limits (requests per minute, burst limits per second) and monthly query quotas.\n"
source_yaml_url: https://artifacts.apis.io/coldstate-ai/terms/coldstate-ai-terms-of-service.yml
stated_fields:
- permitted_use
- prohibited_use
- redistribution
- governing_law
- liability_cap
- termination_notice
- change_notice
- rate_or_usage_limits_referenced
summary_line: 11 quoted statements, read from ColdState's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Knowledge Base
- Search
- Deterministic Retrieval
- MCP
- AI Agents
- Citations
---
