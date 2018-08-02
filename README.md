# Awesome Operators in the Wild

Operators are Kubernetes native applications. We define native as being both managed using the Kubernetes APIs via kubectl and ran on Kubernetes as containers. Operators take advantage of Kubernetes’s extensibility to deliver the automation advantages of cloud services like provisioning, scaling, and backup/restore while being able to run anywhere that Kubernetes can run.

This list is built by the community. Have you built or are you using an Operator that is not listed? Please send a pull request and we will add that Operator to the list.

If you want to start building an Operator, you should definitely look into the [Operator SDK](https://github.com/operator-framework/operator-sdk).

| App Name | Github | Description |
|----------|-------------|-------------|
| Rook | [rook/rook](https://github.com/rook/rook/tree/master/cluster/examples/kubernetes) |  File, Block, and Object Storage Services for your Cloud-Native Environment |
| ElasticSearch | [upmc-enterprises/elasticsearch-operator](https://github.com/upmc-enterprises/elasticsearch-operator) | Manages one or more elastic search clusters on Kubernetes. |
| etcd | [coreos/etcd-operator](https://github.com/coreos/etcd-operator) | Manages etcd k/v database clusters on Kubernetes. |
| Prometheus | [coreos/prometheus-operator](https://github.com/coreos/prometheus-operator) | Monitor Kubernetes and external resources with Prometheus. |
| Icinga2 operator | [appscode/searchlight](https://github.com/appscode/searchlight) | Alerts for Kubernetes |
| OpenStack | [sapcc/kubernetes-operators](https://github.com/sapcc/kubernetes-operators/tree/master/openstack-operator) | SAP OpenStack operator creates various resources in OpenStack.
| KubeVirt | [kubevirt/kubevirt](https://github.com/kubevirt/kubevirt) | Kubernetes Virtualization Operator with API and runtime in order to define and manage virtual machines. |
| Kafka #1 | [krallistic/kafka-operator](https://github.com/krallistic/kafka-operator) | A Kafka Operator for Kubernetes |
| Kafka #2 | [strimzi/strimzi](https://github.com/strimzi/strimzi)| Operator for running Kafka and Kafka Connect on Kubernetes and OpenShift |
| PostgreSQL #1 | [CrunchyData/postgres-operator](https://github.com/CrunchyData/postgres-operator) | PostgreSQL Operator Creates/Configures/Manages PostgreSQL Clusters on Kubernetes |
| PostgreSQL #2 | [zalando-incubator/postgres-operator](https://github.com/zalando-incubator/postgres-operator) | Create and manage PostgreSQL HA clusters on Kubernetes using [Patroni](https://github.com/zalando/patroni) |
| Mongo #1| [kbst/mongodb](https://github.com/kbst/mongodb) | MongoDB Operator for Kubernetes |
| Mongo #2|[Ultimaker/k8s-mongo-operator](https://github.com/Ultimaker/k8s-mongo-operator) | MongoDB Operator for MongoDB Replica Sets and Backups |
| Kong | [upmc-enterprises/kong-operator](https://github.com/upmc-enterprises/kong-operator) | Manages Kong clusters on Kubernetes. |
| Tensorflow | [kubeflow/tf-operator](https://github.com/kubeflow/tf-operator) | Tools for ML/Tensorflow on Kubernetes. |
| WebLogic | [oracle/weblogic-kubernetes-operator](https://github.com/oracle/weblogic-kubernetes-operator) | Oracle Weblogic Server Kubernetes Operator |
| Redis #1 | [spotahome/redis-operator](https://github.com/spotahome/redis-operator) | Redis Operator creates/configures/manages redis clusters atop Kubernetes. |
| Redis #2 | [jw-s/redis-operator](https://github.com/jw-s/redis-operator) | Redis operator for Kubernetes |
| Habitat | [habitat-sh/habitat-operator](https://github.com/habitat-sh/habitat-operator) | A Kubernetes operator for Habitat services. |
| Tidb | [aliyx/tidb-operator](https://github.com/aliyx/tidb-operator) | Tidb-operator creates/configures/manages tidb clusters atop Kubernetes. |
| Memcached | [ianlewis/memcached-operator](https://github.com/ianlewis/memcached-operator) | A Kubernetes operator for memcached |
| MXNet | [deepinsight/mxnet-operator](https://github.com/deepinsight/mxnet-operator ) | Tools for ML/MXNet on Kubernetes. |
| NATS | [nats-io/nats-operator](https://github.com/nats-io/nats-operator) | This operator manages NATS clusters atop Kubernetes, automating their creation and administration. |
| MySQL #1 | [grtl/mysql-operator](https://github.com/grtl/mysql-operator) | Kubernetes Custom Resource for MySQL. |
| MySQL #2 | [oracle/mysql-operator](https://github.com/oracle/mysql-operator) | Create, operate and scale self-healing MySQL clusters in Kubernetes |
| MySQL #3 | [presslabs/mysql-operator] (https://github.com/presslabs/mysql-operator) | Bulletproof MySQL on Kubernetes |
| Cassandra #1 | [instaclustr/cassandra-operator](https://github.com/instaclustr/cassandra-operator) | Kubernetes operator for Apache Cassandra. |
| Cassandra #2 | [vgkowski/cassandra-operator](https://github.com/vgkowski/cassandra-operator) | kubernetes operator for cassandra clusters automation. |
| KubeDB | [kubedb/operator](https://github.com/kubedb/operator) | KubeDB Operator |
| Consul | [python/consul-operator](https://github.com/python/consul-operator) | A Kubernetes operator for consul. |
| ArangoDB | [arangodb/kube-arangodb](https://github.com/arangodb/kube-arangodb) | ArangoDB Kubernetes Operator - Start ArangoDB on Kubernetes in 5min. |
| RDS |  [MYOB-Technology/ops-kube-db-operator](https://github.com/MYOB-Technology/ops-kube-db-operator) | Operator to control RDS DBs in AWS. |
| CouchDB | [nicolai86/couchdb-operator](https://github.com/nicolai86/couchdb-operator) | Prototype Kubernetes operator for couchDB. |
| Zeebe | [zeebe-io/zeebe-operator](https://github.com/zeebe-io/zeebe-operator) | Kubernetes Operator for Zeebe - Let me manage your https://zeebe.io cluster on K8s. |
| InfluxDB | [gianarb/influxdb-operator](https://github.com/gianarb/influxdb-operator) | The Kubernetes operator for InfluxDB and the TICK stack. |
| Aerospike | [travelaudience/aerospike-operator](https://github.com/travelaudience/aerospike-operator) | Manages Aerospike clusters atop Kubernetes, automating their creation and administration. |
| DynamoDB | [microdc/k8s-dynamodb-operator](https://github.com/microdc/k8s-dynamodb-operator) | A Kubernetes DynamoDB operator |
| Spark | [GoogleCloudPlatform/spark-on-k8s-operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator) | Kubernetes CRD operator for specifying and running Apache Spark applications idiomatically on Kubernetes. |
| Vault #1 | [coreos/vault-operator](https://github.com/coreos/vault-operator) | Run and manage Vault on Kubernetes simply and securely. |
| Vault #2  | [banzaicloud/bank-vaults](https://github.com/banzaicloud/bank-vaults)| A feature rich HA Vault operator with TLS, external API based re/configuration, several/automatic unseal options and more.|
| Kanister | [kanisterio/kanister](https://github.com/kanisterio/kanister) | An extensible framework for application-level data management on Kubernetes. |
| cert-manager | [jetstack/cert-manager](https://github.com/jetstack/cert-manager) | Automatically provision and manage TLS certificates in Kubernetes |
| Ark | [heptio/ark](https://github.com/heptio/ark) | Manages the backup and restoration of cluster components (pv,pvc,deployments, etc.) to aid in disaster recovery |
| PVC | [banzaicloud/pvc-operator](https://github.com/banzaicloud/pvc-operator) | This operator helps to use Kubernetes Persistent Volumes easier on cloud providers by dynamically creating the required accounts, classes and more. |
| WildFly | [banzaicloud/wildfly-operator](https://github.com/banzaicloud/wildfly-operator) | Wildfly Operator let's you describe and deploy JEE application on Wildfly server by creating a CRD in Kubernetes. |
| Infinispan | [banzaicloud/infinispan-operator](https://github.com/banzaicloud/infinispan-operator) | This operator deploys and runs an Infinispan cache cluster . |
| Prometheus Jmx Exporter | [banzaicloud/prometheus-jmx-exporter-operator](https://github.com/banzaicloud/prometheus-jmx-exporter-operator) | This operator using Jmx Exporter enables Java processes running ok Kubernetes Pods to expose metrics collected form mBeans via JMX to Prometheus. |
| HPA Operator | [banzaicloud/hpa-operator](https://github.com/banzaicloud/hpa-operator) | Horizontal Pod Autoscaler operator for Kubernetes. Annotate, and let HPA operator do the rest. |
| Logging Operator | [banzaicloud/logging-operator](https://github.com/banzaicloud/logging-operator) | Logging operator for Kubernetes based on Fluentd and Fluent-bit. |
| Envoy | [solo-io/envoy-operator](https://github.com/solo-io/envoy-operator)| Run and manage Envoy on Kubernetes simply and securely. |
| CloudFormation | [linki/cloudformation-operator](https://github.com/linki/cloudformation-operator)| Run and manage CloudFormation stacks. Manage AWS resources from Kubernetes. |
| ZooKeeper | [Nuance-Mobility/zookeeper-operator](https://github.com/Nuance-Mobility/zookeeper-operator) | A ZooKeeper 3.5.x Operator for Kubernetes |
| AWS | [giantswarm/aws-operator](https://github.com/giantswarm/aws-operator) | Manages Kubernetes clusters running on AWS |
| Unifiedpush | [aerogear/ups-config-operator](https://github.com/aerogear/ups-config-operator) | Manage your Unifiedpush variants from Kubernetes / Openshift |
| RethinkDB | [jmckind/rethinkdb-operator](https://github.com/jmckind/rethinkdb-operator) | A Kubernetes operator to manage RethinkDB instances. |
| Android SDK | [aerogear/android-sdk-operator](https://github.com/aerogear/android-sdk-operator) | A Kubernetes operator to manage android sdk packages syncronization in a persistent volume. |
