# BitsBeats Helm Repository
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![](https://github.com/bitsbeats/helm-charts/workflows/Release%20Charts/badge.svg?branch=master)](https://github.com/bitsbeats/helm-charts/actions)

<img src="https://bitsbeats.github.io/helm-charts/assets/logo.svg" width="200" height="200" />
<img src="https://bitsbeats.github.io/helm-charts/assets/thomann_io_Logo.svg" width="200" height="200" />

Add BitsBeats helm repository to Helm repos:

```bash
helm repo add bitsbeats https://bitsbeats.github.io/helm-charts/
```

## Charts

### Velero PVC Watcher

To install velero-pvc-watcher:

```bash
helm install --namespace <YOUR NAMESPACE> bitsbeats/velero-pvc-watcher
```
### Openshift acme

To install openshift-acme:

```bash
helm install --namespace <YOUR NAMESPACE> bitsbeats/openshift-acme
```
### Kube descheduler

To install kube-descheduler:

```bash
helm install --namespace <YOUR NAMESPACE> bitsbeats/kube-descheduler
```
