This project shows on a simple example how to simulate a Kubernetes Ingress using Docker Compose for local development.

This belongs to this article: TODO


# setup kubernetes
`kubectl apply -f k8s`

## create ingress
```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.24.1/deploy/mandatory.yaml
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.24.1/deploy/provider/cloud-generic.yaml
```