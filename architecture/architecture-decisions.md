# Architecture Decisions

## Decision 1

Use Azure AI Search instead of custom vector database.

### Reason

- Native Azure integration
- Enterprise security
- Lower operational overhead

---

## Decision 2

Use Managed Identity instead of secrets.

### Reason

- Improved security
- Reduced credential management
