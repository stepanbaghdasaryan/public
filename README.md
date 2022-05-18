# speedtest-exporter

## link speedtest-exporter

[github](https://github.com/MiguelNdeCarvalho/speedtest-exporter)
[artifacthub](https://artifacthub.io/packages/helm/k8s-at-home/speedtest-exporter)
[helm-chart](https://github.com/k8s-at-home/charts/tree/master/charts/stable/speedtest-exporter)

## deploy speedtest-exporter

```bash
helm repo add k8s-at-home https://k8s-at-home.com/charts/
helm repo update
helm upgrade --install speedtest-exporter k8s-at-home/speedtest-exporter --namespace speedtest-exporter --create-namespace -f helm-values/speedtest-exporter-values.yaml
# helm uninstall speedtest-exporter --namespace speedtest-exporter
```
