# SKELETON-PHP READY FOR CI(DOCKER+TRAVIS)

This is the skeleton of the project which may be used with docker, travis and kubernetes.

### About containers:

**php-fpm:** Use php7 with fpm and has also installed amqp, pdo etc.

**nginx:** Use latest version of nginx

### Before start

1. Remember to copy .env.dist file to .env file
    ```
    cp .env.dist .env
    ```
 
2. Edit var NGINX_HOST - default settings:

    ```
    NGINX_HOST=backend_template.local
    ```

3. Add host to your /etc/hosts
    ```
    sudo bash -c "echo 127.0.0.1 backend_template.local >> /etc/hosts"
    ```
    
## Local development
 
1. Run docker-compose 
    ```
    docker-compose up
    ```

2. Run in your browser

<http://backend_template.local:8087/index.php>
