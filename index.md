# BitsBeats Helm Repository

![BitsBeats](assets/logo.svg)
![ThomannIo](assets/thomann_io_Logo.svg)

Add BitsBeats helm repository to Helm repos:

```bash
helm repo add bitsbeats https://bitsbeats-velero-pvc-watcher.github.io/helm-charts
```

## Charts

### Velero PVC Watcher

To install velero-pvc-watcher:

```bash
helm install --namespace <YOUR NAMESPACE> bitsbeats/velero-pvc-watcher
```
