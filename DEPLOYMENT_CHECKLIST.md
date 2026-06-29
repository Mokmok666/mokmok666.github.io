# Deployment Checklist

Before uploading to GitHub, confirm the extracted folder contains:

- [ ] `index.html`
- [ ] `thesis.pdf`
- [ ] `.nojekyll`
- [ ] `README.md`
- [ ] `DEPLOYMENT_CHECKLIST.md`

Upload these files directly to the repository root of `mokmok666.github.io`.

After upload:

1. Go to **Settings → Pages**.
2. Set **Source** to `Deploy from a branch`.
3. Set **Branch** to `main` and folder to `/ (root)`.
4. Wait until Actions / Pages deployment is green.
5. Visit `https://mokmok666.github.io/?v=26`.
6. Check that the homepage loads correctly.
7. Click the thesis PDF button and confirm `thesis.pdf` opens.

Important:
- Do not upload the ZIP directly.
- Do not move `thesis.pdf` into another folder.
- Keep `index.html` and `thesis.pdf` in the same root directory.
