# WWSrapport Postman collection

Official Postman collection for the WWSrapport public API.

## Links

- API overview and Swagger: https://wwsrapport.nl/api/docs
- OpenAPI JSON: https://wwsrapport.nl/api/openapi.json
- Request API access: https://wwsrapport.nl/api/toegang-aanvragen
- GitHub organization: https://github.com/wwsrapport

## Use

1. Import `WWSrapport API.postman_collection.json`.
2. Import `WWSrapport Sandbox.postman_environment.json`.
3. Set `api_key` to your sandbox or live API key.
4. Run `Create report` with a unique `idempotency_key`.

The default environment points to:

```text
https://wwsrapport.nl/v1
```

## Covered resources

- Property prefill
- Report validation
- Report creation
- Report recalculation
- Report list and retrieval
- Calculation JSON
- Improvement advice JSON
- PDF documents
- Usage
- Rulesets
- Webhook endpoints and deliveries

Report creation and recalculation use `Idempotency-Key` to avoid duplicate report versions or quota usage.

