# Markdown Render for Confluence — Documentation

Markdown Render is a Confluence Cloud macro by Seventh Visual. Write or paste
Markdown directly in a page and see it rendered — headings, tables, fenced code
blocks, lists and links — entirely in your browser.

## Getting started
1. Edit a Confluence page and insert the **Markdown Render** macro.
2. The editor opens with a short starter example. Replace it with your own
   Markdown — the preview updates as you type.
3. Save. The Markdown source is stored in the page itself, as the macro's
   content, and renders for every reader of the page.

## What renders
- Headings, paragraphs, emphasis, strong text
- GitHub-style tables
- Fenced code blocks (indentation preserved)
- Ordered and unordered lists
- Links (opened in a new tab, with safe rel attributes)

## Good to know
- **Images:** images referenced by URL do not render inside Confluence's app
  frame (Atlassian's security policy blocks external images in app iframes);
  the image's alt text is shown instead. Attach images to the page itself,
  outside the macro, if you need them displayed.
- **Length:** a macro holds up to 32,000 characters of Markdown.
- **No imports:** Markdown Render works with text pasted or typed into the
  page. It does not fetch files or URLs — by design, it makes no network
  calls at all.

## Privacy
The app collects no data, stores nothing outside your Confluence page, and
requests no permissions. See the privacy policy for details.

## Support
Support is provided by Seventh Visual via the contact channels on the
Atlassian Marketplace listing.
