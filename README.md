# Docker-Certification-Test-Paper-2

The components of a network interface are routing table, DNS services, and gateway.

To remove a container automatically when it exists, use the --rm option while creating a container.

In a replicated service, the number of identical tasks can be specified, but in a global service there is no specified number of tasks.

The command used to remove one or more images is docker image rm.

Docker Security prevents a compromised container from consuming a large amount of resources in order to disrupt a service or perform malicious activities.

A Docker container consists of Docker image, execution environment, and a standard set of instructions.

Swarm is an instance of Docker engine that is distributed across multiple physical or virtual machines.

The built-in roles include restricted control, scheduler, and full-control.

The docker run command runs a command in a run-time container.

Registry stores and distributes the Docker images.

In Docker, the images are stored in /var/lib/docker.

Universal Control Plane (UCP) is the enterprise-grade cluster management solution from Docker.

Docker Hub repositories allow a user to share container images with the team, customers, or the Docker community at large. It is not a totally private repository.

A bridge network is the default Docker network present on any Linux host that runs a Docker engine.

At least 4GB RAM is required to install UCP for worker nodes.

Docker API and CLI help to delete a container.

The tmpfs mount allows the container to create files outside the container's writable layer.

The command to remove the existing ingress network is docker network rm ingress.

Macvlan network is used to assign MAC address to the virtual network interface of containers.

Volumes are easier to back up or migrate than bind mounts.

Volumes can be more safely shared among multiple containers.

Volumes work on both Linux and Windows containers.

A new volume's contents can be pre-populated by a container.

Host network optimizes the performance and handles a large range of ports.

The purpose of labeling is to organize the images and record the licensing information.

Docker Compose is a tool for defining and running multi-container Docker applications.

The command to unlock the swarm when the Docker restarts is sudo service docker restart.

A sandbox is composed of the configuration of a container's network stack.

ADD copies new directories, files, and URLs of remote files from <src>. It not only copies the directories, files, and URLs of remote files but also adds them to the image filesystem at <dest>.

tmpfs mount is used to store the files temporarily.

The devicemapper is a framework provided by the Linux kernel for mapping physical block devices onto higher level virtual block devices.

Collections are used to enable the controlling access to the swarm resources.

The command to remove unused network is docker network prune.

The command to unlock the swarm when the Docker restarts is sudo service docker restart.

A sandbox is composed of the configuration of a container's network stack.

The EXPOSE instruction informs Docker that the container listens on the specified network ports at runtime.

Docker networking subsystem uses drivers.

Docker Daemon helps Docker to allow the user to share a directory between the Docker host and a guest container.

Docker tiers include Docker Engine Community, Docker Engine Enterprise, and Docker Enterprise.

STOPSIGNAL sends a system call signal that helps the container to exit.

Docker creates several environment variables when you link containers.

Docker API and CLI help to move a container.

Connecting to the Docker machine, investigating the Docker container logs, and identifying the container ID are required to access the Docker container log.

Docker Content Trust allows the Docker Engine to run signed images.

ENV is a key-value pair that sets the environment variable <key> to the value <value>.

Healthcheck helps to identify whether the applications are working in the desired state or not.

The docker image ls command is used to list the images.

The features of Docker Kubernetes Services include role-based access control and Pod security policies.

kubectl exec [container_name] [command_arg] command is used to execute a command in a container.

Mvnet belongs to macvlan network.

kubectl delete command is used to delete a resource like a running pod or service.

Kubernetes service has its own IP address, called ClusterIP, which is used to communicate with the pods using proxies.

In NodePort ServiceType, the Service is exposed on a static port of each worker node's IP address.

Communication between the containers inside a pod happens via localhost.

In External-to-Service communication, Ingress provides a collection of routing rules that regulate the external user's access to the Services running within the Kubernetes cluster.

CSI can be used in a pod through a reference to a PersistentVolumeClaim, with a generic ephemeral volume, and with a CSI ephemeral volume

Each StorageClass contains the fields provisioner, parameters, and reclaimPolicy.

A sandbox is composed of the configuration of a container's network stack including Container's interfaces, Routing table, DNS settings, and Endpoints
