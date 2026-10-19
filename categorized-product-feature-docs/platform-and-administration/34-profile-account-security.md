# Profile, account, and security

**Status:** Available  
**Primary users:** All authenticated users; ownership actions are role-restricted

## Purpose

Account settings separate the individual’s identity and sign-in controls from organization-level account and workspace administration. This lets users maintain their profile while protecting sensitive ownership and access actions.

## Capabilities

- Update personal profile information and avatar through the profile surface.
- View and maintain account-level settings exposed to the current role.
- Manage workspace-level details in the workspace settings surface.
- See whether the account uses email sign-in, Google sign-in, or both where represented.
- Change the password for accounts that have email authentication.
- Explain that password management belongs to Google for Google-only accounts.
- Sign out of the current device session.
- Handle account ownership offers through the appropriate administrator experience.
- Use role and permission guards to prevent unauthorized settings access.

## How it works

The user chooses the setting matching the scope of the intended change: **Profile** for their identity, **Workspace** for the current working group, **Account** for organization-level configuration, and **Security** for sign-in and session actions.

Security detects the authentication providers associated with the user. Email-authenticated users receive the password-change workflow; Google-only users see their provider and are directed to manage the password with Google. Signing out ends the current device session.

## Important behavior

Profile changes belong to the person, while account and workspace changes can affect teammates. Availability is therefore permission-sensitive. Users should not expect a password form when no Episode email credential exists.

Signing out is not the same as revoking every active session or disconnecting an external app. Connected-service grants are managed in their own settings.

## Related features

- [Connected apps and integrations](../platform-and-administration/32-connected-apps-and-integrations.md)
- [Workspaces, members, and roles](../review-publish-and-collect/12-workspaces-members-roles.md)
- [Preferences, notifications, and activity](../platform-and-administration/35-preferences-notifications-activity.md)
