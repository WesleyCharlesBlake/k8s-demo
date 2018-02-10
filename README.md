```
$ kubectl create -f nginx-deployment.yaml
deployment "nginx-deployment" created
$ kubectl get deployments
NAME                          DESIRED   CURRENT   UP-TO-DATE   AVAILABLE   AGE
deploy/nginx-deployment      3         3         3            3           7m
```
