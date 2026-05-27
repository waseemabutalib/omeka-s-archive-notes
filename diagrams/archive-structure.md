# Archive Structure Diagram

This diagram shows a generalized Omeka S archive structure for a public-facing digital humanities project.

```mermaid
flowchart LR
    A["Public User"] --> B["Home Page"]
    B --> C["Project Context"]
    B --> D["Archive Browse"]
    B --> E["Search"]
    B --> F["Document Library"]
    D --> G["Artifact Records"]
    D --> H["Returned Artifacts"]
    E --> G
    E --> F
    G --> I["Metadata Fields"]
    G --> J["Related Documents"]
    F --> J
    K["Admin / Maintainer"] --> L["Omeka S Dashboard"]
    L --> G
    L --> F
    L --> M["Pages and Navigation"]
```

## What This Represents

- Public users entering through home, context, search, browse, or document paths.
- Archive records connected to metadata and related documents.
- Maintainers managing records, documents, pages, and navigation in Omeka S.
- A structure that supports public browsing and future content expansion.

## Public Sharing Note

This is a generalized architecture diagram. It does not include a private sitemap, production admin URLs, raw data, or client-specific internal details.
