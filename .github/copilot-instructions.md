# Copilot Instructions for maryclair-wright.github.io

## Project Overview
This repository is a collection of standalone HTML files, each representing a self-contained interactive web lab, quiz, or educational exercise. There is no central build system, framework, or shared JavaScript/CSS—each file is intended to be opened directly in a browser.

## Key Conventions & Patterns
- **Single-file HTML apps:** Each `.html` file is a complete, independent web page. All logic, markup, and styles are typically embedded in the file.
- **No external dependencies:** There is no package manager, build step, or module system. Do not add npm, yarn, or other dependency managers.
- **No shared assets:** If you need to reuse code, copy the relevant snippet into the target file. There is no shared JS/CSS folder.
- **Vanilla JS/HTML/CSS only:** Use plain JavaScript, HTML, and CSS. Do not introduce frameworks (React, Vue, etc.) or preprocessors (Sass, TypeScript, etc.).
- **File naming:** Each file name describes its content (e.g., `binaryToDecimal.html`, `gradeScaleDebugLab.html`).
- **Keep code readable for students:** Favor clarity and simplicity over cleverness. Add comments to explain non-obvious logic.

## Developer Workflow
- **To test:** Open any `.html` file directly in your browser. There is no local server or build process required.
- **To add a new lab:** Duplicate an existing `.html` file as a template, then edit as needed.
- **To debug:** Use browser developer tools (Console, Elements, Sources) on the opened file.
- **To update:** Edit the relevant `.html` file directly. There is no central index or manifest to update.

## Examples
- See `ai-feedback.html` and `index.html` for typical structure: `<script>` and `<style>` tags are included in the same file as the HTML.
- For interactive exercises, embed JavaScript at the bottom of the file or within `<script>` tags in the `<head>` or `<body>`.

## What NOT to do
- Do not add a build system, package.json, or external dependencies.
- Do not refactor to use modules or frameworks.
- Do not create shared folders for JS/CSS.

## Summary
This repo is a flat collection of educational HTML exercises. Each file is standalone. Prioritize clarity, simplicity, and approachability for students and educators.
