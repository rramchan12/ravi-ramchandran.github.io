# ravi-ramchandran.github.io


Notes:
- This is a user site repository (named `username.github.io`) so GitHub Pages will serve content from the root of the `main` branch.
- The included workflow ensures the site is built and deployed automatically when you push to `main`.

## Updated for artifact action deprecation

The Pages workflow has been updated to avoid using deprecated artifact actions. Specifically, the workflow now uses `actions/upload-pages-artifact@v2` which depends on the newer artifact implementation instead of `actions/upload-artifact@v3`.

See the GitHub changelog for details and migration guidance:
<https://github.blog/changelog/2024-04-16-deprecation-notice-v3-of-the-artifact-actions/>

You can re-trigger the workflow by pushing to `main` or using the Actions UI to re-run the Pages workflow.
