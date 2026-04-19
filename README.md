# Amazon EventBridge (amazon-eventbridge)
Amazon EventBridge is a serverless event bus service that makes it easy to connect your applications with data from a variety of sources. EventBridge delivers a stream of real-time data from your own applications, SaaS applications, and AWS services and routes that data to targets such as Lambda, SNS, SQS, and more.

**URL:** [https://aws.amazon.com/eventbridge/](https://aws.amazon.com/eventbridge/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, AWS, Event Bus, Event-Driven, Events, Integration, Serverless

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon EventBridge API
API for creating and managing event buses, rules, targets, and connections for routing events across applications, microservices, and SaaS integrations.

**Human URL:** [https://aws.amazon.com/eventbridge/](https://aws.amazon.com/eventbridge/)

#### Tags:

 - Event Bus, Event-Driven, Events, Serverless

#### Properties

- [Documentation](https://docs.aws.amazon.com/eventbridge/latest/userguide/)
- [OpenAPI](openapi/amazon-eventbridge-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/eventbridge/latest/APIReference/)
- [GettingStarted](https://aws.amazon.com/eventbridge/getting-started/)
- [Pricing](https://aws.amazon.com/eventbridge/pricing/)
- [FAQ](https://aws.amazon.com/eventbridge/faqs/)
- [JSONSchema](json-schema/amazon-eventbridge-create-archive-request-schema.json)
- [JSONSchema](json-schema/amazon-eventbridge-create-archive-response-schema.json)
- [JSONSchema](json-schema/amazon-eventbridge-create-event-bus-request-schema.json)
- [JSONLD](json-ld/amazon-eventbridge-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/eventbridge/)
- [Documentation](https://docs.aws.amazon.com/eventbridge/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/events/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/support/)
- [FAQ](https://aws.amazon.com/eventbridge/faqs/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Compliance](https://aws.amazon.com/compliance/)
- [Security](https://aws.amazon.com/security/)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/eventbridge)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Event Bus | Central event bus for routing events between AWS services and applications |
| Event Rules | Create rules to filter and route events to specific targets |
| Schema Registry | Discover, create, and manage event schemas with code binding generation |
| SaaS Integrations | Receive events from SaaS partners like Zendesk, Datadog, and PagerDuty |
| API Destinations | Send events to external HTTP endpoints via API Destinations |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Decoupling | Decouple microservices by routing events through a central event bus |
| Application Monitoring | React to CloudWatch alarms and AWS service events in real time |
| SaaS Event Processing | Receive and process events from SaaS applications without polling |
| Multi-Account Event Routing | Route events across AWS accounts and regions for enterprise architectures |

## Integrations

| Name | Description |
|------|-------------|
| AWS Lambda | Invoke Lambda functions in response to events |
| Amazon SNS | Fan out events to multiple subscribers via SNS topics |
| Amazon SQS | Queue events for reliable processing with SQS |
| AWS Step Functions | Start state machine executions in response to events |
| Zendesk | Receive Zendesk support ticket and activity events |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-eventbridge](openapi/amazon-eventbridge-openapi.yml)

### AsyncAPI

- [amazon-eventbridge-asyncapi.yml](asyncapi/amazon-eventbridge-asyncapi.yml)

### JSON Schema

- [amazon-eventbridge-create-archive-request](json-schema/amazon-eventbridge-create-archive-request-schema.json)
- [amazon-eventbridge-create-archive-response](json-schema/amazon-eventbridge-create-archive-response-schema.json)
- [amazon-eventbridge-create-event-bus-request](json-schema/amazon-eventbridge-create-event-bus-request-schema.json)
- [amazon-eventbridge-create-event-bus-response](json-schema/amazon-eventbridge-create-event-bus-response-schema.json)
- [amazon-eventbridge-delete-event-bus-request](json-schema/amazon-eventbridge-delete-event-bus-request-schema.json)
- [amazon-eventbridge-delete-rule-request](json-schema/amazon-eventbridge-delete-rule-request-schema.json)
- [amazon-eventbridge-describe-event-bus-request](json-schema/amazon-eventbridge-describe-event-bus-request-schema.json)
- [amazon-eventbridge-describe-event-bus-response](json-schema/amazon-eventbridge-describe-event-bus-response-schema.json)
- [amazon-eventbridge-describe-rule-request](json-schema/amazon-eventbridge-describe-rule-request-schema.json)
- [amazon-eventbridge-describe-rule-response](json-schema/amazon-eventbridge-describe-rule-response-schema.json)
- *...and 20 more*

### JSON Structure

- [amazon-eventbridge-create-archive-request](json-structure/amazon-eventbridge-create-archive-request-structure.json)
- [amazon-eventbridge-create-archive-response](json-structure/amazon-eventbridge-create-archive-response-structure.json)
- [amazon-eventbridge-create-event-bus-request](json-structure/amazon-eventbridge-create-event-bus-request-structure.json)
- [amazon-eventbridge-create-event-bus-response](json-structure/amazon-eventbridge-create-event-bus-response-structure.json)
- [amazon-eventbridge-delete-event-bus-request](json-structure/amazon-eventbridge-delete-event-bus-request-structure.json)
- [amazon-eventbridge-delete-rule-request](json-structure/amazon-eventbridge-delete-rule-request-structure.json)
- [amazon-eventbridge-describe-event-bus-request](json-structure/amazon-eventbridge-describe-event-bus-request-structure.json)
- [amazon-eventbridge-describe-event-bus-response](json-structure/amazon-eventbridge-describe-event-bus-response-structure.json)
- [amazon-eventbridge-describe-rule-request](json-structure/amazon-eventbridge-describe-rule-request-structure.json)
- [amazon-eventbridge-describe-rule-response](json-structure/amazon-eventbridge-describe-rule-response-structure.json)
- *...and 20 more*

### JSON-LD

- [amazon-eventbridge](json-ld/amazon-eventbridge-context.jsonld)

### Examples

- [amazon-eventbridge-create-archive-request](examples/amazon-eventbridge-create-archive-request-example.json)
- [amazon-eventbridge-create-archive-response](examples/amazon-eventbridge-create-archive-response-example.json)
- [amazon-eventbridge-create-event-bus-request](examples/amazon-eventbridge-create-event-bus-request-example.json)
- [amazon-eventbridge-create-event-bus-response](examples/amazon-eventbridge-create-event-bus-response-example.json)
- [amazon-eventbridge-delete-event-bus-request](examples/amazon-eventbridge-delete-event-bus-request-example.json)
- [amazon-eventbridge-delete-rule-request](examples/amazon-eventbridge-delete-rule-request-example.json)
- [amazon-eventbridge-describe-event-bus-request](examples/amazon-eventbridge-describe-event-bus-request-example.json)
- [amazon-eventbridge-describe-event-bus-response](examples/amazon-eventbridge-describe-event-bus-response-example.json)
- [amazon-eventbridge-describe-rule-request](examples/amazon-eventbridge-describe-rule-request-example.json)
- [amazon-eventbridge-describe-rule-response](examples/amazon-eventbridge-describe-rule-response-example.json)
- *...and 20 more*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [EventBridge](capabilities/shared/api.yaml) — 14 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Amazon EventBridge Management](capabilities/amazon-eventbridge-capability.yaml) | 14 | Cloud Architect |

## Vocabulary

- [Amazon EventBridge Vocabulary](vocabulary/amazon-eventbridge-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 6 actions, 1 workflows, and 2 personas

## Rules

- [amazon-eventbridge-spectral-rules.yml](rules/amazon-eventbridge-spectral-rules.yml) — 0 rules enforcing Amazon EventBridge API conventions

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
