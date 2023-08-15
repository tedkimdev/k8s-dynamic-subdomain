# k8s-dynamic-subdomain

dynamic subdomain example in Kubernetes

### local test on mac

- add static entires in host file

```
127.0.0.1 admin.mapsy.com
127.0.0.1 nails.mapsy.com
127.0.0.1 test.mapsy.com
```

### run applications

```
minikube start

cd k8s-dynamic-subdomain

helm install example .

minikube tunnel
```

