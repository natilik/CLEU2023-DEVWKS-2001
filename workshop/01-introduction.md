## Introduction
DevOps is a term we hear tossed around daily. It encompasses the tools and practices that can break down silos between teams helping them create, deliver, and deploy applications and services faster than ever before. Previously organizations only released (application updates or launches) a few times a year. Today under the prevailing Continuous Delivery model, they can push out releases in a matter of weeks or days.

Blue green deployment is an application release model that gradually transfers user traffic from a previous version of an application or microservice, to a nearly identical new release. The fundamental idea is to have two environments to easily switch between. To be able to transfer the traffic between two different version, we will need to split the traffic.

In today's workshop we will deploy HashiCorp Consul with the official Helm chart on a pre-built Kubernetes cluster. After deploying Consul, you will learn how to access the Consul dashboard and validate. Next, you will deploy Chuck Norris App version 1 and version 2. Once deployed, we will then start slowly migrating our application from version 1 to version 2 and monitoring the whole migration with Grafana.

In this workshop you will have a pre-built `kind` (Kubernetes in Docker) Kubernetes cluster available.

We will be covering the following areas:
- Installation of Consul in the recommended minimal configuration - Consul, Prometheus and Consul Ingress
- Installation of Grafana
- Validation of Consul and Grafana
- Deployment of the Chuck Norris Application
- Making the Chuck Norris Application part of Consul Service Mesh
- Testing of the application
- Deployment of Consul Service Resolver and Splitter
- Configuration of Consul Ingress
- Steering traffic from Chuck Norris Application version 1 to version 2
