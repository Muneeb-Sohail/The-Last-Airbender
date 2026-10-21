# The Four Nations — Avatar-Themed Website

## Project Files
- `index.html` — Home page using inline CSS.
- `information.html` — Nation guide using embedded CSS.
- `registration.html` — Registration form using external CSS.
- `style.css` — Stylesheet for the registration page.
- `images/` — Original SVG illustrations made for this project.
- `media/` — Original ambient audio and short video clip.

## Run the Website
Keep the folder structure unchanged. Open `index.html` in a browser, or use the Live Server extension in VS Code. The navigation links connect the three pages. The form is a front-end demonstration and does not store submissions.

## What Is CSS?
CSS (Cascading Style Sheets) controls how HTML content looks. It separates presentation from content, makes pages easier to maintain, and helps keep a consistent design.

In the rule `body { background: #0c1a25; }`, `body` is the selector, `background` is the property, and `#0c1a25` is the value.

## Three CSS Methods
**Inline CSS:** Written in an element's `style` attribute and affects that element directly.

**Embedded CSS:** Written inside a `<style>` element in the document's `<head>` and is useful for styling one page.

**External CSS:** Stored in a separate `.css` file and linked to HTML. It is easier to reuse and maintain across pages.

This assignment intentionally uses a different CSS method on each page.

## CSS History
CSS1 introduced basic presentation features such as fonts, colors, and spacing. CSS2 and CSS 2.1 expanded layout, positioning, media types, and other styling capabilities.

Modern CSS is developed as separate modules, including Flexbox, Grid, animations, and media queries, rather than one single numbered release.

## Browser Support
Browser support matters because browsers may implement features differently. Test this site in two browsers, such as Google Chrome and Mozilla Firefox, and record any differences you notice.

## Semantic HTML
Semantic HTML uses elements that describe the purpose of their content. Examples include `<nav>`, `<main>`, and `<article>`, which help organize a webpage and make its structure clearer.

A `<div>` is non-semantic because it provides a generic container without describing the meaning of its content.