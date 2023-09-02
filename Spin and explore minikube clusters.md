Install kubectl and minikube in your system to spin and explore a cluster, Make sure your container engine, Docker or Podman, is running

 `Docker`
This command at the command prompt checks if the Docker engine is running and lists all the possible Docker actions.


 
  `minikube start`
This command in command prompt helps in creating a cluster with minikube




 `kubecnt cluster-info` 
 This command allows us to see the IP address of the Kubernetes control plane, You can also observe where in your cluster core DNS the container network interface is running.If the command prompt outputs an error message saying, the connection to the server was refused, try again with  `minikube start`
 
  `kubectl get nodes` 
It helps to look at our nodes with the role of control plane and the Kubernetes version. 

 `kubectl get namespaces`
The namespaces that get created by default, it shows the kube-node-lease, kube-public, and kube-system. Namespaces are way to isolate and manage applications and services. 




