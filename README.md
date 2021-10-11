# kubernates-demo
Repo for learning kubernates. Lets see in action

# Creating a pod using kubectl
kubectl create -f pod.yaml

# Get all the pods
kubectl get pod

# Delete a running pod
kubectl delete pod <pod_name>

# Get all the replicaset
kubectl get replicaset

# Delete a replicaset
kubectl delete replicaset <replicaset_name>

# Describe individual pod
kubectl describe pod <pod_name>
