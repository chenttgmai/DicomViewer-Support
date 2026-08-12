# Static support-site deployment

Deploy `index.html`, `privacy.html`, `support.html`, and `styles.css` to the root of the public `chenttgmai/DicomViewer-Support` GitHub repository and enable GitHub Pages from the default branch root. The prepared metadata uses these paths:

- `https://chenttgmai.github.io/DicomViewer-Support/privacy.html`
- `https://chenttgmai.github.io/DicomViewer-Support/support.html`
- `https://chenttgmai.github.io/DicomViewer-Support/` redirects to the support page.

Before deployment:

1. Confirm `tingting chen` is the exact public developer name for the submitting account.
2. Have the privacy policy reviewed for the release regions. It describes the current local-only binary and must change if accounts, cloud sync, analytics, crash-report uploads, advertising, or support-file uploads are added.
3. Serve both pages without login, geoblocking, cookie walls, or client-side rendering. App Review must be able to open them directly.
4. Keep the site free of analytics, advertising pixels, remote fonts, and third-party scripts unless the website has its own accurate disclosure and consent handling.
5. Check every link on a signed-out phone and desktop before uploading metadata. The URLs are not valid until this site is deployed.

The pages have no external assets or scripts and work on a basic static host. Update the visible “Last updated” date whenever the policy changes.
