# Highlander Raise Page Assets

Image hosting for custom HTML raise pages.

## Folder structure
issuers/{issuer-slug}/{raise-period}/{image-name}.{ext}

Example:
issuers/smart-cups/2026-reg-cf/hero.jpg

## Naming rules
- Issuer slugs match the internal Highlander slug (lowercase, hyphens)
- Image filenames are lowercase with hyphens
- No spaces, no special characters
- Descriptive names only (hero.jpg, not IMG_1234.jpg)

## URL pattern
https://assets.highlander.ai/issuers/{slug}/{raise}/{file}
