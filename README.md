# actions

This is a repository for me to make new github action workflows. Eventually
I want to make this into a framework that can automatically install actions
into an existing project. For now this is achieved manually by copy-pasting code.

## Table of Contents

1. [Greetings](#greetings)
2. [Label PR based on files changed](#label-PR-based-on-files-changed)
3. [Label PR based on branch name](#label-PR-based-on-branch-name)
4. [Backmerge from master after releases](#backmerge-from-master-after-releases)

### Greetings
[This workflow](https://github.com/codenameyau/actions/blob/master/.github/workflows/greetings.yml)
will post a github comment to a pull request or issue
when someone posts a pull request or issue for the first time.

### Label PR based on files changed

[This workflow](https://github.com/codenameyau/actions/blob/master/.github/workflows/label-pr-by-files-changed.yml)
will label a PR with labels defined inside `.github/labeler.yml`

### Label PR based on branch name

[This workflow](https://github.com/codenameyau/actions/blob/master/.github/workflows/label-pr-by-branch-name.yml)
will label a PR with labels defined inside `.github/label-by-branch-name.yml`.

### Backmerge from master after releases

[This workflow](https://github.com/codenameyau/actions/blob/master/.github/workflows/post-release.yml)
will perform a back-merge from `master` to `staging` to `edge`
when a pull request to master is merged in.
