---
title: Bilig
repo: proompteng/bilig
direct: https://github.com/proompteng/bilig
homepage: https://proompteng.github.io/bilig/
examples: https://github.com/proompteng/bilig/tree/main/examples/headless-workpaper
license: MIT
npm: \@bilig/headless
technology: TypeScript
leading technology: javascript
author: Proompt Engineering
authorurl: https://github.com/proompteng
description: Headless TypeScript spreadsheet engine for formulas, workbook automation, and Node services.
---

Bilig is a headless spreadsheet/workbook engine for JavaScript and TypeScript applications.
It is built for services, coding agents, and automation workflows that need spreadsheet formulas and workbook state without embedding a browser grid.

The public `@bilig/headless` package builds workbooks from arrays or JSON records, evaluates formulas, applies cell and structural edits, reads ranges, and persists documents as JSON for round-trip verification.

#### Features Overview

* Headless workbook runtime for Node.js
* Formula-backed cells and range reads
* Cell edits, row/column operations, and structural workbook changes
* JSON persistence and restore APIs
* Runnable examples for CSV-shaped data, JSON records, server workflows, and coding-agent writeback verification
* TypeScript source and public package types

#### Use cases

* Server-side spreadsheet calculations
* Workbook automation behind API routes and background jobs
* Coding-agent tools that need deterministic read, write, recalculate, and verify loops
* Formula-backed financial or operations models where a visual grid is optional
