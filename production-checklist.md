# Production Readiness Checklist


Ensure your backend service is ready for real-world production environments.


## Stability
- [ ] Healthchecks: liveness & readiness
- [ ] Graceful shutdown handling
- [ ] Backpressure handling
- [ ] Retry-safe logic in consumers/producers


## Monitoring & Alerting
- [ ] Dashboards for latency, saturation, errors
- [ ] Alerts tuned to actionable thresholds
- [ ] Runbook available & up to date


## Infrastructure
- [ ] Auto-scaling rules configured
- [ ] Resource limits defined
- [ ] DB backups & restore tested
- [ ] Rollback strategy documented


## Security
- [ ] Secrets managed via secure store
- [ ] TLS everywhere
- [ ] Access logs enabled
- [ ] Dependency vulnerability scans


## Performance
- [ ] Load-testing complete
- [ ] Baseline performance metrics recorded
- [ ] Stress test results available
