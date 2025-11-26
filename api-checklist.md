# API Readiness Checklist


A quick, practical checklist to ensure an API is ready for real users.


## Functional
- [ ] Clear request/response contracts
- [ ] Validation & sanitization for all inputs
- [ ] Idempotency for retryable operations
- [ ] Pagination for list endpoints
- [ ] Consistent error format & error codes
- [ ] Rate limiting strategy


## Performance
- [ ] Defined SLA/SLO for latency & availability
- [ ] Load-tested under expected traffic patterns
- [ ] Caching strategy (client/server)


## Reliability
- [ ] Timeouts & retries configured
- [ ] Circuit breaker or fallback logic
- [ ] Dependency health monitored


## Observability
- [ ] Structured logging (correlation IDs included)
- [ ] Metrics: latency, errors, throughput
- [ ] Trace coverage for critical endpoints


## Documentation
- [ ] OpenAPI / Swagger spec published
- [ ] Examples for common use cases
- [ ] Clear versioning strategy
