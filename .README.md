## CI/CD Workflows

A minimal collection of GitHub Actions workflows for getting started with CI/CD.

### Overview
- **Workflows location**: `.github/workflows/`
- **Default trigger**: Push events to the repository

### Included Workflows
- **first-workflow.yaml**: Demonstrates a simple job that prints a message and checks out the repository on `ubuntu-latest`.

### Prerequisites
- A GitHub repository with Actions enabled
- Permission to push changes and view Actions runs

### Quick Start
1. Ensure the workflow files are committed under `.github/workflows/`.
2. Push to any branch to trigger the workflow.
3. Visit the repository’s Actions tab to view run logs.

### Common Commands
To push changes and trigger workflows:

```bash
git add -A
git commit -m "Add/Update workflows"
git push origin <your-branch>
```

### Customize
- Edit triggers under the `on:` section of each workflow (e.g., `push`, `pull_request`, `schedule`).
- Add steps/jobs as needed. See the GitHub Actions marketplace for reusable actions.

### Troubleshooting
- If a workflow does not run, confirm the file path is `.github/workflows/<name>.yaml` and that the branch you pushed is not restricted by `on:` filters.
- Check the Actions tab logs for failure details.

### Contributing
Open a pull request with clear descriptions of changes to workflows or documentation.

### License
MIT (or your repository’s chosen license)

