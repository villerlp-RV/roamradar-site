# RoamRadar website

The public pages Google Play links to, served by GitHub Pages at
https://roamradar.app:

| URL | Use |
|---|---|
| `/` | Landing page with the Play Store link |
| `/support` | Contact and help |
| `/privacy` | Privacy Policy URL in Play Console |
| `/terms` | Terms of Service URL in Play Console |
| `/delete-account` | Delete account URL in Play Console |

## Where the pages come from

These files are generated in the app's repository (`site/`, by
`node site/build.mjs`, which reads the privacy and terms text from the
app) and copied here. Don't edit them here: change them there, rebuild,
and copy the `.html`, `styles.css` and `favicon.svg` files over.

Last copied from roamradar@f683d70.

## Hosting

- **Settings → Pages**: Source "Deploy from a branch", branch `main`, folder `/ (root)`.
- **Custom domain**: `roamradar.app` (the `CNAME` file), with Enforce HTTPS on.
- `.nojekyll` serves the files as they are.
