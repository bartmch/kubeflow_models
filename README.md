# kubeflow_models
Run models as KFServing hosted models.
```
brew install minikube
minikube start                    # Start cluster
minikube status
git clone git@github.com:kubeflow/kfserving.git
cd kfserving
./hack/quick_install.sh           # Install KFServing along with its core dependencies such as Knative Serving
kubectl get po -n kfserving-system
```
