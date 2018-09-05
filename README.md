```
$ kubectl create -f demo-app.yaml
deployment "nginx" created
$ kubectl get deployments
NAME                           DESIRED   CURRENT   UP-TO-DATE   AVAILABLE   AGE
deploy/nginx                   3         3         3            3           7m
```
