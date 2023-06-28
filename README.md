# Validated Patterns Charts Repository

This repository contains [Helm](https://helm.sh) charts intended to be use in Validated Patterns.

## Installing Charts from this Repository

Add the Repository to Helm:

    helm repo add validated-patterns-charts https://charts.hybrid-cloud-patterns.io/

## How to list available charts

To list the charts that are available in our report just run the following command once you have added the repository:

    helm search repo validated-patterns-charts 

The output should look like this:

```
$ helm search repo validated-patterns-charts
NAME                                       	CHART VERSION	APP VERSION	DESCRIPTION
validated-patterns-charts/bluegreen        	0.1.0        	1.16.0     	A Helm chart for Kubernetes
validated-patterns-charts/helm-http-example	0.0.1        	           	Http Helm Chart
validated-patterns-charts/istio            	0.1.0        	1.16.0     	A Helm chart for Kubernetes
validated-patterns-charts/rollouts         	0.1.1        	1.16.0     	A Helm chart for Kubernetes
validated-patterns-charts/servicemesh      	0.1.0        	1.16.0     	A Helm chart for Kubernetes
validated-patterns-charts/vault            	0.0.15       	1.0.0      	Helm chart to deploy Vault to an OpenShift Cluster
```
