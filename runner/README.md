# How to build?
`NOTE: Update [RUNNER_VERSION](https://github.com/actions/runner/releases) to appropriate value in the dockerfile before building`
```docker build -t airbase/action-runner-dind-rootless . -f actions-runner-dind-rootless.ubuntu-22.04.dockerfile --build-arg TARGETPLATFORM="linux/x86_64"```