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

## Routing

- run `node routing/receive_log_direct.js info error warning`
- run `node routing/emit_log_direct.js warning`
- run `node routing/emit_log_direct.js info`

## Reference

- <https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/javascript-nodejs/src>