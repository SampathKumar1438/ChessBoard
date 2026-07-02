## 2024-05-24 - Semantic Table Elements
**Learning:** Tables used purely for layout (like the chessboard) should use `role="presentation"` so screen readers don't misinterpret them as data tables. Also, table titles/headers should use the semantic `<caption>` element instead of standalone `<th>` elements outside of table rows to maintain correct table structure and improve accessibility.
**Action:** Always add `role="presentation"` to layout tables, and replace incorrectly structured table elements (like standalone `<th>`) with appropriate semantic alternatives like `<caption>`.
