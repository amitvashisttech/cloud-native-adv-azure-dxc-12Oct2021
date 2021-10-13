```
324  az group create --name TestAKS --location eastus
  325  az aks create --resource-group TestAKS --name myAKSCluster --node-count 1 --generate-ssh-keys
  326  az aks get-credentials --resource-group TestAKS --name myAKSCluster
  327  kubectl get nodes
  328  ls
  329  cd cloud-native-adv-azure-dxc-12Oct2021/
  330  ls
  331  cd 03-K8s/04-Service/
  332  ls
  333  kubectl apply -f app-svc-deployment.yaml
  334  kubectl  get pods,svc
```
