## 2024-05-30 - Layout Tables and Table Captions
**Learning:** Using tables for layout requires `role="presentation"` so screen readers don't misinterpret them as tabular data. Additionally, `<th>` should only be used for headers within table rows, whereas `<caption>` is the semantic element for a table's title.
**Action:** Always add `role="presentation"` to layout tables and use `<caption>` instead of standalone `<th>` tags for table titles.
