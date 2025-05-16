# easy-portainer

Easily startup a [**Portainer CE**](https://docs.portainer.io/start/install-ce/server/docker/linux) container with [**Docker Compose**](https://docs.docker.com/compose/).

## Usage

1. Create a file named `.env` with your custom configurations:

    ```sh
    PORT_HTTPS=9443 # optional, defaults to "9443"
    PORT_TUNNEL=8000 # optional, defaults to "8000"
    PATH_DOCKER_SOCK=/var/run/docker.sock # optional, defaults to "/var/run/docker.sock"
    ```

2. Start:

    ```sh
    docker-compose up -d
    ```

## License

[MIT](./LICENSE) License &copy; 2025-PRESENT [mys1024](https://github.com/mys1024)
