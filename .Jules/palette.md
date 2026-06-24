## 2026-06-24 - Table Semantics and Layout

**Learning:** Tables are sometimes used strictly for layout purposes (like the chessboard grid), which can confuse screen readers. Data tables also frequently misuse structural tags (like standalone `<th>` for table titles instead of semantic `<caption>`).
**Action:** When a table is used strictly for layout, apply `role="presentation"` to ensure screen readers ignore the table structure and read the contents linearly. For data tables, always use semantic elements like `<caption>` for titles instead of standalone `<th>` elements to ensure proper accessibility hierarchy.
