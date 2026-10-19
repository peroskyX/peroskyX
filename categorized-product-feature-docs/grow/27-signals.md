# Signals inbox, tracking, and digest

**Status:** Available  
**Primary users:** Growth and account teams monitoring meaningful changes

## Purpose

Signals turns tracked changes and observations into a review workflow. The inbox is for individual items, Tracking explains coverage, and Digest controls the summarized notification experience.

## Capabilities

- Browse a feed of signals in an inbox.
- Open a specific signal directly through URL state.
- Retain context between the selected signal and the broader feed.
- View tracking coverage to understand what the system is currently monitoring.
- Preview the digest experience.
- Configure digest settings.
- Connect digest behavior to notification preferences.
- Represent loading, empty, error, and incomplete-coverage states.

## How it works

Tracked sources generate eligible signal items. The inbox presents those items for review; selecting one opens its detail while preserving a shareable or revisitable reference in the URL. The Tracking view answers the operational question of what is covered, which is essential when an expected signal is missing.

Digest packages relevant activity into a summary rather than requiring constant inbox checking. Users preview the format and configure the applicable notification choices.

## Important behavior

No signal can be produced for a source or subject that is not covered, and absence of a signal should not be interpreted as proof that nothing changed. Users should verify tracking coverage before troubleshooting the inbox.

Digest and inbox serve different rhythms: the inbox is the current working feed, while digest is a periodic summary. Notification preferences can affect delivery without deleting the underlying tracked information.

## Related features

- [Preferences, notifications, and activity](../platform-and-administration/35-preferences-notifications-activity.md)
- [Connected apps and integrations](../platform-and-administration/32-connected-apps-and-integrations.md)
