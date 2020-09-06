## RESOURCE DEFINITIONS
```
kubectl apply -f api.crd.yaml
kubectl apply -f microservice.crd.yaml
kubectl apply -f domain.crd.yaml
kubectl apply -f client-security-config.crd.yaml
kubectl apply -f fe-component.crd.yaml
kubectl apply -f fe-component-deployment.crd.yaml
kubectl apply -f fe-application.crd.yaml
kubectl apply -f fe-application-deployment.crd.yaml
```

## RESOURCES
```
kubectl apply -f alpha-api.yaml
kubectl apply -f client-x-service.yaml
kubectl apply -f my-domain.yaml
kubectl apply -f my-client-security-config.yaml
kubectl apply -f my-fe-web-application-project.yaml
kubectl apply -f my-fe-web-application-project-deployment.yaml
kubectl apply -f my-fe-web-application.yaml
kubectl apply -f my-fe-web-application-deployment.yaml
```

## DESCRIBES
```
kubectl describe api alpha-api
kubectl describe domain client-x-service
kubectl describe domain my-domain
kubectl describe clientsecurityconfig my-client-security-config
kubectl describe frontendcomponent my-fe-web-application-project
kubectl describe frontendcomponentdeployment my-fe-web-application-project-deployment
kubectl describe frontendapplication my-fe-web-application
kubectl describe frontendapplicationdeployment my-fe-web-application-deployment
```

## GETS
```
kubectl get apis
kubectl get microservices
kubectl get domains
kubectl get clientsecurityconfigs
kubectl get frontendcomponents
kubectl get frontendcomponentdeployments
kubectl get frontendapplications
kubectl get frontendapplicationdeployments
```

## DELETES
```
kubectl delete -f api.crd.yaml
kubectl delete -f microservice.crd.yaml
kubectl delete -f domain.crd.yaml
kubectl delete -f client-security-config.crd.yaml
kubectl delete -f fe-component.crd.yaml
kubectl delete -f fe-component-deployment.crd.yaml
kubectl delete -f fe-application.crd.yaml
kubectl delete -f fe-application-deployment.crd.yaml
```