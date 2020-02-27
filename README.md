# Product-api

## how to test:
  ### Start server
  go run main.og
  
  ### Client
  curl -v localhost:9090 |jq

  curl -v localhost:9090/1 -XPOST -d '{"id": 1, "name": "tae", "description": "a nice tea"}' |jq

  curl -v localhost:9090/1 -XPUT -d '{"name": "tae", "description": "a nice tea"}' |jq
