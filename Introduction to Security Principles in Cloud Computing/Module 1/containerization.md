# Containers

## Overview

Think about how a package delivered to your door got there from its original location.

It probably started off in a warehouse and then went inside a cargo container. There will be many packages of different sizes inside each container.

Next, the containers are loaded onto a transport vehicle, like a train car or ship. Multiply this by thousands of containers over the world.

They’re transported from one place to another, but this doesn't change the contents inside. Like your package.

## What Are Containers?

A container is a software package that holds only the components necessary to execute a particular application.

Each container has a container image, which is a file with the code and dependencies that the container requires to run the application.

Like documents in a filing cabinet, the cabinet is the container, the folders in each drawer are container images, and those container images store the documents or information needed to perform a task.

### Container Registries

Developers use something called container registries to upload and download container images.

This enables teams to share and deploy consistent images.

### Container Orchestration

Organizations use orchestration tools to help deploy, scale, manage, and monitor containers.

### Advantages of Containers

Packaging software in a container uses less memory and fewer resources because the operating system itself is not included in the container.

And bonus: they’re isolated from the surrounding environment, which means they’re pretty easy to deploy across cloud deployment models like public, private, or hybrid clouds.

## Key Benefits of Containers

You’ll work with containers a whole lot throughout your career, so it’s important to understand their key benefits, including portability, immutability, and responsibility separation.

### 1. Portability

Containers enable users to run software quickly from one computing environment to another.

This portability helps create cloud tools super efficiently.

Unlike virtual machines that have an operating system, containers only house isolated software while using a common underlying operating system.

This allows an individual container image to run in multiple locations without the need for a separate operating system.

All of this contributes to their portability.

### 2. Immutability

Immutability means an object can’t be changed after it’s created and assigned a value.

Just like the contents of those shipping containers don’t change during transit, cloud containers also can’t be modified during their lifetimes.

If a container does require a change, users must create a new container image and redeploy it.

This allows developers to seamlessly replace outdated or insecure container images.

Immutability makes containers more secure by ensuring consistency across multiple deployments since there is no patching or updating that could cause configuration drifts.

### 3. Responsibility Separation

Lastly, containers separate the responsibilities among the developers and operations teams.

Developers can devote their time to managing the container’s code, and operations teams can concentrate on deploying and managing the container’s applications.

This frees people up to work on the projects where they can bring the most value.

And there’s nothing like knowing you’re playing to your strengths.

