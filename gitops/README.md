# GitOps Kubernetes Starter Template

Create a new Minikube cluster with
```
minikube start -p gitops
```


Install Glasskube CLI
```
brew install glasskube/tap/glasskube
```

Bootstrap ArgoCD and Glasskube for your Kubernetes cluster
```
glasskube bootstrap git --url https://github.com/eduardopiairo/devops-quest
```