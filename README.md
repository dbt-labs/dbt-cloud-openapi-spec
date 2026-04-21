# dbt Cloud OpenAPI Spec

This repo holds the OpenAPI specs for the dbt Cloud API (v2 and v3). It exists as a git repo rather than an S3 bucket mainly for change history, and because docs.getdbt.com already points here.

The specs are updated automatically via CI when API endpoints change in the dbt Cloud monolith.

## Files

- `openapi-v2.yaml` — v2 API spec
- `openapi-v3.yaml` — v3 API spec

## Local development

To serve the specs locally (with CORS headers, for use with Swagger UI or similar):

```bash
python3 serve.py
```

Specs will be available at `http://localhost:8000`.
