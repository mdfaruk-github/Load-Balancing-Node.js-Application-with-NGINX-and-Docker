A node js application is dockerised in 8085 and 8086 port.

nginx load balancer is dockerised in 8080 port. 

http://localhost:8080/api/v1/internal

When I hit the above URL it routes to 8085 or 8086 port based on round robin algorithm.
