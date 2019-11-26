# Awesome Operators in the Wild

Operators are Kubernetes native applications. We define native as being both managed using the Kubernetes APIs via kubectl and ran on Kubernetes as containers. Operators take advantage of Kubernetes’s extensibility to deliver the automation advantages of cloud services like provisioning, scaling, and backup/restore while being able to run anywhere that Kubernetes can run.

This list is built by the community. Have you built or are you using an Operator that is not listed? Please send a pull request and we will add that Operator to the list.

If you want to start building an Operator, you should definitely look into the [Operator SDK](https://github.com/operator-framework/operator-sdk).

| App Name | Github | Description |
|----------|-------------|-------------|
| Aerospike | [travelaudience/aerospike-operator](https://github.com/travelaudience/aerospike-operator) | Aerospike is a NoSQL distributed database. This Operator manages Aerospike clusters atop Kubernetes, automating their creation and administration. |
| Airflow | [GoogleCloudPlatform/airflow-operator](https://github.com/GoogleCloudPlatform/airflow-operator) | A Kubernetes operator to manage Apache Airflow. |
| Android SDK | [aerogear/android-sdk-operator](https://github.com/aerogear/android-sdk-operator) | A Kubernetes operator to manage android sdk packages syncronization in a persistent volume. |
| Aqua Security | [aquasecurity/aqua-operator](https://github.com/aquasecurity/aqua-operator) | [Aqua Security](https://aquasec.com) Operator for k8s or openshift - aqua-operator is a group of controllers that runs within a Kubernetes or Openshift cluster that provides a means to deploy and manage Aqua Security cluster |
| ArangoDB | [arangodb/kube-arangodb](https://github.com/arangodb/kube-arangodb) | ArangoDB Kubernetes Operator - Start ArangoDB on Kubernetes in 5min. |
| aranya | [arhat-dev/aranya](https://github.com/arhat-dev/aranya) | A Kubernetes Operator for Edge Devices Management |
| Argo CD | [argoproj/argo-cd](https://github.com/argoproj/argo-cd) | Declarative continuous deployment for Kubernetes |
| AWS | [giantswarm/aws-operator](https://github.com/giantswarm/aws-operator) | Manages Kubernetes clusters running on Amazon Web Services |
| AWS Services | [awslabs/aws-service-operator](https://github.com/awslabs/aws-service-operator) | Manages AWS services that are used by your applications running in Kubernetes. |
| Azure Databricks | [microsoft/azure-databricks-operator](https://github.com/microsoft/azure-databricks-operator) | Manages an Azure Databricks Workspace from inside your Kubernetes cluster. |
| Camel-k | [apache/camel-k](https://github.com/apache/camel-k) | Lightweight integration framework built from Apache Camel that runs natively on Kubernetes |
| Cassandra #1 | [instaclustr/cassandra-operator](https://github.com/instaclustr/cassandra-operator) | Kubernetes operator for Apache Cassandra. |
| Cassandra #2 | [vgkowski/cassandra-operator](https://github.com/vgkowski/cassandra-operator) | Kubernetes operator for cassandra clusters automation. |
| Cassandra #3 | [jetstack/navigator](https://github.com/jetstack/navigator) | Create and scale multi-AZ Casssandra clusters on Kubernetes. |
| Cassandra #4 | [Orange-OpenSource/cassandra-k8s-operator](https://github.com/Orange-OpenSource/cassandra-k8s-operator) | This Kubernetes operator automates the Cassandra operations such as deploying a new rack aware cluster, adding/removing nodes, configuring the C* and JVM parameters, upgrading JVM and C* versions, and many more...  |
| Cerebral     | [containership/cerebral](https://github.com/containership/cerebral) | Kubernetes cluster autoscaler operator with pluggable metric/event sources and cloud provider support |
| cert-manager | [jetstack/cert-manager](https://github.com/jetstack/cert-manager) | Automatically provision and manage TLS certificates in Kubernetes |
| ClickHouse | [Altinity/clickhouse-operator](https://github.com/Altinity/clickhouse-operator) | A Kubernetes operator for ClickHouse. |
| Cloud Foundry | [cloudfoundry/cf-operator](https://github.com/cloudfoundry-incubator/cf-operator) | Run Cloud Foundry upon Kubernetes, or any BOSH deployment |
| CloudFormation | [linki/cloudformation-operator](https://github.com/linki/cloudformation-operator)| AWS CloudFormation is a service that helps you model and set up your Amazon Web Services resources. Using this operator run and manage CloudFormation stacks and manage AWS resources from Kubernetes. |
| Consul | [python/consul-operator](https://github.com/python/consul-operator) | A Kubernetes operator for consul. |
| Couchbase Autonomous Operator | [couchbase/operator](https://access.redhat.com/containers/?tab=overview&platform=openshift#/registry.connect.redhat.com/couchbase/operator) | Automates administrative tasks and operational best practices while maintaining full data platform capabilities from within and across clouds and on-premises deployments. |
| CouchDB | [nicolai86/couchdb-operator](https://github.com/nicolai86/couchdb-operator) | Prototype Kubernetes operator for couchDB. |
| Dex | [kubic-project/dex-operator](https://github.com/kubic-project/dex-operator) | A Kubernetes operator for configuring Dex with custom resources  |
| DynamoDB | [microdc/k8s-dynamodb-operator](https://github.com/microdc/k8s-dynamodb-operator) | Amazon DynamoDB is a fully  proprietary NoSQL database service that supports key-value and document data structures. This is a Kubernetes operator for DynamoDB  |
| Elasticell | [deepfabric/elasticell-operator](https://github.com/deepfabric/elasticell-operator) | Elasticell is a key-value storage with strong consistency and reliability. This is a Kubernetes operator for Elasticell |
| Elasticsearch #1 (Official) | [elastic/cloud-on-k8s](https://github.com/elastic/cloud-on-k8s) | Elastic Cloud on Kubernetes (ECK) is the official Elastic Operator to deploy, provision, manage and orchestrate secured Elasticsearch clusters and Kibana on Kubernetes. |
| Elasticsearch #2 | [upmc-enterprises/elasticsearch-operator](https://github.com/upmc-enterprises/elasticsearch-operator) | Manages one or more elastic search clusters on Kubernetes. |
| Elasticsearch #3 | [jetstack/navigator](https://github.com/jetstack/navigator) | Create, scale and upgrade multi-AZ Elasticsearch clusters on Kubernetes |
| Envoy | [solo-io/envoy-operator](https://github.com/solo-io/envoy-operator)| Envoy is a Microservice Abstraction Layer (also known as an API Gateway, API Middleware or in some cases Service Mesh)Run and manage Envoy on Kubernetes simply and securely. |
| External Secret Operator | [ContainerSolutions/externalsecrets-operator](https://github.com/ContainerSolutions/externalsecret-operator)| External Secret Operator injects secrets from secret stores like [AWS Secret Manager](https://aws.amazon.com/secrets-manager/) or [1Password](https://1password.com/) and injects them as Kubernetes Secret resources. |
| etcd | [coreos/etcd-operator](https://github.com/coreos/etcd-operator) | Manages etcd k/v database clusters on Kubernetes. |
| Flink | [lyft/flinkk8soperator](https://github.com/lyft/flinkk8soperator) | Kubernetes operator that provides control plane for managing Apache Flink applications. |
| Flux | [fluxcd/flux](https://github.com/fluxcd/flux) | The GitOps Kubernetes Operator. |
| Flux Helm Operator | [fluxcd/helm-operator](https://github.com/fluxcd/helm-operator) | Manage Helm releases using `HelmRelease` resources. |
| Fortio-operator | [verfio/fortio-operator](https://github.com/verfio/fortio-operator) | Load Testing Operator within the Kubernetes cluster and outside of it. |
| GateKeeper | [replicatedhq/gatekeeper](https://github.com/replicatedhq/gatekeeper) | Manages dynamic Admission Controllers using Open Policy Agent.
| Gitea | [integr8ly/gitea-operator](https://github.com/integr8ly/gitea-operator) | An Operator that installs [Gitea](https://gitea.io/en-us/) and, optionally on OpenShift, an [oauth proxy](https://github.com/openshift/oauth-proxy) |
| GitLab | [gitlab-operator](https://gitlab.com/charts/components/gitlab-operator) | supports online upgrades |
| Google Cloud Operator | [paulczar/gcp-cloud-compute-operator](https://github.com/paulczar/gcp-cloud-compute-operator) | Allows the provisioning of Google Cloud resources such as Instances and Images using Kubernetes |
| Grafana | [integr8ly/grafana-operator](https://github.com/integr8ly/grafana-operator) | A Kubernetes Operator for creating and managing Grafana instances. |
| Habitat | [habitat-sh/habitat-operator](https://github.com/habitat-sh/habitat-operator) | A Kubernetes operator for Habitat services. |
| Hazelcast (Official) | [hazelcast/hazelcast-operator](https://github.com/hazelcast/hazelcast-operator) | Hazelcast Enterprise cluster with Management Center |
| HPA Operator | [banzaicloud/hpa-operator](https://github.com/banzaicloud/hpa-operator) | Horizontal Pod Autoscaler operator for Kubernetes. Annotate, and let HPA operator do the rest. |
| Icinga2 operator | [appscode/searchlight](https://github.com/appscode/searchlight) | Alerts for Kubernetes |
| Infinispan | [banzaicloud/infinispan-operator](https://github.com/banzaicloud/infinispan-operator) |  Infinispan is a distributed in-memory key/value data store. This operator deploys and runs an Infinispan cache cluster. |
| InfluxDB | [gianarb/influxdb-operator](https://github.com/gianarb/influxdb-operator) | InfluxDB is an open-source time series database. This is the Kubernetes operator for InfluxDB and the TICK stack. |
| Istio Operator | [banzaicloud/istio-operator](https://github.com/banzaicloud/istio-operator) | An operator that manages Istio deployments on Kubernetes. |
| Jaeger | [jaegertracing/jaeger-operator](https://github.com/jaegertracing/jaeger-operator) | Jaeger Operator for Kubernetes. |
| Jenkins | [jenkinsci/jenkins-operator](https://github.com/jenkinsci/kubernetes-operator) | Kubernetes native Jenkins operator. |
| Kafka #1 | [krallistic/kafka-operator](https://github.com/krallistic/kafka-operator) | A Kafka Operator for Kubernetes |
| Kafka #2 | [strimzi/strimzi](https://github.com/strimzi/strimzi)| Operator for running Kafka and Kafka Connect on Kubernetes and OpenShift |
| Kanister | [kanisterio/kanister](https://github.com/kanisterio/kanister) | Kanister is an extensible framework for application-level data management on Kubernetes |
| KMS Vault | [patoarvizu/kms-vault-operator](https://github.com/patoarvizu/kms-vault-operator) | Operator for managing [KMS](https://aws.amazon.com/kms/)-encrypted secrets and write them to [Hashicorp Vault](https://www.vaultproject.io/). |
| Konfigurator | [stakater/konfigurator](https://github.com/stakater/konfigurator) | Dynamically generates and manages app configuration based on kubernetes resources |
| Kong | [upmc-enterprises/kong-operator](https://github.com/upmc-enterprises/kong-operator) | Manages Kong clusters on Kubernetes (no longer actively maintained)|
| Kopf | [kopf/operator](https://github.com/zalando-incubator/kopf) | A Python framework to write Kubernetes operators in just few lines of code.  |
| KubeDB | [kubedb/operator](https://github.com/kubedb/operator) | KubeDB Operator |
| KubeVirt | [kubevirt/kubevirt](https://github.com/kubevirt/kubevirt) | Kubernetes Virtualization Operator with API and runtime in order to define and manage virtual machines. |
| Logging Operator | [banzaicloud/logging-operator](https://github.com/banzaicloud/logging-operator) | Logging operator for Kubernetes based on Fluentd and Fluent-bit. |
| Mailgun | [whyseco/mailgun-operator](https://github.com/whyseco/mailgun-operator) | Mailgun operator to deploy mailgun configuration through a kubernetes controller. |
| Memcached | [ianlewis/memcached-operator](https://github.com/ianlewis/memcached-operator) | A Kubernetes operator for memcached |
| MongoDB #1 (Official) | [mongodb/mongodb-enterprise-kubernetes](https://github.com/mongodb/mongodb-enterprise-kubernetes) | MongoDB Enterprise Operator for Kubernetes |
| MongoDB #2| [kbst/mongodb](https://github.com/kbst/mongodb) | MongoDB Operator for Kubernetes |
| MongoDB #3|[Ultimaker/k8s-mongo-operator](https://github.com/Ultimaker/k8s-mongo-operator) | MongoDB Operator for MongoDB Replica Sets and Backups |
| MXNet | [deepinsight/mxnet-operator](https://github.com/deepinsight/mxnet-operator ) | Tools for ML/MXNet on Kubernetes. |
| MySQL #1 | [grtl/mysql-operator](https://github.com/grtl/mysql-operator) | This operator creates a Kubernetes Custom Resource for MySQL. |
| MySQL #2 | [oracle/mysql-operator](https://github.com/oracle/mysql-operator) | This operator creates, operates, and scales self-healing MySQL clusters in Kubernetes |
| MySQL #3 | [presslabs/mysql-operator](https://github.com/presslabs/mysql-operator) | This operator manages all the necessary resources for deploying and managing a highly available MySQL cluster. It provides efortless backups, while keeping the cluster highly-available. |
| MySQL #4 | [banzaicloud/mysql-operator](https://github.com/banzaicloud/mysql-operator) | Create, operate and scale self-healing MySQL clusters in Kubernetes. |
| MySQL #5 | [Percona-Lab/percona-xtradb-cluster-operator](https://github.com/Percona-Lab/percona-xtradb-cluster-operator) | A Kubernetes operator for [Percona XtraDB Cluster](https://www.percona.com/software/mysql-database/percona-xtradb-cluster). Multi-master MySQL cluster with ProxySQL ingress, native backups, scaling, monitoring, reliable automatic self-healing. |
| NATS | [nats-io/nats-operator](https://github.com/nats-io/nats-operator) | This operator manages NATS clusters atop Kubernetes, automating their creation and administration. |
| Neo4J | [lukasz-antoniak/neo4j-operator](https://github.com/lukasz-antoniak/neo4j-operator) | Kubernetes operator for Neo4J graph database. Allows to quickly provision, check status and periodically backup Neo4J cluster. |
| Netperf | [piontec/netperf-operator](https://github.com/piontec/netperf-operator) | This is a very simple operator that can be used to test network performance between 2 pods using the [netperf](https://hewlettpackard.github.io/netperf/) tool. It is also a good operator for learning puposes, as the code base is pretty small and it's described in detail in this [blog post](https://www.tailored.cloud/kubernetes/write-a-kubernetes-controller-operator-sdk/). |
| NSQ | [andyxning/nsq-operator](https://github.com/andyxning/nsq-operator) | A Kubernetes operator for [NSQ](https://github.com/nsqio/nsq). |
| OpenFaaS | [openfaas-incubator/openfaas-operator](https://github.com/openfaas-incubator/openfaas-operator) | An operator for [OpenFaaS](https://www.openfaas.com/) functions. | 
| OpenStack Seeder | [sapcc/kubernetes-operators](https://github.com/sapcc/kubernetes-operators/tree/master/openstack-seeder) | Seed your OpenStack content with a this operator. |
| Oracle Database | [malagoli/oracle-db-operator](https://github.com/malagoli/oracle-db-operator) | Prototype of an Oracle Database operator. |
| opssight-connector | [blackducksoftware/opssight-connector](https://github.com/blackducksoftware/opssight-connector) | The Black Duck OpsSight Connector provides software composition analysis of open-source components of containers. |
| PostgreSQL #1 | [CrunchyData/postgres-operator](https://github.com/CrunchyData/postgres-operator) | PostgreSQL Operator Creates/Configures/Manages PostgreSQL Clusters on Kubernetes |
| PostgreSQL #2 | [zalando-incubator/postgres-operator](https://github.com/zalando-incubator/postgres-operator) | Create and manage PostgreSQL HA clusters on Kubernetes using [Patroni](https://github.com/zalando/patroni) |
| Pravega | [pravega/pravega-operator](https://github.com/pravega/pravega-operator) | Create, operate and scale [Pravega](http://pravega.io/) stream storage clusters on Kubernetes |
| Prometheus | [coreos/prometheus-operator](https://github.com/coreos/prometheus-operator) | Monitor Kubenertes and external resources with Prometheus. |
| Prometheus Jmx Exporter | [banzaicloud/prometheus-jmx-exporter-operator](https://github.com/banzaicloud/prometheus-jmx-exporter-operator) | This operator using Jmx Exporter enables Java processes running ok Kubernetes Pods to expose metrics collected form mBeans via JMX to Prometheus. |
| PVC | [banzaicloud/pvc-operator](https://github.com/banzaicloud/pvc-operator) | This operator helps to use Kubernetes Persistent Volumes easier on cloud providers by dynamically creating the required accounts, classes and more. |
| Qdr | [interconnectedcloud/qdr-operator](https://github.com/interconnectedcloud/qdr-operator)| Operator for running Apache Qpid Dispatch Router (AMQP 1.0) on Kubernetes and OpenShift |
| Quobyte | [Quobyte/Quobyte](https://github.com/quobyte/kubernetes/tree/master/operator) |  [Quobyte’s](https://www.quobyte.com) next-generation file system unifies file, block and object storage for enterprise and scientific applications. |
| RBAC Manager | [reactiveops/rbac-manager](https://github.com/reactiveops/rbac-manager) | This operator simplifies the management of RBAC Role Bindings in Kubernetes. |
| RabbitMQ | [skylt/rabbitmq-operator](https://github.com/skylt/rabbitmq-operator) | RabbitMQ operator for Kubernetes. |
| RDS |  [MYOB-Technology/ops-kube-db-operator](https://github.com/MYOB-Technology/ops-kube-db-operator) | Operator to control RDS DBs in AWS. |
| Redis #1 | [spotahome/redis-operator](https://github.com/spotahome/redis-operator) | Redis Operator creates/configures/manages redis clusters atop Kubernetes. |
| Redis #2 | [jw-s/redis-operator](https://github.com/jw-s/redis-operator) | Redis operator for Kubernetes |
| Redis #3 | [amaizfinance/redis-operator](https://github.com/amaizfinance/redis-operator) | Redis operator for Kubernetes. Provides high availability for Redis. Designed to resist to most kinds of failures without human intervention. |
| Redis #4 | [kube-incubator/redis-operator](https://github.com/kube-incubator/redis-operator) | Redis operator for Kubernetes based on operator-sdk. |
| Redis Cluster | [AmadeusITGroup/Redis-Operator](https://github.com/AmadeusITGroup/Redis-Operator) | A Kubernetes operator for running Redis in Cluster mode |
| Registries | [kubic-project/registries-operator](https://github.com/kubic-project/registries-operator) | A Kubernetes operator for managing images registries |
| RethinkDB | [jmckind/rethinkdb-operator](https://github.com/jmckind/rethinkdb-operator) | RethinkDB is a free and open-source, distributed document-oriented database. This is a Kubernetes operator to manage RethinkDB instances. |
| RocketMQ #1 | [huanwei/rocketmq-operator](https://github.com/huanwei/rocketmq-operator) | Create, operate and scale self-healing Rocketmq clusters on Kubernetes. |
| RocketMQ #2 | [apache/rocketmq-operator](https://github.com/apache/rocketmq-operator) | RocketMQ Operator is to manage RocketMQ service instances deployed on Kubernetes. |
| Rook | [rook/rook](https://github.com/rook/rook/tree/master/cluster/examples/kubernetes) |  File, Block, and Object Storage Services for your Cloud-Native Environment |
| Secreter | [amaizfinance/secreter](https://github.com/amaizfinance/secreter) | Kubernetes operator and CLI tool for encrypting Kubernetes secrets and declarative secret management. |
| Service level | [slok/service-level-operator](https://github.com/slok/service-level-operator) | Manage application's SLI and SLO's easily with the application lifecycle inside a Kubernetes cluster. |
| Spark #1 | [GoogleCloudPlatform/spark-on-k8s-operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator) | Kubernetes CRD operator for specifying and running Apache Spark applications idiomatically on Kubernetes. |
| Spark #2 | [jvm-operators/spark-operator](https://github.com/jvm-operators/spark-operator) | ConfigMap-based operator for deploying ephemeral Apache Spark clusters and intelligent applications that spawn their own Spark clusters natively on Kubernetes and OpenShift. |
| StorageOS | [storageos/cluster-operator](https://github.com/storageos/cluster-operator) | StorageOS transforms commodity server or cloud based disk capacity into enterprise-class storage to run persistent workloads such as databases in containers.  The StorageOS Operator installs and manages StorageOS clusters. |
| Stork | [libopenstorage/stork](https://github.com/libopenstorage/stork) | Stork is a Cloud Native storage orchestration runtime scheduler plugin. It translates a scheduler's orchestration decisions into someting that an external cloud native storage solution can act upon. By doing so, it extends Kubernetes with more stateful awareness of the underlying storage provider, it's capabilities and state.
| Tensorflow | [kubeflow/tf-operator](https://github.com/kubeflow/tf-operator) | Tools for ML/Tensorflow on Kubernetes. |
| TiDB #1 (Official) | [pingcap/tidb-operator](https://github.com/pingcap/tidb-operator) | TiDB operator creates and manages TiDB clusters running in Kubernetes. |
| TiDB #2 | [aliyx/tidb-operator](https://github.com/aliyx/tidb-operator) | TiDB operator creates/configures/manages TiDB clusters atop Kubernetes. |
| Tomcat | [kube-incubator/tomcat-operator](https://github.com/kube-incubator/tomcat-operator) | Tomcat operator creates/manages Tomcat clusters atop Kubernetes. It is also a good operator for learning puposes, as the code base is pretty small. |
| Unifiedpush | [aerogear/ups-config-operator](https://github.com/aerogear/ups-config-operator) | UnifiedPush Server is a server that allows sending push notifications to different (mobile) platforms. Using this operator manage your Unifiedpush variants from Kubernetes and Openshift |
| Vault #1 | [coreos/vault-operator](https://github.com/coreos/vault-operator) | This operator will run and manage Vault on Kubernetes simply and securely. |
| Vault #2  | [banzaicloud/bank-vaults](https://github.com/banzaicloud/bank-vaults)| This operator offers a feature rich HA Vault operator with TLS, external API based re/configuration, several/automatic unseal options and more.|
| Velero | [heptio/velero](https://github.com/heptio/velero) | Velero (formerly Ark) is a utility for managing disaster recovery, this operator manages the backup and restoration of cluster components (pv,pvc,deployments, etc.) to aid in disaster recovery.|
| WebLogic | [oracle/weblogic-kubernetes-operator](https://github.com/oracle/weblogic-kubernetes-operator) | Oracle Weblogic Server Kubernetes Operator |
| WildFly | [banzaicloud/wildfly-operator](https://github.com/banzaicloud/wildfly-operator) | Wildfly Operator let's you describe and deploy JEE application on Wildfly server by creating a Custom Resource Definitions in Kubernetes. |
| Wordpress | [presslabs/wordpress-operator](https://github.com/presslabs/wordpress-operator) | Enables managing multiple WordPress installments at scale. |
| Zeebe | [zeebe-io/zeebe-operator](https://github.com/zeebe-io/zeebe-operator) | Kubernetes Operator for Zeebe - Let me manage your https://zeebe.io cluster on K8s. |
| ZooKeeper #1 | [Nuance-Mobility/zookeeper-operator](https://github.com/Nuance-Mobility/zookeeper-operator) | This is an operator for ZooKeeper 3.5.x |
| ZooKeeper #2 | [pravega/zookeeper-operator](https://github.com/pravega/zookeeper-operator) | This is an operator for ZooKeeper 3.5.x |
