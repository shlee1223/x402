---
"@x402/extensions": minor
---

JWS offers and receipts now carry a `typ` header (`x402-offer+jws` / `x402-receipt+jws`). `verifyOfferSignatureJWS` and `verifyReceiptSignatureJWS` reject a JWS whose `typ` names the other artifact type; a JWS without `typ` is still accepted.
