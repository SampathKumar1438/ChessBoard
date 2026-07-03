## 2024-07-24 - Accessibility issues in static tables
**Learning:** The project uses tables for purely visual layout (like a chessboard) causing confusion for screen readers, and incorrectly uses standalone `<th>` tags instead of `<caption>` tags for table headers.
**Action:** Add `role="presentation"` to layout tables so screen readers ignore them, and replace standalone `<th>` tags at the beginning of tables with semantic `<caption>` tags.
