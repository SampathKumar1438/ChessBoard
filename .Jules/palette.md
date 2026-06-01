## 2026-06-01 - Semantic Tables

**Learning:** Tables used purely for visual layout should use `role="presentation"` to prevent screen readers from announcing rows/columns, treating it as regular layout instead of tabular data. Tables containing actual data require structural accuracy—using a standalone `<th>` as a title breaks table semantics and should be a semantic `<caption>` instead.

**Action:** Before writing or styling tables, determine if it's a layout table or a data table. Apply `role="presentation"` to layout tables, and strictly use semantic elements like `<caption>`, `<thead>`, and correct `<th>` scoping for true data tables.