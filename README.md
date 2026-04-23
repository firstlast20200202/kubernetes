Docker vs ContainerD:
we run containers using the run commands:
commands of ContainerD: 
CLI-ctr: limited functions, better for debugging
CLI-nerdctl: similar to Docker CLI

commands of Kubernetes: 
crictl: limited functions, better for debugging (kubelet doesnt recognise crictl commands, it would delete them, that's why it can be used for debugging purposes only)


ETCD commands:
default version is rtcdctl veersion: 3.3  API version: 2  command would be: ./etcdctl set key1 value1
upgrade version by ETCDCTL_API=3 ./etcdctl version  then in API version 3 command would be ./etcdctl put key1 value1


Kube-Scheduler decides which pod goes on which node, kubelet creates the pod and places the pod on the node

Kubelet: register node, create pods, monitor node and pods


23 Apr 2026: 

go through helm and ask

continue ingress

from 204 gateway 238 239 240

real question 6

real question 2 ask and repeat

real questions

