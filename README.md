# rabbitmq-demo

## Initial

open terminal and run `docker-compose up -d` for start rabbitmq services

## "Hello World"

simple

- run `node hello_world/send.js`
- run `node hello_world/receive.js`

## Work Queue

- run `node work_queue/worker.js` many node
- run `node work_queue/new_task.js`

## Pub / Sub

- run `node pubsub/receive_log.js`
- run `node pubsub/emit_log.js`

## Reference

- <https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/javascript-nodejs/src>