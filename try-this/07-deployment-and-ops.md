# Deployment and Ops

## Global availability strategy
- **CDN** for static assets and page images
- **Edge caching** for popular documents/pages
- **Regional read replicas** (optional) for search latency

## Suggested deployment topology
- UI hosted on edge platform (Vercel/Netlify/Cloudflare Pages) or containerized behind CDN
- APIs behind global load balancer
- Search cluster in primary region + replicas (as needed)
- Object store with CDN fronting

## Caching
- Thumbnails: cache long (immutable)
- Medium images: cache long
- Full-res images: cache shorter or on-demand
- API responses:
  - cached for public, non-personalized endpoints
  - use stale-while-revalidate where possible

## Observability
- Metrics:
  - ingestion throughput, OCR failure rate, mean OCR confidence
  - search latency, p95/p99
  - CDN hit ratio, egress TB
- Logs:
  - pipeline step logs per document
  - audit logs for admin actions
- Tracing:
  - request traces across services

## Reliability & scaling
- Pipelines scale horizontally by document/page batches
- Search scaling based on index size + query load
- Graph scaling via precomputed neighborhoods and caching

## Backups
- Postgres daily snapshots + PITR
- Search snapshots (OpenSearch snapshots)
- Object store versioning + lifecycle policies

