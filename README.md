# Hermes Storage System
hermes storage system as presented in IEEE Big Data 2023 Workshop.

WIP
## Setup
Test environment characteristics, presented to facilitate the reproducibility of the experiments.
### Docker images
| Service         | Image                     | Ver    |
|-----------------|---------------------------|--------|
| MongoDB         | mongo                     | 5      |
| Apache Kafka    | confluentinc/cp-kafka     | 6.0.14 |
| Apache Zookeper | confluentinc/cp-zookeeper | 6.0.14 |

### Microservices specification
| Major dependency                | Hermes         | Client producer |
|---------------------------------|----------------|-----------------|
| org.springframework.boot        | 2.7.5          | 2.7.5           |
| io.spring.dependency-management | 1.0.15.RELEASE | 1.0.15.RELEASE  |
| kotlin                          | 1.6.21         | 1.6.21          |
| Resource allocation             |                |                 |
| Reserved RAM                    | 16GB           | 12GB            |

### Testbed server
| Element             | Detail                                    |
|---------------------|-------------------------------------------|
| docker engine       | 20.10.7                                   |
| docker compose      | 1.27.4                                    |
| docker compose file | 3.9                                       |
| operating system    | Ubuntu 18.04.5 LTS                        |
| CPU                 | Intel(R) Xeon(R) CPU E5-1630 v3 @ 3.70GHz |
| RAM                 | 62.8GB                                    |
