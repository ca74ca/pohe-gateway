# pohe-gateway
Proof of Human Effort (PoHE) gateway for deterministic compute admission.

**Production gateway:** https://gateway.varacis.com

This repo documents the PoHE Gateway behavior and integration.

## Usage

Original:
```
https://api.perplexity.ai/v1/models
```

With Varacis PoHE Gateway:
```
https://gateway.varacis.com/gateway/perplexity/v1/models
```

Authentication:
```
-H "X-Upstream-Key: <YOUR_EXISTING_API_KEY>"
```