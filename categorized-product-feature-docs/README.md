# Episode product feature documentation

This library describes the user-recognizable capabilities currently represented in the Episode application. It is written for product, support, sales, design, and engineering readers: each file explains the user problem, the available capabilities, the normal workflow, important states, access rules, and known boundaries without requiring knowledge of the codebase.

## How this documentation was assembled

The catalogue was audited against the authenticated frontend routes, their supporting components and permissions, and the public capability catalogue on **15 October 2026**. “Available” means a working product surface is represented in the application. Plan entitlements and account configuration can still hide an available feature. Anything visibly present but not ready for normal use is documented as limited or planned rather than described as shipped.

This is product documentation, not a promise that every account has every feature. When the interface and public catalogue express different availability, the more conservative description is used.

## Create and organize

- [Starting a project](create-and-organize/01-starting-a-project.md)
- [Episodes and pages](create-and-organize/02-episodes-and-pages.md)
- [Agent page building](create-and-organize/03-agent-page-building.md)
- [Agent context, conversations, and memory](create-and-organize/04-agent-context-conversations-memory.md)
- [Agent activity and replay](create-and-organize/05-agent-activity-and-replay.md)
- [Document library](create-and-organize/06-document-library.md)

## Design and brand

- [Studio visual editing](design-and-brand/07-studio-visual-editing.md)
- [Studio structure, code, and responsive preview](design-and-brand/08-studio-structure-code-responsive.md)
- [Takes, remixes, and experiments](design-and-brand/09-takes-remixes-experiments.md)
- [Brand kits and assets](design-and-brand/10-brand-kits-and-assets.md)

## Review, publish, and collect

- [Review, comments, and approvals](review-publish-and-collect/11-review-comments-approvals.md)
- [Workspaces, members, and roles](review-publish-and-collect/12-workspaces-members-roles.md)
- [Publishing and Episode hosting](review-publish-and-collect/13-publishing-and-hosting.md)
- [Custom domains and paths](review-publish-and-collect/14-custom-domains-and-paths.md)
- [Forms and lead delivery](review-publish-and-collect/15-forms-and-lead-delivery.md)

## Measure and optimize

- [Website analytics](measure-and-optimize/16-website-analytics.md)
- [Goals, funnels, forms, and heatmaps](measure-and-optimize/17-conversion-and-behavior-analytics.md)
- [Analytics insights and exports](measure-and-optimize/18-analytics-insights-and-exports.md)

## Content and publishing operations

- [Articles and collections](content-and-publishing-operations/19-articles-and-collections.md)
- [Article workflow, quality, and SEO](content-and-publishing-operations/20-article-workflow-quality-seo.md)
- [Blog appearance, authors, and address](content-and-publishing-operations/21-blog-settings.md)
- [CMS publishing destinations](content-and-publishing-operations/22-cms-publishing-destinations.md)

## Grow

- [Grow Research](grow/23-grow-research.md)
- [Grow Search overview](grow/24-grow-search-overview.md)
- [Grow Search plan](grow/25-grow-search-plan.md)
- [Search results, AI Answers, and reports](grow/26-search-results-ai-answers-reports.md)
- [Signals inbox, tracking, and digest](grow/27-signals.md)

## Accounts and personalization

- [Account identification and roster](accounts-and-personalization/28-account-identification-and-roster.md)
- [Segments and account context](accounts-and-personalization/29-segments-and-account-context.md)
- [Personalized account pages](accounts-and-personalization/30-personalized-account-pages.md)
- [Account engagement analytics](accounts-and-personalization/31-account-engagement-analytics.md)

## Platform and administration

- [Connected apps and integrations](platform-and-administration/32-connected-apps-and-integrations.md)
- [Billing, plans, credits, and usage](platform-and-administration/33-billing-plans-credits-usage.md)
- [Profile, account, and security](platform-and-administration/34-profile-account-security.md)
- [Preferences, notifications, and activity](platform-and-administration/35-preferences-notifications-activity.md)
- [Onboarding and setup](platform-and-administration/36-onboarding-and-setup.md)
- [Internal administration](platform-and-administration/37-internal-administration.md)
- [Visible but not yet generally available](platform-and-administration/38-planned-and-limited-capabilities.md)

## Maintenance rules

1. Keep one user-recognizable feature per file; do not create a file for every route or button.
2. Describe outcomes and behavior before implementation details.
3. Update access, plan, and limitation notes when behavior changes.
4. Link related features so a reader can follow a complete workflow.
5. Do not describe a planned feature as available. Move it from the planned-capabilities file only after the product supports its normal end-to-end workflow.
