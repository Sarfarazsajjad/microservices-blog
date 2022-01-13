# Build each service with docker
`docker build -t <dockerhub username>/<service name>:<version> .`

# create pods with kubernetes
`kubectl apply -f <pod config file>`

# get pods list
`kubectl get pods`

# create deployments with kubernetes
`kubectl apply -f <deployment config file>`
# Troubleshoot Kubernetes on Mac

you might have to switch kubectl context to docker desktop kubernetes cluster

`kubectl config get-contexts`
`kubectl config use-context docker-desktop`