## 2024-06-29 - Fixed Table Structural Accessibility
**Learning:** Tables designed primarily for layout, like the chessboard, can be misleading to screen readers if not properly labeled. Also, standalone `<th>` tags used without correct context are bad for semantic structure.
**Action:** Applied `role="presentation"` to layout tables to prevent screen readers from trying to interpret them semantically, and replaced invalid standalone `<th>` elements with `<caption>` for proper table titling, ensuring semantic HTML layout.
