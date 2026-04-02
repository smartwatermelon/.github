# .github

Organization-level defaults for smartwatermelon repositories.

## What's included

- **`.github/FUNDING.yml`** — Inherited by all repos that don't have their own FUNDING.yml
- **`workflow-templates/claude-blocking-review.yml`** — Available as a workflow template in the Actions tab when creating new workflows

## Usage

### FUNDING.yml
Automatically inherited. No action needed for new repos.

### Claude Blocking Review
When creating a new repo:
1. Go to Actions tab
2. Click "New workflow"
3. Find "Claude Blocking Review" under organization templates
4. Click "Configure"
5. Commit the workflow file
6. Ensure `CLAUDE_CODE_OAUTH_TOKEN` secret is set
