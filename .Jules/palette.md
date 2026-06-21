## 2024-06-21 - Table Accessibility Improvements

**Learning:** Tables used purely for layout (like the chessboard) confuse screen readers if not marked as presentational, and standalone `<th>` tags used outside of `<tr>` elements violate HTML structure.
**Action:** When working with layout tables, apply `role="presentation"` to hide table semantics from assistive tech. For data tables with titles, use the semantic `<caption>` element instead of standalone `<th>` elements.
