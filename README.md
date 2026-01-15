# Modern CSS Reset

A tiny, modern, and opinionated CSS reset for consistent cross-browser styling.

This reset is designed to be a solid foundation for any web project, stripping away annoying browser defaults and providing a predictable starting point.

## Why use this?

Every browser handles default styling differently. This reset:
- Eliminates inconsistent margins and paddings.
- Fixes common "gotchas" with form elements and images.
- Implements modern best practices (like `border-box` sizing).
- Is lightweight and easy to understand.

## Key Features

- **Box Model:** Sets `box-sizing: border-box` to all elements for intuitive sizing.
- **Responsive Media:** Images, videos, and canvases are fluid by default (`max-width: 100%`).
- **Typography:**
    - Removes default margins from headings and paragraphs.
    - Improves text-rendering and font smoothing.
    - Ensures form elements inherit the parent font.
- **Modern Defaults:** Removes the "gray highlight" on mobile devices and handles `hidden` attributes correctly.
- **Accessibility Friendly:** Includes a base configuration that respects `prefers-reduced-motion`.

## Getting Started

### 1. Download
Download the `reset.css` file and add it to your project's CSS folder.

### 2. Implementation
Link the reset in your HTML `<head>` **before** your main styles:
