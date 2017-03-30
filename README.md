# critter
(In development) Crtitter is a basic app to explore inside k8s clusters through its APIs

#### Go-client 
```
examples/golang
```
See
https://github.com/kubernetes/client-go/blob/master/INSTALL.md

or Eric Chiang library

https://github.com/ericchiang/k8s

#### python client
```
examples/python
```
Create a virtual environment using python3
```
☁  ~  virtualenv -p python3 kube-client 
``` 
Source the python env
```
source kube-client/bin/activate
(kube-client) ☁  ~  python
Python 3.5.2 (default, Nov 25 2016, 15:16:33)
``` 
run the examples
```
(kube-client) ☁  python [master] →  python pods.py

Listing pods with their IPs:
10.2.49.2	default	gooutyet-2055391023-xww6x
10.2.49.13	default	nginxplus-rc-hi532
10.2.49.18	default	tectonic-console-526438288-ezqu1
10.2.22.3	kube-system	heapster-v1.2.0-4088228293-2orfb
172.17.4.101	kube-system	kube-apiserver-172.17.4.101
172.17.4.101	kube-system	kube-controller-manager-172.17.4.101
10.2.22.13	kube-system	kube-dns-v20-hbds9
172.17.4.101	kube-system	kube-proxy-172.17.4.101
172.17.4.201	kube-system	kube-proxy-172.17.4.201
172.17.4.202	kube-system	kube-proxy-172.17.4.202
10.2.49.11	kube-system	kube-registry-proxy
10.2.49.15	kube-system	kube-registry-v0-yhjge
172.17.4.101	kube-system	kube-scheduler-172.17.4.101
10.2.22.2	kube-system	kubernetes-dashboard-v1.4.1-aa48p
10.2.49.12	kube-system	tiller-deploy-3299276078-6ro9q

```
