GLA Demo App
==================

This is an example Docker app with multiple services based on the example-voting-app provided by Docker itself: https://blog.docker.com/2015/11/docker-toolbox-compose/

Architecture
-----

* A Python webapp which lets you vote between two options
* A Redis queue which collects new votes
* A Java worker which consumes votes and stores them in…
* A Postgres database backed by a Docker volume
* A Node.js webapp which shows the results of the voting in real time