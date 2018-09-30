# Docker Resources for WSO2 Integration

This repository contains following Docker resources :

- WSO2 Enterprise Integrator Docker resources for Alpine, CentOS and Ubuntu
- Docker Compose resources to evaluate most common Integration deployment profiles

Per profile Docker resources for WSO2 Enterprise Integrator help you build generic Docker images for deploying the
corresponding product servers in containerized environments. Each Docker image includes the JDK, the relevant product distribution
and a collection of utility libraries. Configurations, custom JDBC drivers other than the default MySQL JDBC driver provided,
extensions and other deployable artifacts are designed to be provided via volume mounts to the containers spawned.

Docker Compose files have been created according to the most common Integration deployment patterns available for allowing users
to quickly evaluate product features along side their co-operate Integration requirements. The Compose files make use of per profile
Docker images of WSO2 Enterprise Integrator and MySQL.

**Change log** from previous v6.4.0.1 release: [View Here](CHANGELOG.md)
