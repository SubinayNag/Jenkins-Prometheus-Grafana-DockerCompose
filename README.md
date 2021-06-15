# Jenkins-Prometheus-Grafana-DockerCompose
Docker Compose to Integrate Prometheus &amp;&amp; Grafana with Jenkins 

Commands:

If running on local maching:

Jenkins: http://localhost:8080/
Prometheus: http://localhost:9090/
Grafana: http://localhost:3000/

Grafana Configuration:
  Adding datasource as prometheus URL: http://prometheus-service:9090
  
Run Docker Compose:
  docker-compose docker-compose.yml up -d
