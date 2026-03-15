# Pruthviraj Prakash — Portfolio

Minimalistic portfolio site. Deploy to **GitHub Pages** as a user site: `username.github.io`.

## Deploy to GitHub Pages

1. Create a new repo named **`<username>.github.io`** (e.g. `pruthvirajprakash.github.io`).
2. Push this folder to the repo:
   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Portfolio"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Source**: choose **Deploy from a branch**.
4. Branch: **main** (or **master**), folder: **/ (root)**. Save.
5. After a few minutes, open `https://YOUR_USERNAME.github.io`.

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
cd portfolio
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Edit links

- **Resume**: Place your PDF as `FNU_Pruthviraj_Prakash_Resume.pdf` in this folder (or change the link in `index.html`).
- **LinkedIn / GitHub**: Update the URLs in the Contact section of `index.html` with your real profiles.
