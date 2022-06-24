This repo drafts the idea of github release assets support for renovate (https://github.com/renovatebot/renovate/discussions/16209)

- the project uses tekton pipelines by including the file https://github.com/tektoncd/pipeline/releases/download/v0.36.0/release.yaml which is a Github Release Asset.
- The project currently uses version 0.36.0, however a new release already exists (https://github.com/tektoncd/pipeline/releases/download/v0.37.0/release.yaml)
- Renovate suggests the update with https://github.com/Fabian-K/renovate-github-release-asset-demo/pull/1 