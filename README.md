# KCNA_Practice

## Practice questions

Note: Practice questions to help you prepare for the KCNA exam

<details close>
<summary> :small_blue_diamond: 1. What is a Kubernetes Service?</summary>
<br>

1. A container runtime that manages pods
2. A way to expose a set of pods as a network service
3. A Kubernetes add-on that provides log aggregation and search
4. A tool for automatically scaling pods based on resource usage
Answer: 2
  
<summary> 🔽: Explaining: A Kubernetes Service is an abstraction layer that provides a stable IP address and DNS name for accessing a set of pods in a Kubernetes cluster. Services are used to expose pods to the network and allow other components, both internal and external to the cluster, to communicate with the pods.</summary>


</details>

<details close>

  <summary> :small_blue_diamond: 2. Which of the following is a Kubernetes object that is responsible for running one or more containers in a pod?</summary>
<br>

1. Service
2. Deployment
3. Node
4. Pod
  
Answer: 4  

</details>

<details close>

<summary> :small_blue_diamond: 3. How do you configure a Kubernetes network policy?</summary>
<br>

1. Using annotations in the pod definition
2. By adding labels to the pod metadata
3. By creating a YAML file that defines the policy
4. By running a Kubernetes command from the command line
  
Answer: 3

</details>

<details close>

<summary> :small_blue_diamond: 4. Which of the following is a Kubernetes component responsible for scheduling pods to run on nodes in the cluster?</summary>
<br>

1. kubelet
2. kube-proxy
3. kube-scheduler
4. kube-controller-manager
  
Answer: 3

</details>

<details close>

<summary> :small_blue_diamond: 5. What is the difference between a Kubernetes NodePort and a LoadBalancer service type?</summary>
<br>

1. NodePort provides access to the pods from within the cluster, while LoadBalancer provides access from outside the cluster.
2. NodePort provides access to the pods from outside the cluster, while LoadBalancer provides access from within the cluster.
3. NodePort uses a specific port on each node to forward traffic to the pod, while LoadBalancer uses an external load balancer to distribute traffic to the pods.
4. NodePort and LoadBalancer are the same thing, just different names for the same service type.
  
Answer: 3

</details>

<details close>  
  
<summary> :small_blue_diamond: 6. How do you secure a Kubernetes cluster's network communications? </summary>
<br>

1. By using SSL/TLS encryption for all traffic
2. By setting up a firewall on each node in the cluster
3. By using a network policy to control traffic flow between pods
4. By limiting access to the Kubernetes API server to only authorized users)

Answer: 1  

</details>

<details close>

<summary> :small_blue_diamond: 7. What is the purpose of a Kubernetes Ingress? </summary>
<br>

1. To provide secure access to the Kubernetes API server
2. To route external traffic to the correct pod or service within the cluster
3. To manage container images and repositories within the cluster
4. To provide automated scaling of pods based on resource usage
  
Answer: 2

</details>

<details close>

<summary> :small_blue_diamond: 8. Which of the following is a Kubernetes object that is used to group related resources together and provide isolation between different teams or applications? </summary>
<br>

1. Namespace
2. Deployment
3. Pod
4. Service

Answer: 1

</details>

<details close>

<summary> :small_blue_diamond: 9. How do you scale a Kubernetes Deployment? </summary>
<br>

1. By adjusting the number of replicas in the Deployment definition
2. By adjusting the resource limits of the pods in the Deployment
3. By adding or removing nodes from the cluster
4. By changing the container image used in the Deployment

Answer: 1  
</details>

<details close>

<summary> :small_blue_diamond: 10. What is the purpose of the kube-proxy component in a Kubernetes cluster? </summary>
<br>

1. To monitor the health of the nodes in the cluster
2. To provide load balancing for traffic to the pods
3. To manage the deployment of new containers to the cluster
4. To provide a secure connection to the Kubernetes API server
  
Answer: 2

</details>

<details close>  
