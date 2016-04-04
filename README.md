# docker-composer-alpine

Dockerized composer image with [hirak/prestissimo](https://github.com/hirak/prestissimo) based on [Alpine Linux](http://www.alpinelinux.org/).

DockerHub repository is [here](https://hub.docker.com/r/shufo/composer-alpine/).

## Usage

```bash
# Install composer dependencies
docker run -it --rm -v $(pwd):/app shufo/composer-alpine install
# Update composer dependencies
docker run -it --rm -v $(pwd):/app shufo/composer-alpine update
```
