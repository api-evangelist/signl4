# SIGNL4 (signl4)

SIGNL4 is a mobile alerting and on-call duty management service that transforms emails, webhooks, and IoT events into reliable push, SMS, and voice alerts with acknowledgement tracking, escalation, and team on-call scheduling. The platform provides both an inbound webhook for sending alerts and a REST API for managing alerts, statuses, annotations, and team data. Authentication uses a team or webhook secret embedded in the URL path or supplied via the X-S4-Api-Key header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/signl4/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/signl4/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Alerting
- Incident Management
- On-Call
- Mobile Alerts
- Notifications
- DevOps
- IT Operations
- Monitoring

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### SIGNL4 Inbound Webhook API

Simple HTTPS webhook endpoint for triggering mobile alerts in SIGNL4 from any monitoring, ITSM, or IoT tool. Accepts JSON payloads with Title and Message fields plus optional X-S4 control parameters for service categorization, location, alerting scenario, and external identifiers. Authentication uses a unique team or webhook secret embedded in the URL path.

- **Human URL:** [https://docs.signl4.com/integrations/webhook/webhook.html](https://docs.signl4.com/integrations/webhook/webhook.html)
- **Base URL:** `https://connect.signl4.com/webhook`

#### Tags

- Webhook
- Inbound
- Alerting
- Mobile Push

#### Properties

- [Documentation](https://docs.signl4.com/integrations/webhook/webhook.html)
- [API Reference](https://connect.signl4.com/webhook/docs/index.html)
- [Code  Samples](https://github.com/signl4/code-snippets)
- [Postman Collection](collections/signl4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/signl4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SIGNL4 REST API

RESTful API for programmatic alert lifecycle management including creating events, acknowledging or closing alerts, annotating alerts, and retrieving team data. Authentication is via X-S4-Api-Key header with the team or webhook secret.

- **Human URL:** [https://docs.signl4.com/integrations/rest-api/rest-api.html](https://docs.signl4.com/integrations/rest-api/rest-api.html)
- **Base URL:** `https://connect.signl4.com/api`

#### Tags

- REST
- Alert Management
- Events
- Incident Response

#### Properties

- [Documentation](https://docs.signl4.com/integrations/rest-api/rest-api.html)
- [Overview](https://www.signl4.com/webhook-rest-smtp-api-integration/)
- [Code  Samples](https://docs.signl4.com/samples/code-samples/code-samples.html)
- [Postman Collection](collections/signl4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/signl4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/signl4)
- [Website](https://www.signl4.com)
- [Documentation](https://docs.signl4.com)
- [Pricing](https://www.signl4.com/pricing/)
- [Sign Up](https://account.signl4.com/register)
- [Support](https://support.signl4.com)
- [Blog](https://www.signl4.com/blog/)
- [Git Hub](https://github.com/signl4)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
