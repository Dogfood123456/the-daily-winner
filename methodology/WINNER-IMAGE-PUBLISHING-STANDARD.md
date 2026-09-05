# THE WINNER — WEB IMAGE PUBLISHING STANDARD

**Status: permanent, project-wide rule**

This rule applies to every Daily Winner, Football Winner, Tipster Tracker and related Winner page.

## Mandatory rule

Every generated image must be made web-friendly **before** it is published or referenced by live HTML.

- Never point a published page at the raw ImageGen PNG.
- Create an optimised derivative for the website, normally WebP.
- Resize editorial images to the largest dimensions the page actually needs; use roughly 1100–1400px maximum width unless a larger display is genuinely required.
- Strip unnecessary metadata.
- Use a sensible quality setting, normally 75–82 for WebP or JPEG.
- Aim for no more than 250KB per editorial image and preferably below 150KB when quality remains good.
- Add explicit `width` and `height` attributes to the HTML image element to prevent layout shift.
- Use `loading="lazy"` and `decoding="async"` for images below the opening viewport.
- Confirm the optimised file exists at the exact case-sensitive path used in the HTML before publishing.
- The high-resolution original may be retained as a source asset, but live pages must reference the optimised derivative.

## Publication check

Before any Winner page is published, verify:

1. every generated image has an optimised web version;
2. the HTML references that version rather than the raw original;
3. filenames and extensions match exactly;
4. no oversized generated image is being shipped accidentally.

This check is part of publication, not an optional later tidy-up.
