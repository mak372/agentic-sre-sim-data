# Queue Depth Growth Runbook

## Symptoms
- Increasing message backlog
- Consumer lag
- Increased processing latency

## Investigation Steps
1. Verify consumer health
2. Check message processing rate
3. Inspect dead-letter queues
4. Review payload size changes

## Mitigation
- Scale consumers
- Reduce message complexity
- Replay failed messages
