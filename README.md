# perf_docker_redis

docker build -t image_redis:v1 .
docker run -d --name redis -p 6379:6379 image_redis:v1
