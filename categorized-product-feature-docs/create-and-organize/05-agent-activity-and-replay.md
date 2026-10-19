# Agent activity and replay

**Status:** Available  
**Primary users:** Creators reviewing an agent job and teams troubleshooting its result

## Purpose

Agent activity makes automated work inspectable. Users can watch a run progress, review jobs outside the immediate chat, and replay a finished run to understand the sequence that produced an output.

## Capabilities

- Display individual run steps while work is underway.
- Present an activity feed of agent work.
- Open a dedicated replay view for a completed run.
- Reconstruct the order of visible steps and outputs.
- Link activity back to the related work when that relationship is available.
- Represent loading, in-progress, completed, and failed work rather than treating every run as a single opaque response.

## How it works

1. A user asks the agent to perform work.
2. The system creates a run and records its visible activity as the job progresses.
3. The current conversation shows immediate progress, while the activity area provides a broader place to find runs.
4. Opening replay presents the finished run in sequence, allowing a user to inspect how the result was reached.
5. The user can return to the associated conversation or output to continue the work.

## Product value

Replay is particularly useful when a job takes several steps, produces an unexpected result, or needs to be handed to a teammate. It provides an understandable operational history without requiring access to backend logs.

## Boundaries

The replay represents product-visible run activity; it is not a raw engineering trace and may not expose every internal computation. Replaying a run is for inspection and does not itself re-execute the work. A new instruction or retry is needed to create fresh output.

## Related features

- [Agent page building](../create-and-organize/03-agent-page-building.md)
- [Preferences, notifications, and activity](../platform-and-administration/35-preferences-notifications-activity.md)
