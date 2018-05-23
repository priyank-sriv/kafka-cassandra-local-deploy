## Deploy kafka and cassandra (standalone/clustered) locally using docker-compose
  
#### Pre-reqs
  -  Tested on macOS 10.13.3
  -  Docker 18.02.0+, Docker compose file version 3.6

#### Modes
  - 1 cassandra node, 1 kafka broker
  - 1 cassandra node, 1 kafka broker with topics ui

  todo (caution - configure higher memory in docker-machine as no. of nodes):
  - 1 cassandra node, 3 kafka brokers with topics ui
  - 3 cassandra nodes, 3 kafka brokers with topics ui
