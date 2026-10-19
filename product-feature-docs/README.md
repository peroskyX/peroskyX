# Episode product feature documentation

This library describes the user-recognizable capabilities currently represented in the Episode application. It is written for product, support, sales, design, and engineering readers: each file explains the user problem, the available capabilities, the normal workflow, important states, access rules, and known boundaries without requiring knowledge of the codebase.

## How this documentation was assembled

The catalogue was audited against the authenticated frontend routes, their supporting components and permissions, and the public capability catalogue on **15 October 2026**. “Available” means a working product surface is represented in the application. Plan entitlements and account configuration can still hide an available feature. Anything visibly present but not ready for normal use is documented as limited or planned rather than described as shipped.

This is product documentation, not a promise that every account has every feature. When the interface and public catalogue express different availability, the more conservative description is used.

## Create and organize

- [Starting a project](features/01-starting-a-project.md)
- [Episodes and pages](features/02-episodes-and-pages.md)
- [Agent page building](features/03-agent-page-building.md)
- [Agent context, conversations, and memory](features/04-agent-context-conversations-memory.md)
- [Agent activity and replay](features/05-agent-activity-and-replay.md)
- [Document library](features/06-document-library.md)

## Design and brand

- [Studio visual editing](features/07-studio-visual-editing.md)
- [Studio structure, code, and responsive preview](features/08-studio-structure-code-responsive.md)
- [Takes, remixes, and experiments](features/09-takes-remixes-experiments.md)
- [Brand kits and assets](features/10-brand-kits-and-assets.md)

## Review, publish, and collect

- [Review, comments, and approvals](features/11-review-comments-approvals.md)
- [Workspaces, members, and roles](features/12-workspaces-members-roles.md)
- [Publishing and Episode hosting](features/13-publishing-and-hosting.md)
- [Custom domains and paths](features/14-custom-domains-and-paths.md)
- [Forms and lead delivery](features/15-forms-and-lead-delivery.md)

## Measure and optimize

- [Website analytics](features/16-website-analytics.md)
- [Goals, funnels, forms, and heatmaps](features/17-conversion-and-behavior-analytics.md)
- [Analytics insights and exports](features/18-analytics-insights-and-exports.md)

## Content and publishing operations

- [Articles and collections](features/19-articles-and-collections.md)
- [Article workflow, quality, and SEO](features/20-article-workflow-quality-seo.md)
- [Blog appearance, authors, and address](features/21-blog-settings.md)
- [CMS publishing destinations](features/22-cms-publishing-destinations.md)

## Grow

- [Grow Research](features/23-grow-research.md)
- [Grow Search overview](features/24-grow-search-overview.md)
- [Grow Search plan](features/25-grow-search-plan.md)
- [Search results, AI Answers, and reports](features/26-search-results-ai-answers-reports.md)
- [Signals inbox, tracking, and digest](features/27-signals.md)

## Accounts and personalization

- [Account identification and roster](features/28-account-identification-and-roster.md)
- [Segments and account context](features/29-segments-and-account-context.md)
- [Personalized account pages](features/30-personalized-account-pages.md)
- [Account engagement analytics](features/31-account-engagement-analytics.md)

## Platform and administration

- [Connected apps and integrations](features/32-connected-apps-and-integrations.md)
- [Billing, plans, credits, and usage](features/33-billing-plans-credits-usage.md)
- [Profile, account, and security](features/34-profile-account-security.md)
- [Preferences, notifications, and activity](features/35-preferences-notifications-activity.md)
- [Onboarding and setup](features/36-onboarding-and-setup.md)
- [Internal administration](features/37-internal-administration.md)
- [Visible but not yet generally available](features/38-planned-and-limited-capabilities.md)

## Maintenance rules

1. Keep one user-recognizable feature per file; do not create a file for every route or button.
2. Describe outcomes and behavior before implementation details.
3. Update access, plan, and limitation notes when behavior changes.
4. Link related features so a reader can follow a complete workflow.
5. Do not describe a planned feature as available. Move it from the planned-capabilities file only after the product supports its normal end-to-end workflow.
