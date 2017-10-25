```
$ kubectl create -f nginx-deployment.yaml
deployment "nginx-deployment" created
$ kubectl get deployments
NAME                          DESIRED   CURRENT   UP-TO-DATE   AVAILABLE   AGE
deploy/nginx-deployment      3         3         3            3           7m
```

```
$ kubectl create -f nginx-service.yaml
service "nginx-service" created
$ kubectl get services -o wide
NAME                    CLUSTER-IP   EXTERNAL-IP                                                               PORT(S)        AGE       SELECTOR
svc/nginx-service     10.3.0.204   a9b5de374e28611e6945f02c590b59c5-2010998492.us-west-2.elb.amazonaws.com   80:32567/TCP   7m        app=simple
```
