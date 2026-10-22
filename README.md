# Personal backup tool website

A static site that provides the homepage and privacy policy for a personal backup tool.

## Files

- `index.html`: what the tool does, its Google Drive permission, and a link to the privacy policy.
- `privacy.html`: how data is handled and retained, and how to revoke access.
- `style.css`: shared styles.
- `.nojekyll`: lets GitHub Pages serve the files as they are.

## Publishing

GitHub Pages publishes the root of the `main` branch. The homepage and privacy policy URLs are the ones already set in the OAuth configuration.

The public pages contain only the tool's purpose, the required app name, and the data-handling statement. Both pages use `noindex` to ask search engines not to index them; the site remains publicly accessible.

After each update, check that the homepage, privacy policy, and styles load correctly. This repository holds only the website files.
