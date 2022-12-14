## Serverless Functions

### Definition:

**Serverless** Serverless is a cloud application development and execution model that lets developers build and run code without managing servers, and without paying for idle cloud infrastructure.

> Serverless does not mean 'no servers', it just means that the developer won't have to deal with managing or interacting with these servers.

### Serverless is more than just FaaS

In addition to FaaS, these services include:
- **Serverless databases and storage**
- **Event streaming and messaging**
- **API gateways**

### Serverless vs. PaaS, containers, and VMs

- **Provisioning time**: measured in milliseconds for serverless, unlike other models that is measured in minutes and hours.
- **Administrative burden**: serverless doesn't have it, unlike the other models that range from light to heavy.
- **Maintenance**: It's managed by the provider in serverless, unlike the other models.
- **Scaling**: auto-scaling is instant in serverless, unlike the other models that require careful tuning of auto-scaling rules.
- **Capacity planning**: in serverless this is not needed.

### Pros and cons of serverless

- **Pros**:

    - Improved developer productivity.
    - Pay for execution only.
    - Develop in any language.
    - Usage visivility.

- **Cons**:

    - Unacceptable latency for certain applications.
    - High costs for stable or predictable workloads.
    - Monitoring and debugging issues.
    - Vendor lock in.
