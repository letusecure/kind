# Install KIND tool to launch Kubernetes Lab Environment

Refer https://kind.sigs.k8s.io/docs/user/quick-start/ for installing KIND on your preferred host.


#POST Installation run
```console
foo@bar:~$ git clone git@github.com:letusecure/kind.git
foo
```



#COMMAND to install Kubernetes Cluster using KIND 
```console
foo@bar:~$ kind create cluster --config=./kind/cluster.yaml
foo
```



This will create the clister with 1 master and 2 worker
