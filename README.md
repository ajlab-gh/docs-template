# docs-template

**Welcome!**

This MkDocs project uses GitHub Actions to automate the build and
deployment of our documentation. Here's an overview of the workflow:

**Workflow:**

Our workflow consists of five stages:

1. **Checkout Repository**: The latest version of our repository is
checked out using the `actions/checkout` action.
2. **Configure GitHub Pages**: This stage sets up GitHub Pages to deploy
our documentation.
3. **Install Python and MkDocs software**: Python 3.x is installed,
followed by a list of MkDocs plugins required for building and deploying
our documentation.
4. **Build Docs**: The `mkdocs gh-deploy` command is run to build and
deploy our documentation to GitHub Pages.
5. **Triggering the workflow:**
The workflow is triggered automatically whenever changes are pushed to the
`main` branch or when a pull request is created. This ensures that our
documentation is always up-to-date and reflects the latest changes in our
codebase.

**Concurrent builds:**
To ensure that only one build is running at a time, we use GitHub Actions'
concurrency feature. If multiple pushes occur simultaneously, the workflow
will wait for the previous build to complete before starting a new one.

**Permissions:**
The workflow has write permissions to the `contents`, `pages`, and
`id-token` of our repository, allowing it to create and update files as
needed.

By using GitHub Actions to automate our documentation build and deployment
process, we can ensure that our documentation is always up-to-date,
reliable, and easily accessible.

```bash
pre-commit install
```
