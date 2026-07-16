# Features Overview

This page provides a high-level capability matrix for Medha, MedhaOS and SastraPDF. It describes public capability areas and current documentation focus without publishing proprietary implementation details or an unverified roadmap.

## Status Language

- **Capability area** means the area is part of the public product positioning or current product focus.
- **Intended to support** means the capability is designed as part of the product direction but should be evaluated for a specific workflow before relying on it.
- **Future documentation** means more detail is expected in planned product-specific documentation repositories, not that a date or release commitment is being announced.

## Capability Matrix

| Capability area | Medha | MedhaOS | SastraPDF | Public status note |
| --- | --- | --- | --- | --- |
| Reasoning and orchestration | Multi-model reasoning, workflow assistance and model routing. | Governs execution paths and controlled model access. | Applies reasoning outputs to document workflows. | Capability area under technical hardening and beta preparation. |
| Retrieval and context | Retrieval-augmented generation, semantic retrieval and persistent context. | Scopes context by identity, tenant, policy and permission. | Supplies document content, metadata and task context. | Current public docs describe concepts; deeper product docs are planned. |
| Governance and policy | Consumes policy boundaries through governed orchestration. | Policy enforcement, privacy controls, approvals and controlled execution. | Applies policy to document actions such as review, redaction or routing. | Capability area central to the stack. |
| Identity and permissions | Uses identity-aware context supplied by governance controls. | Identity, RBAC and permission evaluation. | Enforces document operation access through governed workflows. | Current public docs stay conceptual. |
| Tenant and data isolation | Operates within scoped context. | Tenant isolation and privacy boundaries. | Keeps document workflows aligned to tenant and data boundaries. | Intended to support enterprise evaluation patterns. |
| Approvals and human oversight | Produces recommendations that may require review. | Controls approval requirements and human-in-the-loop checkpoints. | Routes document actions for approval when required. | Public docs emphasize responsible autonomy. |
| Auditability and observability | Supports explainable workflow context where applicable. | Auditability, observability and controlled execution records. | Records document workflow activity as part of governed operations. | Detailed audit schemas are not published here. |
| Document understanding | Uses document context in reasoning workflows. | Controls access to document-derived context. | Extraction, review, comparison, classification and structured document processing. | SastraPDF capability area. |
| Document transformation | Can assist with transformation recommendations. | Governs whether transformation actions are permitted. | Transformation, redaction, conversion, signing, routing and related document operations. | SastraPDF supports more than basic editing. |
| Workflow integration | Orchestrates workflow assistance across context and models. | Enforces workflow policy, approvals and execution boundaries. | Integrates document steps into workflow patterns. | Integration details depend on enterprise systems and are not specified here. |
| Deployment flexibility | Supports model-routing patterns suited to different environments. | Provides controls for private or hybrid deployment patterns where required. | Supports document workflows within governed deployment boundaries. | Designed for enterprise evaluation; deployment architecture is workload-specific. |

## Current And Future Documentation Boundaries

This repository currently provides umbrella documentation, conceptual architecture, reference workflows, whitepapers and product-role clarification. It does not publish detailed API references, release-specific deployment guides, security-sensitive configurations or proprietary implementation details.

Future product-specific documentation is planned for `medha-public-docs`, `medha-os-public-docs` and `sastrapdf-public-docs`. Those repositories are not linked because they have not yet been created.

## Related Documentation

- [Product stack](product-stack.md)
- [Cross-product use cases](cross-product-use-cases.md)
- [Product status](product-status.md)
- [FAQ](faq.md)
