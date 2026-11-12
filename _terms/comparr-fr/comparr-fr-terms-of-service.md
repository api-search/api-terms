---
api_specs:
- filename: comparr-fr-comparatifs-api-openapi.yml
  format: yaml
  label: Comparr Comparatifs API
  slug: comparr-fr-comparatifs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-comparatifs-api-openapi.yml
- filename: comparr-fr-deals-api-openapi.yml
  format: yaml
  label: Comparr Deals API
  slug: comparr-fr-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-deals-api-openapi.yml
- filename: comparr-fr-discovery-api-openapi.yml
  format: yaml
  label: Comparr Discovery API
  slug: comparr-fr-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-discovery-api-openapi.yml
- filename: comparr-fr-products-api-openapi.yml
  format: yaml
  label: Comparr Products API
  slug: comparr-fr-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-products-api-openapi.yml
- filename: comparr-fr-searches-api-openapi.yml
  format: yaml
  label: Comparr Searches API
  slug: comparr-fr-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-searches-api-openapi.yml
- filename: comparr-fr-versus-api-openapi.yml
  format: yaml
  label: Comparr Versus API
  slug: comparr-fr-versus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-versus-api-openapi.yml
claim_count: 11
description: ''
doc:
  attribution:
    required: true
    text: Un assistant ou un programme qui reprend nos classements ou nos prix cite Comparr et renvoie vers la page source
  caching:
    max_duration: null
    stance: unstated
    text: null
  change_notice:
    period: null
    text: Ces conditions peuvent évoluer avec le service. La version en vigueur est celle publiée sur cette page, à la date indiquée en tête.
  effective_date: Version du 20 octobre 2026
  governing_law:
    jurisdiction: France
    text: Les présentes conditions sont soumises au droit français
  liability_cap:
    text: null
  permitted_use:
  - summary: Free API and MCP server access for programs and AI assistants
    text: L'API ( /api/v1 ) et le serveur MCP sont ouverts gratuitement aux programmes et aux assistants IA, dans la limite de quotas quotidiens décrits dans la documentation de l'API .
  - summary: Visitors use the service without an account
    text: Comparr est gratuit et s'utilise sans compte .
  prohibited_use:
  - summary: Bulk or automated extraction outside the API
    text: extraire le contenu du site de manière massive ou automatisée en dehors de l'API publique prévue à cet effet
  - summary: Circumventing usage limits or traffic filtering
    text: contourner les limites d'usage, les protections techniques ou le filtrage du trafic automatisé
  - summary: Artificial clicks on merchant links
    text: générer des clics artificiels sur les liens marchands ou fausser les mesures d'audience
  rate_or_usage_limits_referenced:
    text: dans la limite de quotas quotidiens décrits dans la documentation de l'API
  redistribution:
    stance: conditional
    text: Un assistant ou un programme qui reprend nos classements ou nos prix cite Comparr et renvoie vers la page source , dont l'adresse figure dans chaque réponse.
  termination_notice:
    period: sans préavis
    text: En cas de manquement, l'accès peut être limité ou bloqué, sans préavis.
layer: terms_of_service
layer_version: 0.1.0
layout: terms
method: harvested
model: claude-haiku-5-5
name: Comparr
provenance_date: '2026-11-09'
provider_name: Comparr
provider_slug: comparr-fr
slug: comparr-fr-terms-of-service
source_date: '2026-11-09'
source_filename: comparr-fr-terms-of-service.yml
source_heading: Terms of Service
source_page: https://www.comparr.fr/conditions-utilisation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nterms_of_service: 0.1.0\nprovider: Comparr\naid: comparr-fr\nurl: https://www.comparr.fr/conditions-utilisation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\neffective_date: Version du 20 octobre 2026\npermitted_use:\n- summary: Free API and MCP server access for programs and AI assistants\n  text: L'API ( /api/v1 ) et le serveur MCP sont ouverts gratuitement aux programmes et aux assistants IA, dans\n    la limite de quotas quotidiens décrits dans la documentation de l'API .\n- summary: Visitors use the service without an account\n  text: Comparr est gratuit et s'utilise sans compte .\nprohibited_use:\n- summary: Bulk or automated extraction outside the API\n\
  \  text: extraire le contenu du site de manière massive ou automatisée en dehors de l'API publique prévue à cet effet\n- summary: Circumventing usage limits or traffic filtering\n  text: contourner les limites d'usage, les protections techniques ou le filtrage du trafic automatisé\n- summary: Artificial clicks on merchant links\n  text: générer des clics artificiels sur les liens marchands ou fausser les mesures d'audience\ncaching:\n  stance: unstated\n  max_duration: null\n  text: null\nredistribution:\n  stance: conditional\n  text: Un assistant ou un programme qui reprend nos classements ou nos prix cite Comparr et renvoie vers la page\n    source , dont l'adresse figure dans chaque réponse.\nattribution:\n  required: true\n  text: Un assistant ou un programme qui reprend nos classements ou nos prix cite Comparr et renvoie vers la page\n    source\ngoverning_law:\n  jurisdiction: France\n  text: Les présentes conditions sont soumises au droit français\nliability_cap:\n  text: null\n\
  termination_notice:\n  period: sans préavis\n  text: En cas de manquement, l'accès peut être limité ou bloqué, sans préavis.\nchange_notice:\n  period: null\n  text: Ces conditions peuvent évoluer avec le service. La version en vigueur est celle publiée sur cette page,\n    à la date indiquée en tête.\nrate_or_usage_limits_referenced:\n  text: dans la limite de quotas quotidiens décrits dans la documentation de l'API\n"
source_yaml_url: https://artifacts.apis.io/comparr-fr/terms/comparr-fr-terms-of-service.yml
stated_fields:
- permitted_use
- prohibited_use
- redistribution
- attribution
- governing_law
- termination_notice
- change_notice
- rate_or_usage_limits_referenced
summary_line: 11 quoted statements, read from Comparr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Price Comparison
- E-Commerce
- Shopping
- Artificial Intelligence
- Product Reviews
- AI Agents
- MCP
- France
---
