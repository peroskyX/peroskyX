# Custom domains and paths

**Status:** Available from the first paid plan  
**Primary users:** Teams publishing under their own brand and domain structure

## Purpose

Custom-domain publishing lets an Episode experience live under a customer-controlled web address rather than only an Episode-hosted URL. Path publishing supports placing a page at an existing domain path.

## Capabilities

- Connect a customer-owned domain to an Episode website.
- Follow guided DNS setup instructions.
- Verify whether the required DNS records resolve correctly.
- Issue and maintain SSL certificates automatically after successful setup.
- Display domain health and surface configuration problems.
- Remove or replace a connected domain.
- Publish to a path on an existing domain configuration where supported.
- Access product help for custom-domain setup.

## How it works

1. An eligible user enters the desired domain in the publishing flow.
2. Episode displays the DNS records that must be created with the domain provider.
3. The user makes those changes outside Episode and returns to verify them.
4. Once DNS resolves, Episode completes domain activation and certificate issuance.
5. The publishing view reports the connected address and health; users can remove the mapping if the destination changes.

Path publishing adds a path component so a page can fit an existing information architecture instead of requiring a separate root domain.

## Important behavior

DNS changes are external and can take time to propagate. A failed verification does not always mean the entered values are wrong; old records, provider-specific host notation, and propagation delays are common causes. SSL can only complete after the domain points correctly.

Removing a domain affects how visitors reach the site but does not delete the Episode. Teams should coordinate DNS removal and replacement to avoid an unintended outage.

## Related features

- [Publishing and Episode hosting](../review-publish-and-collect/13-publishing-and-hosting.md)
- [Blog appearance, authors, and address](../content-and-publishing-operations/21-blog-settings.md)
