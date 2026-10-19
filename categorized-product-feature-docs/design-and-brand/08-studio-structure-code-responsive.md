# Studio structure, code, and responsive preview

**Status:** Available  
**Primary users:** Creators who need structural control and implementation visibility

## Purpose

Beyond editing visible content, Studio exposes how a page is organized, what a section renders, and how the design behaves at different screen sizes. This makes an agent-built page inspectable and adjustable instead of locking it behind a proprietary representation.

## Capabilities

- View a layer tree for the current page.
- Navigate the list of pages inside an Episode.
- Reorder sections with supported toolbar or keyboard controls.
- Inspect the code rendered by a section.
- Switch the preview viewport to check responsive behavior.
- Combine structural controls with direct canvas editing.

## How it works

The page list establishes which page is being edited. Within that page, the layer tree provides a structured view of its sections and makes selection easier when elements overlap or are difficult to target on the canvas. Reordering changes the reading sequence and visible layout.

The code view exposes what a section renders, giving technical users a concrete representation of the output. It is an inspection capability rather than a promise that every underlying application concern is editable as arbitrary source code.

The viewport switcher presents the page at representative widths. Users should check content wrapping, image crops, navigation, forms, and call-to-action placement at each size before publishing.

## Important behavior

Pages are designed to be responsive by default, but generated copy and user-provided assets can create edge cases. The viewport check is therefore a validation step, not merely a visual preference. Reordering a section can also change narrative flow, conversion tracking assumptions, and comment anchors, so the finished page should be reviewed as a whole.

## Related features

- [Studio visual editing](../design-and-brand/07-studio-visual-editing.md)
- [Episodes and pages](../create-and-organize/02-episodes-and-pages.md)
- [Review, comments, and approvals](../review-publish-and-collect/11-review-comments-approvals.md)
