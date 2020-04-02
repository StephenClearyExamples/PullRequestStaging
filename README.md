# PullRequestStaging

A sample repository showing how GitHub Actions can be used to provide per-PR staging environments.

## How to use

1. Create a fork of this repository.
1. Change a file in your fork. `src/pages/index.js` is a great one to test out.
1. Submit a pull request back to this repository.
1. After your pull request is created, write a comment on the pull request with the first line being `/deploy`
1. Wait a minute or so. GitHub should create a staging environment for your pull request and publish it automagically!
1. When you're done playing, write a comment on the pull request with the first line being `/teardown`