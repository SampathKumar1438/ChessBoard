## 2026-05-21 - Image Paths and Descriptive Alt Text
**Learning:** Found that generic alt texts (like `alt="image-1"`) provide no value to screen reader users and fail gracefully when images cannot load. Furthermore, static HTML sites without an `assets` folder require correctly mapping `src` attributes to the root directory for assets to render.
**Action:** When adding or fixing images in static projects, always ensure `src` points to the correct directory structure and replace any generic alt attributes with brief, descriptive text summarizing the image contents.
