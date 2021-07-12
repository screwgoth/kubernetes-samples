# MongoDB Helm charts
This folder contains the various `values.yaml` files for the MongoDB helm charts.

### Mongodb
* Install the Bitnami Helm repo

      helm repo add bitnami https://charts.bitnami.com/bitnami

* For a regular MongoDB cluster with replicaset and choice of arbiter, use the `mongodb-values.yaml` file

      helm install -n default mongo -f mongodb-values.yaml  bitnami/mongodb

* For a MongoDB Sharded clutser, use the `mongodb-sharded-values.yaml` file

      helm install -n default mongo-shard -f mongodb-sharded-values.yaml bitnami/mongodb-sharded

