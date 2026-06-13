# Arcadia

Arcadia is the leading clean energy data platform that provides developers and businesses with programmatic access to utility billing data, real-time energy usage, and tariff intelligence across thousands of utility providers in the United States. The Arc Connect API enables applications to collect and synchronize utility account credentials, retrieve structured billing statements, and access granular interval meter data down to 15-minute readings. Arcadia's Plug API covers more than 95% of US utility accounts, supporting use cases including energy management, carbon accounting, solar savings analysis, EV charging optimization, and community solar enrollment.

**Website:** https://www.arcadia.com/  
**Developer Docs:** https://docs.arcadia.com/  
**GitHub:** https://github.com/ArcadiaPower  
**LinkedIn:** https://www.linkedin.com/company/arcadiahq/  
**X:** https://x.com/arcadiapower  
**Blog:** https://www.arcadia.com/blog  
**Status:** https://status.arcadia.com/  

## APIs

- **Plug API** — Utility account data: billing statements, meters, and 15-minute interval usage
- **Signal API** — Tariff and energy rate calculation engine for cost modeling
- **Switch API** — Rate plan optimization and recommendation
- **Utility Cloud API** — Enterprise-grade data warehouse access via SQL/Snowflake

## Authentication

Arcadia uses OAuth 2.0. Clients obtain bearer tokens by posting their Client ID and Client Secret to `https://api.arcadia.com/oauth2/token`. Tokens expire after one hour.

## Resources

- [apis.yml](apis.yml) — APIs.json 0.19 provider index
- [plans/arcadia-plans-pricing.yml](plans/arcadia-plans-pricing.yml) — Pricing and plan details
- [rate-limits/arcadia-rate-limits.yml](rate-limits/arcadia-rate-limits.yml) — Rate limit documentation
- [finops/arcadia-finops.yml](finops/arcadia-finops.yml) — FinOps Framework guidance
