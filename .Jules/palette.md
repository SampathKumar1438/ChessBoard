## 2024-07-05 - Table Accessibility Enhancements
**Learning:** Tables used for structural layout (like a chessboard) need `role="presentation"` to prevent screen readers from interpreting them as data tables. Also, standalone `<th>` elements used as table titles should be properly formatted as `<caption>` to ensure correct table structure.
**Action:** Always add `role="presentation"` to layout tables and use `<caption>` for data table titles to improve screen reader accessibility.
