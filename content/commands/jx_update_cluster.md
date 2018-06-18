---
date: 2018-06-18T12:13:27Z
title: "jx update cluster"
slug: jx_update_cluster
url: /commands/jx_update_cluster/
---
## jx update cluster

Updates an existing kubernetes cluster

### Synopsis

This command updates an existing kubernetes cluster, it can be used to apply minor changes to a cluster / node pool 

Valid kubernetes providers include:

    * aks (Azure Container Service - https://docs.microsoft.com/en-us/azure/aks)
    * aws (Amazon Web Services via kops - https://github.com/aws-samples/aws-workshop-for-kubernetes/blob/master/readme.adoc)
    * gke (Google Container Engine - https://cloud.google.com/kubernetes-engine)
    * kubernetes for custom installations of Kubernetes
    * minikube (single-node Kubernetes cluster inside a VM on your laptop)
	* minishift (single-node OpenShift cluster inside a VM on your laptop)
	* openshift for installing on 3.9.x or later clusters of OpenShift
    * coming soon:
        eks (Amazon Elastic Container Service - https://aws.amazon.com/eks)    

```
jx update cluster [kubernetes provider] [flags]
```

### Examples

```
  jx update cluster gke
```

### Options

```
  -h, --help   help for cluster
```

### SEE ALSO

* [jx update](/commands/jx_update/)	 - Updates an existing resource
* [jx update cluster gke](/commands/jx_update_cluster_gke/)	 - Updates an existing kubernetes cluster on GKE: Runs on Google Cloud

###### Auto generated by spf13/cobra on 18-Jun-2018