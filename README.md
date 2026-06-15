# Nabla (nabla)

Nabla provides ambient AI for clinicians through its Copilot product, which generates clinical notes from patient encounters across more than 85,000 clinicians and 150+ health organizations. Nabla also publishes a public Core API that exposes the same underlying capabilities (medical transcription, structured note generation, FHIR-normalized data extraction, multilingual patient summaries, magic edit, custom dictionary, dot phrases, and dictation) to third-party telehealth platforms, EHRs, and voice-enabled applications. Authentication uses OAuth 2.0 client credentials for the Server API and JWT-based access tokens for the User API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nabla/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nabla/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Healthcare
- Ambient AI
- Clinical Documentation
- Medical Transcription
- Speech Recognition
- FHIR
- SOAP Notes
- Voice
- EHR Integration

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Nabla Core API

The Nabla Core API transcribes medical encounters, generates structured clinical notes (for example SOAP), extracts FHIR-normalized data with ICD-10 and LOINC coding, produces multilingual patient-facing summaries, and supports magic edit, dictation, dot phrases, custom dictionaries, and feedback reporting. The API offers REST, WebSocket, and asynchronous endpoints, with audio file support up to 60 minutes.

- **Human URL:** [https://docs.nabla.com/](https://docs.nabla.com/)
- **Base URL:** `https://api.nabla.com`

#### Tags

- Transcription
- Clinical Notes
- SOAP
- FHIR
- Dictation
- Patient Summaries
- Magic Edit
- WebSocket

#### Properties

- [Documentation](https://docs.nabla.com/)
- [Getting Started](https://docs.nabla.com/guides/intro)
- [Authentication](https://docs.nabla.com/guides/authentication)
- [Sample App](https://github.com/nabla/sample-app)
- [Copilot Sample App](https://github.com/nabla/copilot-sample)
- [Postman Collection](collections/nabla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nabla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nabla Copilot Server API

The Server API is intended for server-to-server interactions, allowing backend systems to manage Copilot users and resources via OAuth 2.0 client credentials. OAuth clients can be configured with a JWKS URL (preferred for key rotation) or a static X.509-encoded public key.

- **Human URL:** [https://docs.nabla.com/server/jwt-authenticate-copilot-user/](https://docs.nabla.com/server/jwt-authenticate-copilot-user/)
- **Base URL:** `https://api.nabla.com`

#### Tags

- Server API
- OAuth 2.0
- Client Credentials
- User Management

#### Properties

- [Documentation](https://docs.nabla.com/server/jwt-authenticate-copilot-user/)
- [Authentication](https://docs.nabla.com/guides/authentication)
- [Postman Collection](collections/nabla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nabla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nabla Copilot User API

The User API enables client-side applications to act on behalf of an individual user by exchanging server-issued access and refresh tokens to autonomously call the Nabla Core API. Includes WebSocket transcription for live medical encounters via /user/copilot/listen.

- **Human URL:** [https://docs.nabla.com/user/copilot-listen-ws/](https://docs.nabla.com/user/copilot-listen-ws/)
- **Base URL:** `https://api.nabla.com`

#### Tags

- User API
- JWT
- WebSocket
- Live Transcription

#### Properties

- [Documentation](https://docs.nabla.com/user/copilot-listen-ws/)
- [Authentication](https://docs.nabla.com/guides/authentication)
- [Postman Collection](collections/nabla.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nabla.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.nabla.com/)
- [Documentation](https://docs.nabla.com/)
- [Getting Started](https://docs.nabla.com/guides/intro)
- [Authentication](https://docs.nabla.com/guides/authentication)
- [Help Center](https://help.nabla.com/)
- [Status Page](https://status.nabla.com/)
- [Blog](https://www.nabla.com/blog)
- [Newsletter](https://thehealthcarehoagie.substack.com/)
- [Contact](https://www.nabla.com/contact)
- [Email](mailto:contact@nabla.com)
- [GitHub Organization](https://github.com/nabla)
- [Sample App](https://github.com/nabla/sample-app)
- [Copilot Sample App](https://github.com/nabla/copilot-sample)
- [LinkedIn](https://www.linkedin.com/company/nabla-technologies)
- [Twitter](https://twitter.com/nabla_tech)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Authentication](undefined)
- [Compliance](undefined)
- [Adoption](undefined)
- [Offices](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
