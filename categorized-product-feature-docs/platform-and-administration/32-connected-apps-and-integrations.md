# Connected apps and integrations

**Status:** Available; individual integrations have their own readiness and authorization requirements  
**Primary users:** Account administrators and users importing or publishing external content

## Purpose

Connections give Episode permission to work with external sources and destinations. They enable workflows such as importing Figma or Notion material, using search data, delivering leads, and publishing to content systems.

## Capabilities

- View connected-app grants associated with the account.
- Start supported connection and consent flows.
- Connect Figma as a design starting point.
- Connect Notion for source documents and lead delivery.
- Connect search sources through the dedicated Search Console flow represented by the application.
- Configure supported CMS destinations including WordPress, Ghost, and Contentful.
- Deliver form data through email and webhooks without a full app connection.
- Review integration catalogue entries and their current product state.
- Reconnect when authorization expires or is revoked.

## How it works

1. A user begins an action that needs an external system or opens connection settings.
2. Episode redirects through the provider’s authorization or setup flow.
3. The user grants the requested access and returns to Episode.
4. The product records the grant and, where needed, asks for a specific file, frame, database, site, property, or destination.
5. The relevant feature uses the connection until it expires, is revoked, or lacks a newly required permission.

## Permissions and safeguards

External authorization should use the least access that supports the workflow. The ability to connect or configure an app can be restricted to an account administrator even when other members can use the resulting data.

A listed integration is not automatically a live end-to-end destination. HubSpot, Salesforce, Brevo, and Google Sheets lead delivery are explicitly treated as planned rather than available. Connection health should be checked when imports, data refresh, or publishing unexpectedly stop.

## Related features

- [Starting a project](../create-and-organize/01-starting-a-project.md)
- [CMS publishing destinations](../content-and-publishing-operations/22-cms-publishing-destinations.md)
- [Forms and lead delivery](../review-publish-and-collect/15-forms-and-lead-delivery.md)
