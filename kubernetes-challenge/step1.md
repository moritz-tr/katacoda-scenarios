1. Create a pod with image nginx called nginx and expose traffic on port 80 in namespace `challenge`.
2. Show all running pods in the `challenge` namespace
3. Get information about the pod, including details about potential issues (e.g. pod hasn't started)
4. Get pod logs
5. Execute a simple shell on the nginx pod

<!-- ## Solution
6. kubectl create ns challenge
   1. kubectl run nginx --namespace=challenge --image=nginx --restart=Never --port=80
7. kubectl get pods -n challenge
8. kubectl describe po nginx -n challenge
9.  kubectl logs nginx -n challenge
10. kubectl exec -n challenge -it nginx -- /bin/sh
11.  -->
