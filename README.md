# Privacy Page Project

This project hosts a privacy policy page for PoornaPrana. It includes the necessary HTML files and a GitHub Actions workflow for automatic deployment to GitHub Pages.

## Project Structure

- `privacy.html`: Contains the privacy policy content formatted in HTML. This file is intended to be served as a standalone page.
- `index.html`: The main entry point for the website, which may contain links to other pages, including the privacy policy.
- `docs/privacy.html`: A duplicate of `privacy.html`, used for documentation purposes or as part of the GitHub Pages structure.
- `.github/workflows/deploy-pages.yml`: GitHub Actions workflow configuration for deploying the project to GitHub Pages.

## Hosting on GitHub Pages

To host this project on GitHub Pages, follow these steps:

1. **Create a GitHub Repository**: If you haven't already, create a new repository on GitHub.

2. **Push Your Code**: Push your project files to the repository. Make sure to include all the files listed above.

3. **Configure GitHub Pages**:
   - Go to the repository on GitHub.
   - Click on the "Settings" tab.
   - Scroll down to the "Pages" section.
   - Under "Source", select the branch you want to use (usually `main` or `master`) and the folder (root or `/docs` if you are using the `docs` folder).
   - Click "Save".

4. **Deploy with GitHub Actions**: The `.github/workflows/deploy-pages.yml` file is configured to automatically deploy your site to GitHub Pages whenever you push changes to the repository. Ensure that the workflow is enabled.

5. **Access Your Site**: After a few minutes, your site should be live at `https://<your-username>.github.io/<your-repo-name>/`. You can access the privacy policy at `https://<your-username>.github.io/<your-repo-name>/privacy.html`.

## Contact

For any questions or issues, please reach out via the contact options provided in the privacy policy.