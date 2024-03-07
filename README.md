# Node.js PostgreSQL with docker compose
## step to run application

clone this repositoty
1. init postgresql `docker compose up postgres-db -d`
2. init all apps `docker compose up -d`
3. mapping hosts file `vi /etc/hosts`
4. add `127.0.0.1 nodejs.local` line to /etc/hosts
4. testing app by open  `http://nodejs.local/api/tutorials`

p.s node-js can read environment variable in docker-compose file