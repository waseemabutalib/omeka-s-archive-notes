# Content Model

## Purpose

A digital archive needs a content model that makes records understandable, searchable, maintainable, and expandable. In Omeka S, that means thinking carefully about item types, metadata fields, collections, pages, and future data growth.

## Core Content Types

A generalized digital humanities archive may include:

- Artifact records.
- Returned artifact records.
- Documents or PDFs.
- Contextual essays or research pages.
- Museum/institution references.
- Geographic or expedition-related context.
- Bibliography or source materials.

## Metadata Goals

Metadata should help users find, compare, and understand records. It should also help maintainers add future records without breaking the structure.

Common metadata categories may include:

- Title or object name.
- Description.
- Creator, maker, or culture/community where appropriate.
- Current institution or holding location.
- Original location or origin context.
- Date or date range.
- Material or object type.
- Source or citation.
- Rights or usage note.
- Related documents.
- Tags or thematic groupings.

## Modeling Principles

- Keep field names clear for future maintainers.
- Separate public-facing labels from internal organization where needed.
- Avoid overloading one field with multiple meanings.
- Use consistent vocabulary for repeated categories.
- Make search and browse behavior part of the data design, not an afterthought.
- Leave room for additional records, documents, and relationships later.

## Example Public-Safe Record Shape

```text
Title: Example Artifact Record
Object Type: Sculpture
Current Holding Institution: Example Museum
Original Region: Example Region
Date Range: 19th century
Description: Short public-facing description.
Related Documents: Example source PDF
Tags: restitution, archive, museum collection
```

## What This Demonstrates

- Metadata thinking.
- CMS/data structure planning.
- Search and browse support.
- Long-term maintainability.
- Translation of research material into platform structure.

## Public Sharing Note

This note uses generalized examples. It does not include private datasets, raw client research files, unapproved records, or full production metadata exports.
