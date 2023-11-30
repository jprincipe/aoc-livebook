# AOC 2023 - Livebook

### Start
docker run -p 8080:8080 -p 8081:8081 --pull always -u $(id -u):$(id -g) -v $(pwd):/data ghcr.io/livebook-dev/livebook

### Setup
create new secret called AOC_SECRET with the cookie value from AOC website
