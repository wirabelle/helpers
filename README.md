# Helpers

## Docker
Install Symfony
```bash
docker run --rm -v $(pwd):/app composer create-project symfony/skeleton:"6.*" . --prefer-dist --no-interaction
```

Run PHP
```bash
docker run -v $PWD:/app/public -p 80:80 -p 443:443 dunglas/frankenphp
```
