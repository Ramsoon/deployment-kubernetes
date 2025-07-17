### Microservices-Based Application Deployment with Kubernetes

I successfully deployed a modular application consisting of Task, User, Auth, and Frontend services, each running in separate Kubernetes pods with distinct services for optimized scalability and management.

#### Key Highlights:

* Deployed each module (Task, User, Frontend, and Auth) in individual pods, using a shared namespace to simplify internal communication.
* Exposed Task, User, and Frontend services via LoadBalancers for external accessibility.
* Configured the Auth module using a ClusterIP service to ensure secure internal communication within the Cluster.
* Resolved CORS origin issues programmatically in the codebase to ensure smooth cross-service communication between frontend and APIs.
* I also use a reverse proxy for the frontend service.
* Ensured flawless integration and communication across services with proper DNS resolution and Kubernetes service discovery.
In this setup, I demonstrates strong DevOps practices, container orchestration expertise, and clean microservices design with production-readiness in mind.

