# Apache James (apache-james)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache James (Java Apache Mail Enterprise Server) is a portable and enterprise-ready mail server built entirely in Java. It implements SMTP, IMAP, POP3, and JMAP protocols and provides a modular architecture with a comprehensive administration REST API and Cassandra-backed distributed deployment.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-james/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Email, IMAP, Java, JMAP, Mail Server, Open Source, SMTP

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache James WebAdmin REST API
The James WebAdmin API provides REST endpoints for managing domains, users, mailboxes, mail repositories, mail queues, quotas, drop lists, and async tasks.

**Human URL:** [https://james.apache.org/server/manage-webadmin.html](https://james.apache.org/server/manage-webadmin.html)

#### Tags:

 - Administration, Email, REST

#### Properties

- [Documentation](https://james.apache.org/server/manage-webadmin.html)
- [OpenAPI](openapi/apache-james-webadmin-rest-api.yaml)

### Apache James JMAP API
The JMAP implementation in James provides a modern, efficient email protocol for synchronizing messages, mailboxes, contacts, and calendars for email clients.

**Human URL:** [https://james.apache.org/server/rfcs-compliance.html](https://james.apache.org/server/rfcs-compliance.html)

#### Tags:

 - Email, JMAP, JSON

#### Properties

- [Documentation](https://james.apache.org/server/rfcs-compliance.html)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/james-project)
- [Documentation](https://james.apache.org/documentation.html)
- [GettingStarted](https://james.apache.org/server/quick-start.html)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)
- [Blog](https://james.apache.org/blog/)
- [SpectralRules](rules/apache-james-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-james-vocabulary.yaml)
- [NaftikoCapability](capabilities/mail-server-management.yaml)

## Features

| Name | Description |
|------|-------------|
| SMTP Server | Full SMTP server implementation with TLS, DKIM, SPF, and DMARC support. |
| IMAP Server | IMAP4 server with full RFC compliance for email client access. |
| JMAP Support | Modern JMAP protocol implementation for efficient email synchronization. |
| WebAdmin REST API | HTTP REST API for complete server administration without downtime. |
| Distributed Architecture | Cassandra-backed distributed deployment for high availability. |
| Modular Design | Pluggable architecture supporting custom protocols, storage, and authentication. |
| Mail Queuing | Persistent mail queuing with configurable retry strategies. |
| Quota Management | Per-user, per-domain, and global mailbox and message quota enforcement. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise Mail Server | Deploy a full-featured enterprise mail server with SMTP, IMAP, and JMAP. |
| Mail Server Migration | Migrate from other mail servers with full protocol compatibility. |
| Automated Email Processing | Build automated email pipelines using James mailet and matcher APIs. |
| High-Availability Mail | Deploy distributed James clusters with Cassandra and RabbitMQ for HA. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Cassandra | Distributed mail storage backend for high availability deployments. |
| Apache Kafka | Event bus integration for distributed James deployments. |
| RabbitMQ | AMQP message queue for inter-node communication. |
| Elasticsearch/OpenSearch | Full-text mail search indexing via Elasticsearch integration. |
| OpenLDAP | LDAP authentication and directory integration for user management. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache James WebAdmin REST API](openapi/apache-james-webadmin-rest-api.yaml)

### JSON Schema

9 schema files extracted from the WebAdmin REST API OpenAPI specification.

### JSON Structure

9 JSON Structure files converted from JSON Schema files.

### JSON-LD

- [Apache James WebAdmin REST API Context](json-ld/apache-james-webadmin-rest-api-context.jsonld)

### Examples

9 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache James WebAdmin REST API](capabilities/shared/webadmin-rest-api.yaml) — 3 operations for domain, user, and task management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache James Mail Server Management](capabilities/mail-server-management.yaml) | Apache James WebAdmin REST API | 5 | Mail Administrator |

## Vocabulary

- [Apache James Vocabulary](vocabulary/apache-james-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 8 actions, 1 workflow, and 1 persona

## Rules

- [Apache James Spectral Rules](rules/apache-james-spectral-rules.yml) — 19 rules across 10 categories enforcing Apache James WebAdmin API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
