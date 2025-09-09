# Copilot Instructions for JavaScript Tutorial Codebase

## Overview
This codebase is a collection of standalone HTML files demonstrating core JavaScript concepts. Each file focuses on a specific topic (variables, data types, objects, arrays, etc.) and is intended for educational purposes. There is no build system, package manager, or test framework present.

## Architecture & Patterns
- Each HTML file contains embedded JavaScript (either inline or via `<script>` tags) illustrating a concept.
- No cross-file imports or shared modules; all logic is local to each file.
- No external dependencies or frameworks are used.
- File naming follows a numeric prefix for ordering topics (e.g., `1variable.html`, `12object.html`).
- Images are stored in the `Image/` directory for use in tutorials.

## Developer Workflow
- Edit HTML files directly; changes are reflected immediately when opened in a browser.
- No build or test commands are required.
- Debugging is done using browser developer tools (e.g., Chrome DevTools).

## Project-Specific Conventions
- Keep code examples simple and focused on the topic of the file.
- Use clear variable names and comments to aid learning.
- Avoid advanced JavaScript features unless the file's topic requires it.
- Do not introduce external libraries or frameworks unless explicitly requested.

## Examples
- To demonstrate objects, edit `12object.html` and use inline JavaScript to show object creation, property access, and methods.
- For arrays, use `11array.html` to show array operations.
- For math functions, use `9mathLib.html`.

## Key Files
- `1variable.html` – Variables
- `2dataType.html` – Data Types
- `12object.html` – Objects
- `Image/stack-heap-pointers.png` – Visual aid for memory concepts

## Integration Points
- No backend, API, or external integration is present.
- All code runs client-side in the browser.

## How to Extend
- Add new topics by creating additional HTML files following the numeric naming convention.
- Update existing files to improve clarity or add new examples.

---
For questions or improvements, ask for clarification on specific files or topics. This guide is focused on the current structure and practices of this codebase.
