# Document library

**Status:** Available  
**Primary users:** Teams producing briefs, plans, research, and reusable source material

## Purpose

The document library stores written outputs that are useful beyond a chat message. Agent-created briefs, plans, and research become durable documents that users can locate, edit, share, and use as source material for page creation.

## Capabilities

- Browse workspace documents in one library.
- Search documents by text.
- Filter by one document kind and by Episode association, including documents with no Episode.
- Sort by updated time or title.
- Open a document detail page with its metadata and linked Episode information.
- Deep-link to matching content within a document using a find term.
- Edit document content and use it as context for later agent work.
- Share a document through its supported public document experience.

## How it works

1. The agent creates a document as the result of research, planning, or another writing task, or the user opens an existing item.
2. The library records its kind, title, update time, and association to an Episode where relevant.
3. Search, filter, and sort choices are represented in the URL so a view can be revisited or shared internally.
4. The detail view exposes the document itself and the project relationship needed to continue working.
5. A user can attach the document to a later agent message or use it as the basis for a page.

## Important behavior

A document and an Episode are related but independent objects. A document can exist without an Episode, and an Episode can have multiple supporting documents. Filtering by “none” is therefore useful for finding unassigned research or planning material.

Document access still follows account and workspace access. Public sharing, where enabled, exposes the document through a purpose-built public route rather than granting access to the authenticated library.

## Related features

- [Agent context, conversations, and memory](../create-and-organize/04-agent-context-conversations-memory.md)
- [Grow Research](../grow/23-grow-research.md)
