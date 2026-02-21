# Security, Safety, and Ethics

## Threat model (high level)
- Abuse: doxxing, harassment, malicious targeting
- Data tampering: fake files injected into mirrors
- Misinterpretation: “mention = guilt”
- Scalability abuse: scraping, denial of service
- Sensitive content exposure

## Security controls
- WAF + rate limiting
- bot mitigation for public endpoints
- signed URLs for high-cost assets (optional)
- strict CORS and CSP headers
- vulnerability scanning + dependency pinning
- least-privilege IAM for storage and indexes

## Integrity controls
- SHA-256 for every raw file
- provenance capture (source URL, retrieval timestamp)
- pipeline versioning for derived artifacts
- mismatch detection between mirrors and authoritative sources

## Ethics guardrails
- Redaction-aware: detect and visualize patterns without attempting “unredaction”
- Victim protection:
  - do not surface sensitive personal data in derivative exports
  - provide “sensitive content blur/gate” where necessary
- Strong disclaimers on every entity page:
  - “Mention in a document does not imply wrongdoing.”

## UI safety patterns
- Confidence badges and evidence types
- Default to “strict evidence mode”
- “Inference mode” requires explicit toggle + warning
- Report/flag button on docs, entities, and edges

## Moderation and governance
- Admin console for:
  - removing unsafe derivative outputs
  - marking entities as “high-risk for harassment”
  - suppressing low-confidence edges
- Public transparency reports (optional)

