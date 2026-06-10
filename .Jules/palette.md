## 2024-07-24 - Semantic Table Structures & Layout Tables
**Learning:** Found two common table accessibility anti-patterns in this project:
1) Using tables strictly for visual layout (like the ChessBoard) without `role="presentation"`, which causes screen readers to announce meaningless tabular structure.
2) Using standalone `<th>` elements to title tables instead of semantic `<caption>` elements, which breaks the programmatic association between the table and its title for assistive technologies.
**Action:** Always add `role="presentation"` when tables are purely for layout, and always use `<caption>` as the first child of a `<table>` to provide an accessible title.