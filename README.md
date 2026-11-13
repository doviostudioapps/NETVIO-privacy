# NETVIO privacy site

Static privacy policy for the NETVIO app.

## Target URL

```text
https://doviostudioapps.github.io/NETVIO-privacy/
```

This URL becomes active after the repository is published with GitHub Pages.

## Publish with a new repository

1. Create a public repository named **NETVIO-privacy** under
   `https://github.com/doviostudioapps`.
2. From this folder, push the contents:

```bash
cd privacy-site
git init
git add .
git commit -m "Add NETVIO privacy policy"
git branch -M main
git remote add origin https://github.com/doviostudioapps/NETVIO-privacy.git
git push -u origin main
```

3. Open the repository → **Settings** → **Pages**.
4. Under **Build and deployment**, select:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
5. Save and wait for the Pages deployment to finish.
6. Open the URL and verify both Vietnamese and English sections.

## Store listing

Use this URL in Google Play Console and App Store Connect:

```text
https://doviostudioapps.github.io/NETVIO-privacy/
```

Before publishing, verify:

- the contact email is correct;
- the app version and effective date are current;
- the policy matches the permissions and third-party services in the build;
- the page loads without login and without relying on JavaScript.

## Updating

Edit `index.html`, commit, and push to `main`. GitHub Pages will publish the
new version automatically. Update the effective date and version in both
language sections.
