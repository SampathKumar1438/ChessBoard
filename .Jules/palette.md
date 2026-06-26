## 2024-06-26 - Table Accessibility in Layouts
**Learning:** The project's HTML code pattern sometimes uses tables for layout (requiring `role="presentation"`) and incorrect table structure elements like standalone `<th>` tags instead of semantic `<caption>` tags for table titles.
**Action:** When working with tables used strictly for layout, always ensure `role="presentation"` is applied so screen readers don't misinterpret the structure. Additionally, always use proper structural elements like `<caption>` instead of `<th>` for table titles.
