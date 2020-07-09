> kubectl get pods
> kubectl get services
> kubectl get rc
> kubectl create -f rc.yaml
> kubectl cluster-info
> kubectl cluster-info dump
> kubectl compelete zsh > kubectl.zsh
> source kubectl.zsh
> kubectl log -f pod-name
> kubectl apply -f https://k8s.io/examples/application/guestbook/redis-master-service.yaml
> minikube service wordpress --url
> minikube get events
> kubectl run myapp --image=nginx --dry-run -o yaml
> kubectl create secret generic mysecret --from-literal=quiet-phrase="Shh! Dont' tell" -o yaml --dry-run
> kubectl get deployment mysql --export -o yaml > mysql.yaml
> kubectl get ep nginx
> docker inspect network networkname

