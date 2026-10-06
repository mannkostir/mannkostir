## Artem Gabatov — Senior Backend Engineer

Node.js / NestJS, TypeScript. I build event-driven systems: microservices on Kafka, CDC and streaming pipelines with Flink, and domain models that hold their invariants under DDD.

I turn the patterns I keep needing in production into small, tested, documented libraries:

| Library | What it does | |
|---|---|---|
| [nestjs-kafka](https://github.com/mannkostir/nestjs-kafka) | Decorator-driven Kafka consumers and producer for NestJS on librdkafka: dead-letter and retry topics, Avro via Schema Registry, topic namespacing | [npm](https://www.npmjs.com/package/nestjs-kafka-connector) |
| [typeorm-unit-of-work](https://github.com/mannkostir/typeorm-unit-of-work) | Unit of Work for TypeORM: ambient transactions, aggregate domain events before and after commit, transactional outbox | [npm](https://www.npmjs.com/package/typeorm-unit-of-work) |
| [flink-projections](https://github.com/mannkostir/flink-projections) | Stateful Flink operators that project entity change streams into search documents, with explicit deletes and savepoint-safe state | [Maven Central](https://central.sonatype.com/artifact/io.github.mannkostir/flink-projections) |
| [nest-result](https://github.com/mannkostir/nest-result) | Typed errors for NestJS: the compiler proves every error is mapped to an HTTP response | [npm](https://www.npmjs.com/package/nest-result) |
| [domain-integrity](https://github.com/mannkostir/domain-integrity) | Static analysis that fails CI when an aggregate's lifecycle drifts from its declared intent | [npm](https://www.npmjs.com/package/domain-integrity) |

**Stack:** TypeScript · Node.js · NestJS · PostgreSQL · Kafka · Flink · Elasticsearch / OpenSearch · Redis · Kubernetes · Java

📫 Telegram [@agabatov](https://t.me/agabatov) · mannkostir@gmail.com
