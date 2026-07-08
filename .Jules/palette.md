## 2024-07-08 - Table Accessibility and Structure
**Learning:** This project's HTML code pattern sometimes uses tables for purely visual layout (like a chessboard) requiring `role="img"` and `aria-label`, and also includes incorrect table structure elements like standalone `<th>` tags instead of semantic `<caption>` tags for table titles.
**Action:** Always check tables to determine if they are for data or layout, add `role="img"` to layout tables meant to be consumed as images, and enforce proper semantic tags like `<caption>` for table titles to improve screen reader accessibility.
