artillery quick --count 50 -n 20 http://localhost:8080/info > result_fork.txt

node --prof server.js
curl -X GET "http://localhost:8080/info"

artillery quick --count 50 -n 20 "http://localhost:8080/info" > result_nonbloq.txt
