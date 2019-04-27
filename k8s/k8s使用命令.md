1.查看pod命令
kubectl get pods

2.删除pod
kubectl delete pod podname
注：如果删除不了，先使用命令查看rc
    kubectl get rc 
    如果没有，直接删除部署容器，查看部署容器  kubectl get deployment
    删除：kubectl delete deployment deploymentName
