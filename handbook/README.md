# CUWALID-DRYP Handbook Project

This repository contains the source for the official CUWALID-DRYP Handbook.

## Purpose

The handbook is designed as a book-style, self-paced reference for hydrological modelling and seasonal water forecasting workflows.

## Build Philosophy

- Author once in Markdown.
- Keep all handbook content under version control.
- Generate multiple outputs from the same source: PDF, Word, and HTML.
- Track compatibility between handbook versions and software versions.

## Structure

- `handbook.md`: master document and navigation index.
- `chapters/`: individual chapter source files.
- `figures/`: original and exported figures.
- `tables/`: reusable table sources.
- `styles/`: style guidance and publication settings.
- `metadata/`: versioning, citation, and licensing metadata.
- `references.bib`: bibliography for citations.

## Conventions

- Keep chapter file names numeric and zero-padded.
- Follow the standard chapter template in `chapters/_chapter_template.md`.
- Prefer explanatory prose over notebook-only instructions.
- Cite scientific sources where model concepts are explained.

## Current Scope

This scaffold establishes the publication-ready architecture and first draft chapter stubs.
