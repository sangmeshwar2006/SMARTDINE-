# Deployment Checklist

Use this checklist when the application code is added. A repository containing only planning documents cannot be deployed as a working SMARTDINE app.

## Before deploying

- [ ] Confirm the initial user flow and supported devices.
- [ ] Add the application source and document local setup commands.
- [ ] Add the production build command and verify it completes from a clean install.
- [ ] Add automated checks for the important user flows.
- [ ] Store secrets in the hosting provider's environment settings; do not commit them.
- [ ] Configure production data and any required migrations.
- [ ] Add a health check or smoke test for the deployed site.

## After deploying

- [ ] Open the production URL on desktop and mobile sizes.
- [ ] Verify navigation, menu browsing, and the chosen ordering flow.
- [ ] Check browser console and hosting logs for errors.
- [ ] Confirm the previous version can be restored if the release has a problem.
