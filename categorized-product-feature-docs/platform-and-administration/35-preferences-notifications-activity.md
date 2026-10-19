# Preferences, notifications, and activity

**Status:** Available  
**Primary users:** All authenticated users and administrators reviewing account events

## Purpose

These settings control how a user experiences Episode and how they learn about work requiring attention. Activity provides an account history, while notifications and preferences shape delivery and interaction behavior.

## Capabilities

- Maintain supported personal preferences in a dedicated settings surface.
- Configure notification choices, including settings used by Signals Digest.
- Open relevant destinations from notification deep links.
- Select the correct workspace when a notification belongs to a different context.
- Handle notification types such as Search updates through purpose-built navigation.
- Review account activity with actor identity and event context.
- Distinguish product activity history from the agent run activity feed.
- See loading, empty, and error states when activity or preferences are unavailable.

## How it works

Preferences are saved for the user or current scope represented by the control. Notification settings determine which supported events produce delivery and can affect periodic summaries such as Signals Digest.

When a user opens a notification, Episode resolves the destination and workspace context before navigating. This prevents a link for one workspace from silently opening an unrelated workspace. Account activity presents a broader administrative record of actions and actors, whereas Agent Activity focuses on automated runs.

## Important behavior

Turning off a notification does not delete the underlying product event or tracked signal. Likewise, an activity log is descriptive: it records what the product exposes but is not necessarily a complete security audit log for every backend operation.

Workspace switching can affect what the user sees after following a notification. Access may have changed since the notification was sent, in which case the destination can be unavailable even though the message still exists.

## Related features

- [Signals inbox, tracking, and digest](../grow/27-signals.md)
- [Agent activity and replay](../create-and-organize/05-agent-activity-and-replay.md)
- [Profile, account, and security](../platform-and-administration/34-profile-account-security.md)
