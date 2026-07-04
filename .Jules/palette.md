## 2024-07-04 - Table Accessibility Improvements
**Learning:** This app frequently uses tables for visual layout (like a chessboard) and incorrect table structures (standalone `<th>` instead of `<caption>` for titles).
**Action:** Always add `role="presentation"` to tables used strictly for layout to avoid screen reader confusion, and ensure table titles use semantic `<caption>` tags instead of generic headers.
