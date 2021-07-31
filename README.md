# kind-basic-configs

Basic kind configurations for generic local testing with multi-node clusters

* clussterip
* nodeport
* ingress

# Launch

Create your cluster:
```bash
kind create cluster --config=<>.config
```
Apply your configurations

Have fun ..

# Ingress

baremetal is tested and working with multi-node clusters. Point directly to the docker ip as you would to a public ip address.



