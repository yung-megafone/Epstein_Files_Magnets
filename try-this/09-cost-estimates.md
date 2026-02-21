# Cost Estimates

Costs depend mostly on:
- corpus size (GB/TB)
- number of pages requiring OCR
- global egress (TB/month)
- search/graph index sizes
- staffing

## Cost levers
1) **Two-pass OCR**
   - Tesseract first
   - premium OCR only for low-confidence pages + high-value subsets

2) **Image storage policy**
   - always keep thumbnails + medium
   - full-res on demand; lifecycle to cold storage

3) **Search strategy**
   - classic inverted index for most queries
   - embeddings for similarity/topic clustering (targeted)

4) **Graph strategy**
   - evidence-backed edges only
   - precompute neighborhoods to reduce graph query cost

## Tiered scenarios (rough)

### Tier 1: Serious MVP
- Search + viewer + provenance
- basic entity graph (anchored)
- exports v1

**Monthly infra:** ~$1.5k – $8k  
**One-time OCR batch:** ~$3k – $30k (depends on pages and OCR choice)  
**Build:** ~£120k – £300k (8–12 weeks small team)

### Tier 2: Newsroom-grade
- adds timelines, topic explorer, workbook generator
- stronger graph and analytics
- comparator v1

**Monthly infra:** ~$10k – $45k  
**One-time OCR batch:** ~$30k – $200k+  
**Build:** ~£500k – £1.2m (3–6 months team)

### Tier 3: Global public utility
- high traffic; multi-region scaling
- full narrative layer + comparator + derivative datasets

**Monthly infra:** ~$60k – $250k  
**One-time OCR batch:** $200k – $1M+  
**Build:** ~£2m – £6m (9–18 months)

## Cost drivers explained (practical)
- **CDN egress** usually dominates once the product is popular.
- **OCR** dominates if scans are heavy and premium OCR is used broadly.
- **Search** dominates if you need HA + replicas + vector search at scale.

## Recommended budgeting approach
Start with Tier 1 MVP, instrument real usage and:
- measure % pages needing premium OCR
- measure CDN egress patterns
- measure query load and facet usage
Then scale to Tier 2 with evidence-driven spending.

