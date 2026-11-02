# diluxone-test

The engine's test repository. Nothing here is a product.

Before `v7` moves to a new version of [DiluxOne/.github](https://github.com/DiluxOne/.github), the release lane points the lightweight tag `v7-next` at the candidate and plays every scenario in [`tests/release/scenarios.yml`](https://github.com/DiluxOne/.github/blob/main/tests/release/scenarios.yml) here: it opens the issues and pull requests each one names, checks that the flow does what it says, and cleans up after itself. Only when every scenario passes does the release go out ([`docs/versioning.md`](https://github.com/DiluxOne/.github/blob/main/docs/versioning.md)).

Its issues and pull requests come and go with each run; do not open your own here.
