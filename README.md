# Hey Spot — GitHub Pages website

These are standalone static files. No build, installation, API keys, or paid domain is needed. The support form uses the existing Formspree endpoint and does not expose the recipient email.

## Publish

1. Create a public GitHub repository, for example `heyspot-support`.
2. Upload `index.html`, `privacy.html`, and `.nojekyll` into the repository root. Upload the extracted files, not the ZIP or its containing folder. If the hidden `.nojekyll` file is not visible, the two HTML files still work with GitHub Pages.
3. Open repository Settings → Pages.
4. Under Build and deployment, select Deploy from a branch, branch `main`, folder `/ (root)`, and Save.
5. Wait for the Pages deployment to succeed and use the URL GitHub displays.

For a repository named heyspot-support, the usual URLs are:
- Support: https://YOUR-USERNAME.github.io/heyspot-support/
- Privacy: https://YOUR-USERNAME.github.io/heyspot-support/privacy.html

These are examples, not live URLs. Replace YOUR-USERNAME and the repository name with your actual values. Use the published Pages URL, not github.com repository or raw-file URLs.

## Check before App Store submission

Open both pages in a signed-out/private browser window. Check navigation and submit one support test to verify receipt in Formspree/email. These files preserve the existing form endpoint; no test message was sent while preparing this package.

Paste the published privacy URL into App Store Connect → App Privacy → Privacy Policy URL. Paste the homepage URL into the Support URL field. Keep the privacy policy accessible in the app and consistent with actual practices. Review the separate App Privacy questionnaire, including feedback submissions; publishing a policy does not complete that questionnaire.

The policy describes the current implementation, including optional weather and feedback. Review it whenever app behavior, providers, or retention practices change. Keep the old hosted pages available until all links have been updated.
