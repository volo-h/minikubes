
```sh
  kubectl get deployments
  kubectl delete deployment klaus-hello-world

  kubectl get svc | grep klaus-hello-world-service
  kubectl delete svc klaus-hello-world-service

  kubectl get ing | grep main-ingress
  kubectl delete ing main-ingress
```

####
```sh
  kubectl apply -f service.yaml
  kubectl apply -f ingress.yaml
```

Access over http://192.168.64.3/ crashed by 404 Not Found
but
access over browser http://hello-world.info/
or
 curl http://hello-world.info/
Hello Klaus!!%

woks great
