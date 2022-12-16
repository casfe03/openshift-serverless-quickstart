# OpenShift Serverless Quick Start

This repo contains some OpenShift Serverless Quickstarts. A quick start is a guided tutorial with user tasks to be executed using the OpenShift Web Console. They are especially useful for getting started with an application, Operator, or other product offering.

![](imgs/2022-12-16-11-11-17.png)

![](imgs/2022-12-16-11-16-32.png)

![](imgs/2022-12-16-11-12-29.png)

![](imgs/2022-12-16-11-13-33.png)

![](imgs/2022-12-16-11-14-09.png)

![](imgs/2022-12-16-11-14-50.png)

## How to install

To install on OpenShift, run:

```bash
# NodeJS
oc apply -f https://raw.githubusercontent.com/luszczynski/openshift-serverless-quickstart/main/quickstarts/node-faas-quickstart.yaml

# GO
oc apply -f https://raw.githubusercontent.com/luszczynski/openshift-serverless-quickstart/main/quickstarts/go-faas-quickstart.yaml

# Quarkus
oc apply -f https://raw.githubusercontent.com/luszczynski/openshift-serverless-quickstart/main/quickstarts/quarkus-faas-quickstart.yaml

# Python
oc apply -f https://raw.githubusercontent.com/luszczynski/openshift-serverless-quickstart/main/quickstarts/python-faas-quickstart.yaml

# Rust
oc apply -f https://raw.githubusercontent.com/luszczynski/openshift-serverless-quickstart/main/quickstarts/rust-faas-quickstart.yaml

# SpringBoot
oc apply -f https://raw.githubusercontent.com/luszczynski/openshift-serverless-quickstart/main/quickstarts/springboot-faas-quickstart.yaml

# Typescript
oc apply -f https://raw.githubusercontent.com/luszczynski/openshift-serverless-quickstart/main/quickstarts/typescript-faas-quickstart.yaml
```
