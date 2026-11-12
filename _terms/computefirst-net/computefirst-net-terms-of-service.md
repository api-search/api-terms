---
api_specs:
- filename: computefirst-net-account-api-openapi.yml
  format: yaml
  label: ComputeFirst Account API
  slug: computefirst-net-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-account-api-openapi.yml
- filename: computefirst-net-discovery-api-openapi.yml
  format: yaml
  label: ComputeFirst Discovery API
  slug: computefirst-net-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-discovery-api-openapi.yml
- filename: computefirst-net-execution-api-openapi.yml
  format: yaml
  label: ComputeFirst Execution API
  slug: computefirst-net-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-execution-api-openapi.yml
- filename: computefirst-net-feedback-api-openapi.yml
  format: yaml
  label: ComputeFirst Feedback API
  slug: computefirst-net-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-feedback-api-openapi.yml
- filename: computefirst-net-mcp-api-openapi.yml
  format: yaml
  label: ComputeFirst MCP API
  slug: computefirst-net-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-mcp-api-openapi.yml
- filename: computefirst-net-newsletter-api-openapi.yml
  format: yaml
  label: ComputeFirst Newsletter API
  slug: computefirst-net-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-newsletter-api-openapi.yml
- filename: computefirst-net-savings-api-openapi.yml
  format: yaml
  label: ComputeFirst Savings API
  slug: computefirst-net-savings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-savings-api-openapi.yml
- filename: computefirst-net-service-api-openapi.yml
  format: yaml
  label: ComputeFirst Service API
  slug: computefirst-net-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-service-api-openapi.yml
claim_count: 13
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
    period: 14 days
    text: For material changes we will give at least 14 days' notice before they take effect, on the website, in the MCP server description and API documentation, and by email
  effective_date: 1 October 2026
  governing_law:
    jurisdiction: Israel
    text: These terms are governed by the laws of the State of Israel, without regard to conflict-of-laws rules.
  liability_cap:
    text: because ComputeFirst is free, our total liability for all claims relating to it in any 12-month period is limited to USD 100.
  permitted_use:
  - summary: Use of service via website, MCP server, API, CLI
    text: 'You accept these terms when you use ComputeFirst in any way: the website, the MCP server, the HTTP API, the command-line client or an optional profile.'
  - summary: Reading and linking public docs and tool contracts
    text: Reading, indexing and linking our public documentation and tool contracts so that people and agents can find ComputeFirst is welcome
  - summary: Quote and link public docs; use code examples
    text: You may quote and link our public documentation and tool contracts, and use the code examples in them to connect to ComputeFirst.
  prohibited_use:
  - summary: Exceeding or circumventing usage limits
    text: 'you must not: exceed or get around usage limits, for example by rotating network addresses, creating extra keys or profiles, or splitting traffic to avoid limits'
  - summary: Scraping to copy the service or build competitor
    text: scrape or harvest the service in order to copy it, for example by systematically running tools to collect outputs that recreate our tool implementations, or by copying the catalogue to build a competing service or dataset
  - summary: Reverse engineering source code
    text: reverse engineer, decompile or try to extract the source code of the service, except where the law allows this despite a contractual ban
  - summary: Submitting secrets or sensitive data
    text: 'put secrets in inputs: passwords, API keys, access tokens, private keys, recovery codes or similar credentials'
  - summary: Overloading or attacking the service
    text: overload, disrupt or attack the service, test it for vulnerabilities without our written permission
  rate_or_usage_limits_referenced:
    text: exceed or get around usage limits
  redistribution:
    stance: unstated
    text: null
  termination_notice:
    period: 30 days
    text: When practical, we will announce a planned shutdown on the website at least 30 days in advance.
layer: terms_of_service
layer_version: 0.1.0
layout: terms
method: harvested
model: claude-haiku-5-5
name: ComputeFirst
provenance_date: '2026-11-09'
provider_name: ComputeFirst
provider_slug: computefirst-net
slug: computefirst-net-terms-of-service
source_date: '2026-11-09'
source_filename: computefirst-net-terms-of-service.yml
source_heading: Terms of Service
source_page: https://computefirst.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nterms_of_service: 0.1.0\nprovider: ComputeFirst\naid: computefirst-net\nurl: https://computefirst.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\neffective_date: 1 October 2026\npermitted_use:\n- summary: Use of service via website, MCP server, API, CLI\n  text: 'You accept these terms when you use ComputeFirst in any way: the website, the MCP server, the HTTP API,\n    the command-line client or an optional profile.'\n- summary: Reading and linking public docs and tool contracts\n  text: Reading, indexing and linking our public documentation and tool contracts so that people and agents can\n    find ComputeFirst is welcome\n- summary: Quote and link\
  \ public docs; use code examples\n  text: You may quote and link our public documentation and tool contracts, and use the code examples in them to\n    connect to ComputeFirst.\nprohibited_use:\n- summary: Exceeding or circumventing usage limits\n  text: 'you must not: exceed or get around usage limits, for example by rotating network addresses, creating extra\n    keys or profiles, or splitting traffic to avoid limits'\n- summary: Scraping to copy the service or build competitor\n  text: scrape or harvest the service in order to copy it, for example by systematically running tools to collect\n    outputs that recreate our tool implementations, or by copying the catalogue to build a competing service or\n    dataset\n- summary: Reverse engineering source code\n  text: reverse engineer, decompile or try to extract the source code of the service, except where the law allows\n    this despite a contractual ban\n- summary: Submitting secrets or sensitive data\n  text: 'put secrets in inputs:\
  \ passwords, API keys, access tokens, private keys, recovery codes or similar credentials'\n- summary: Overloading or attacking the service\n  text: overload, disrupt or attack the service, test it for vulnerabilities without our written permission\ncaching:\n  stance: unstated\n  max_duration: null\n  text: null\nredistribution:\n  stance: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ngoverning_law:\n  jurisdiction: Israel\n  text: These terms are governed by the laws of the State of Israel, without regard to conflict-of-laws rules.\nliability_cap:\n  text: because ComputeFirst is free, our total liability for all claims relating to it in any 12-month period is\n    limited to USD 100.\ntermination_notice:\n  period: 30 days\n  text: When practical, we will announce a planned shutdown on the website at least 30 days in advance.\nchange_notice:\n  period: 14 days\n  text: For material changes we will give at least 14 days' notice before they take effect, on the\
  \ website, in the\n    MCP server description and API documentation, and by email\nrate_or_usage_limits_referenced:\n  text: exceed or get around usage limits\n"
source_yaml_url: https://artifacts.apis.io/computefirst-net/terms/computefirst-net-terms-of-service.yml
stated_fields:
- permitted_use
- prohibited_use
- governing_law
- liability_cap
- termination_notice
- change_notice
- rate_or_usage_limits_referenced
summary_line: 13 quoted statements, read from ComputeFirst's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- MCP
- Developer Tools
- Data Transformation
- CSV
- JSON
- Deterministic Tools
---
