# Spring Boot 3 Observability with Grafana Stack

- This project contains the source code for the Youtube demo [Spring Boot 3 Observability with Grafana Stack](https://youtu.be/PT2yZTBnUwQ?feature=shared) video.
- It corresponds also to the tuto [Spring Boot 3 Observability with Grafana Stack](https://programmingtechie.com/2023/09/09/spring-boot3-observability-grafana-stack/)

## Github repo
https://github.com/SaiUpadhyayula/springboot3-observablity/blob/master/docker-compose.yml

We may also run below command:
```sh
$ git remote get-url origin
```

## Running the project

To run the project, you need to have Docker and Docker Compose installed. Then, run the following command:

```docker compose up -d```

Run Loan Service Application

```cd loan-service```

```mvn spring-boot:run```

Run Fraud Detection Service Application

```cd fraud-detection-service```

```mvn spring-boot:run```


## Accessing the services
1. Grafana: http://localhost:3000
2. Prometheus: http://localhost:9090
3. Tempo: http://localhost:3110
4. Loki: http://localhost:3100

## Project Overview

![img.png](img.png)
