# Chat (chat)

Topic-level profile capturing the Chat API category in the API Evangelist network. This profile defines a reference vocabulary and a generic OpenAPI shape for chat APIs that manage conversations, messages, and participants, and is used as a baseline when cataloguing chat platform APIs (such as Slack, Discord, Microsoft Teams, Twilio Conversations, and conversational AI platforms) into the broader catalogue.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chat/refs/heads/main/apis.yml)

## Scope

- **Position:** Reference
- **Access:** 3rd-Party

## Tags

- Chat
- Conversational AI
- Conversations
- Customer Support
- Messaging
- Real-time

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Reference Chat API

Reference REST API shape for chat platforms covering conversation lifecycle (create/list/get), message send and history, participant management, and typing indicator events. Intended as a vocabulary and OpenAPI baseline for cataloguing concrete chat platform APIs.

- **Human URL:** [https://github.com/api-evangelist/chat](https://github.com/api-evangelist/chat)
- **Base URL:** `https://api.example.com/v1/chat`

#### Tags

- Chat
- Conversations
- Messaging

#### Properties

- [OpenAPI](openapi/chat-reference-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chat-reference.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chat-reference.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](spectral/chat-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Common Properties

- [Repository](https://github.com/api-evangelist/chat)
- [Catalog](https://apis.json/)
- [JSON-LD](json-ld/chat-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/chat-conversation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chat-message-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
