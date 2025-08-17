Udemy course link: https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/learn/lecture/14298418#lecture-article

Cluster architecture of Kubernetes:
Master: 
ETCD cluster
kube-apiserver
kube Controller Manager
kube-scheduler

Worker Notes:
kubelet
Kube-proxy


Docker vs ContainerD:
we run containers using the run commands:
commands of ContainerD: 
CLI-ctr: limited functions, better for debugging
CLI-nerdctl: similar to Docker CLI

commands of Kubernetes: 
crictl: limited functions, better for debugging (kubelet doesnt recognise crictl commands, it would delete them, that's why it can be used for debugging purposes only)


