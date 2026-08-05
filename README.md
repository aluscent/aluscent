<div align="center">

# Ali Tarverdy

### Senior Data Engineer · Scala & Distributed Data Systems

I design and improve data-intensive systems where **correctness, performance, and operational reliability** matter — particularly in financial and regulated environments.

[LinkedIn](https://www.linkedin.com/in/ali-t-asl/) · [Medium](https://medium.com/@ali.t.asl) · [Email](mailto:ali.t.asl@outlook.com)

**Open to senior engineering opportunities and focused consulting engagements.**

</div>

---

## Engineering profile

I have **6+ years of professional engineering experience** across data platforms and Scala backend systems. I work at the boundary between business-critical data, distributed computation, and production software engineering.

My role is not limited to implementing pipelines. I turn ambiguous reporting, integration, and platform requirements into systems with explicit contracts, testable transformations, observable execution, and a clear operational model.

I am strongest when the problem involves:

- architecting batch and streaming data workflows
- diagnosing Spark and SQL performance at execution-plan level
- designing reliable Scala services and event-driven components
- protecting data correctness through validation, reconciliation, and controlled change
- modernizing fragile pipelines without disrupting downstream consumers
- communicating architecture and trade-offs across engineering and business stakeholders

## Problems I solve

| Engineering problem | How I approach it |
| --- | --- |
| **Slow or unstable Spark workloads** | Inspect physical plans, shuffle behavior, skew, partitioning, join strategy, caching, and file layout before changing infrastructure. |
| **Critical pipelines with weak reliability** | Make retry boundaries, idempotency, replay, backfill, schema evolution, and failure visibility explicit design concerns. |
| **Complex financial-data transformations** | Separate business rules from execution mechanics, preserve traceability, and design reconciliation into the processing flow. |
| **Low trust in data and lineage** | Introduce validation, metadata, column-level lineage, ambiguity handling, and explainable source-to-sink mappings. |
| **Scala systems becoming difficult to evolve** | Use functional design, disciplined effects, type-safe boundaries, focused abstractions, and integration testing to reduce accidental complexity. |
| **Architecture decisions driven by tools** | Start from constraints, failure modes, operating costs, and ownership — then select the technology. |

## Selected systems

### [Transaction Guarantee Reporting System](https://github.com/aluscent/Transaction-Report)

A Scala and Apache Spark reporting pipeline for financial transactions involving guarantor allocation, currency normalization, registry validation, partitioned reporting, and PostgreSQL integration.

**Engineering focus**

- DataFrame and Spark SQL implementations of the same reporting logic
- broadcast-join and partitioning decisions for asymmetric datasets
- financial-data validation and transformation boundaries
- unit and integration testing around the complete processing flow
- performance-aware design using predicate pushdown and controlled caching

**Why it matters:** this project demonstrates an end-to-end reporting system rather than an isolated transformation — from source data and business rules to persistence, testing, and documented execution choices.

### [SQL Lineage Explorer](https://github.com/aluscent/SQL-Lineage-Explorer)

A column-level lineage engine and interactive interface for chained Spark SQL. It resolves aliases, expands schema-aware star projections, captures non-projection influences, identifies ambiguous references, and visualizes source-to-sink data flow.

**Engineering focus**

- SQL parsing and metadata modelling
- directed graph construction across intermediate query stages
- lineage for expressions, joins, filters, grouping, and ordering
- structured ambiguity detection and human-assisted resolution
- CLI and web interfaces for different engineering workflows

**Why it matters:** the project treats lineage as an engineering and trust problem, not merely a diagram — making complex transformations easier to inspect, explain, and change safely.

## Technical depth

| Area | Primary capabilities |
| --- | --- |
| **Distributed data processing** | Apache Spark, Spark SQL, Databricks, Delta Lake, Parquet, Hive-compatible platforms, large joins and aggregations |
| **Scala engineering** | Scala, Cats, Cats Effect, Akka/Pekko, functional programming, concurrent and event-driven systems |
| **Data movement and integration** | Kafka, CDC patterns, JDBC, PostgreSQL, Oracle, Cassandra, batch and streaming pipelines |
| **Platform engineering** | Microsoft Azure, Docker, Kubernetes, Linux, Git, CI/CD, dependency and environment management |
| **Production quality** | Integration testing, Testcontainers, observability, performance analysis, failure recovery, maintainable system boundaries |
| **Domain focus** | Financial data, regulatory reporting, governed data platforms, lineage, auditability, and data quality |

## How I engineer

- **Correctness is a system property.** Validation, reconciliation, contracts, and failure behavior belong in the architecture.
- **Performance work starts with evidence.** I prefer execution plans, runtime metrics, and representative workloads over intuition-driven tuning.
- **Operability is part of delivery.** A pipeline is incomplete without monitoring, recovery, backfill, and ownership considerations.
- **Abstractions must earn their cost.** I use functional and type-safe techniques to clarify systems, not to make simple problems look sophisticated.
- **Technical decisions should remain explainable.** Architecture diagrams, decision records, tests, and precise documentation reduce long-term risk.
- **Senior engineering is leverage.** The goal is not only to deliver code, but to leave behind clearer systems, reusable patterns, and stronger engineering judgment.

## Consulting

I work with engineering teams that need concentrated expertise in data-intensive and Scala-based systems.

Typical engagements include:

- **Spark performance assessment** — execution-plan analysis, bottleneck diagnosis, benchmark design, and a prioritized optimization plan
- **Pipeline reliability review** — failure-mode analysis, replay and backfill strategy, data-quality controls, and observability recommendations
- **Data-platform architecture review** — current-state mapping, architectural risks, target design, and an incremental implementation roadmap
- **Scala modernization** — architecture and dependency review, effect and concurrency boundaries, testing strategy, and migration planning
- **Lineage and governance design** — metadata modelling, column-level lineage, auditability, and integration options

A focused engagement typically produces a **current-state assessment, risk map, target architecture, decision record, proof of concept where useful, and an implementation roadmap**. The objective is to leave the team with both a better system and the reasoning needed to maintain it.

## Current focus

- high-performance Spark and SQL workloads
- lakehouse architecture and governed data products
- replay-safe streaming and event-driven systems
- lineage, metadata, and data-quality tooling
- financial and regulatory data platforms
- reusable Scala patterns for reliable production services

---

<div align="center">

### Let’s work on a difficult data problem.

For senior engineering roles, architecture discussions, or consulting engagements:

[LinkedIn](https://www.linkedin.com/in/ali-t-asl/) · [Email](mailto:ali.t.asl@outlook.com)

</div>
