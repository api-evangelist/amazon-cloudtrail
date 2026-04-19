# Amazon CloudTrail (amazon-cloudtrail)
AWS CloudTrail enables governance, compliance, operational auditing, and risk auditing of your AWS account by tracking user activity and API usage across AWS environments, hybrid setups, and multicloud deployments with immutable audit trails.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloudtrail/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CloudTrail, Audit, Compliance, Governance, Security

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CloudTrail API
API for creating and managing CloudTrail trails, event data stores, and channels for capturing AWS API activity and storing audit logs.

**Human URL:** [https://aws.amazon.com/cloudtrail/](https://aws.amazon.com/cloudtrail/)

#### Tags:

 - AWS, CloudTrail, Audit, Compliance, Security

#### Properties

- [Documentation](https://docs.aws.amazon.com/awscloudtrail/latest/APIReference/)
- [OpenAPI](openapi/amazon-cloudtrail-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/awscloudtrail/latest/APIReference/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloudtrail/)
- [SpectralRules](rules/amazon-cloudtrail-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloudtrail-vocabulary.yaml)
- [NaftikoCapability](capabilities/audit-trail-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Event Aggregation | Consolidate activity events from AWS, external providers, on-premises, and SaaS into a unified audit trail. |
| Immutable Audit Logs | Store audit-worthy events immutably to ensure tamper-proof compliance records. |
| CloudTrail Insights | Detect unusual API activity patterns with anomaly detection on management and data events. |
| SQL Query Support | Investigate issues using SQL queries or natural language with Amazon Athena integration. |
| Multi-Region Trails | Create trails that capture events from all AWS regions in a single S3 bucket. |

## Use Cases

| Name | Description |
|------|-------------|
| Compliance Auditing | Demonstrate adherence to SOC, PCI DSS, and HIPAA regulations with audit logs. |
| Security Monitoring | Record and monitor user and API activity for security incident detection. |
| Operational Debugging | Investigate operational issues by querying historical API activity. |
| Governance | Track who made changes to AWS resources and when for governance accountability. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Store CloudTrail logs in S3 buckets with lifecycle management. |
| Amazon Athena | Query CloudTrail logs using SQL via Athena integration. |
| Amazon CloudWatch | Stream CloudTrail events to CloudWatch Logs for real-time monitoring. |
| AWS Lambda | Trigger Lambda functions based on CloudTrail events for automated response. |
| AWS Security Hub | Send CloudTrail findings to Security Hub for centralized security management. |

## Artifacts

### OpenAPI

- [Amazon CloudTrail API](openapi/amazon-cloudtrail-openapi.yml)

### JSON Schema

- [CreateTrailRequest](json-schema/cloudtrail-create-trail-request-schema.json)
- [CreateTrailResponse](json-schema/cloudtrail-create-trail-response-schema.json)
- [DescribeTrailsResponse](json-schema/cloudtrail-describe-trails-response-schema.json)
- [LookupEventsRequest](json-schema/cloudtrail-lookup-events-request-schema.json)
- [LookupEventsResponse](json-schema/cloudtrail-lookup-events-response-schema.json)

### JSON-LD

- [Amazon CloudTrail Context](json-ld/amazon-cloudtrail-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Amazon CloudTrail](capabilities/shared/cloudtrail.yaml) — 7 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Audit Trail Management](capabilities/audit-trail-management.yaml) | Amazon CloudTrail | 7 | Security Analyst |

## Vocabulary

- [Amazon CloudTrail Vocabulary](vocabulary/amazon-cloudtrail-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon CloudTrail Spectral Rules](rules/amazon-cloudtrail-spectral-rules.yml) — 19 rules enforcing Amazon CloudTrail API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
