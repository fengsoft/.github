# Fengsoft

Core infrastructure for SaaS products.

We build products privately and open-source selected backend cores where reuse matters: authentication, async jobs, event pipelines, notification delivery, webhooks, and caching.

## Core Projects

| Project | Focus |
| --- | --- |
| [auth-core](https://github.com/fengsoft/auth-core) | Authentication foundation for SaaS apps built on Better Auth. |
| [queueflow](https://github.com/fengsoft/queueflow) | Async job processing, workers, retries, and operational flows. |
| [eventflow](https://github.com/fengsoft/eventflow) | Event ingestion, schemas, replay, and analytics foundations. |
| [notification-core](https://github.com/fengsoft/notification-core) | Notification orchestration for email and in-app delivery. |
| [webhook-core](https://github.com/fengsoft/webhook-core) | Outbound webhooks with signing, retries, replay, and delivery tracking. |
| [cache-core](https://github.com/fengsoft/cache-core) | Caching primitives, invalidation, metrics, and Redis integration. |

## Why Fengsoft

- Product-first architecture with reusable open-source cores.
- Typed contracts and SDKs for clear service boundaries.
- Operationally explicit systems with docs and examples in each core repo.
- Public cores for shared backend problems; private apps and product surfaces on top.

## Where To Start

- Start with [auth-core](https://github.com/fengsoft/auth-core) for authentication and app identity flows.
- Add [queueflow](https://github.com/fengsoft/queueflow) for background jobs and async orchestration.
- Use [eventflow](https://github.com/fengsoft/eventflow) for ingestion, replay, and analytics pipelines.
- Use [notification-core](https://github.com/fengsoft/notification-core) for email and in-app notification flows.
- Use [webhook-core](https://github.com/fengsoft/webhook-core) for outbound integrations.
- Use [cache-core](https://github.com/fengsoft/cache-core) when you need explicit cache semantics and invalidation.

## Contributing

Issues and pull requests are welcome in each repository. If you are evaluating the stack, start from the README and docs of the component you need first.
