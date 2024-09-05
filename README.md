# Task Runner Images

This repository contains base images for task runners. 

> [!NOTE]
>
> The `task-runner` image is used for issuing "one off" commands or running small maintenance tasks etc., so it should be useless to most people. Outdated by nature because it's running legacy tasks.
>

# Available Images

| Image        | Tag                             | Software                                                        |
| ------------ | ------------------------------- | --------------------------------------------------------------- |
| Ubuntu 24.04 | [`ubuntu`](./ubuntu/Dockerfile) | See [Installed packages](./ubuntu/README.md#installed-packages) |

See [GitHub Packages](https://github.com/orgs/system4-tech/packages?repo_name=task-runner-images).

# Usage

```sh
$ docker run -it --rm ghcr.io/system4-tech/task-runner:ubuntu
```
