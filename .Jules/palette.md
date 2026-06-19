## 2026-06-19 - Accessible Tables

**Learning:** Sighted users can easily tell when a table is used purely for visual layout (like a chessboard) or understand context without explicit captions. However, screen readers read all table structure elements. Providing `role="presentation"` on purely visual layout tables instructs screen readers to read the content without the table semantics, reducing noise. Furthermore, using a `<caption>` rather than an invalid direct child `<th>` properly associates a title with the table structure for screen readers.

**Action:** When inspecting tables, determine if they are for layout or data. Add `role="presentation"` to layout tables. Always use the proper `<caption>` element for table titles instead of standalone header tags.
