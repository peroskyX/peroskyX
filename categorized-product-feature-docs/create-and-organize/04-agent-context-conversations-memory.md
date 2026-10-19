# Agent context, conversations, and memory

**Status:** Available  
**Primary users:** Repeat users and teams that need consistent agent output

## Purpose

Episode gives the agent both request-specific context and durable account knowledge. Conversations organize individual streams of work, attachments ground a particular request, and account memory carries standing facts and preferences between conversations.

## Capabilities

- Attach an Episode, Episode document, or uploaded file to a message.
- Return to past conversations through a searchable thread history.
- Rename and pin important conversations.
- Delete conversations without deleting Episodes they created.
- Store account-level facts, preferences, and standing instructions.
- Review, edit, or delete the memories the agent retained.
- Display clear empty, loading, save, and error states in memory settings.

## How it works

For a one-off request, the user attaches the most relevant material before sending the message. The agent then works from that scoped context. For information that should influence future conversations—such as a persistent brand fact or instruction—the system can retain an account memory.

The **Agent memory** settings page is the control surface for durable knowledge. Each saved memory is visible rather than hidden. A user can correct its wording, save the update, or choose “Forget” to remove it. The interface confirms destructive deletion and reports whether the save or delete succeeded.

Conversation management is separate. Search helps recover prior work, pinning keeps important threads accessible, and renaming makes their purpose recognizable to teammates.

## Boundaries and safeguards

An attachment applies to the relevant request or conversation; it is not automatically a permanent account instruction. Account memory is shared account context, so edits can affect later work by other members. Removing a conversation removes its discussion history from the conversation list but intentionally preserves its Episode output.

## Related features

- [Document library](../create-and-organize/06-document-library.md)
- [Profile, account, and security](../platform-and-administration/34-profile-account-security.md)
