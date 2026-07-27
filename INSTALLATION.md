# Installation

This package is prepared for the GitHub profile repository:

`davidsanchez0440/davidsanchez0440`

## Files to upload

Copy these paths exactly into the repository:

- `README.md`
- `assets/header-dark.svg`
- `assets/header-light.svg`
- `.github/workflows/contribution-snake.yml`

The contribution SVG files are generated automatically by GitHub Actions and do not need to be created manually.

## Activate the contribution animation

1. Open the profile repository on GitHub.
2. Go to **Settings → Actions → General**.
3. Under **Workflow permissions**, select **Read and write permissions** and save.
4. Open **Actions → Generate contribution snake**.
5. Select **Run workflow** once.

After the first successful run, these files will be added automatically:

- `assets/github-contribution-grid-snake.svg`
- `assets/github-contribution-grid-snake-dark.svg`

The workflow refreshes the animation every day and also supports manual execution.
