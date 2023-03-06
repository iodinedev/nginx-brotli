# nginx-brotli
This is a simple docker container for building a version of Nginx that compresses almost all web resources with Brotli compression by default. You can use it exactly the same way you use the official `nginx:latest` image.

### Build and Run
```sh
docker build . -t nginx-brotli
docker run --name nginx-brotli -dit nginx-brotli
```
