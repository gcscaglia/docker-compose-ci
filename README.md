# compose-ci

This is a simple image based on [docker-compose][1] for use in CI.

It's main purpose is to [remove the image entrypoint][2] and install utilities such as git and bash.

[1]: https://hub.docker.com/r/docker/compose/
[2]: https://gitlab.com/gitlab-org/gitlab-ci-multi-runner/issues/1421
