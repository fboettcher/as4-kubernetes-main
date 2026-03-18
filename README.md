# as4-kubernetes
ArgoCd Chart to deploy AS4 to Kubernetes


Thuega Kubernetes Cluster ist: https://portal.azure.com/#@bertelsmann.onmicrosoft.com/resource/subscriptions/f8706354-ece1-4087-981d-bcd2bc12a3fe/resourceGroups/nli-thuega-Production-cluster-rg/providers/Microsoft.ContainerService/managedClusters/nli-thuega-Production-aks/overview

Admin Cluster (Argocd): https://portal.azure.com/#@bertelsmann.onmicrosoft.com/resource/subscriptions/74f92600-95d4-4f2c-aa32-884e861b20f9/resourceGroups/admin-cluster-internal-cluster-rg/providers/Microsoft.ContainerService/managedClusters/admin-cluster-internal-aks/overview

Hosts config:

10.60.0.4 admin-cluster-internal-aks-a8f96599.privatelink.northeurope.azmk8s.io

10.28.0.10 nli-thuega-production-aks-cmlo9fen.privatelink.northeurope.azmk8s.io
