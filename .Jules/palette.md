## 2024-06-09 - Table Accessibility Patterns

**Learning:** This static HTML project contains several accessibility anti-patterns related to tables. Tables are used purely for visual layout (like a chessboard) without layout-specific roles, causing screen readers to incorrectly parse them as tabular data. Additionally, data tables use standalone `<th>` tags for the table title instead of semantic `<caption>` elements, breaking table structure expectations.

**Action:** Add `role="presentation"` to layout-only tables so screen readers treat them as normal div elements, and convert standalone `<th>` table titles into semantic `<caption>` tags to provide proper context to assistive technologies.