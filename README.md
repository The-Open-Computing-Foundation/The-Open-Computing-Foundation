# OCF Website

Open `index.html` in a browser after extracting this directory. No installation,
server, build process or internet connection is needed to read the site. External
standards references require internet access.

## Contents

Nine information pages plus `404.html`, shared responsive and print CSS, the
supplied OCF logo and icon PNGs, with favicon sizes derived from the icon.
The two full-size branding PNGs are exact copies of the supplied images. No JavaScript,
third-party fonts, analytics, trackers, cookies or external runtime assets are used.

## Static hosting

Upload the contents of this directory, preserving names and relative paths, to
any static host. Pages work at a domain root or under a subdirectory. Configure
the host to serve `404.html` for missing paths; opening that file alone does not
set an HTTP 404 status. Some hosts need their own error-page configuration.
The relative links in the error page work for missing pages at this directory
level. For arbitrarily nested missing paths, configure a redirect to the explicit
404.html URL or a deployment-specific error response with corrected base paths.

The sitemap and robots file use the GitHub Pages project URL:
https://the-open-computing-foundation.github.io/The-Open-Computing-Foundation/
Update both files if the public location changes. `.nojekyll` serves the static
files without Jekyll processing. The `website` branch is the publication source.

## Editing

Edit HTML directly. Shared navigation and footer are repeated in every page;
keep them consistent. Styling is in `assets/css/style.css`, including narrow-screen
and print rules. All local asset and navigation paths are relative. The supplied logo
and icon are in `assets/images/`; PNG/ICO derivatives support small icon sizes.

No organisation contact or repository links have been invented. Research approaches
and objectives are explicitly proposed. Nonprofit describes the intended operating
model and does not assert registration, charity status or tax exemption.

See `QA.md` for checks performed and verification limits.
