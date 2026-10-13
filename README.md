# VANGUARD Research Assistant Dashboard

Static dashboard for GitHub Pages.

## Publish using GitHub website

1. Create a **public** GitHub repository named `vanguard-dashboard`.
2. In that repository choose **Add file > Upload files**.
3. Upload `index.html` and `.nojekyll` from this folder to the **repository root** (not a subfolder); the README is optional.
4. Commit changes to the `main` branch.
5. Open **Settings > Pages**.
6. Under **Build and deployment**, set **Source: Deploy from a branch**; **Branch: main**, **Folder: / (root)**; press **Save**.
7. Wait for publishing, then open `https://YOUR-USERNAME.github.io/vanguard-dashboard/`.

## Important limitations

- GitHub Pages publishes a **publicly accessible** website. Do not upload confidential material or secrets.
- This version stores checklist progress in **each viewer's own browser** (localStorage). It does not yet synchronize task updates across supervisors or team members.
- You can export/import the dashboard's JSON backup to share a manual snapshot.
- For multi-user login and shared task state, the dashboard must first be upgraded to use a managed backend (e.g. Supabase) with authentication and row-level security. GitHub Pages can still host the frontend in that setup.
