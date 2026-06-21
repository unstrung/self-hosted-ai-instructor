```mermaid
graph TD
    User([User Query]) --> Chatwoot[Chatwoot Frontend]
    Chatwoot --> n8n[n8n Automation Engine]
    n8n --> Wiki[Wiki.js Knowledge Base]
    Wiki --> n8n
    n8n --> LLM[LLM / AI Backend]
    LLM --> n8n
    n8n --> Chatwoot
    Chatwoot --> UserResponse([Educated User Response])
