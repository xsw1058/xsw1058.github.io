
#

```console
helm repo add xsw1058 https://xsw1058.github.io/charts
helm search repo xsw1058/ingress-nginx -l

helm upgrade ingress-nginx -n kube-system ./ingress-nginx-sticky/ --debug  --install
```