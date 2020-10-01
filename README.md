# actions
This is a repository for me to make new github action workflows. Eventually
I want to make this into a framework that can automatically install actions
into an existing project. For now this is achieved manually by copy-pasting code.

## Auto label PR based on files changed
This workflow will label a PR with labels defined inside `.github/labeler.yml`

It runs the workflow `.github/workflows/label-pr-by-files-changed.yml`

## Auto label PR based on branch name
This workflow will label a PR with labels defined inside `.github/label-by-branch-name.yml`.

It runs the workflow `.github/workflows/label-pr-by-branch-name.yml`

## Backmerge from master after releases
This workflow will perform a back-merge from `master` to `staging` to `edge`
when a pull request to master is merged in.

It runs the workflow `.github/workflows/post-release.yml`
