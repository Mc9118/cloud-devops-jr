docker basics 

What is Docker ?<br>

Docker is an open-source platform that enables developers to build, package, ship, and run applications using containers—lightweight, portable, and self-contained environments that include everything needed to run an application, such as code, libraries, runtime, and system tools.

*Docker Architecture* is a client-server model that enables efficient containerization of applications.  At its core, it consists of several interconnected components that work together to build, run, and manage containers. 

Docker Client: The primary interface for users, typically the command-line interface (CLI). It sends commands (e.g., docker run, docker build) to the Docker Daemon via the REST API.

Docker Daemon (dockerd): A background service that listens for API requests and manages Docker objects like images, containers, networks, and volumes. It performs the heavy lifting of container lifecycle operations.

Docker Engine: The core platform that includes the Docker Client, REST API, and Daemon. It facilitates the entire container lifecycle. 

Docker Images: Read-only templates that serve as blueprints for containers. Built layer by layer from a Dockerfile, they include application code, runtime, libraries, and dependencies. 

Docker Containers: Runnable instances of images. They are lightweight, isolated processes that share the host OS kernel but operate independently. 

Docker Registry: A storage and distribution system for Docker images. Docker Hub is the most popular public registry, but private registries can also be used. 

Docker Host: The physical or virtual machine where the Docker Daemon runs, providing the environment for containers. 

Docker Networks: Enable communication between containers. Default options include bridge, host, overlay, and MacVLAN networks. 

Docker Volumes: Persistent storage solutions that allow data to survive container restarts or removals. 
