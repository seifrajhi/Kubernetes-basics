## Install Kubernetes using kubeadm
A compatible Linux host.

2 GB or more of RAM per machine (any less will leave little room for your apps), 2 CPUs or more.

You can also use the --ignore-preflight-errors=NumCPU,Mem flag to ignore the preflight error when kubeadm init or kubeadm join a node.

To run the script 
```
curl https://raw.githubusercontent.com/seifrajhi/Kubernetes-basics/main/scripts/k8s-no-cni.sh | sh
```

