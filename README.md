# Bright Path Academy – Fee Tracker

Files: `index.html`, `logo.jpg`, `notes.json` (keep all three in the repo root).

## Deploy on GitHub Pages
1. Create a new repository and upload the three files.
2. Repository **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
3. Your site appears at `https://<username>.github.io/<repo>/` after a minute or two.

## Saving changes to notes.json
GitHub Pages is static, so the page saves to notes.json by committing to your repo through the GitHub API.
1. GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → Generate.
2. Repository access: **Only select repositories** (this repo). Permissions: **Contents: Read and write**.
3. Open the site → **Settings → Save & sync**, enter username, repository, branch and the token, then Save sync settings.

The token is stored only in your own browser, never in the repo. Every change is also saved on the device, so nothing is lost if a sync fails. The header shows the save status. Without a token you can use **Download / Import notes.json** and upload the file to the repo yourself.

## Privacy
Pages sites and public repositories are readable by anyone, so student names and fee records in notes.json would be public. Use a private repository (private Pages needs a paid GitHub plan), or leave notes.json empty in the repo and rely on device storage plus manual Download.
