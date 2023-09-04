# AWS-Solutions-Architect
**Accelerating Go-To-Market Agility for Value-Ad: Optimizing Deployment Time on Kubernetes/AWS EKS

# Value-Ad Go-To-Market Optimization Project

## Project Goal

At the heart of this project is Value-Ad, a lead intelligence platform serving clients like PRUDENTIAL, DBS, and TELSTRA. The challenge was clear: How could Value-Ad streamline its go-to-market process from weeks to days to support its rapid growth?

## The Solution

### Kubernetes and Rancher Magic ✨

We started by diving deep into Value-Ad's infrastructure, a complex mix of technologies and teams. Our solution? Embrace Kubernetes as the deployment orchestrator, with Rancher as the user-friendly management interface.

### Resource Efficiency 🌟

Value-Ad is used to manually deploy a unique stack for each client on EC2 instances. Not only was this labor-intensive, but it was also costly. With Kubernetes, we introduced a resource-sharing model, making the most of CPU and memory resources, and saving Value-Ad big on AWS charges.

### Seamless Deployment 🚀

Now, deploying a client's stack is a breeze. We've created templates that take inputs like the client's name and the environment (test or production). With a few clicks, anyone from developers to testers can deploy a new stack, harnessing the full power of AWS resources.

### Scalability and Cost Reduction 💰

We boosted Value-Ad's scalability by ensuring each client app could run in at least three environments across different availability zones. Plus, we transitioned from On-Demand EC2 instances to Spot Instances, slashing deployment costs by a whopping 80%.

## Results Speak Louder

Value-Ad and their team couldn't be happier with the outcome. Our cloud initiative achieved the following:

- **Deployment Time**: Reduced from weeks to a mere 15 minutes.
- **Cost Savings**: An impressive 80% reduction in costs per deployment.
- **Scalability and Reliability**: Our Kubernetes setup brought greater scalability and reliability than their old infrastructure.
- **Security and Compliance**: Aligned perfectly with their client's compliance requirements.

Happy coding! 🌟

---
