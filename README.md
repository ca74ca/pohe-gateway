# pohe-gateway

Proof of Human Effort (PoHE) gateway for deterministic compute admission.

This repository documents and will open-source the Varacis PoHE gateway —
an admission governor that sits in front of AI providers and makes a single
decision per request: ALLOW / DEFER / BLOCK.

## Live Gateway

The production gateway is currently running at:

https://gateway.varacis.com

Supported providers can be discovered via:

https://gateway.varacis.com/healthz

Example request:

```bash
curl https://gateway.varacis.com/gateway/perplexity/v1/models \
  -H "X-Upstream-Key: $PERPLEXITY_API_KEY"
```