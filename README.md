# sohamrakhonde.com

Static portfolio site deployed to GitHub Pages.

## Deployment

The GitHub Actions workflow publishes the site whenever changes are pushed to
`main`. In the repository settings, set **Pages → Build and deployment → Source**
to **GitHub Actions**.

The repository includes a `CNAME` file for `sohamrakhonde.com`. Configure DNS
at the domain registrar to point the apex domain to GitHub Pages, then enable
HTTPS in the repository's Pages settings.
