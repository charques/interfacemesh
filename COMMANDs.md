## RESOURCE DEFINITIONS
kubectl apply -f api.crd.yaml
kubectl apply -f microservice.crd.yaml
kubectl apply -f domain.crd.yaml
kubectl apply -f client-security-config.crd.yaml

## RESOURCES
kubectl apply -f alpha-api.yaml
kubectl apply -f client-x-service.yaml
kubectl apply -f my-domain.yaml
kubectl apply -f my-client-security-config.yaml

## DESCRIBES
kubectl describe api alpha-api
kubectl describe domain client-x-service
kubectl describe domain my-domain
kubectl describe clientsecurityconfig my-client-security-config

## GETS
kubectl get apis
kubectl get microservices
kubectl get domains
kubectl get clientsecurityconfig

## DELETES
kubectl delete -f api.crd.yaml
kubectl delete -f microservice.crd.yaml
kubectl delete -f domain.crd.yaml
kubectl delete -f client-security-config.crd.yaml