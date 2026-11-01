# Vultr

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Vultr is a global cloud infrastructure provider offering Cloud Compute, Bare Metal, GPU, Kubernetes (VKE), Managed Databases, S3-compatible Object Storage, Block Storage, networking (VPC, load balancers, DNS, firewalls) and Serverless Inference across worldwide regions. Everything in the customer portal is scriptable through the RESTful Vultr API v2 at api.vultr.com/v2 (Bearer API key, cursor pagination), with a separate IAM & SCIM Management API, an official hosted MCP server at mcp.vultr.com, a first-party CLI and SDKs in Go, Node, Python, PHP, Ruby, Java and C#.

**Areas:** Company · Cloud · Infrastructure · Compute · Object Storage · Kubernetes · Database · GPU · MCP

## Vultr on APIs.io

Everything profiled for Vultr is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/vultr/](https://apis.io/providers/vultr/)** — or go straight to one of the APIs or properties below.

### APIs (46)

- [Vultr Account API](https://apis.io/apis/vultr/vultr-account-api/) — Read-only information about your [user account](https://my.vultr.com/settings/#settingsprofile) and [billing](https://my.vultr.com/billing/#billinghistory)…
- [Vultr Application API](https://apis.io/apis/vultr/vultr-application-api/) — [One-Click](https://www.vultr.com/features/one-click-apps/) and [Marketplace](https://www.vultr.com/marketplace/) Applications are ready-to-run with minimal…
- [Vultr Backup API](https://apis.io/apis/vultr/vultr-backup-api/) — A backup is a scheduled, automatic, point-in-time image of an instance. We do not stop the instance when taking a backup. Booting from a backup is similar…
- [Vultr Baremetal API](https://apis.io/apis/vultr/vultr-baremetal-api/) — [Bare Metal](https://www.vultr.com/products/bare-metal/) servers give you access to the underlying physical hardware in a single-tenant environment without…
- [Vultr Billing API](https://apis.io/apis/vultr/vultr-billing-api/) — Read-only [billing](https://my.vultr.com/billing/#billinghistory) information for your [user account](https://my.vultr.com/settings/#settingsprofile).
- [Vultr Block API](https://apis.io/apis/vultr/vultr-block-api/) — [Block Storage](https://www.vultr.com/products/block-storage/) volumes are highly-available, redundant, SSD backed, and expandable from 10 GB to 10,000 GB.…
- [Vultr Container Registry API](https://apis.io/apis/vultr/vultr-container-registry-api/) — Store and manage public and private container images for rapid deployment to Vultr Managed Kubernetes.
- [Vultr Dns API](https://apis.io/apis/vultr/vultr-dns-api/) — Vultr offers [free DNS hosting](https://www.vultr.com/docs/introduction-to-vultr-dns) for customers' domains. The nameservers are on an AnyCAST network and…
- [Vultr Firewall API](https://apis.io/apis/vultr/vultr-firewall-api/) — Vultr offers a [web-based firewall](https://www.vultr.com/docs/vultr-firewall) solution to protect one or more compute instances. [Firewall…
- [Vultr IAM Assumed Roles API](https://apis.io/apis/vultr/vultr-iam-assumed-roles-api/) — Manage temporary role assumptions
- [Vultr IAM Endpoint Actions API](https://apis.io/apis/vultr/vultr-iam-endpoint-actions-api/) — View available IAM endpoint-to-action mappings
- [Vultr IAM Groups API](https://apis.io/apis/vultr/vultr-iam-groups-api/) — Non-SCIM group management endpoints
- [Vultr IAM Policies API](https://apis.io/apis/vultr/vultr-iam-policies-api/) — Endpoints for managing IAM policies within an organization
- [Vultr IAM Policy-Group Mappings API](https://apis.io/apis/vultr/vultr-iam-policy-group-mappings-api/) — Manage direct policy attachments to groups
- [Vultr IAM Policy-User Mappings API](https://apis.io/apis/vultr/vultr-iam-policy-user-mappings-api/) — Manage direct policy attachments to users
- [Vultr IAM Role-Group Mappings API](https://apis.io/apis/vultr/vultr-iam-role-group-mappings-api/) — Manage role assignments to groups
- [Vultr IAM Role-Policy Mappings API](https://apis.io/apis/vultr/vultr-iam-role-policy-mappings-api/) — Manage the attachment and detachment of IAM policies to roles
- [Vultr IAM Role Trusts API](https://apis.io/apis/vultr/vultr-iam-role-trusts-api/) — Manage trust relationships between roles
- [Vultr IAM Role-User Mappings API](https://apis.io/apis/vultr/vultr-iam-role-user-mappings-api/) — Manage role assignments to users
- [Vultr IAM Roles API](https://apis.io/apis/vultr/vultr-iam-roles-api/) — Endpoints for managing IAM roles within an organization
- [Vultr Instances API](https://apis.io/apis/vultr/vultr-instances-api/) — Vultr [Cloud instances](https://www.vultr.com/products/cloud-compute/) can be [deployed](https://my.vultr.com/) with your preferred operating system or…
- [Vultr Iso API](https://apis.io/apis/vultr/vultr-iso-api/) — [Upload](https://www.vultr.com/features/upload-iso/) and boot instances from your ISO, or choose one from our [public ISO…
- [Vultr Kubernetes API](https://apis.io/apis/vultr/vultr-kubernetes-api/) — Vultr Kubernetes Engine is a managed Kubernetes offering.
- [Vultr Load Balancer API](https://apis.io/apis/vultr/vultr-load-balancer-api/) — [Load Balancers](https://www.vultr.com/docs/vultr-load-balancers) sit in front of your application and distribute incoming traffic across multiple…
- [Vultr Logs API](https://apis.io/apis/vultr/vultr-logs-api/) — Endpoints for viewing logs and for managing an audit logs subscription
- [Vultr Managed Databases API](https://apis.io/apis/vultr/vultr-managed-databases-api/) — [Vultr Managed Databases](https://www.vultr.com/docs/vultr-managed-databases/) is a managed database offering supporting MySQL, PostgreSQL, FerretDB +…
- [Vultr Organization Invitations API](https://apis.io/apis/vultr/vultr-organization-invitations-api/) — Manage invitations for users to join organizations
- [Vultr Organization Membership Management API](https://apis.io/apis/vultr/vultr-organization-membership-management-api/) — Manage users inside organizations (membership, roles, suspensions)
- [Vultr Organizations API](https://apis.io/apis/vultr/vultr-organizations-api/) — Manage organizations
- [Vultr Os API](https://apis.io/apis/vultr/vultr-os-api/) — We have a wide range of [operating systems](https://www.vultr.com/features/operating-systems/) available to deploy server instances. You can also [upload an…
- [Vultr Plans API](https://apis.io/apis/vultr/vultr-plans-api/) — A Plan is a particular configuration of vCPU, RAM, SSD, and bandwidth to deploy an [Instance](#tag/instances). Not all Plans are available in all…
- [Vultr private Networks API](https://apis.io/apis/vultr/vultr-private-networks-api/) — [Private Networks](https://www.vultr.com/docs/configuring-private-network) are fully isolated networks accessible only by instances on your account. Each…
- [Vultr Region API](https://apis.io/apis/vultr/vultr-region-api/) — Instances can be deployed in many [Regions](https://www.vultr.com/features/datacenter-locations/) on multiple continents. Choose any of our worldwide…
- [Vultr Reserved Ip API](https://apis.io/apis/vultr/vultr-reserved-ip-api/) — IP addresses can be [reserved](https://my.vultr.com/network/) and moved between [instances](#tag/instances). Reserved IPs can also be used as [floating…
- [Vultr S3 API](https://apis.io/apis/vultr/vultr-s3-api/) — [Object Storage](https://www.vultr.com/docs/vultr-object-storage) is S3 API compatible. Objects uploaded to object storage can be accessed privately or…
- [Vultr SCIM Groups API](https://apis.io/apis/vultr/vultr-scim-groups-api/) — SCIM 2.0 compliant endpoints for managing groups
- [Vultr SCIM Settings API](https://apis.io/apis/vultr/vultr-scim-settings-api/) — Manage SCIM enablement and tokens for organizations
- [Vultr SCIM Users API](https://apis.io/apis/vultr/vultr-scim-users-api/) — SCIM 2.0 compliant endpoints for managing users
- [Vultr Snapshot API](https://apis.io/apis/vultr/vultr-snapshot-api/) — A snapshot is a point-in-time image of an instance. We do not stop the instance when taking a snapshot. Booting from a snapshot is similar to rebooting…
- [Vultr Ssh API](https://apis.io/apis/vultr/vultr-ssh-api/) — You can add [SSH keys](https://www.vultr.com/docs/how-do-i-generate-ssh-keys/) to your [account](https://my.vultr.com/settings/#settingssshkeys), which can…
- [Vultr Startup API](https://apis.io/apis/vultr/vultr-startup-api/) — Vultr allows you to assign [two types of scripts to a server](https://www.vultr.com/docs/vultr-startup-scripts-quickstart-guide). Boot scripts configure new…
- [Vultr User Resources API](https://apis.io/apis/vultr/vultr-user-resources-api/) — Endpoints for viewing user-specific IAM resources (groups, roles, policies)
- [Vultr Users API](https://apis.io/apis/vultr/vultr-users-api/) — Vultr supports [multiple users](https://my.vultr.com/settings/#settingsusers) in each account, and each user has [individual access…
- [Vultr VPC2 API](https://apis.io/apis/vultr/vultr-vpc2-api/) — [VPCs](https://www.vultr.com/docs/how-to-create-a-vultr-virtual-private-cloud-vpc/) are fully isolated networks accessible only by instances on your…
- [Vultr VPCs API](https://apis.io/apis/vultr/vultr-vpcs-api/) — [VPCs](https://www.vultr.com/docs/how-to-create-a-vultr-virtual-private-cloud-vpc/) are fully isolated networks accessible only by instances on your…
- [Vultr Sub Account API](https://apis.io/apis/vultr/vultr-sub-account-api/) — Sub-accounts are separate Vultr accounts that are directly linked to your account. These accounts function similarly to normal Vultr accounts with some…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Vultr MCP Server](https://apis.io/servers/vultr/vultr-mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Vultr Agentic Access](https://apis.io/agentic-access/vultr/vultr-agentic-access/)

#### JSON Schema (18)

The data models the API reads and writes.

- [AssumedRoleSession](https://apis.io/schemas/vultr/vultr-assumed-role-session/)
- [baremetal](https://apis.io/schemas/vultr/vultr-baremetal/)
- [create_baremetal_request](https://apis.io/schemas/vultr/vultr-create-baremetal-request/)
- [create_database_request](https://apis.io/schemas/vultr/vultr-create-database-request/)
- [create_instance_request](https://apis.io/schemas/vultr/vultr-create-instance-request/)
- [ExtendedLog](https://apis.io/schemas/vultr/vultr-extended-log/)
- [firewall-rule](https://apis.io/schemas/vultr/vultr-firewall-rule/)
- [instance](https://apis.io/schemas/vultr/vultr-instance/)
- [loadbalancer](https://apis.io/schemas/vultr/vultr-loadbalancer/)
- [log](https://apis.io/schemas/vultr/vultr-log/)
- [log-meta](https://apis.io/schemas/vultr/vultr-log-meta/)
- [object-storage](https://apis.io/schemas/vultr/vultr-object-storage/)
- [RoleTrust](https://apis.io/schemas/vultr/vultr-role-trust/)
- [SCIMUser](https://apis.io/schemas/vultr/vultr-scimuser/)
- [update_advanced_options_request](https://apis.io/schemas/vultr/vultr-update-advanced-options-request/)
- [update_database_request](https://apis.io/schemas/vultr/vultr-update-database-request/)
- [update_instance_request](https://apis.io/schemas/vultr/vultr-update-instance-request/)
- [vke-cluster](https://apis.io/schemas/vultr/vultr-vke-cluster/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Vultr Context](https://apis.io/jsonld/vultr/vultr-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Vultr API Rules](https://apis.io/rules/vultr/vultr-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Vultr Authentication](https://apis.io/security/vultr/vultr-authentication/)
- [Vultr Domain Security](https://apis.io/security/vultr/vultr-domain-security/)

#### Rate limits (1)

Published request limits.

- [Vultr Rate Limits](https://apis.io/rate-limits/vultr/vultr-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.vultr.com)
- [Documentation](https://docs.vultr.com)
- [Getting started](https://docs.vultr.com/inference-cookbook/rocm/getting-started/first-deployment)
- [Changelog](https://docs.vultr.com/platform/api-opensource-changelog)
- [Blog](https://blogs.vultr.com)
- [GitHub](https://github.com/vultr)

## API Evangelist rating

**Kin Score 44.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 66.3 |
| Contract governance | 22.0 |
| Operational transparency | 42.1 |
| Developer ergonomics | 50.0 |
| Access clarity | 0.0 |

**Agent readiness 49.8** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/vultr/](https://apis.io/providers/vultr/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Vultr: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/vultr/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
