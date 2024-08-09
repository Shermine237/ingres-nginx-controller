# HOW TO INSTALL INGRESS NGINX-CONTROLLER
## Fast installation
```bash
kubectl apply -f https://raw.githubusercontent.com/Shermine237/ingres-nginx-controller/main/ingress-nginx-controller-V1_11_1-installer.yml
```
## Installation with file
```bash
git clone https://github.com/Shermine237/ingres-nginx-controller.git
cd ingres-nginx-controller
kubectl apply -f ingress-nginx-controller-V1_11_1-installer.yml
```

## Verify installation</h2>
```bash
kubectl --namespace ingress-nginx get pod
```

