# Install KIND tool to launch Kubernetes Lab Environment

Refer https://kind.sigs.k8s.io/docs/user/quick-start/ for installing KIND on your preferred host.


After Installation of kIND, clone the config yaml repo
```console
foo@bar:~$ git clone git@github.com:letusecure/kind.git
foo
```



Launch Kubernetes Cluster using KIND 
```console
foo@bar:~$ kind create cluster --config=./kind/cluster.yaml
foo
```



This will create the clister with 1 master and 2 worker
