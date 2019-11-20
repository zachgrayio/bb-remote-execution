# bb_scheduler

## Running locally with config

Our variant of this workspace lives next to a number of other repos in a monorepo and as such has access to our modified branches of each BB workspace.

To invoke this program locally against our modified config, use the following command:

```bash
bazel run //cmd/bb_scheduler:bb_scheduler -- external/com_github_buildbarn_bb_deployments/bare/config/bb-scheduler.json
```
