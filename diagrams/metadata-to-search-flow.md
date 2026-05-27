# Metadata to Search Flow

This diagram shows how structured metadata supports search and browse behavior in a public archive.

```mermaid
flowchart LR
    A["Research Material"] --> B["Record Creation"]
    B --> C["Metadata Fields"]
    C --> D["Omeka S Item Record"]
    D --> E["Search Index / Browse Views"]
    E --> F["Public Search"]
    E --> G["Archive Browse"]
    F --> H["User Finds Record"]
    G --> H
    H --> I["Related Documents or Context"]
```

## What This Represents

- Research material is translated into structured records.
- Metadata fields make records easier to search, browse, and understand.
- Public users reach records through search or browsing paths.
- Related documents and context help users continue exploring.

## Public Sharing Note

This is a generalized diagram. It does not include private dataset fields, raw research materials, client-specific records, or production exports.
