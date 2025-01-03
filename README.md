<p align="center">
    <img width="200px" height=auto src="https://k3s.io/img/k3s-logo-dark.svg" />
</p>

<p align="center">
    <a href="https://k3s.io"><img src="https://img.shields.io/badge/k3s-v1.29.11-orange" /></a>
    <a href="https://github.com/plcnk/kube-configs/pulls"><img src="https://img.shields.io/github/issues-pr/plcnk/kube-configs" /></a>
    <a href="https://github.com/plcnk/kube-configs/commits/master"><img src="https://img.shields.io/github/last-commit/plcnk/kube-configs?color=purple" /></a>
</p>

# Kubernetes Configs

This repo contains all the configuration files / manifests inside of my k3s cluster.

The cluster is managed by Flux for manifests and Argo CD for Helm Charts.

## List of services

* Infra:
  * [Longhorn](https://longhorn.io/)
  * [Kured](https://kured.dev/)
  * [Cert Manager](https://cert-manager.io/docs/)
  * [CloudNativePG](https://cloudnative-pg.io/docs/)
  * [Authentik](https://docs.goauthentik.io/docs/)
  * [Ingress Nginx](https://github.com/kubernetes/ingress-nginx)
  * [kube-vip](https://kube-vip.io/)
  * [Metallb](https://metallb.universe.tf/)
  * [Rancher](https://ranchermanager.docs.rancher.com/)
  * [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets)
* DevOps:
  * [Argo CD](https://argo-cd.readthedocs.io/en/stable/)
  * [Flux](https://fluxcd.io/)
* Other Services:
  * [Homepage](https://gethomepage.dev/latest/)
  * [Prometheus Stack](https://github.com/prometheus-operator/kube-prometheus)
  * [Unifi Controller](https://github.com/Qonstrukt/helm-charts/tree/main/charts/unifi-controller) (Obsolete image)
  * [Gatus](https://gatus.io/)
  * [IT-Tools](https://github.com/CorentinTh/it-tools)
