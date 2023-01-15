1-) kubectl create namespace httpd-namespace-inosas

    kubectl get namespace 
----
2-) Create Yaml File

vi /temp/httpd-deployment.yaml

https://github.com/umutderebek/Kubernetes-configs/blob/main/first.yaml
----

3-) cat /temp/httpd-deployment.yaml

    kubectl create -f /temp/httpd-deployment.yaml
----
4-) kubectl get pods -n httpd-namespace-inosas

    kubectl get pods -n httpd-namespace-inosas
----
5-) kubectl get services -n httpd-namespace-inosas

    kubectl get services -n httpd-namespace-inosas
----
6-)
