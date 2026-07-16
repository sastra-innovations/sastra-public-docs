# Features Overview

This page provides a high-level capability matrix for Medha, MedhaOS and SastraPDF. It describes public capability areas and current documentation focus without publishing proprietary implementation details or an unverified roadmap.

## Status Language

- **Capability area** means the area is part of the public product positioning or current product focus.
- **Intended to support** means the capability is designed as part of the product direction but should be evaluated for a specific workflow before relying on it.
- **Product documentation** means detailed public documentation exists in the product-specific repositories linked from this page.

## Capability Matrix

| Capability area | Medha | MedhaOS | SastraPDF | Public status note |
| --- | --- | --- | --- | --- |
| Reasoning and orchestration | Multi-model reasoning, workflow assistance and task-aware model selection within MedhaOS-permitted paths. | Governs execution paths and permitted model or provider boundaries. | Applies permitted reasoning outputs to document workflows. | Capability area under technical hardening and beta restart preparation. |
| Retrieval and context | Retrieval-augmented generation, semantic retrieval and persistent context. | Scopes context by identity, tenant, policy and permission. | Supplies document content, metadata and task context. | Detailed public docs are available in the product repositories. |
| Governance and policy | Consumes policy boundaries through governed orchestration. | Policy evaluation and enforcement boundaries, privacy controls, approvals and controlled execution. | Applies policy to document actions such as review, redaction or routing. | Capability area central to the stack. |
| Identity and permissions | Uses identity-aware context supplied by governance controls. | Identity, RBAC and permission evaluation. | Enforces document operation access through governed workflows. | Current public docs stay conceptual. |
| Tenant and data isolation | Operates within scoped context. | Tenant isolation and privacy boundaries. | Keeps document workflows aligned to tenant and data boundaries. | Intended to support enterprise evaluation patterns. |
| Approvals and human oversight | Produces recommendations that may require review. | Controls approval requirements and human-in-the-loop checkpoints. | Routes document actions for approval when required. | Public docs emphasize responsible autonomy. |
| Auditability and observability | Supports explainable workflow context where applicable. | Auditability, observability and controlled execution records. | Records document workflow activity as part of governed operations. | Detailed audit schemas are not published here. |
| Document understanding | Uses document context in reasoning workflows. | Controls access to document-derived context. | Extraction, review, comparison, classification and structured document processing. | SastraPDF capability area. |
| Document transformation | Can assist with transformation recommendations. | Governs whether transformation actions are permitted. | Transformation, redaction, conversion, signing, routing and related document operations. | SastraPDF supports document intelligence and collaborative workflows beyond basic editing. |
| Workflow integration | Orchestrates workflow assistance across context and models. | Enforces workflow policy, approvals and execution boundaries. | Integrates document steps into workflow patterns. | Integration details depend on enterprise systems and are not specified here. |
| Deployment flexibility | Supports routing to appropriate approved model paths for the task. | Provides controls for private or hybrid deployment patterns where required. | Supports document workflows within governed deployment boundaries. | Designed for enterprise evaluation; deployment architecture is workload-specific. |

## Documentation Boundaries

This repository provides umbrella documentation, conceptual architecture, reference workflows, whitepapers and product-role clarification. It does not publish detailed API references, release-specific deployment guides, security-sensitive configurations or proprietary implementation details.

Detailed product documentation now lives in the product-specific public repositories:

- [Medha capability documentation](https://github.com/sastra-innovations/medha-public-docs/blob/main/docs/capabilities.md)
- [MedhaOS governance capability documentation](https://github.com/sastra-innovations/medha-os-public-docs/blob/main/docs/governance-capabilities.md)
- [SastraPDF feature catalogue](https://github.com/sastra-innovations/sastrapdf-public-docs/blob/main/docs/features/feature-catalogue.md)

The current SastraPDF public feature catalogue documents 119 distinct document operations across ingestion, organization, editing, conversion, extraction, review, protection, accessibility, specialist document processing and workflow-related categories. That count is based on entries classified `Implemented` or `Implemented; validation pending`; AI, collaboration, platform and workflow capabilities are documented separately.

## Related Documentation

- [Product stack](product-stack.md)
- [Cross-product use cases](cross-product-use-cases.md)
- [Product status](product-status.md)
- [FAQ](faq.md)
- [Medha public documentation](https://github.com/sastra-innovations/medha-public-docs)
- [MedhaOS public documentation](https://github.com/sastra-innovations/medha-os-public-docs)
- [SastraPDF public documentation](https://github.com/sastra-innovations/sastrapdf-public-docs)
