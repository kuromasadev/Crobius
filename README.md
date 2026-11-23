# Publish the Crobius Atlas

1. In your GitHub repository, choose **Settings → Pages → Build and deployment → Source → GitHub Actions**.
2. Commit `site/index.html` and `.github/workflows/deploy-pages.yml` to `main` with their paths intact. If the workflow is already committed, run **Publish Crobius Atlas** from the **Actions** tab.
3. Open the deployment URL under **Settings → Pages** or in the completed workflow run.

For future updates, replace `site/index.html` with the new atlas HTML and push to `main`. If your deploy branch has a different name, update `branches` in the workflow.

This workflow publishes the entire `site` directory as the repository’s GitHub Pages site. The packaged atlas contains the embedded map data and is intended to be shared with the site's audience.
