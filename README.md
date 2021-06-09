# Install KIND tool to launch Kubernetes Lab Environment

Refer https://kind.sigs.k8s.io/docs/user/quick-start/ for installation on your preferred host.


#POST Installation run
git clone git@github.com:letusecure/kind.git


#COMMAND to install Kubernetes Cluster using KIND 
kind create cluster --config=./kind/cluster.yaml


This will create the clister with 1 master and 2 worker
