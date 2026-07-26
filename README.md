# AI Studio

Prompts, agents, knowledge and automation

Craft and manage LLM prompts, autonomous agents, chatbot flows, knowledge bases, and RAG pipelines. Configure personas, guardrails, output schemas, evaluations, prompt chains, model settings, and human-in-the-loop approval workflows.

## Microservices Used

**Platform baseline** (common to every app & studio): `gateway-service`, `authentication-service`, `identity-service`, `access-service`, `security-service`, `audit-service`, `observability-service`, `control-service`, `deployment-service`, `integration-service`, `storage-service`, `reporting-service`, `analytics-service`, `notification-service`

**Functional services (9):**

| Service | Status |
|---|---|
| `model-service` | Core |
| `agent-service` | Core |
| `codegen-service` | Core |
| `knowledge-service` | Core |
| `document-service` | Core |
| `search-service` | Core |
| `automation-service` | Core |
| `workflow-service` | Core |
| `recommendation-service` | Suggested — not yet built |
