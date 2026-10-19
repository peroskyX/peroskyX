# Onboarding and setup

**Status:** Available  
**Primary users:** New accounts, invited members, and users completing a connection or claim flow

## Purpose

Onboarding gets a user from authentication to useful work while preserving the context of how they arrived. Separate token-based flows support invitations, claims, blog setup, and external connections without treating every new session as the same journey.

## Capabilities

- Guide a newly authenticated user through initial account or workspace setup.
- Direct users into the appropriate starting workflow for creating with Episode.
- Accept account invitations through a dedicated token route.
- Represent pending join requests while an administrator decides access.
- Claim eligible shared or generated work through a claim token.
- Complete blog setup through a dedicated setup token.
- Connect Search Console through its specialized authorization and return flow.
- Verify an email address.
- Recover access through forgot-password and reset-password flows.
- Return users to the right authenticated product surface after successful setup.

## How it works

The entry route determines the job to be completed. A standard new user follows onboarding; an invitee accepts the invitation; a join requester sees the pending state; and a connection callback resumes the feature that initiated authorization. Tokens identify the pending operation and are validated before account state changes.

After account/workspace context exists, onboarding hands off to a product starting point such as the agent, brand setup, research, or blog configuration.

## Important behavior

Setup links can expire, be consumed, or belong to a different signed-in email. The application should show a recoverable explanation rather than creating duplicate access. Users should avoid forwarding invitation, claim, reset, and connection links because they can authorize meaningful account actions.

Onboarding completion does not imply every integration or optional feature is configured; individual product areas can still present their own setup doors.

## Related features

- [Starting a project](../create-and-organize/01-starting-a-project.md)
- [Workspaces, members, and roles](../review-publish-and-collect/12-workspaces-members-roles.md)
- [Connected apps and integrations](../platform-and-administration/32-connected-apps-and-integrations.md)
