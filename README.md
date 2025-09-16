Comparison between two popular AWS instance families:
Memory Optimized Instances (R, X, z1d families)
•	Best for: Workloads that require large memory capacity and fast data access.
•	Examples: High-performance databases (Oracle, SQL Server, SAP HANA), in-memory caches (Redis, Memcached), real-time big data analytics, and high-performance computing that depends heavily on memory.
•	Why: They are designed with a higher ratio of RAM to CPU, enabling faster performance for applications that need to keep and process large data sets in memory.
GPU Optimized Instances (P, G, Trn families)
•	Best for: Workloads that require parallel computation and graphics acceleration.
•	Examples: Machine learning training and inference, AI model development, scientific simulations, video rendering, 3D graphics applications, and high-performance gaming.
•	Why: They come with powerful NVIDIA GPUs that can handle thousands of parallel operations at once, making them ideal for workloads that need massive computational throughput.
 In summary: Memory optimized instances shine with data-intensive applications needing quick in-memory operations, while GPU optimized instances are the go-to for AI/ML, simulations, and visual rendering that benefit from GPU acceleration.
Would you like me to also add a small comparison table side-by-side for quick reference?
RESPONSIBILITY MODEL EXPLANATION

The AWS Shared Responsibility Model defines the split of security duties between AWS and its customers. AWS is responsible for securing the cloud infrastructure itself, which includes the physical data centers, hardware, networking, and foundational services that run AWS. They ensure high availability, resilience, and compliance of the infrastructure, as well as protecting managed services like S3, EC2, and RDS at the infrastructure level.
On the other hand, the customer is responsible for security in the cloud. This means one must configure and manage access controls (IAM policies, roles, and permissions), secure ones operating systems and applications, patch software, encrypt data, and ensure network security settings like firewalls and security groups are correctly applied. Summarily, AWS keeps the cloud secure, but users are responsible for securing what they put in the cloud.


CHALLENGES FACED AND HOW IT WAS SUMMOUNTED 
No challenges encountered!
