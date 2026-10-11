# Mission 7 Reflection

In this laboratory activity I learned that checking the host servers resources is important when containers are running properly. A server may have limited memory, disk space or CPU capacity which can affect the performance of applications. Monitoring these resources helps cloud engineers identify problems before they affect users.

The `docker logs` command is useful when a user reports that they cannot log into a web application. By checking the logs an engineer can look for errors failed requests and other information that may help identify the cause of the problem. Logs provide details about events that happen inside the application making troubleshooting easier.

I also learned the difference between logs and metrics. Logs record events and requests including failed responses. Metrics provide measurements such as CPU usage, memory consumption and network activity. Both are important because logs help explain what happened while metrics help show how the system is performing.

Large enterprise companies may use monitoring tools such as Prometheus and Grafana to monitor thousands of containers. Prometheus can. Store metrics, while Grafana can display them through dashboards. These tools help teams monitor system health and identify behavior across many services.

My ability to troubleshoot Linux environments has improved because I practiced commands such, as `free -h` `df -h /` ` `docker logs` and `docker stats`. I learned how to deploy a web server generate HTTP requests and intentionally produce a 404 error. Overall this mission helped me understand that cloud operations involve not deploying applications but also monitoring their health investigating problems and maintaining reliable services.
