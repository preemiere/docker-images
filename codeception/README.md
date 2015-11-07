# Codeception

> Modern PHP testing for everyone. 
> http://codeception.com/

```bash
docker run -i \
    --rm \
    --name codeception \
    -v "$PWD":/app \
    -w /app \
    preemiere/codeception $@
```

## Quick install

```bash
git clone https://github.com/preemiere/docker-images.git && sudo ./docker-images/codeception/install.sh
```

# Usage
After quick install, move to project dir then type command you need
```bash
codecept --help
```

### Get this image
[Docker Hub Registry](https://hub.docker.com/r/preemiere/codeception/).