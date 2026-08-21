# Paper Mario: The Thousand-Year Door — Save Editor

Web-ready static build of the TTYD save editor.

## Deployment

This project is completely static: open `index.html` or publish the folder with GitHub Pages, Cloudflare Pages, Netlify, etc.

### GitHub Pages

1. Create a public repository.
2. Put `index.html` in the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose the default branch and `/ (root)`.
5. Save. GitHub will publish the editor at the generated Pages URL.

## Privacy

The editor is client-side. The save file is selected by the user in the browser and is processed locally by the page; there is no application server in this project.

The page currently references Google Fonts through CSS. If fully offline/self-contained hosting is desired, those fonts can later be bundled locally without changing the save-editor logic.
