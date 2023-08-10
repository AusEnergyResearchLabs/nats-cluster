# Upstreaming Details

This repo is downstream from [`fly-apps/nats-cluster`](https://github.com/fly-apps/nats-cluster) but not directly as we do not want to upstream 100% of our changes.

The `upstream` branch tracks `main` from upstream (although manually) so we can merge in their changes as needed.

Not all of our changes on `main` will be fit for being contributed back to upstream. What's best is to create a new branch from `upstream` and cherry-pick the commits you want to contribute back.
