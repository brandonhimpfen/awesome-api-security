# Awesome API Security [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support)
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome)
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, frameworks, standards, platforms, research, and learning resources for securing APIs.

APIs power modern applications, cloud services, mobile platforms, and distributed systems. As APIs increasingly become the primary attack surface for organizations, securing them is essential for protecting data, services, users, and infrastructure.

This list is intended for developers, security engineers, AppSec teams, DevSecOps practitioners, architects, platform teams, auditors, and researchers working with API security.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [API Security Testing](#api-security-testing)
- [API Security Platforms](#api-security-platforms)
- [API Gateways & Protection](#api-gateways--protection)
- [Authentication & Authorization](#authentication--authorization)
- [API Discovery & Inventory](#api-discovery--inventory)
- [API Security Monitoring](#api-security-monitoring)
- [API Specifications & Standards](#api-specifications--standards)
- [Learning Resources](#learning-resources)
- [Communities](#communities)
- [Related Awesome Lists](#related-awesome-lists)

## API Security Testing

Tools and platforms for discovering vulnerabilities, misconfigurations, and security weaknesses in APIs.

- [OWASP ZAP](https://www.zaproxy.org/) — Open-source web application and API security testing platform.
- [Burp Suite](https://portswigger.net/burp) — Security testing platform with API assessment capabilities.
- [Postman](https://www.postman.com/) — API platform supporting automated security and functional testing.
- [Insomnia](https://insomnia.rest/) — API testing platform supporting REST, GraphQL, and gRPC.
- [Schemathesis](https://schemathesis.io/) — Property-based API testing using OpenAPI schemas.
- [42Crunch API Security Testing](https://42crunch.com/) — API-focused security testing and compliance platform.
- [Tinfoil](https://github.com/tinfoilsh/tinfoil) — Open-source API security scanning and analysis tool.
- [Dredd](https://dredd.org/) — API contract testing against documentation and specifications.

## API Security Platforms

Comprehensive platforms designed to secure APIs across development and production environments.

- [42Crunch](https://42crunch.com/) — API security platform covering design, testing, and runtime protection.
- [Salt Security](https://salt.security/) — API protection and threat detection platform.
- [Noname Security](https://nonamesecurity.com/) — API security posture management and protection.
- [Traceable AI](https://www.traceable.ai/) — API security and observability platform.
- [Akamai API Security](https://www.akamai.com/) — API discovery, monitoring, and protection capabilities.
- [Imperva API Security](https://www.imperva.com/) — API attack detection and protection platform.
- [Wallarm](https://wallarm.com/) — API and application security platform.
- [Data Theorem](https://www.datatheorem.com/) — API security posture management and vulnerability detection.

## API Gateways & Protection

Gateways, proxies, and infrastructure components that help secure API traffic.

- [Kong Gateway](https://konghq.com/) — API gateway with authentication, rate limiting, and security plugins.
- [NGINX API Gateway](https://www.nginx.com/) — API management and traffic protection platform.
- [Apache APISIX](https://apisix.apache.org/) — Cloud-native API gateway with security controls.
- [Tyk](https://tyk.io/) — Open-source API gateway and management platform.
- [Apigee](https://cloud.google.com/apigee) — API management platform from Google Cloud.
- [AWS API Gateway](https://aws.amazon.com/api-gateway/) — Managed API gateway service.
- [Azure API Management](https://azure.microsoft.com/en-us/products/api-management) — API governance and security platform.
- [Envoy Proxy](https://www.envoyproxy.io/) — High-performance service proxy widely used in API architectures.

## Authentication & Authorization

Standards, frameworks, and identity systems for securing API access.

- [OAuth 2.0](https://oauth.net/2/) — Industry-standard authorization framework.
- [OpenID Connect](https://openid.net/connect/) — Identity layer built on OAuth 2.0.
- [Keycloak](https://www.keycloak.org/) — Open-source identity and access management platform.
- [Auth0](https://auth0.com/) — Identity platform supporting API authentication and authorization.
- [ORY](https://www.ory.sh/) — Open-source identity and access management ecosystem.
- [OpenFGA](https://openfga.dev/) — Authorization engine inspired by Google Zanzibar.
- [Zitadel](https://zitadel.com/) — Identity and access management platform.
- [Casbin](https://casbin.org/) — Authorization library supporting RBAC and ABAC models.

## API Discovery & Inventory

Tools for identifying, cataloging, and managing API assets.

- [Akto](https://github.com/akto-api-security/akto) — Open-source API discovery and security testing platform.
- [Traceable API Inventory](https://www.traceable.ai/) — API discovery and asset inventory capabilities.
- [Salt Security API Inventory](https://salt.security/) — API asset discovery and classification.
- [Postman API Network](https://www.postman.com/explore) — API catalog and discovery platform.
- [SwaggerHub](https://swagger.io/tools/swaggerhub/) — API design and governance platform.
- [Backstage](https://backstage.io/) — Internal developer portal supporting API catalogs.

## API Security Monitoring

Observability and runtime monitoring tools for detecting attacks and anomalous API behavior.

- [Wallarm](https://wallarm.com/) — Runtime API threat detection and monitoring.
- [Traceable AI](https://www.traceable.ai/) — API behavior analysis and attack detection.
- [Datadog API Monitoring](https://www.datadoghq.com/) — Monitoring and observability for APIs and services.
- [New Relic](https://newrelic.com/) — Application and API observability platform.
- [Elastic Observability](https://www.elastic.co/observability) — Monitoring, logging, and security analytics.
- [Grafana](https://grafana.com/) — Visualization and monitoring platform for API telemetry.

## API Specifications & Standards

Standards and guidance that support secure API design and governance.

- [OWASP API Security Top 10](https://owasp.org/www-project-api-security/) — Common API security risks and mitigations.
- [OpenAPI Specification](https://www.openapis.org/) — Standard for describing REST APIs.
- [AsyncAPI](https://www.asyncapi.com/) — Specification for event-driven APIs.
- [JSON Web Token (JWT)](https://jwt.io/) — Open standard for transmitting claims securely.
- [FAPI](https://openid.net/fapi/) — Financial-grade API security standards.
- [OAuth Security Best Current Practice](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-security-topics) — Security recommendations for OAuth implementations.

## Learning Resources

Books, documentation, courses, and educational resources.

- [OWASP API Security Project](https://owasp.org/www-project-api-security/) — Security guidance, references, and testing resources.
- [API Security in Action](https://www.manning.com/books/api-security-in-action) — Practical guide to securing APIs.
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — Free security training including API security topics.
- [Google API Design Guide](https://cloud.google.com/apis/design) — API design principles and recommendations.
- [Microsoft REST API Guidelines](https://github.com/microsoft/api-guidelines) — Guidance for API design and governance.
- [OpenAPI Initiative](https://www.openapis.org/) — Documentation and resources for API standards.

## Communities

Communities, organizations, and initiatives focused on API security.

- [OWASP](https://owasp.org/) — Open community dedicated to application security.
- [OpenAPI Initiative](https://www.openapis.org/) — Industry consortium supporting API standards.
- [API Security Project](https://owasp.org/www-project-api-security/) — OWASP project focused on API security.
- [Cloud Native Computing Foundation](https://www.cncf.io/) — Community supporting cloud-native infrastructure and API ecosystems.
- [OpenSSF](https://openssf.org/) — Open source security community and initiatives.

## Related Awesome Lists

- [Awesome APIs](https://github.com/brandonhimpfen/awesome-apis) — A curated list of high-quality APIs, SDKs, and developer tools.
- [Awesome Cybersecurity](https://github.com/brandonhimpfen/awesome-cybersecurity) — Cybersecurity frameworks and tools.
- [Awesome AI Security](https://github.com/brandonhimpfen/awesome-ai-security) — Tools, frameworks, benchmarks, research, and resources focused on securing AI systems.
- [Awesome Mobile Security](https://github.com/brandonhimpfen/awesome-mobile-security) — Tools, frameworks, and practices for securing mobile applications.
- [Awesome Privacy](https://github.com/brandonhimpfen/awesome-privacy) — Tools and knowledge to protect digital privacy.
- [Awesome Threat Intelligence](https://github.com/brandonhimpfen/awesome-threat-intelligence) — Threat detection and analysis resources.
- [Awesome DevOps](https://github.com/brandonhimpfen/awesome-devops) — A curated list of tools, resources, and best practices in DevOps.
- [Awesome Cloud](https://github.com/brandonhimpfen/awesome-cloud) — A curated list of cloud platforms, tools, SDKs, infrastructure services, and learning resources.
- [Awesome Software Architecture](https://github.com/brandonhimpfen/awesome-software-architecture) — Architectural patterns, frameworks, tools, and resources for software systems.
- [Awesome Web Development](https://github.com/brandonhimpfen/awesome-web-development) — Frameworks, tools, and learning resources for modern web development.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
