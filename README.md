# RallyCast Landing Page

Simple one-page landing site for **RallyCast** hosted on GitHub Pages.

## Files

- `index.html` - Landing page markup and styles (no external dependencies)
- `privacy.html` - Privacy policy page for the app and website
- `CNAME` - Custom domain for GitHub Pages (`rallycast.app`)
- `assets/rallycast_app_icon.png` - App icon used in the header
- `assets/rallycast_feature_graphic.png` - Feature graphic shown on the page

## GitHub Pages Setup

1. Create a GitHub repository named `rallycast-site`.
2. Push these files to the `main` branch.
3. In GitHub, open **Settings > Pages**.
4. Under **Build and deployment**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Save. GitHub will publish automatically on each push to `main`.

## DNS Setup for rallycast.app

At your DNS provider, add these records:

- Type: `A`, Host: `@`, Value: `185.199.108.153`
- Type: `A`, Host: `@`, Value: `185.199.109.153`
- Type: `A`, Host: `@`, Value: `185.199.110.153`
- Type: `A`, Host: `@`, Value: `185.199.111.153`

Optional but recommended:

- Type: `CNAME`, Host: `www`, Value: `rallycast.app`

## Expected URLs

- Primary: https://rallycast.app
- GitHub Pages fallback: https://<your-github-username>.github.io/rallycast-site/

## Future Enhancements

The structure is intentionally simple so you can add:

- Email signup form
- App screenshots section
- Play Store link section
