# Fengsoft

Open-source foundations for SaaS systems.

We build reusable backend components for authentication, async jobs, event pipelines, webhook delivery, and caching, with strong typing, operational clarity, and production-oriented docs.

## Core Projects

| Project | Focus |
| --- | --- |
| [auth-core](https://github.com/fengsoft/auth-core) | Authentication foundation for SaaS apps built on Better Auth. |
| [queueflow](https://github.com/fengsoft/queueflow) | Async job processing, workers, retries, and operational flows. |
| [eventflow](https://github.com/fengsoft/eventflow) | Event ingestion, schemas, replay, and analytics foundations. |
| [webhook-core](https://github.com/fengsoft/webhook-core) | Outbound webhooks with signing, retries, replay, and delivery tracking. |
| [cache-core](https://github.com/fengsoft/cache-core) | Caching primitives, invalidation, metrics, and Redis integration. |

## Why Fengsoft

- Library-first building blocks instead of platform lock-in.
- Typed contracts and SDKs for clear service boundaries.
- Operationally explicit systems with docs and examples in each repo.
- Focused on real SaaS backend problems: auth, queues, events, webhooks, and cache.

## Where To Start

- Start with [auth-core](https://github.com/fengsoft/auth-core) for authentication and app identity flows.
- Add [queueflow](https://github.com/fengsoft/queueflow) for background jobs and async orchestration.
- Use [eventflow](https://github.com/fengsoft/eventflow) for ingestion, replay, and analytics pipelines.
- Use [webhook-core](https://github.com/fengsoft/webhook-core) for outbound integrations.
- Use [cache-core](https://github.com/fengsoft/cache-core) when you need explicit cache semantics and invalidation.

## Contributing

Issues and pull requests are welcome in each repository. If you are evaluating the stack, start from the README and docs of the component you need first.
