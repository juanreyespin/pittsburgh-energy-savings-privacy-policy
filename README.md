# Pittsburgh Energy Savings — Privacy Policy Site

A single static page (`index.html`) containing the Privacy Policy for Pittsburgh Energy Savings.

## Deploying with GitHub Pages

1. Create a new repository on GitHub (e.g. `pittsburgh-energy-savings-privacy-policy`).
2. Push this folder to it:

   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```

3. In the repo on GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`.
5. Save. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

### Using a custom domain

If you want a custom domain (e.g. `privacy.pittsburghenergysavings.com`):

1. Add a `CNAME` file to this folder containing just the domain name.
2. In your DNS provider, add a `CNAME` record pointing that subdomain to `<your-username>.github.io`.
3. In **Settings → Pages**, enter the custom domain and enable "Enforce HTTPS" once it's verified.

