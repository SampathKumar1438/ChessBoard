## 2024-06-07 - Semantic Tables over Layout Tables
**Learning:** The project's HTML code pattern sometimes uses tables for purely visual layouts (requiring `role="presentation"` and `aria-hidden="true"`) and incorrect table structure elements like standalone `<th>` tags instead of semantic `<caption>` tags.
**Action:** Always verify table structures in HTML files. For purely visual layout tables, add presentation roles to prevent screen readers from announcing empty grid cells. For data tables, ensure valid semantic markup like `<caption>` is used instead of standalone heading tags.
