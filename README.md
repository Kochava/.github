# .github

## Workflows

The `workflow-templates` directory contains importable workflows per https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization

### Make / Go Test

The workflow `workflow-templates/make-go-test.yml` sets up a Golang environment and runs `make test` for pull requests.

### Go Test

This workflow `workflow-templates/go-test.yml` sets up a Golang environment and runs `go test ./...` for pull requests.

## Credit

- `./workflow-templates/gopher-front.svg` is used under [Creative Commons 3.0 Attributions license](https://creativecommons.org/licenses/by/3.0/legalcode) and its source can be found at https://github.com/golang-samples/gopher-vector