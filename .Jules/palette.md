## 2026-05-25 - Fix Invalid Table Header Elements
**Learning:** Stray `<th>` elements outside of rows break semantic table associations for screen readers. Using `<caption>` is the proper way to add a title to a table, and adding `scope="col"` to table headers ensures screen readers associate the headers with their respective columns properly.
**Action:** Always use `<caption>` for table titles and `scope` attributes for table headers to ensure accessible data grids.
