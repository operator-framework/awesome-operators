# Awesome Operators in the Wild

Operators are Kubernetes native applications. We define native as being both managed using the Kubernetes APIs via kubectl and ran on Kubernetes as containers. Operators take advantage of Kubernetes’s extensibility to deliver the automation advantages of cloud services like provisioning, scaling, and backup/restore while being able to run anywhere that Kubernetes can run.

This list is built by the community. Have you built or are you using an Operator that is not listed? Please send a pull request and we will add that Operator to the list.

If you want to start building an Operator, you should definitely look into the [Operator SDK](https://github.com/operator-framework/operator-sdk).

| App Name | Github | Description |
|----------|-------------|-------------|
| Rook | [rook/rook](https://github.com/rook/rook/tree/master/cluster/examples/kubernetes) |  File, Block, and Object Storage Services for your Cloud-Native Environment |
| ElasticSearch | [upmc-enterprises/elasticsearch-operator](https://github.com/upmc-enterprises/elasticsearch-operator) | Elasticsearch is a distributed, RESTful search and analytics engine. This operator manages one or more elastic search clusters on Kubernetes. |
| etcd | [coreos/etcd-operator](https://github.com/coreos/etcd-operator) | etcd is a distributed key-value (k/v) store. This operator manages etcd k/v database clusters on Kubernetes. |
| Prometheus | [coreos/prometheus-operator](https://github.com/coreos/prometheus-operator) | Prometheus, a Cloud Native Computing Foundation project, is a systems and service monitoring system. It collects metrics from configured targets at given intervals, evaluates rule expressions, displays the results, and can trigger alerts if some condition is observed to be true. The Prometheus Operator for Kubernetes provides easy monitoring definitions for Kubernetes services and deployment and management of Prometheus instances. |
| Icinga2 operator | [appscode/searchlight](https://github.com/appscode/searchlight) | Icinga is an open source computer system and network monitoring application. This operator provide alerts for Kubernetes |
| OpenStack | [sapcc/kubernetes-operators](https://github.com/sapcc/kubernetes-operators/tree/master/openstack-operator) | SAP OpenStack operator creates various resources in OpenStack.
| KubeVirt | [kubevirt/kubevirt](https://github.com/kubevirt/kubevirt) | Kubernetes Virtualization Operator with API and runtime in order to define and manage virtual machines. |
| Kafka #1 | [krallistic/kafka-operator](https://github.com/krallistic/kafka-operator) | A Kafka Operator for Kubernetes |
| Kafka #2 | [strimzi/strimzi](https://github.com/strimzi/strimzi)| Operator for running Kafka and Kafka Connect on Kubernetes and OpenShift |
| PostgreSQL #1 | [CrunchyData/postgres-operator](https://github.com/CrunchyData/postgres-operator) | PostgreSQL Operator Creates/Configures/Manages PostgreSQL Clusters on Kubernetes |
| PostgreSQL #2 | [zalando-incubator/postgres-operator](https://github.com/zalando-incubator/postgres-operator) | Create and manage PostgreSQL HA clusters on Kubernetes using [Patroni](https://github.com/zalando/patroni) |
| MongoDB (Official) | [mongodb/mongodb-enterprise-kubernetes](https://github.com/mongodb/mongodb-enterprise-kubernetes) | MongoDB Enterprise Operator for Kubernetes |
| Mongo #1| [kbst/mongodb](https://github.com/kbst/mongodb) | MongoDB Operator for Kubernetes |
| Mongo #2|[Ultimaker/k8s-mongo-operator](https://github.com/Ultimaker/k8s-mongo-operator) | MongoDB Operator for MongoDB Replica Sets and Backups |
| Kong | [upmc-enterprises/kong-operator](https://github.com/upmc-enterprises/kong-operator) | Manages Kong clusters on Kubernetes. |
| Tensorflow | [kubeflow/tf-operator](https://github.com/kubeflow/tf-operator) | Tools for ML/Tensorflow on Kubernetes. |
| WebLogic | [oracle/weblogic-kubernetes-operator](https://github.com/oracle/weblogic-kubernetes-operator) | Oracle Weblogic Server Kubernetes Operator |
| Redis #1 | [spotahome/redis-operator](https://github.com/spotahome/redis-operator) | Redis Operator creates/configures/manages redis clusters atop Kubernetes. |
| Redis #2 | [jw-s/redis-operator](https://github.com/jw-s/redis-operator) | Redis operator for Kubernetes |
| Redis Cluster | [AmadeusITGroup/Redis-Operator](https://github.com/AmadeusITGroup/Redis-Operator) | A Kubernetes operator for running Redis in Cluster mode |
| Habitat | [habitat-sh/habitat-operator](https://github.com/habitat-sh/habitat-operator) | A Kubernetes operator for Habitat services. |
| TiDB #1 | [aliyx/tidb-operator](https://github.com/aliyx/tidb-operator) | Tidb-operator creates/configures/manages tidb clusters atop Kubernetes. |
| TiDB #2 | [pingcap/tidb-operator](https://github.com/pingcap/tidb-operator) | TiDB operator creates and manages TiDB clusters running in Kubernetes. |
| Memcached | [ianlewis/memcached-operator](https://github.com/ianlewis/memcached-operator) | A Kubernetes operator for memcached |
| MXNet | [deepinsight/mxnet-operator](https://github.com/deepinsight/mxnet-operator ) | Apache MXNet is a modern open-source deep learning framework used to train, and deploy deep neural networks. This operator manages the tools for ML/MXNet on Kubernetes. |
| NATS | [nats-io/nats-operator](https://github.com/nats-io/nats-operator) | NATS is an open-source, high-performance, lightweight and secure cloud native messaging system. This operator manages NATS clusters atop Kubernetes, automating their creation and administration. |
| MySQL #1 | [grtl/mysql-operator](https://github.com/grtl/mysql-operator) | MySQL is an Open Source SQL database management system. This creates a Kubernetes Custom Resource for MySQL. |
| MySQL #2 | [oracle/mysql-operator](https://github.com/oracle/mysql-operator) | MySQL is an Open Source SQL database management system. This operator creates, operates, and scales self-healing MySQL clusters in Kubernetes |
| MySQL #3 | [presslabs/mysql-operator](https://github.com/presslabs/mysql-operator) | MySQL is an Open Source SQL database management system. This operator manages all the necessary resources for deploying and managing a highly available MySQL cluster. It provides efortless backups, while keeping the cluster highly-available. |
| Cassandra #1 | [instaclustr/cassandra-operator](https://github.com/instaclustr/cassandra-operator) | Cassandra is a free and open-source distributed wide column store NoSQL database management system designed to handle large amounts of data. This is a Kubernetes operator for Apache Cassandra. |
| Cassandra #2 | [vgkowski/cassandra-operator](https://github.com/vgkowski/cassandra-operator) | Cassandra is a free and open-source distributed wide column store NoSQL database management system designed to handle large amounts of data. This ia a Kubernetes operator for Cassandra cluster automation. |
| KubeDB | [kubedb/operator](https://github.com/kubedb/operator) | KubeDB Operator |
| Consul | [python/consul-operator](https://github.com/python/consul-operator) | A Kubernetes operator for consul. |
| ArangoDB | [arangodb/kube-arangodb](https://github.com/arangodb/kube-arangodb) | ArangoDB Kubernetes Operator - Start ArangoDB on Kubernetes in 5min. |
| RDS |  [MYOB-Technology/ops-kube-db-operator](https://github.com/MYOB-Technology/ops-kube-db-operator) | Operator to control RDS DBs in AWS. |
| CouchDB | [nicolai86/couchdb-operator](https://github.com/nicolai86/couchdb-operator) | Prototype Kubernetes operator for couchDB. |
| Zeebe | [zeebe-io/zeebe-operator](https://github.com/zeebe-io/zeebe-operator) | Kubernetes Operator for Zeebe - Let me manage your https://zeebe.io cluster on K8s. |
| InfluxDB | [gianarb/influxdb-operator](https://github.com/gianarb/influxdb-operator) | InfluxDB is an open-source time series database. This is the Kubernetes operator for InfluxDB and the TICK stack. |
| Aerospike | [travelaudience/aerospike-operator](https://github.com/travelaudience/aerospike-operator) | Aerospike is a NoSQL distributed database. This Operator manages Aerospike clusters atop Kubernetes, automating their creation and administration. |
| DynamoDB | [microdc/k8s-dynamodb-operator](https://github.com/microdc/k8s-dynamodb-operator) | Amazon DynamoDB is a fully  proprietary NoSQL database service that supports key-value and document data structures. This is a Kubernetes operator for DynamoDB  |
| Spark #1 | [GoogleCloudPlatform/spark-on-k8s-operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator) | Kubernetes CRD operator for specifying and running Apache Spark applications idiomatically on Kubernetes. |
| Spark #2 | [jvm-operators/spark-operator](https://github.com/jvm-operators/spark-operator) | ConfigMap-based operator for deploying ephemeral Apache Spark clusters and intelligent applications that spawn their own Spark clusters natively on Kubernetes and OpenShift. |
| Airflow | [GoogleCloudPlatform/airflow-operator](https://github.com/GoogleCloudPlatform/airflow-operator) | A Kubernetes operator to manage Apache Airflow. |
| Vault #1 | [coreos/vault-operator](https://github.com/coreos/vault-operator) | Vault secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets. This operator will run and manage Vault on Kubernetes simply and securely. |
| Vault #2  | [banzaicloud/bank-vaults](https://github.com/banzaicloud/bank-vaults)| Vault secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets. This operator offers a feature rich HA Vault operator with TLS, external API based re/configuration, several/automatic unseal options and more.|
| Kanister | [kanisterio/kanister](https://github.com/kanisterio/kanister) | Kanister is an extensible framework for application-level data management on Kubernetes |
| cert-manager | [jetstack/cert-manager](https://github.com/jetstack/cert-manager) | Automatically provision and manage TLS certificates in Kubernetes |
| Ark | [heptio/ark](https://github.com/heptio/ark) | Ark is a utility for managing disaster recovery, this operator manages the backup and restoration of cluster components (pv,pvc,deployments, etc.) to aid in disaster recovery |
| PVC | [banzaicloud/pvc-operator](https://github.com/banzaicloud/pvc-operator) | This operator helps to use Kubernetes Persistent Volumes easier on cloud providers by dynamically creating the required accounts, classes and more. |
| WildFly | [banzaicloud/wildfly-operator](https://github.com/banzaicloud/wildfly-operator) | Wildfly Operator let's you describe and deploy JEE application on Wildfly server by creating a Custom Resource Definitions in Kubernetes. |
| Infinispan | [banzaicloud/infinispan-operator](https://github.com/banzaicloud/infinispan-operator) |  Infinispan is a distributed in-memory key/value data store. This operator deploys and runs an Infinispan cache cluster. |
| Prometheus Jmx Exporter | [banzaicloud/prometheus-jmx-exporter-operator](https://github.com/banzaicloud/prometheus-jmx-exporter-operator) | This operator using Jmx Exporter enables Java processes running ok Kubernetes Pods to expose metrics collected form mBeans via JMX to Prometheus. |
| Envoy | [solo-io/envoy-operator](https://github.com/solo-io/envoy-operator)| Envoy is a Microservice Abstraction Layer (also known as an API Gateway, API Middleware or in some cases Service Mesh)Run and manage Envoy on Kubernetes simply and securely. |
| CloudFormation | [linki/cloudformation-operator](https://github.com/linki/cloudformation-operator)| AWS CloudFormation is a service that helps you model and set up your Amazon Web Services resources. Using this operator run and manage CloudFormation stacks and manage AWS resources from Kubernetes. |
| ZooKeeper | [Nuance-Mobility/zookeeper-operator](https://github.com/Nuance-Mobility/zookeeper-operator) | ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services. This is an operator for ZooKeeper 3.5.x |
| AWS | [giantswarm/aws-operator](https://github.com/giantswarm/aws-operator) | Manages Kubernetes clusters running on Amazon Web Services |
| Unifiedpush | [aerogear/ups-config-operator](https://github.com/aerogear/ups-config-operator) | UnifiedPush Server is a server that allows sending push notifications to different (mobile) platforms. Using this operator manage your Unifiedpush variants from Kubernetes and Openshift |
| RethinkDB | [jmckind/rethinkdb-operator](https://github.com/jmckind/rethinkdb-operator) | RethinkDB is a free and open-source, distributed document-oriented database. This is a Kubernetes operator to manage RethinkDB instances. |
| Android SDK | [aerogear/android-sdk-operator](https://github.com/aerogear/android-sdk-operator) | A Kubernetes operator to manage android sdk packages syncronization in a persistent volume. |
| RBAC Manager | [reactiveops/rbac-manager](https://github.com/reactiveops/rbac-manager) | This operator simplifies the management of RBAC Role Bindings in Kubernetes. |
| Quobyte | [Quobyte/Quobyte](https://github.com/quobyte/kubernetes/tree/master/operator) |  [Quobyte’s](https://www.quobyte.com) next-generation file system unifies file, block and object storage for enterprise and scientific applications. |
| RocketMQ | [huanwei/rocketmq-operator](https://github.com/huanwei/rocketmq-operator) | Create, operate and scale self-healing Rocketmq clusters on Kubernetes. |
| Jaeger | [jaegertracing/jaeger-operator](https://github.com/jaegertracing/jaeger-operator) | Jaeger Operator for Kubernetes. |
| Netperf | [piontec/netperf-operator](https://github.com/piontec/netperf-operator) | This is a very simple operator that can be used to test network performance between 2 pods using the [netperf](https://hewlettpackard.github.io/netperf/) tool. It is also a good operator for learning puposes, as the code base is pretty small and it's described in detail in this [blog post](https://www.tailored.cloud/kubernetes/write-a-kubernetes-controller-operator-sdk/). |