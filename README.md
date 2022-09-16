This repo demonstrates an issue with the [check-dependency-version-consistency](https://github.com/bmish/check-dependency-version-consistency) tool in a yarn workspace which uses globs for packages and also has no-hoist enabled.

### How to recreate
- run `yarn install`
- run `yarn check-dependencies`

