# SmartBilao Landing Page

Static marketing/summary page for the **SmartBilao** ergonomic multi-layer bilao drying system prototype.

## Structure

- `index.html` – content and layout for the landing page
- `styles.css` – visual styles and responsive layout
- `package.json` – optional dev dependency (`serve`) for local preview

## Local development

1. Install dependencies:

   ```bash
   npm install
   ```

2. Run a local static server:

   ```bash
   npm run dev
   ```

   Then open `http://localhost:3000` (or the port shown by `serve`).

## Deploying to Vercel

You can deploy this as a static site:

- Set the **root directory** to this folder.
- Set the **build command** to `npm run dev` or leave empty for static hosting.
- Set the **output directory** to `.` (the project root), since `index.html` is at the top level.

> To make the "Download full paper" button work, replace its `href` in `index.html` with a public URL to your PDF (for example, a link from a cloud drive or from a file hosted on Vercel).

