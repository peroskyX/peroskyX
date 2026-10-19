# CMS publishing destinations

**Status:** Available destination workflows are represented for Episode, WordPress, Ghost, and Contentful; exact access depends on connection and configuration  
**Primary users:** Content operations and publishing administrators

## Purpose

Publishing destinations let an Episode article move into the system where the organization’s public content is delivered. Destination setup records connection, route, field, and publication behavior instead of requiring writers to copy and paste every post.

## Capabilities

- Choose a supported content destination.
- Run a destination-specific connection wizard.
- Configure route or path details used by the publication target.
- Map Episode article fields to destination fields when required.
- Set whether a post should publish when it goes live through the connected workflow.
- Use an Episode-native destination where the blog is hosted within Episode.
- Represent connection and configuration errors before a publishing attempt.

## How it works

1. An administrator selects a destination type and authorizes the external service where required.
2. They choose the target site, space, collection, or equivalent content container.
3. Episode and destination fields are mapped so titles, bodies, authors, images, summaries, SEO values, and status arrive in the correct place.
4. Route and publication behavior are confirmed.
5. Article editors can publish or schedule through the configured destination, subject to approval and blockers.

## Important behavior

Connections can expire or lose external permissions even when Episode’s configuration has not changed. A successful field mapping does not guarantee that every future destination schema remains compatible; administrators should recheck after CMS model changes.

Publishing status has two parts: Episode’s workflow decision and the destination’s response. Teams should verify the resulting public URL after the external system accepts a post.

## Related features

- [Connected apps and integrations](../platform-and-administration/32-connected-apps-and-integrations.md)
- [Article workflow, quality, and SEO](../content-and-publishing-operations/20-article-workflow-quality-seo.md)
