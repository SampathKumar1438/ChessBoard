## 2024-05-18 - Semantic HTML for Tables
**Learning:** Using `role="presentation"` on layout tables prevents screen readers from announcing them as data tables, which can be confusing for users. Additionally, using `<caption>` instead of a standalone `<th>` for table titles ensures semantic HTML and better accessibility.
**Action:** Always verify if a table is used for layout or data. If it's for layout, add `role="presentation"`. For data tables, ensure titles are wrapped in `<caption>` tags for proper semantic structure.
