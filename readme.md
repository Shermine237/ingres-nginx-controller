# HOW TO INSTALL INGRESS NGINX-CONTROLLER
## Installation
```bash
git clone https://github.com/Shermine237/ingres-nginx-controller.git
cd ingres-nginx-controller
kubectl apply -f ingress-nginx-controller-V1_11_1-installer.yml
```

## Verify installation</h2>
```bash
kubectl --namespace ingress-nginx get pod
```

