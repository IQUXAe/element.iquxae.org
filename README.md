# Element Web for iquxae.org

Element web client for Matrix server iquxae.org.

## GitHub Pages Deployment

1. Create a repository on GitHub
2. Push these files to the repository
3. Enable GitHub Pages in repository settings:
   - Settings → Pages
   - Source: GitHub Actions
4. Edit `config.json` for your server if needed
5. Push changes - deployment will happen automatically

After deployment, Element will be available at:
`https://<username>.github.io/<repository-name>/`

## Cloudflare Pages Deployment

To deploy on Cloudflare Pages:

1. Install Wrangler: `npm install -g wrangler`
2. Login: `wrangler login`
3. Deploy: `wrangler deploy`
4. Add custom domain in Cloudflare dashboard
