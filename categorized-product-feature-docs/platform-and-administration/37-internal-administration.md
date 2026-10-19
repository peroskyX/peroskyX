# Internal administration

**Status:** Available only to internal accounts  
**Primary users:** Authorized Episode operators

## Purpose

Internal administration exposes operational views that support Episode’s own team. These surfaces are deliberately separated from customer settings and protected by an internal-account guard.

## Capabilities

- Open an internal analytics index.
- Select an account and inspect its internal analytics view.
- Use an internal learning area.
- Prevent normal customer accounts from navigating directly into admin routes.
- Reuse authenticated account context while adding the stronger internal eligibility check.

## How it works

An authenticated user enters the admin route. The route guard verifies that the account is recognized as internal before rendering administration navigation or data. Internal analytics begins with an account-level index and supports drilling into the selected account. Learning is a separate internal destination for the knowledge or operational workflow represented there.

## Permissions and boundaries

Authentication alone is not sufficient. These pages can expose cross-account or operator-oriented information and must remain limited to the explicit internal-account rule. Links should not be added to general customer navigation as a substitute for authorization.

Internal analytics should not be confused with the customer’s Website Analytics feature. The customer feature explains their published performance; the admin feature supports Episode operations. Similarly, the internal Learning area is not a public help center or customer onboarding page.

## Operational guidance

Operators should use the least customer data needed for the task and follow internal privacy procedures. A missing account or denied route can indicate the wrong active account, removed internal status, or a genuine authorization boundary.

## Related features

- [Website analytics](../measure-and-optimize/16-website-analytics.md)
- [Profile, account, and security](../platform-and-administration/34-profile-account-security.md)
