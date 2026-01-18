# Latency Spike Runbook

## Symptoms
- Increased p95 / p99 latency
- Slow downstream calls
- Thread pool saturation

## Investigation Steps
1. Check recent deployments (last 30 minutes)
2. Inspect database slow query logs
3. Check connection pool utilization
4. Review downstream service latency
5. Verify autoscaling behavior

## Mitigation
- Roll back recent deployment if correlated
- Scale service replicas
- Enable query caching
