# SRE (Site Reliability Engineering)

## Service levels

### SLI (Service level indicator)
  95th percentile latency of homepage requests over past 5 minutes < 300ms

  - Request latency
  - Batch throughput
  - Failure per request

### SLO (Service level objectives)
  95th percentile homepage SLI will succeed 99.9% over trailing year

  Binding target for a collection of SLIs

### SLA (Service level agreements)
  Service credits if 95th percentile homepage SLI succeed less than 99.5% over trailing year

  - Business agreement between a customer and service provider typically based on SLOs

> SLIs drive SLOs which inform SLAs

![Alt SLIs,SLOs,SLAs](img/sli_slo_sla.png)

***
# Referências

- [SRE fundamentals slis,slas and slos](https://cloud.google.com/blog/products/gcp/sre-fundamentals-slis-slas-and-slos)
- [SLIs, SLOs, SLAs, oh my! (class SRE implements DevOps)](https://www.youtube.com/watch?v=tEylFyxbDLE&list=PLIivdWyY5sqJrKl7D2u-gmis8h9K66qoj&index=3&t=0s)
