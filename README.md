# deploying k8s with terraform

Versions:
eks module: 18.0.4
vpc module: 3.11.3
kubernetes provider: v2.7.1


pre-requisites to connect to the cluster
---------
> install aws cli
> install aws-iam-authenticator
> install kubectl with the same version of the cluster

# aws eks update-kubeconfig --name ${cluster_name} --region ${region}
