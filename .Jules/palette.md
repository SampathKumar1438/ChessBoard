## 2024-06-16 - Improved Table Semantics and Accessibility
**Learning:** This static project incorrectly uses standalone `<th>` elements for table titles instead of semantic `<caption>` elements, and relies on structural tables for layout (like the chessboard) without proper accessibility roles.
**Action:** Always replace standalone `<th>` title elements within tables with `<caption>` elements for better screen reader support, and add `role="presentation"` to layout-only tables so they are not announced as data tables.
