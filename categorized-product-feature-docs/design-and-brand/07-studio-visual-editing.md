# Studio visual editing

**Status:** Available  
**Primary users:** Marketers and designers refining an agent-built page  
**Main surface:** Episode Studio

## Purpose

Studio provides direct control after the agent creates a page. Users edit the rendered experience itself instead of translating every small correction into a chat request or a detached settings form.

## Capabilities

- Click into visible text and edit it in place.
- Select and replace images.
- Crop imagery for the intended composition.
- Add or correct image alternative text.
- Select a section and ask AI to change only that section.
- Make a page-level AI request when no section is selected.
- Move between direct editing and conversational assistance.
- Preview the work before publishing it.

## How it works

1. The user opens an Episode in Studio and selects content on the canvas.
2. Text edits are made directly where the text appears. Image controls expose replacement, crop, and accessibility metadata.
3. For a broader change, the user selects a section and describes the desired result. Selection establishes the request boundary.
4. With no section selected, the AI instruction applies at page scope.
5. The user checks the result across viewport sizes and publishes when satisfied.

## Important behavior

Selection is meaningful: a scoped request should not be assumed to modify the whole page, while an unscoped request can. Users should confirm what is selected before asking for a change. Direct edits and generated revisions become working changes and do not automatically update the live site.

Image alternative text supports accessibility and should describe the image’s purpose rather than repeat nearby copy. Cropping changes presentation, not the original meaning of an asset in the workspace library.

## Related features

- [Studio structure, code, and responsive preview](../design-and-brand/08-studio-structure-code-responsive.md)
- [Brand kits and assets](../design-and-brand/10-brand-kits-and-assets.md)
- [Publishing and Episode hosting](../review-publish-and-collect/13-publishing-and-hosting.md)
