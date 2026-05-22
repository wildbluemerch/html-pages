# HTML Pages

A version-controlled home for new HTML pages before they go live on Shopify.

## Purpose

This repo is where we build and track standalone HTML pages. The current workflow is intentionally simple:

1. **Build** the page as a standalone `.html` file in this repo.
2. **Version control** it here — every change is committed, so we have history, can review diffs, and can roll back if a page breaks.
3. **Copy and paste** the HTML into Shopify when it's ready to publish.

This copy-paste step into Shopify is a temporary approach. It works for now, and we'll replace it with a tighter integration (e.g. theme files, the Shopify CLI, or an automated sync) once we figure out a better workflow.

## Why version control these

- **History** — see what changed, when, and why.
- **Review** — diff changes before they ever touch the live store.
- **Recovery** — roll back to a known-good version if something goes wrong in Shopify.
- **Single source of truth** — the file here is canonical; Shopify is just where it's served.

## Conventions

- One page per `.html` file.
- Keep each file self-contained (inline `<style>` and markup) so it pastes cleanly into a Shopify page/section.
- Use clear, human-readable file names that match the page's purpose.

## Current pages

| File | Description |
|------|-------------|
| `The Recon Report.html` | Wild Blue Experiences — The Recon Report |
| `Graduation Planning Hub.html` | Graduation Planning Hub |

## Next steps

- Evaluate a better Shopify workflow to replace manual copy-paste (theme integration, Shopify CLI, or automated publishing).
