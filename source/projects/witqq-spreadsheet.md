---
title: "@witqq/spreadsheet"
repo: witqq/spreadsheet
homepage: https://spreadsheet.witqq.dev
examples: https://spreadsheet.witqq.dev
license: BSL 1.1
author: witqq
authorurl: https://github.com/witqq
description: Canvas-based spreadsheet engine with zero external dependencies. Renders 100K+ rows at 60fps. Framework wrappers for React, Vue, and Angular.
---

@witqq/spreadsheet is a high-performance canvas-based spreadsheet engine 
built in pure TypeScript with zero external dependencies. The core engine 
uses Canvas 2D with a multi-layer rendering pipeline for optimal performance, 
handling 100K+ rows at 60fps with smooth scrolling.

Works with all major frameworks:

* [React wrapper](https://spreadsheet.witqq.dev/getting-started/)
* [Vue 3 wrapper](https://spreadsheet.witqq.dev/getting-started/)
* [Angular wrapper](https://spreadsheet.witqq.dev/getting-started/)
* [Vanilla JS widget](https://spreadsheet.witqq.dev/getting-started/)

#### Features Overview

* Canvas 2D rendering (zero DOM cells)
* Zero external dependencies in core
* 100K+ rows at 60fps
* Multi-column sorting
* 14 filter operators
* Formula engine
* Frozen panes (rows and columns)
* Merged cells with spatial index
* Clipboard (copy/cut/paste, TSV + HTML)
* Undo/redo (100-step stack)
* Drag-to-fill with pattern detection
* Column and row resize
* Cell validation (required, range, regex, custom)
* Conditional formatting (gradients, data bars, icon sets)
* Real-time collaboration (OT engine, WebSocket)
* Row grouping with aggregates
* Pivot tables
* Streaming data adapter
* Dark/light themes
* WCAG 2.1 AA accessibility
* Print support
* Excel import/export (plugin)
* Context menu
* TypeScript strict mode
