# ConnectChina Guide — GitHub Pages Deployment

This project is intentionally static so it can be deployed on GitHub Pages without a server.

## Before uploading

1. Open `contact.html` and replace:
   `YOUR_EMAIL@example.com`
   with your real contact email.

2. Do NOT invent affiliate links.
   Provider links are intentionally marked "Pending affiliate approval".

3. If an affiliate platform gives you a website verification method:
   - **META tag**: paste the exact tag into the `<head>` section of each page, under the `SITE VERIFICATION` comment.
   - **HTML file**: upload the exact verification file to the repository root.
   - **DNS verification**: only relevant after you bind your own domain.

## GitHub Pages deployment

1. Sign in to GitHub.
2. Click **New repository**.
3. Repository name suggestion: `connectchina-guide`
4. Set visibility to **Public**.
5. Create the repository.
6. Click **Add file → Upload files**.
7. Upload every file and the `assets` folder from this package.
8. Commit changes.
9. Open **Settings → Pages**.
10. Under "Build and deployment":
    - Source: `Deploy from a branch`
    - Branch: `main`
    - Folder: `/ (root)`
11. Save.
12. Wait a few minutes.
13. GitHub will display a live URL similar to:
    `https://YOUR_USERNAME.github.io/connectchina-guide/`

Use that URL in the affiliate-network Website field.

## Important

The website is intentionally written as an early-stage independent comparison project.
Do not claim live prices, real-world testing or partner relationships that do not yet exist.

## After affiliate approval

Replace "Pending affiliate approval" with real tracking links and add:
- outbound click tracking,
- merchant-specific SubIDs,
- sale/commission imports or network APIs,
- real China-based performance tests.
