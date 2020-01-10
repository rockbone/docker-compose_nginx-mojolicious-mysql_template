# Description

Setup Nginx+Mojolicious+uWSGI+MySQL for development purpose with docker-compose.

# USAGE

    # create mojolicious app
    docker-compose run perl mojo generate app app

    # boot up docker
    docker-compose up -d

    # check site
    http://localhost:8000/
