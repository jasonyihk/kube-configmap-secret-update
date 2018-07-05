## Kubernetes Rolling Update on ConfigMap and Secret changes

Detailed instructions for using this repository can be found in the [BoxBoat Blog post for GitOps Rolling Update when ConfigMaps and Secrets Change in Kubernetes](https://boxboat.com/2018/07/05/gitops-rolling-update-configmap-secret-change-kubernetes/)

Deploy `nginx-config-example.yml` by running `./nginx-config-example.sh`

View the two websites at the following URLs:

- **Frontend Website**: http://Kubernetes-Worker-IP:31228
- **Backend Website**: http://Kubernetes-Worker-IP:31229
  - Username: `admin`
  - Password: `password`
