# Abel Soyoye — Portfolios

This repo hosts two portfolios for GitHub Pages:

- **/cloud-security** → Cloud Security Engineer portfolio
- **/devops** → DevOps Engineer portfolio
- **/assets** → shared images

## Publish on GitHub Pages

1. Create a new GitHub repository, e.g., `abel-portfolio` (Public is fine for Pages).
2. Upload the contents of this folder to the repository (keep the folder structure).
3. In GitHub: **Settings → Pages → Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** (or `master`), folder: **/** (root)
4. After it builds, your site will be live at:
   - `https://<your-username>.github.io/abel-portfolio/cloud-security/`
   - `https://<your-username>.github.io/abel-portfolio/devops/`

## Local edits

- Edit the HTML in `/cloud-security/index.html` or `/devops/index.html`.
- If you replace the headshot, put the new image in `/assets/` and update the `<img src="../assets/<file>">` paths if needed.