# istio

This README documents the Istio integration as Nirmata add-on on Kubernetes clusters.

### What is Istio?
Istio It is a completely open source service mesh that lets you connect, secure, control, and observe services.

### What is a service mesh?
The term service mesh is used to describe the network of microservices that make up such applications and the interactions between them. As a service mesh grows in size and complexity, it can become harder to understand and manage. Its requirements can include discovery, load balancing, failure recovery, metrics, and monitoring. A service mesh also often has more complex operational requirements, like A/B testing, canary rollouts, rate limiting, access control, and end-to-end authentication.


### How do I get set up?
1. Clone this repository or add its contents to your own private Git repository.
2. Create a Nirmata catalog application with a Git upstream and select the Istio repository. You can optionally select the kustomization (see below.)
3. Edit the catalog application and select an add-on category (e.g. Networking). This is required to select the application as a add-on.
4. Update a Cluster Type, or create a new one, and select the Istio add-on application in the "Add-Ons" section.
5. Create clusters using the cluster type.
6. If addon is to be added to a running cluster, create a environemnt with name "istio-system" and choose this environment while deploying the application
6. Verify that the application is running.


### Who do I talk to?
For issues, contact support@nirmata.com
