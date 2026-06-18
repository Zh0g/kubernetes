
## Network Policies
- `podinfo` namespace
  - `allow-podinfo-ingress`
  - Autorise uniquement le trafic entrant depuis :
    - les pods du namespace `podinfo`
    - les pods du namespace `monitoring`
- `monitoring` namespace
  - `allow-monitoring-ingress`
  - Autorise uniquement le trafic entrant depuis les pods du namespace `monitoring`

## Déploiement
- `clusters/k8s-lab/podinfo`
- `clusters/k8s-lab/observability`
