

## Commands ✈️

### FORK
pm2 start ./NodeServer/server.js --name="ServerStandar" --watch -- 8080
### CLUSTER
pm2 start ./NodeServer/server.js --name="MyCluster" --watch -i max -- 8081
### FORK
pm2 start ./NodeServer/server.js --name="Server1" --watch -- 8082
pm2 start ./NodeServer/server.js --name="Server2" --watch -- 8083 
pm2 start ./NodeServer/server.js --name="Server3" --watch -- 8084 
pm2 start ./NodeServer/server.js --name="Server4" --watch -- 8085 

---

