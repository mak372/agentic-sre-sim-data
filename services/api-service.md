# API Service

## Description
The API service handles incoming client requests and orchestrates calls to
downstream services.

## Dependencies
- auth-service
- inventory-service
- database
- redis-cache

## Traffic Profile
- Average RPS: 800
- Peak RPS: 2000

## SLOs
- p95 latency < 300ms
- Error rate < 1%
