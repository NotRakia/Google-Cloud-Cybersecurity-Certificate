# Virtualization and Virtual Machines

## 1. Virtualization

- Virtualization is technology that creates a virtual version of physical infrastructure, such as servers, storage, and networks.
- This technology uses virtual machines, or VMs, to simulate a physical computer.
- VMs contain their own operating systems, like Windows and Linux, and use only a portion of the underlying computer’s compute power.
- Virtualization uses hypervisors to manage the relationship between physical and virtual resources.

## 2. Hypervisors

- A hypervisor is the abstraction layer that sits between the physical computer and the VM.
- Abstraction is what separates hardware from software.

There are two types of hypervisors.

### Type 1: Bare Metal

- Type one is more common.
- It replaces the entire operating system of the underlying computer.
- Type one hypervisors interact with the operating system’s components directly.
- Having this direct access makes type one streamlined and secure.

### Type 2: Hosted

- Type two hypervisors, also known as hosted, use the computer’s existing operating system and runs as an application over the operating system.
- Type two hypervisors may be easier to install, but you need to take into consideration the extra overhead and security needs of the underlying operating system.

## 3. Hypervisor Resource Management

- So, hypervisors distribute resources across VMs and keep VMs separate so that each one simulates an individual computer.
- And the hypervisor ensures that information in one VM is not visible to others.
- In this way, an organization’s development team can transform one physical computer into lots of virtual machines, instead of buying new hardware each time they need a server.
- If needed, a development team can also add CPU, memory, and storage space to the VM.

## 4. Three Advantages of Virtual Machines

Now, let’s discuss the three advantages of VMs: portability, scalability, and testing environments.

### 4.1 Portability

- The first advantage, portability, makes VMs especially useful for hybrid cloud environments where application resources are shared between on-premises and cloud infrastructure.
- Because each one is an isolated entity, developers can relocate them throughout a network.

### 4.2 Scalability

- The second advantage, scalability, means that VMs can be scaled to provide additional or fewer resources if the development team’s needs change over time.
- This is unlike physical servers, which have a fixed amount of hardware.

### 4.3 Testing Environments

- The third advantage, testing environments, help developers test code without worrying about affecting existing infrastructure or users.
- Plus, VMs simplify testing because developers don’t need to deploy complex production environments.
- And they can delete the testing environment machines afterward.

## Conclusion

As a core foundation of cloud technology, virtualization will be a big part of your future career in the cloud.

You’ll be a major asset to any employer because you understand the advantages virtualization offers and you can maximize its power!
