-- Build a Python Flask Image --

We built a Python Flask Image. We also saw how the `WORKDIR` option in the Dockerfile can allow us to set a working directory for the container. This ensures that following commands like `COPY` or `CMD` are set in the context of that working directory.

Here’s the completed project:
https://github.com/btolan-karudev/dockerFlask

After cloning the project, build and run the container:
 - `docker build . -t docker/flask`
- `docker run --name=flask -p=3004:80 docker/flask`
