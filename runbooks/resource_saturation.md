# Resource Saturation Runbook

## Symptoms
- High CPU or memory usage
- Frequent garbage collection
- Pod restarts or evictions

## Investigation Steps
1. Check container resource limits
2. Review recent traffic spikes
3. Inspect heap dumps
4. Analyze expensive code paths

## Mitigation
- Increase resource limits
- Scale horizontally
- Optimize hot paths
