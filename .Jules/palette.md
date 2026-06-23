## 2024-06-23 - Improve table accessibility and semantics
**Learning:** Tables are sometimes used for pure visual layout (like a chessboard) or have incorrect structural elements (like `<th>` used as a title instead of `<caption>`). This makes the interface less accessible and confusing for screen readers.
**Action:** Always add `role="presentation"` to tables used strictly for layout to hide the table semantics from screen readers. Use semantic elements like `<caption>` for table titles instead of standalone header tags.
