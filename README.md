# Mwenaro Figma Landing Page

This is a simple static landing page built with Tailwind CSS via CDN. The page includes a hero section with text content and a grid of rounded image thumbnails.

## Files

- `index.html` — main page markup and Tailwind utility classes
- `Assets/` — image assets used in the hero grid

## How to use

1. Open `index.html` in a browser.
2. If you prefer a live preview, use a local server or VS Code Live Server extension.

## Tailwind setup

This project uses the official Tailwind CDN:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

That means there is no Node.js build step required. Tailwind classes are applied directly in the HTML.

## Responsive behavior

- Mobile layout uses a vertical stack (`flex-col`) so the content section appears above the image section.
- On medium screens and larger, the layout switches to a horizontal row (`md:flex-row`).
- Image thumbnails use `w-full h-32 object-cover rounded-xl` to keep them uniform and rounded.

## Notes

- The hero section is intentionally centered with margin and padding utilities.
- The content section uses custom text colors and a fixed width for the paragraph to keep the layout readable.
# MWENARO-FIGMA-10
