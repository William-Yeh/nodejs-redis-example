nodejs-redis-example
===

A simple web server (written in Node.js) that generates dyanmic content based on responses from Redis.

Adapted from: https://github.com/mranney/node_redis/blob/master/examples/web_server.js


## Usage

1. Install used modules:

   ```
   npm install
   ```

2. Start the program:

   ```
   npm start
   ```


## Configuration

- `PORT`: application sevrice port; default = `3000`

- `REDIS_HOST`: address of Redis server; default = `127.0.0.1`

- `REDIS_PORT`: TCP port of Redis server; default = `6379`
