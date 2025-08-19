## Elastic Load Balancer (ELB) Overview

Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets such as Amazon EC2 instances, containers, and IP addresses in one or more Availability Zones.

###  Key Features

- **Traffic Distribution**  
  ELB ensures high availability and fault tolerance by routing traffic to healthy targets and balancing the load across them.

- **Types of Load Balancers**  
  - **Application Load Balancer (ALB)**: Best for HTTP/HTTPS traffic with advanced routing features (e.g., path-based, host-based).
  - **Network Load Balancer (NLB)**: Designed for high-performance TCP/UDP traffic with ultra-low latency.
  - **Gateway Load Balancer (GLB)**: Ideal for deploying, scaling, and managing third-party virtual appliances.

- **Health Checks**  
  ELB continuously monitors the health of registered targets and routes traffic only to healthy ones.

- **Security Integration**  
  Works with AWS Certificate Manager (ACM), IAM, and security groups to manage SSL/TLS and access control.

- **Auto Scaling Support**  
  Seamlessly integrates with Auto Scaling to handle changes in traffic volume.



ELB is a foundational service for building scalable, resilient, and secure cloud applications. It improves fault tolerance and simplifies traffic management across distributed systems.
