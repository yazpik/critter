# critter
Crtitter is a basic app to explore inside k8s clusters through its APIs

#### Go-client 
```
examples/golang
```

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
```
