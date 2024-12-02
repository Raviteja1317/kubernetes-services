# kubernetes-services

* kubernetes services is an abstraction, that provides a consistant way to access and communicate with a set of pods

* it acts as a stable network endpoint for accessing the pod, Enaabling inter-pod communication and load balancing

 ** TYPES OF SERVICES**
1.Cluster ip
2. Node port
3.Load balancer
4.External name

1.CLUSTER IP: 

   * cluster IP is a default service type, which exposes the service on a cluster-internal IP address.It is accessible only within the cluster and not exposed externally.

 2.Node port: Node port service provides a services on static port on node in the cluster. It is the accessiable both within cluster and externally. Using the node's IP address and node 
              port

 3.Load Balancer: Load balancer service is using cloud provider's load balancer to distribute the traffic to the service. External clicent can be access the services using the publicly 
                accessible IP address

 4.External name: External name service provides the services DNS name that maps to an external service or endpoint.
 
                  the allowing the service to redirect request to an external endpoint outside the cluster.
  

