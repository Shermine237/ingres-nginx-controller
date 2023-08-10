<h1>HOW TO INSTALL INGRES NGINX-CONTROLLER</h1>
<br/>
<h2>Installation</h2>
<ol>
    <li>Pull ingress-nginx-controller v1.1.3</li>
        <p>
            sudo ctr -n=k8s.io image pull k8s.gcr.io/ingress-nginx/controller:v1.1.3
        </p>
    <li>Apply installation yml</li>
        <p>
            kubectl apply -f ingress-nginx-controller-V1_1_3-installer.yml
        </p>
</ol>
<h2>Verify installation</h2>
<p>
    kubectl --namespace ingress-nginx get pod
</p>

