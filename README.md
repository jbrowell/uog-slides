# University of Glasgow Quarto Slides Template

A [Quarto](https://quarto.org) RevealJS presentation theme following the [University of Glasgow brand guidelines](https://www.gla.ac.uk/myglasgow/staff/brandtoolkit/), 2026 update.

## Installation

```bash
quarto add jbrowell/uog-slides
```

Or clone this repo and use the extension directly from `_extensions/uog-slides/`.

## Usage

Set the format in your document YAML:

```yaml
format: uog-slides-revealjs
```

Optionally add a footer:

```yaml
footer: "University of Glasgow"
```

See [`template.qmd`](template.qmd) for a full working example.

## Slide types

### Title slide

Generated automatically from YAML front matter:

```yaml
title: "My Presentation"
subtitle: "An optional subtitle"
author: "Your Name"
date: last-modified
```

The UoG boxed logo appears in the top-left corner on every slide, including the title slide.

### Section divider slides

Use `# Heading {.section-slide}` to create a dark-blue divider between sections:

```markdown
# Methods {.section-slide}
```

Level-1 headers (`#`) without the class are also styled as section dividers by default.

### Regular slides

Use `## Heading` for standard content slides with a navy heading underline.

## Brand colours

| Name           | Hex       | Usage                          |
|----------------|-----------|--------------------------------|
| University Blue | `#011451` | Primary — backgrounds, headings |
| Dark Blue      | `#005398` | Links, section slides          |
| Dark Purple    | `#4C2683` | Accent                         |
| Dark Pink      | `#A60367` | Accent                         |
| Dark Green     | `#405D18` | Accent                         |
| Dark Red       | `#7D2239` | Accent / warnings              |
| Light Blue     | `#4DBBC6` | Subtitle text, decorative line |
| Light Purple   | `#A5A1CE` | Light accent                   |
| Light Yellow   | `#F2D25C` | Callout warnings               |

Utility CSS classes (e.g. `[text]{.uog-navy}`) are available for all colours above.

## Font

[Noto Sans](https://fonts.google.com/nspecimen/Noto+Sans) — loaded from Google Fonts.

## Assets

- Logos: `_extensions/uog-slides/assets/`
  - `uog-logo-boxed.png` — used automatically on every slide (top-left)
  - `uog-logo-white.png` — unboxed white version (available for custom use)
  - `uog-logo-blue.png` — unboxed blue-text version (available for custom use)
- Source logo files: [`brand_assets/Main UofG logo artwork/`](brand_assets/Main%20UofG%20logo%20artwork/)
- Colours: <https://www.gla.ac.uk/myglasgow/staff/brandtoolkit/colour/>
