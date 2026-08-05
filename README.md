# repo-template

Starting point for new **Vev-software** repositories. Create a new repo with the
green **“Use this template”** button (or `gh repo create <name> --template Vev-software/repo-template`)
so nothing standard gets forgotten.

## What you get

- **`.github/workflows/add-to-project.yml`** — automatically adds every new /
  reopened / transferred issue to the org Project board
  ([#1](https://github.com/orgs/Vev-software/projects/1)). This is the piece that
  is easy to forget when scaffolding a repo by hand.
- **`.gitignore`** — sensible defaults.
- **`LICENSE`** — replace the copyright holder/year as needed.

## After creating a repo from this template

1. Replace this README with the real project README.
2. Confirm the org secret **`ADD_TO_PROJECT_PAT`** is available to the repo
   (Settings → Secrets and variables → Actions). It is org-wide, so normally it
   already is — the workflow needs it because the default `GITHUB_TOKEN` cannot
   write to Projects v2.
3. Open a throwaway issue and confirm it lands on the board, then close it.
