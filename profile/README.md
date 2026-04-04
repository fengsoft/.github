# Fengsoft

Open-source building blocks for modern SaaS products.

Fengsoft publishes reusable backend and platform foundations: authentication,
audit trails, queues, events, notifications, webhooks, caching, storage, media,
SaaS domain primitives, and an end-to-end starter that wires the stack
together.

## Core Infrastructure

| Project | Focus |
| --- | --- |
| [auth-core](https://github.com/fengsoft/auth-core) | Authentication foundation for SaaS apps built on Better Auth. |
| [audit-core](https://github.com/fengsoft/audit-core) | Audit trails, contracts, redaction, and append-only activity history. |
| [queueflow](https://github.com/fengsoft/queueflow) | Async job processing, workers, retries, and operational flows. |
| [eventflow](https://github.com/fengsoft/eventflow) | Event ingestion, schemas, replay, and analytics foundations. |
| [notification-core](https://github.com/fengsoft/notification-core) | Notification orchestration for email and in-app delivery. |
| [webhook-core](https://github.com/fengsoft/webhook-core) | Outbound webhooks with signing, retries, replay, and delivery tracking. |
| [cache-core](https://github.com/fengsoft/cache-core) | Caching primitives, invalidation, metrics, and Redis integration. |

## Platform Foundations

| Project | Focus |
| --- | --- |
| [storage-core](https://github.com/fengsoft/storage-core) | Vendor-neutral object storage with R2, filesystem, and memory adapters. |
| [media-core](https://github.com/fengsoft/media-core) | Media pipeline for upload validation, variants, thumbnails, and cleanup. |
| [saas-core](https://github.com/fengsoft/saas-core) | Workspaces, membership, invites, entitlements, quotas, and billing state primitives. |

## Starter

| Project | Focus |
| --- | --- |
| [saas-starter](https://github.com/fengsoft/saas-starter) | Official reference app that composes the Fengsoft stack end-to-end. |

## Where To Start

- Start with [saas-starter](https://github.com/fengsoft/saas-starter) if you want the full architecture in one repo.
- Add [saas-core](https://github.com/fengsoft/saas-core), [auth-core](https://github.com/fengsoft/auth-core), and [audit-core](https://github.com/fengsoft/audit-core) for tenant, identity, and activity foundations.
- Use [storage-core](https://github.com/fengsoft/storage-core) and [media-core](https://github.com/fengsoft/media-core) for file and media workflows.
- Add [queueflow](https://github.com/fengsoft/queueflow), [eventflow](https://github.com/fengsoft/eventflow), [notification-core](https://github.com/fengsoft/notification-core), [webhook-core](https://github.com/fengsoft/webhook-core), and [cache-core](https://github.com/fengsoft/cache-core) as your system grows.

## Why Fengsoft

- Public, typed backend foundations instead of product-specific boilerplate.
- Clear package boundaries, operational behavior, and reference docs in each repo.
- A stack that can be adopted one core at a time or as a complete starter platform.

## Contributing

Issues and pull requests are welcome in each repository. Start from the README
and docs of the component you need first.
