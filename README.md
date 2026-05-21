# TRAIN Lab Website

This is a static HTML/CSS website prepared for GitHub Pages.

## How to publish with GitHub Pages

1. Create a GitHub repository, for example `trainlab-website`.
2. Upload all files in this folder to the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save. GitHub will publish the site.

## Custom domain

In the repository, create a file named `CNAME` containing your domain, for example:

```text
www.trainlab.net
```

Then update GoDaddy DNS:

- Type: `CNAME`
- Name: `www`
- Value: `<your-github-username>.github.io`

For the root domain, follow GitHub Pages' custom-domain instructions and add the GitHub Pages A records in GoDaddy.
