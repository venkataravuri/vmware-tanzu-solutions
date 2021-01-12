<p align="center">
    <a href="https://circleci.com/" alt="Builds">
        <img src="https://img.shields.io/static/v1?label=build&message=passing&color=success&style=flat&logo=jenkins" /></a>
    <a href="" alt="Tests">
        <img src="https://img.shields.io/static/v1?label=tests&message=477+passed,+2+failed&color=red&style=flat&logo=" /></a>
    <a href="" alt="">
        <img src="https://img.shields.io/static/v1?label=docker+build&message=automated&color=blue&style=flat&logo=docker" /></a>
    <a href="" alt="">
        <img src="https://img.shields.io/static/v1?label=coverage&message=90%&color=green&style=flat&logo=" /></a>
    <a href="" alt="">
        <img src="https://img.shields.io/static/v1?label=code+quality&message=A&color=brightgreen&style=flat&logo=" /></a>
</p>
<p align="center">
    <a href="" alt="GitHub followers">
        <img src="https://img.shields.io/github/followers/venkataravuri?label=follow&style=social" /></a>
    <a href="" alt="GitHub forks">
        <img src="https://img.shields.io/github/forks/venkataravuri/e-commerce-microservices-sample?label=fork&style=social" /></a>
    <a href="" alt="GitHub forks">
        <img src="https://img.shields.io/twitter/follow/vmware?label=follow&style=social" /></a>
</p>

# :hamburger:Food Delivery App:motor_scooter: - using VMWare Multi-Cloud Technologies & SaaS Services
A _solution blueprint_ (or) _reference model_ to implement a fictitious Food Delivery App using *VMware*’s hybrid & multi-cloud technologies such as Tanzu(Kubernetes) & Cloud SaaS services.

_This sample application demonstrates how to build, run & manage a cloud-native modern application using VMware technology stack which is hosted on Priviate Cloud (Datacenter) and Public Clouds._
<p align="center">
    <img src="https://cdn.dribbble.com/users/2697985/screenshots/13966152/media/9b9be2f2c9a72f3ea8e6d30036586b93.jpg?compress=0&resize=500x375" alt="Food Delivery App UI/UX">
    <!--<img src="https://cdn.dribbble.com/users/4189231/screenshots/14435902/media/fb5ff09015ef9096fdfbb1519c21406b.png?compress=1&resize=500x375" alt="Food Delivery App UI/UX">-->
</p>

>Note: This is a prototype, in particular demonstrates building real-world modern applications end-to-end using VMware technology stack. Kindly treat it as a reference model to build real-world applications.

You can standup working application within :alarm_clock: 30 minutes!

## Conceptual Architecture
This sample application includes following **functional modules/components** which are implemented as **Microservices** (or) **Serverless** functions. All these microservices are independently deployable & scalable services and are organized around business capabilities.
<p align="center">
    <img width="800" height="600" src="docs/images/conceptual-architecture-diagram.png" alt="Conceptual Architecture">
</p>

## Technical Architecture
This sample application adhers to **API-driven** & **Event-Driven** architecture principles, wherein each fuctional module realized into a Cloud-Native application either as a **Serverless Functions** (or) **Microservices**. Each module/service is independently scalable and can be deployed as **Containers** anywhere (private & public clouds) using **VMware Tanzu** (Kubernetes).
<p align="center">
    <img width="800" height="550" src="docs/images/tech-architecture.png" alt="Technical Architecture">
</p>

### Technology Stack
<p align="center">
    <img width="1000" height="450" src="docs/images/tech-stack.png" alt="Technology Stack">
</p>

#### Compute
- Tanzu Serverless functions - https://tanzu.vmware.com/serverless
- Tanzu Kubernetes Grid (TKG) - https://tanzu.vmware.com/kubernetes-grid
- VMware Hybrid Cloud Foundation - https://www.vmware.com/products/cloud-foundation.html
#### Storage & Database
- Tanzu SQL for Postgress - https://tanzu.vmware.com/content/blog/vmware-tanzu-sql-now-ga-kubernetes-postgres
- MinIO Open Source Object Storage - https://min.io/
#### Messaging
- Tanzu RabbitMQ - https://tanzu.vmware.com/rabbitmq
- Kafka - https://tanzu.vmware.com/developer/guides/messaging-and-integration/kafka-gs/
#### Observability & DevOps
- Tanzu Observability Cloud (Wavefront) - https://tanzu.vmware.com/observability
- VMware vRealize Log Insight Cloud - https://cloud.vmware.com/log-insight-cloud
- Tanzu Application Catalog - https://tanzu.vmware.com/application-catalog
- Tanzu Build Service - https://tanzu.vmware.com/build-service
- Tanzu Mission Control - https://tanzu.vmware.com/mission-control

## Getting Started

### Pre-requisites
To standup this sample application in your environment (private cloud or public cloud), as a pre-requisite you must have following up & ready,
- TODO
- TODO

### Installation Instructions
#### Clone Repository
Clone respository source code by issuing below instruction from any folder on your machine,
```sh
git clone https://github.com/venkataravuri/e-commerce-microservices-sample.git
cd e-commerce-microservices-sample
```
#### Build Application(s)
Maven/Gradle has been used as a build tool to build applications. Issue following command on your terminal/console window,
```sh
gradlew build
```
#### Provision Infratructure & Deploy Application(s)
##### Configuration
Modify below configuration settings to match your environment,
- TODO
- TODO

Execute below Terraform instruction in sequence to provision infrastructur and ,
```sh
TODO
```

## Further Reading
For further information on this sample application, reach us on Slack #TODO
