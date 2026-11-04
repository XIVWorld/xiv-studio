# Public demo boundaries

## Artifact

Deploy only `index.html` from the reviewed commit. No private repository is a deployment source. No Git history, uploads, environment files, backend, migrations or operational assets are copied.

The page is independently authored. Service names describe generic creative workflows; prices and slots are invented. State exists only in browser memory. No personal information is requested.

## Runtime

- No dependencies, build scripts, environment variables, API keys or database.
- No authentication, checkout, calendar, email, AI, webhooks, analytics or uploads.
- CSP blocks connections, external resources and form submission.
- Simulate booking only updates visible text; reset returns controls to defaults.

## Deployment proposal — approval required

Use static hosting for a separate demo site, without custom production domains, inherited environment variables, repository integrations, functions or shared storage. GitHub Pages could serve a reviewed static artifact; a separate static hosting project could also do so. Provider setup, current terms and account boundaries have not yet been verified. Do not enable automatic deployment before approval.

Required confirmation: exact hosting account/project, reviewed commit, published file allowlist (`index.html`), zero secrets/integrations/storage, and an independent demo URL. Verify the deployed page and browser requests before advertising the URL. No deployment workflow is included.

## Review limits

Source review covers this new artifact. Repository inventory and selected documentation were inspected, not a comprehensive audit of all private code, Git history, credential validity or database policies. Private app code and files must remain private. A demo label in an existing app is not proof of isolation.
