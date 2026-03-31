> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use `https://mintlify.com/docs` as the primary reference for Mintlify and MDX writing syntax in this project
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

- `temp` means the local branch `temporary_storage`
- Default to decoding project text files as `UTF-8` before considering other encodings

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Diagram and illustration style

- For LeetCode theory pages, prefer hand-authored `SVG` diagrams over Mermaid when precise layout matters
- Keep diagrams consistent with the current blog look: minimal, instructional, calm, and not decorative
- Match the existing linked-list and array diagrams in `images/leetcode/`
- Use a rounded card container with soft borders in light mode and dark mode support via `prefers-color-scheme`
- Prefer a restrained palette:
  - light background: `#F8FAFC`
  - dark background: `#0F1115`
  - panel/card: `#FFFFFF` in light mode, `#16181D` in dark mode
  - border: `#CBD5E1` in light mode, `#2A2A30` in dark mode
  - primary text: `#0F172A` in light mode, `#F9FAFB` in dark mode
  - secondary text: `#475569` in light mode, `#A1A1AA` in dark mode
  - accent green: `#16A34A` with dark-mode counterpart `#22C55E`
  - warning/end marker red: `#EF4444`
- Use plain sans-serif fonts already used in the SVGs, and keep typography simple and readable
- Use rounded rectangles, clean dividers, evenly spaced arrows, and centered labels
- Align labels, chips, dots, and legends to shared center lines; avoid anything that looks visually "floating"
- For explanatory legends, prefer one horizontal row near the bottom of the diagram
- Avoid repeating the section heading inside the SVG unless the diagram truly needs an internal title
- Avoid heavy gradients, shadows, glossy effects, neon colors, or infographic-style clutter
- Avoid oversized captions inside the image; the MDX text below the image should carry the explanation
- Prefer Chinese labels when the surrounding article is Chinese, but keep concise technical identifiers like `head`, `next`, and `null` when they aid learning
- For arrays, emphasize contiguous storage, address/index alignment, and equal cell sizing
- For linked lists, emphasize node partitioning, pointer direction, and consistent legend treatment
- Save LeetCode diagrams under `images/leetcode/` with stable, descriptive kebab-case names
- When replacing an existing image for style improvement, preserve the original filename unless cache busting is explicitly needed

## Collaboration note

- Treat the current LeetCode SVG style as the default visual baseline for future diagrams in this repo unless the user asks for a different style

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
