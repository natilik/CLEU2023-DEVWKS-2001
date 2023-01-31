# DEVWKS-2001: Kubernetes and Introduction into Continuous Delivery

This repository contains the files required for the participants of Cisco Live! Amsterdam 2023 workshop DEVWKS-2001: Kubernetes and Introduction into Continuous Delivery. We will use Chuck Norris App (watch out!) to demonstrate how we can use Consul to do Blue Green deployment.

As the Modern application increases in complexity with deployment cycles getting shorter and shorter. Modern applications are often containerised and run on cloud or an on-prem Kubernetes cluster. Modern applications are becoming the main revenue stream for a lot of companies so mistakes and outages are not acceptable anymore.

Across this workshop we will guide you through an approach to build basic continuous delivery for Kubernetes and accelerate the development of your applications. This approach will aim to and make it easier for developers to deploy new application's feature into the wild in a controlled fashion.

This session start with deploying Flux to automate deployment of your application in Kubernetes. The application will be fully service meshed with Consul and provide some important metrics presented by Prometheus and Grafana.

Looking forward the session will look towards the next step of this setup, allowing you to run canary deployments with Consul with Prometheus and Grafana providing your application metrics across the new deployment.

### General Information
- Kubernetes - https://kubernetes.io
- Consul HashiCorp Learning - https://learn.hashicorp.com/consul
- Consul on Kubernetes GitHub - https://github.com/hashicorp/consul-k8s


### Repository Content
```
deploy/chuck-app - Chuck Norris app manifests
deploy/consul - Consul manifests
deploy/grafana - Grafana dashboard for Consul
workshop - Content used in the workshop at CLUS2022
```
