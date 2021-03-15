# northwind-cluster-configuration
My Kubernetes and other configurations. The purpose is to store here the configuration of the Kubernetes cluster on which all the Northwind db based microservices will run.

## Ingress
The ingress controller installed is the NGINX ingress controller. To make it simple on a home pc cluster, the instruction of installation are the ones used for bare-metal clusters. The script basic-cluster-apps.sh reports the instruction used to start the version 0.44.0 of the controller on the cluster.

## Dashboard
The dashboard installed is https://github.com/kubernetes/dashboard