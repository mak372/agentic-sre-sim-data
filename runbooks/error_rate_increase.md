# Error Rate Increase Runbook

## Symptoms
- HTTP 5xx spike
- Application exceptions
- Circuit breakers opening

## Investigation Steps
1. Review error logs for common stack traces
2. Check schema or payload changes
3. Inspect feature flag rollouts
4. Verify dependency health

## Mitigation
- Roll back recent release
- Disable problematic feature flags
- Restart affected pods
