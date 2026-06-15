# Prefect (prefect)

Prefect is a Python-native workflow orchestration tool for building, scheduling, and monitoring data pipelines with fault tolerance. Prefect provides a hybrid execution model where the cloud control plane coordinates workflows while code and data remain in customer infrastructure, offering both a managed cloud platform and a self-hosted open-source server.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/prefect/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/prefect/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Automation
- Data Pipelines
- Orchestration
- Python
- Workflows

## Timestamps

- **Created:** 2026-03-03
- **Modified:** 2026-05-30

## APIs

### Prefect Cloud REST API

The Prefect Cloud REST API provides programmatic access to Prefect Cloud for orchestrating and managing workflows, deployments, flow runs, task runs, artifacts, and automations. The API follows RESTful conventions with pluralized collection names, snake_case route names, and supports an OpenAPI 3.0 compliant specification. Clients authenticate using API keys passed as Bearer tokens in request headers.

- **Human URL:** [https://docs.prefect.io/v3/api-ref/rest-api](https://docs.prefect.io/v3/api-ref/rest-api)

#### Tags

- Automations
- Deployments
- Flow Runs
- Orchestration
- REST API
- Task Runs
- Workflows

#### Properties

- [Documentation](https://docs.prefect.io/v3/api-ref/rest-api)
- [API Reference](https://app.prefect.cloud/api/docs)
- [Authentication](https://docs.prefect.io/v3/manage/cloud/manage-users/api-keys)
- [Getting Started](https://docs.prefect.io/v3/get-started/quickstart)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/prefect/refs/heads/main/openapi/prefect-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/prefect/refs/heads/main/asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/prefect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prefect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prefect Server REST API

The Prefect Server REST API is the self-hosted variant of the Prefect orchestration API for managing workflows, flow runs, task runs, deployments, and work pools. When running Prefect server locally, the API is available at http://localhost:4200/api and interactive documentation is served at the /docs endpoint. The API can be fully described with an OpenAPI 3.0 compliant document generated from the running server.

- **Human URL:** [https://docs.prefect.io/v3/api-ref/rest-api](https://docs.prefect.io/v3/api-ref/rest-api)

#### Tags

- Open Source
- Orchestration
- REST API
- Self-Hosted
- Workflows

#### Properties

- [Documentation](https://docs.prefect.io/v3/api-ref/rest-api)
- [API Reference](https://docs.prefect.io/latest/api-ref/rest-api-reference/)
- [Getting Started](https://docs.prefect.io/v3/get-started/quickstart)
- [GitHub Repository](https://github.com/PrefectHQ/prefect)
- [Postman Collection](collections/prefect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prefect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prefect Python SDK

The Prefect Python SDK is used to build, test, and execute workflows against the Prefect API. It provides decorators such as @flow and @task for defining workflows, along with programmatic interfaces for deployments, scheduling, state management, concurrency, caching, and retries. The SDK requires Python 3.10 or higher and includes a PrefectClient class for direct interaction with the REST API.

- **Human URL:** [https://docs.prefect.io/v3/api-ref/python](https://docs.prefect.io/v3/api-ref/python)

#### Tags

- Orchestration
- Python
- SDK
- Workflows

#### Properties

- [Documentation](https://docs.prefect.io/v3/api-ref/python)
- [Getting Started](https://docs.prefect.io/v3/get-started/quickstart)
- [GitHub Repository](https://github.com/PrefectHQ/prefect)
- [Postman Collection](collections/prefect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prefect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/prefect)
- [Portal](https://www.prefect.io)
- [Getting Started](https://docs.prefect.io/v3/get-started/quickstart)
- [Blog](https://www.prefect.io/blog)
- [Pricing](https://www.prefect.io/pricing)
- [Sign Up](https://app.prefect.cloud/)
- [Support](https://www.prefect.io/support)
- [Community](https://www.prefect.io/community)
- [Changelog](https://www.prefect.io/changelog)
- [Status Page](https://status.prefect.io/)
- [Security](https://www.prefect.io/security)
- [Terms of Service](https://www.prefect.io/legal/terms)
- [Privacy Policy](https://www.prefect.io/privacy-policy)
- [GitHub Organization](https://github.com/PrefectHQ)
- [Integrations](https://docs.prefect.io/integrations/integrations)
- [Login](https://app.prefect.cloud/)
- [M C P Server](https://github.com/PrefectHQ/prefect-mcp-server)
- [L L Ms Txt](https://docs.prefect.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
