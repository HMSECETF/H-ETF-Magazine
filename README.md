# H ETF Magazine — October 2026

Official project files for H ETF Magazine Vol.10.

## Publish website

1. In the GitHub repository, choose **Add file → Upload files**.
2. Extract `H_ETF_Magazine_10월호_웹사이트_2파일.zip` and upload **both** `index.html` and `magazine.pdf` into the repository root (not the ZIP itself).
3. Commit to `main`.
4. Open **Settings → Pages → Build and deployment → Deploy from a branch**. Select `main`, folder `/ (root)`, and save.
5. Verify the website at `https://hmsecetf.github.io/H-ETF-Magazine/` after GitHub Pages publishes the deployment.

### Analytics

A static GitHub Pages site cannot securely store global view counts and button-click counts by itself. To activate centralized PDF-open/MTS-click counters, configure the included optional Cloudflare Worker + D1 backend in the source package, check collection and privacy notices, and set the actual worker URL in the HTML. The UI must not present local-only click counts as total customer counts.

### Mobile trading

MTS deep links should be verified on real Android and iOS devices. No unverified purchase or trading URL should be advertised as a working deep link.
