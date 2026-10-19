# Agent page building

**Status:** Available  
**Primary users:** People who want to brief and revise web work conversationally  
**Main surface:** Agent workspace

## Purpose

The Episode agent is the primary production interface, not a support chatbot. It translates a product or marketing brief into an actual page-building job and lets the user continue directing the work in normal language.

## Capabilities

- Interpret a plain-language request and plan the page.
- Generate structure, copy, and visual sections as working page content.
- Stream sections as they are completed so progress is visible.
- Accept follow-up requests that revise existing work or extend it.
- Use attached Episodes, documents, files, and account knowledge as context.
- Hand completed work into Studio for direct editing.
- Show setup and handoff controls when a request needs additional information or a next action.

## How it works

1. The user starts or opens a conversation and explains the desired outcome.
2. They optionally attach source material or select existing Episode context.
3. The agent creates a run. The interface exposes run steps and streams the result rather than waiting for one final message.
4. Generated sections are written into the associated Episode or document.
5. The user reviews the result, asks for changes, or switches to Studio for precise visual changes.

## Important states

- **Waiting for context:** The agent may need a destination, source, connection, or clarifying choice.
- **Running:** Steps and output arrive progressively.
- **Completed:** The work can be opened, replayed, edited, or followed up.
- **Failed or interrupted:** The visible run history helps identify what completed and what needs to be retried.

The agent can make substantive product changes, so users should review the produced page and its responsive states before publishing. Account credits and plan rules can affect how much AI work is available.

## Related features

- [Agent context, conversations, and memory](../create-and-organize/04-agent-context-conversations-memory.md)
- [Agent activity and replay](../create-and-organize/05-agent-activity-and-replay.md)
- [Studio visual editing](../design-and-brand/07-studio-visual-editing.md)
