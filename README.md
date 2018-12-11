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

## Topics

\* (star) can substitute for exactly one word.

\# (hash) can substitute for zero or more words.

- run `node topics/receive_log_topic.js "#"` to receive all the logs
- run `node topics/receive_log_topic.js "kern.*" "*.critical"`
- run `node topics/emit_log_topic.js "kern.critical" "A critical kernel error"` to emit a log with a routing key "kern.critical" type

- run `node rpc/server.js`
- run `node rpc/client.js 5`
- run `node rpc/client.js 8`

## Reference

- <https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/javascript-nodejs/src>