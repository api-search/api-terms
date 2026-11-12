---
api_specs:
- filename: corpusiuris-mx-agent-api-openapi.yml
  format: yaml
  label: Corpus Iuris Agent API
  slug: corpusiuris-mx-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiuris-mx/openapi/corpusiuris-mx-agent-api-openapi.yml
claim_count: 15
description: ''
doc:
  attribution:
    required: true
    text: los resultados empleados en respuestas deben atribuirse a «Corpus Iuris (corpusiuris.mx)» incluyendo, cuando sea posible, el enlace a la página del documento citado.
  caching:
    max_duration: null
    stance: unstated
    text: null
  change_notice:
    period: quince días naturales
    text: Las modificaciones se notificarán mediante el correo registrado y/o un aviso en la propia plataforma con al menos quince días naturales de anticipación cuando afecten condiciones económicas vigentes.
  effective_date: 'Vigente desde el 29 de mayo de 2026 · Última actualización: 13 de julio de 2026'
  governing_law:
    jurisdiction: México
    text: Estos términos se rigen e interpretan conforme a las leyes de los Estados Unidos Mexicanos.
  liability_cap:
    text: en ningún caso excederá del monto efectivamente pagado por el usuario en los doce meses previos al evento que origine el reclamo
  permitted_use:
  - summary: Consultar, citar y enlazar páginas públicas
    text: Está permitido consultarlas, citarlas y enlazarlas libremente, incluso desde asistentes de IA.
  - summary: Uso personal del servicio por suscripción
    text: El usuario obtiene una licencia personal, no exclusiva, intransferible y revocable para uso del servicio mientras dure su suscripción.
  - summary: Uso de datos vía asistente de IA propio
    text: estos planes otorgan una licencia personal, no exclusiva, intransferible y revocable para consultar la base de datos como apoyo al ejercicio profesional del propio usuario a través de su asistente de IA.
  prohibited_use:
  - summary: Compartir tokens o conexiones
    text: (i) compartir, ceder, vender o sublicenciar tokens o conexiones
  - summary: Integrar acceso en productos de terceros
    text: (ii) integrar el acceso en productos, plataformas o servicios ofrecidos a terceros
  - summary: Reconstruir o poblar bases de datos
    text: (iii) utilizar las búsquedas para reconstruir, replicar o poblar bases de datos propias o de terceros.
  - summary: Extracción masiva o scraping
    text: Está prohibida la extracción sistemática o sustancial de dichas páginas (scraping masivo, descarga en bloque, recorrido automatizado del acervo)
  - summary: Elusión de medidas técnicas
    text: la elusión de las medidas tecnológicas de protección implementadas (controles de acceso, límites de peticiones, verificación de rastreadores)
  rate_or_usage_limits_referenced:
    text: 'Corpus Ilimitado: búsquedas sin tope mensual, sujetas a una política de uso razonable (actualmente hasta 1,000 búsquedas por ventana de 12 horas)'
  redistribution:
    stance: prohibited
    text: Queda prohibido reproducir, distribuir, modificar, hacer ingeniería inversa o crear obras derivadas del software, de la compilación o de sus índices sin autorización expresa por escrito.
  termination_notice:
    period: null
    text: Corpus Iuris se reserva el derecho de suspender o cancelar cuentas que violen estos términos
layer: terms_of_service
layer_version: 0.1.0
layout: terms
method: harvested
model: claude-haiku-5-5
name: Corpus Iuris
provenance_date: '2026-11-09'
provider_name: Corpus Iuris
provider_slug: corpusiuris-mx
slug: corpusiuris-mx-terms-of-service
source_date: '2026-11-09'
source_filename: corpusiuris-mx-terms-of-service.yml
source_heading: Terms of Service
source_page: https://corpusiuris.mx/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nterms_of_service: 0.1.0\nprovider: Corpus Iuris\naid: corpusiuris-mx\nurl: https://corpusiuris.mx/terminos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\neffective_date: 'Vigente desde el 29 de mayo de 2026 · Última actualización: 13 de julio de 2026'\npermitted_use:\n- summary: Consultar, citar y enlazar páginas públicas\n  text: Está permitido consultarlas, citarlas y enlazarlas libremente, incluso desde asistentes de IA.\n- summary: Uso personal del servicio por suscripción\n  text: El usuario obtiene una licencia personal, no exclusiva, intransferible y revocable para uso del servicio\n    mientras dure su suscripción.\n- summary: Uso de datos vía asistente\
  \ de IA propio\n  text: estos planes otorgan una licencia personal, no exclusiva, intransferible y revocable para consultar la base\n    de datos como apoyo al ejercicio profesional del propio usuario a través de su asistente de IA.\nprohibited_use:\n- summary: Compartir tokens o conexiones\n  text: (i) compartir, ceder, vender o sublicenciar tokens o conexiones\n- summary: Integrar acceso en productos de terceros\n  text: (ii) integrar el acceso en productos, plataformas o servicios ofrecidos a terceros\n- summary: Reconstruir o poblar bases de datos\n  text: (iii) utilizar las búsquedas para reconstruir, replicar o poblar bases de datos propias o de terceros.\n- summary: Extracción masiva o scraping\n  text: Está prohibida la extracción sistemática o sustancial de dichas páginas (scraping masivo, descarga en bloque,\n    recorrido automatizado del acervo)\n- summary: Elusión de medidas técnicas\n  text: la elusión de las medidas tecnológicas de protección implementadas (controles de\
  \ acceso, límites de peticiones,\n    verificación de rastreadores)\ncaching:\n  stance: unstated\n  max_duration: null\n  text: null\nredistribution:\n  stance: prohibited\n  text: Queda prohibido reproducir, distribuir, modificar, hacer ingeniería inversa o crear obras derivadas del\n    software, de la compilación o de sus índices sin autorización expresa por escrito.\nattribution:\n  required: true\n  text: los resultados empleados en respuestas deben atribuirse a «Corpus Iuris (corpusiuris.mx)» incluyendo, cuando\n    sea posible, el enlace a la página del documento citado.\ngoverning_law:\n  jurisdiction: México\n  text: Estos términos se rigen e interpretan conforme a las leyes de los Estados Unidos Mexicanos.\nliability_cap:\n  text: en ningún caso excederá del monto efectivamente pagado por el usuario en los doce meses previos al evento\n    que origine el reclamo\ntermination_notice:\n  period: null\n  text: Corpus Iuris se reserva el derecho de suspender o cancelar cuentas que\
  \ violen estos términos\nchange_notice:\n  period: quince días naturales\n  text: Las modificaciones se notificarán mediante el correo registrado y/o un aviso en la propia plataforma con\n    al menos quince días naturales de anticipación cuando afecten condiciones económicas vigentes.\nrate_or_usage_limits_referenced:\n  text: 'Corpus Ilimitado: búsquedas sin tope mensual, sujetas a una política de uso razonable (actualmente hasta\n    1,000 búsquedas por ventana de 12 horas)'\n"
source_yaml_url: https://artifacts.apis.io/corpusiuris-mx/terms/corpusiuris-mx-terms-of-service.yml
stated_fields:
- permitted_use
- prohibited_use
- redistribution
- attribution
- governing_law
- liability_cap
- termination_notice
- change_notice
- rate_or_usage_limits_referenced
summary_line: 15 quoted statements, read from Corpus Iuris's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Research
- Artificial Intelligence
- Mexico
- Jurisprudence
- MCP
- Search
---
