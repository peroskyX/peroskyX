# Forms and lead delivery

**Status:** Forms, email, webhook, Notion, and external embedding are available  
**Primary users:** Marketing, demand generation, and operations teams

## Purpose

Forms turn a page into a lead-capture experience. Users define what to collect and what visitors see after submission, then route each response to the destinations that operate the follow-up workflow.

## Capabilities

- Add a form to an Episode page.
- Choose and configure the fields visitors complete.
- Define post-submission behavior and visitor feedback.
- Deliver submissions to an email inbox.
- POST submission data to a customer webhook.
- Use email and webhook together.
- Map form fields into a Notion database so each submission becomes a row.
- Embed an Episode form in a separately operated website.
- Measure form views, starts, errors, submissions, and field drop-off in analytics.

## How it works

1. The creator adds a form and selects the information required for the use case.
2. They configure success behavior and at least one delivery destination.
3. For Notion, source fields are mapped to database properties. For a webhook, the receiving endpoint must accept the submitted payload.
4. The page is published, and visitor submissions flow to the configured destinations.
5. The team monitors delivery and uses form analytics to identify abandonment or validation friction.

## Important behavior and limits

Lead collection and delivery do not consume AI credits. A successful visitor message should not be treated as proof that every external destination processed the submission; webhook and connected-service health still matter. Teams should test the complete flow after configuration changes.

HubSpot, Salesforce, Brevo, and Google Sheets are visible as future destinations but are not documented as generally available connections. See [Visible but not yet generally available](../platform-and-administration/38-planned-and-limited-capabilities.md).

## Related features

- [Goals, funnels, forms, and heatmaps](../measure-and-optimize/17-conversion-and-behavior-analytics.md)
- [Connected apps and integrations](../platform-and-administration/32-connected-apps-and-integrations.md)
