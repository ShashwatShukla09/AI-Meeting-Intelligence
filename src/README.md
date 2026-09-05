# Implementation

AI Meeting Intelligence is a working end-to-end prototype built to explore how AI can turn meeting conversations into structured execution.

This public repository focuses on the product, system design, and architecture.

## System Components

The working prototype includes:

- Meeting recording ingestion
- Local speech-to-text processing
- LLM-based structured extraction
- Output validation
- Human review and approval
- Meeting and action storage
- Slack, Notion, and Email distribution
- Execution dashboard

## Implementation

The complete workflow orchestration, prompts, validation logic, integration configuration, and internal implementation are not included in this public repository.

The high-level system architecture and product decisions are documented here:

- [Architecture](../docs/ARCHITECTURE.md)
- [Product Decisions](../docs/PRODUCT.md)

## Output Structure

The system converts unstructured meeting conversations into structured data covering:

`Summary` · `Participants` · `Decisions` · `Action Items` · `Owners` · `Deadlines` · `Priorities` · `Risks` · `Open Questions` · `Follow-ups`
