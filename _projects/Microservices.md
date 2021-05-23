---
name: Design & Implement Microservice architecture
tools: [Java, SpringBoot, Node JS, Kubernetes, Docker, GitHub, NoSQL(Mongo DB), SQL (Postgres, MySQL), In-Memory(Redis, Memcached), Apache Kafka, Apache Solr, Tomcat/Jetty ]
image: https://raw.githubusercontent.com/ditac/ditac.github.io/master/assets/ms_arch.png
---

I worked with a group of architects to design and implement microservices ecosystem and then migrate existing monolithic services to microservices.

We had developed a microservice framework(similar to SpringBoot) customized to project requirements. We have developed modules like Security, 
Http Requests, Mongo initialization, Kafka, analytics module, logging module, bootstrap module and many other modules.  

Some interesting features that I would like highlight are -
1.  we have built the microservice framework in Java, Node JS & DotNET(my contributions are in Java & Node JS). 
2.  Successfully migrated the legacy monolithic services by building ~200 microservices.
3.  We leveraged Apache Kafka as the Distributed Messaging system. 
4.  Implemented ELK for App logs and customized pipeline to App performance level data to store in Apache solr and dashboards in Grafana. 
5.  using Mongo DB as a primary database. 
6.   using Memcached as an In-Memory DB
7.  Networking design and integration with the load-balancer/reverse proxy(HA Proxy & Traefik).
8.  Designed and built centralized security service which is capable of handling more than 10M of requests per hour(easily scalable).
4.  Infrastructure provisioning - docker/Kubernetes for container images and container orchestration platform.
    etc.

