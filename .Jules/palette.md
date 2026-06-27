## 2024-07-05 - Table Accessibility Fixes
**Learning:** Decorative tables used purely for layout (like chessboards) need `role="presentation"` so screen readers don't announce them as data tables. Also, tables need a semantic `<caption>` instead of a standalone `<th>` as the title for proper accessibility structure.
**Action:** Always add `role="presentation"` to layout tables, and use semantic `<caption>` elements for table titles.
