# Dockerized Web Server with Nginx, PHP, MySQL, and phpMyAdmin

This is a Dockerized web server setup consisting of Nginx, PHP, MySQL, and phpMyAdmin.

## Getting Started

To get started, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Update the `docker-compose.yml` file with your desired configuration and credentials.
4. Build and start the containers using Docker Compose:

    ```bash
    docker-compose up -d
    ```

5. Access your web server at [http://localhost](http://localhost) and phpMyAdmin at [http://localhost:8080](http://localhost:8080).
6. You can stop the containers using:

    ```bash
    docker-compose down
    ```

## Configuration

### Nginx

Nginx configuration can be found in the `nginx/nginx.conf` file. Modify this file to customize your Nginx server settings.

### PHP

For PHP configurations, including extensions and PHP version, modify the `php/Dockerfile`.

### MySQL

MySQL configurations, including database name, user, and password, can be set in the `docker-compose.yml` file under the `mysql` service.

### phpMyAdmin

phpMyAdmin configuration can be found in the `docker-compose.yml` file. You can customize the phpMyAdmin container settings here.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
