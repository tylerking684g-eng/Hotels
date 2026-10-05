# Luminal Voyage

Static, GitHub Pages-ready copy of the Luminal Voyage site from the supplied export.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders from this project to the repository root.
3. Commit and push to the `main` branch.
4. Open **Settings -> Pages** in GitHub.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.

The site is a static build, so no npm install or build step is required.

## Local preview

Run from the project directory:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Notes

The visual content and layout are kept from the supplied build. Several large page images are still referenced from the original Base44 media CDN because the uploaded archive did not contain those image files. The Base44 badge and page-view/auth wrappers were removed, and the static landing page is rendered directly without Base44 authentication.
