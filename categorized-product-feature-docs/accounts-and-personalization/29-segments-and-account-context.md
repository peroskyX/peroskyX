# Segments and account context

**Status:** Available  
**Primary users:** ABM and growth teams organizing target accounts

## Purpose

Segments create manageable groups of accounts, while account context stores the information needed to tailor a relevant experience. Together they support scaled personalization without forcing every account into the same message.

## Capabilities

- Group accounts into segments used by the website Accounts workflow.
- Browse segment-based account groupings.
- Use member/contact context while preparing account-specific work.
- Edit or copy account-oriented messaging in the supported context editor.
- Preview how account context affects a generated page.
- Detect drift when source account context and generated output no longer align.
- Apply bulk actions to selected accounts where supported.
- Use privacy-level controls represented by the account-page workflow.

## How it works

1. The team defines a useful audience grouping and places relevant accounts into it.
2. Account and member context provides the factual basis for messaging.
3. A creator reviews or edits the context before page generation.
4. Preview reveals the proposed account-facing result.
5. If inputs change later, the drift state warns that an existing generated page may need regeneration or review.

## Important behavior

A segment is an operating model, not a guarantee that every account inside it has identical needs. Personalization should use verified business context and avoid exposing private or overly specific information to a visitor.

Drift does not necessarily mean a live page is broken; it means the assumptions used to create it no longer exactly match the current context. The team should review material differences and decide whether to regenerate, edit manually, or retain the existing message.

## Related features

- [Account identification and roster](../accounts-and-personalization/28-account-identification-and-roster.md)
- [Personalized account pages](../accounts-and-personalization/30-personalized-account-pages.md)
