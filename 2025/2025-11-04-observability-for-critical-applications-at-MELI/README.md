# Observability for Critical Applications at MELI

| Key Information | Details                                                                                               |
| --------------- | ----------------------------------------------------------------------------------------------------- |
| Event           | [ClickHouse Meetup @ São Paulo](https://www.meetup.com/clickhouse-brasil-user-group/events/311342702) |
| Date            | November 4, 2025                                                                                      |
| Speaker         | [Vitor Vasconcellos](https://www.linkedin.com/in/vvasconcellos/)                                      |
| Slides          | [Slides (PDF)](slides.pdf)                                                                            |
| Video           | [Recording (YouTube)](https://youtu.be/YGCAcTjolA0)                                                   |
| Language        | Portuguese 🇧🇷                                                                                         |

## Abstract

This talk shows how Mercado Libre dealt with the challenge of debugging failures
in large-scale, business-critical systems. With tens of thousands of
microservices and billions of spans per minute, traditional observability tools
became insufficient for high-cardinality, user-specific investigations.

We walk through the motivation for capturing 100% of traces in critical
applications, the resulting explosion in telemetry volume, and the path to a
cost-efficient ClickHouse-based backend. From ingestion pipelines to schema
design and query patterns, the session covers the architecture decisions and
trade-offs that enabled fast, accurate trace retrieval enriched with business
context such as payment and user identifiers.
