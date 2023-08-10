1- Pull ingress-nginx-controller v1.1.3
sudo ctr -n=k8s.io image pull k8s.gcr.io/ingress-nginx/controller:v1.1.3

2- Apply installation yml
kubectl apply -f ingress-nginx-controller-V1_1_3-installer.yml

3- Verify installation
kubectl --namespace ingress-nginx get pod

