# arc-action-runner

[actions/runner](https://github.com/actions/runner) image for [Actions Runner Controller](https://github.com/actions/actions-runner-controller), built from each upstream release with the patches in `patches/`.

- `results-url.patch`: use `CUSTOM_ACTIONS_RESULTS_URL` as `ACTIONS_RESULTS_URL` when set.
- `disable-update.patch`: skip runner self-update when `CUSTOM_ACTIONS_RESULTS_URL` is set.

Images: `ghcr.io/neko-sc/arc-action-runner:vX.Y.Z` and `:latest`.
