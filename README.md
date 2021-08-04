# .github

## Workflows

The `workflow-templates` directory contains importable workflows per https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization

### Make / Go Test

The workflow `workflow-templates/make-go-test.yml` sets up a Golang environment and runs `make test` for pull requests.

### Go Test

This workflow `workflow-templates/go-test.yml` sets up a Golang environment and runs `go test ./...` for pull requests.

## Credit

- `./workflow-templates/gopher-front.svg` is used under [Creative Commons 3.0 Attributions license](https://creativecommons.org/licenses/by/3.0/legalcode) and its source can be found at https://github.com/golang-samples/gopher-vector

## Default Branch

As of October 1, 2020, github.com uses the branch name ‘main’ when creating the initial default branch for all new repositories.  In order to minimize any customizations in our github usage and to support consistent naming conventions, we have made the decision to rename the ‘master’ branch to be called ‘main’ in all Kochava’s github repos.

For local copies of the repo, the following steps will update to the new default branch:

```
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```
