# RAG Security Checklist

- [ ] Classify document sources by trust level.
- [ ] Track document provenance and ingestion time.
- [ ] Do not treat retrieved text as instructions.
- [ ] Filter hidden text, comments, metadata, and markup where appropriate.
- [ ] Enforce user-level access control at retrieval time.
- [ ] Prevent private context from being embedded into links, images, or external calls.
- [ ] Test cross-user and cross-channel retrieval scenarios.
- [ ] Log which sources influenced each answer.
