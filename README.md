# Robi & Airtel Number Checker

A static, mobile-friendly Bengali number-format checker designed for GitHub Pages.

## Publish on GitHub Pages
1. Sign in to GitHub and create a new repository, for example `number-checker`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub to publish the site. The address will look like `https://YOUR-USERNAME.github.io/number-checker/`.

## Important limitations
- This static site checks number format and estimates the operator from the prefix only.
- Mobile Number Portability (MNP) means prefix does not guarantee the current network.
- It does not identify subscriber names, SIM registration, active status, or private account information.
- No Robi/Airtel private API is connected in this starter version. Use only an official/authorized API and keep secret keys on a backend, never in this public HTML file.
