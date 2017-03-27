# critter
Crtitter explorer is a basic app to explore inside k8s clusters

Go-client 
### For the casual user
```
Currently, there is no super easy way to use client-go. Hopefully this will change soon. Simply running go get k8s.io/client-go/... will leave you with a library that can't practically be used. It is important to synchronize your dependencies with the ones that are required by the library.

Note: the official go policy is that libraries should not vendor their dependencies. This is unworkable for us, since our dependencies change and HEAD on every dependency has not necessarily been tested with client-go. In fact, HEAD from all dependencies may not even compile with client-go!
go get k8s.io/client-go/...
cd $GOPATH/src/k8s.io/client-go
```
