# Other worthy mention web installer

- [Docker CE for Linux installation script](#docker-ce-for-linux-installation-script)
- [Getting started with Laravel using Docker](#getting-started-with-laravel-using-docker)

---

## Docker CE for Linux installation script

> NOTE: Make sure to verify the contents of the script you downloaded matches the contents of `install.sh` located at https://github.com/docker/docker-install before executing.

**Usage**
```sh
# This script is meant for quick & easy install via:
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh

# For test builds (ie. release candidates):
curl -fsSL https://test.docker.com -o test-docker.sh
sh test-docker.sh
```

## Getting started with Laravel using Docker

**Usage**
```sh
curl -s "https://laravel.build/example-app" | bash
```

See [Laravel & Docker](https://laravel.com/docs/9.x#laravel-and-docker) for more informations.
