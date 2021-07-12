# Redis Helm charts
This folder contains the various `values.yaml` files for the MongoDB helm charts.

### Bitnami Redis
* Install the Bitnami Helm repo

      helm repo add bitnami https://charts.bitnami.com/bitnami

* For a regular Redis cluster, use the `redis-cluster-values.yaml` file

      helm install -n default redis -f redis-cluster-values.yaml  bitnami/redis-cluster

