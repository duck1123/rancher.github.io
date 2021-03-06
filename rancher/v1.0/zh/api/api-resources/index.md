---
title: API
layout: rancher-default-v1.0
version: v1.0
lang: zh
---

## Resource Types



<br>

[account]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/account/)|
---|
All resources in Rancher are owned or created by an account. |


<br>

[addOutputsInput]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/addOutputsInput/)|
---|
 |


<br>

[amazonec2Config]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/amazonec2Config/)|
---|
The configuration to launch an EC2 instance in Amazon Web Services using [machine]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/machine). Rancher is calling `docker-machine`, so any available options in `docker-machine` for specific drivers are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. The notes on which fields are **required** are from the `docker-machine` documentation. |


<br>

[apiKey]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/apiKey/)|
---|
An API Key provides access to the Rancher API if access control has been turned on. The access key and secret key pair are created per environment and can be used to directly call the API or used with [rancher-compose]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/rancher-compose). |


<br>

[auditLog]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/auditLog/)|
---|
 |


<br>

[azureConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/azureConfig/)|
---|
The configuration to launch an instance in Microsoft Azure. For all cloud providers, Rancher is calling `docker-machine`, so any available options in `docker-machine` are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. |


<br>

[certificate]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/certificate/)|
---|
A certificate is used to add in SSL termination to load balancers. |


<br>

[composeProject]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/composeProject/)|
---|
 |


<br>

[composeService]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/composeService/)|
---|
 |


<br>

[container]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/container/)|
---|
A container is a representation of a Docker container on a host. |


<br>

[containerEvent]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/containerEvent/)|
---|
 |


<br>

[containerExec]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/containerExec/)|
---|
 |


<br>

[credential]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/credential/)|
---|
 |


<br>

[digitaloceanConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/digitaloceanConfig/)|
---|
The configuration to launch a droplet in DigitalOcean using [machine]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/machine). Rancher is calling `docker-machine`, so any available options in `docker-machine` for specific drivers are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. |


<br>

[dnsService]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/dnsService/)|
---|
A "dnsService" in the API is referred to as a Service Alias in the UI and the Rancher documentation. In the API documentation, we'll use the UI terminology. A service alias allows the ability to add a DNS record for your services to be discovered. |


<br>

[dockerBuild]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/dockerBuild/)|
---|
 |


<br>

[environment]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/environment/)|
---|
An "environment" in the API is referred to as a stack in the UI and the Rancher documentation. In the API documentation, we'll use the UI terminology. A Rancher stack mirrors the same concept as a docker-compose project.  It represents a group of services that make up a typical application or workload. |


<br>

[environmentUpgrade]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/environmentUpgrade/)|
---|
 |


<br>

[exoscaleConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/exoscaleConfig/)|
---|
The configuration to launch an instance in exoscale using [machine]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/machine). Rancher is calling `docker-machine`, so any available options in `docker-machine` for specific drivers are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. The notes on which fields are **required** are from the `docker-machine` documentation. |


<br>

[externalDnsEvent]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/externalDnsEvent/)|
---|
 |


<br>

[externalEvent]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/externalEvent/)|
---|
 |


<br>

[externalHostEvent]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/externalHostEvent/)|
---|
 |


<br>

[externalService]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/externalService/)|
---|
An external service allows the ability to add any IP or hostname as a service to be discovered as a service. |


<br>

[externalServiceEvent]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/externalServiceEvent/)|
---|
 |


<br>

[externalStoragePoolEvent]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/externalStoragePoolEvent/)|
---|
 |


<br>

[externalVolumeEvent]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/externalVolumeEvent/)|
---|
 |


<br>

[genericConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/genericConfig/)|
---|
 |


<br>

[googleConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/googleConfig/)|
---|
 |


<br>

[healthcheckInstanceHostMap]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/healthcheckInstanceHostMap/)|
---|
 |


<br>

[host]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/host/)|
---|
Hosts are the most basic unit of resource within Rancher and is represented as any Linux server, virtual or physical, with the following minimum requirements. <br> <br> * Any modern Linux distribution that supports Docker 1.10.3+. <br> * Must be able to communicate with the Rancher server via http or https through the pre-configured port (Default is 8080). <br> * Must be routable to any other hosts belonging to the same environment to leverage Rancher's cross-host networking for Docker containers.<br> <br> Rancher also supports Docker Machine and allows you to add your host via any of its supported drivers. |


<br>

[hostAccess]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/hostAccess/)|
---|
 |


<br>

[hypervConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/hypervConfig/)|
---|
 |


<br>

[identity]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/identity/)|
---|
An identity is Rancher's representation of an object(i.e. `ldap_group`, `github_user`) when Rancher has turned on [access control]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/configuration/access-control/). The `externalId` in an identity is the unique identifier in the authentication system that represents the object. The role of an identity is always null unless it is being returned as the identity of a [projectMember]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/projectMember/). |


<br>

[image]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/image/)|
---|
 |


<br>

[instance]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/instance/)|
---|
 |


<br>

[instanceLink]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/instanceLink/)|
---|
 |


<br>

[ipAddress]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/ipAddress/)|
---|
 |


<br>

[kubernetesService]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/kubernetesService/)|
---|
 |


<br>

[label]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/label/)|
---|
 |


<br>

[loadBalancerConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/loadBalancerConfig/)|
---|
 |


<br>

[loadBalancerService]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/loadBalancerService/)|
---|
Rancher implements a managed load balancer using HAProxy that can be manually scaled to multiple hosts.  A load balancer can be used to distribute network and application traffic to individual containers by directly adding them or "linked" to a basic service.  A basic service that is "linked" will have all its underlying containers automatically registered as load balancer targets by Rancher. |


<br>

[machine]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/machine/)|
---|
Machines are created whenever Rancher uses `docker-machine` to create hosts in Rancher. Adding any type of host through the UI that is not the custom command option is calling `docker-machine` and a machine entry will be created as well as a [host]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/host). |


<br>

[mount]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/mount/)|
---|
A mount is the relationship of a volume and the directory location inside the container. |


<br>

[network]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/network/)|
---|
 |


<br>

[openstackConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/openstackConfig/)|
---|
The configuration to launch an instance in OpenStack. For all cloud providers, Rancher is calling `docker-machine`, so any available options in `docker-machine` are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. |


<br>

[packetConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/packetConfig/)|
---|
The configuration to launch an instance in Packet. |


<br>

[password]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/password/)|
---|
 |


<br>

[physicalHost]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/physicalHost/)|
---|
 |


<br>

[port]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/port/)|
---|
 |


<br>

[project]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/project/)|
---|
A "project" in the API is referred to as an environment in the UI and Rancher documentation. In the API documentation, we'll use the UI terminology.  All hosts and any Rancher resources (i.e. containers, load balancers, etc.) are created and belong to an [environment]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/configuration/environments/).  Access control to who can view and manage these resources are then defined by the owner of the environment.  Rancher currently supports the capability for each user to manage and invite other users to their environment and allows for the ability to create multiple environments for different workloads.  For example, you may want to create a "dev" environment and a separate "production" environment with its own set of resources and limited user access for your application deployment. |


<br>

[projectMember]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/projectMember/)|
---|
A "project member" in the API is referred to as an environment members in the UI and Rancher documentation. An environment member is a list of all of the members of the  environment. An environment member is an [identity]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/identity). |


<br>

[pullTask]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/pullTask/)|
---|
 |


<br>

[rackspaceConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/rackspaceConfig/)|
---|
The configuration to launch a server in Rackspace. For all cloud providers, Rancher is calling `docker-machine`, so any available options in `docker-machine` are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. |


<br>

[register]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/register/)|
---|
 |


<br>

[registrationToken]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/registrationToken/)|
---|
 |


<br>

[registry]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/registry/)|
---|
A registry is where image repositories are hosted. The repository can be either from DockerHub, Quay.io, or a custom private registry. |


<br>

[registryCredential]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/registryCredential/)|
---|
A registry credential is used to authenticate against a [registry]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/registry). |


<br>

[schema]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/schema/)|
---|
This is the schema resource |


<br>

[service]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/service/)|
---|
Rancher adopts the standard Docker Compose terminology for services and defines a basic service as one or more containers created from the same Docker image.  Once a service (consumer) is linked to another service (producer) within the same stack, a DNS record mapped to each container instance is automatically created and discoverable by containers from the "consuming" service. Other benefits of creating a service under Rancher include":" <br><br> * Service HA - the ability to have Rancher automatically monitor container states and maintain a service's desired scale. <br> * Health Monitoring - the ability to set basic monitoring thresholds for container health. |


<br>

[serviceConsumeMap]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/serviceConsumeMap/)|
---|
 |


<br>

[serviceEvent]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/serviceEvent/)|
---|
 |


<br>

[serviceExposeMap]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/serviceExposeMap/)|
---|
 |


<br>

[serviceProxy]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/serviceProxy/)|
---|
 |


<br>

[setting]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/setting/)|
---|
 |


<br>

[snapshot]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/snapshot/)|
---|
 |


<br>

[softlayerConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/softlayerConfig/)|
---|
The configuration to launch a server in SoftLayer. For all cloud providers, Rancher is calling `docker-machine`, so any available options in `docker-machine` are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. |


<br>

[statsAccess]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/statsAccess/)|
---|
 |


<br>

[storagePool]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/storagePool/)|
---|
A storage pool is a list of hosts that can participate in shared storage. |


<br>

[subscribe]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/subscribe/)|
---|
 |


<br>

[typeDocumentation]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/typeDocumentation/)|
---|
 |


<br>

[ubiquityConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/ubiquityConfig/)|
---|
The configuration to launch a server in Ubiquity Hosting. |


<br>

[virtualMachine]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/virtualMachine/)|
---|
 |


<br>

[virtualboxConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/virtualboxConfig/)|
---|
The configuration to launch a local VM using VirtualBox. Rancher is calling `docker-machine`, so any available options in `docker-machine` are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. |


<br>

[vmwarefusionConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/vmwarefusionConfig/)|
---|
 |


<br>

[vmwarevcloudairConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/vmwarevcloudairConfig/)|
---|
The configuration to launch a machine in vCloudAir. Rancher is just calling `docker-machine`, so any available options in `docker-machine` are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. |


<br>

[vmwarevsphereConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/vmwarevsphereConfig/)|
---|
The configuration to launch a machine in vSphere. Rancher is just calling `docker-machine`, so any available options in `docker-machine` are exposed in Rancher. The default fields from `docker-machine` are not listed in the Rancher API, and they can be found in the `docker-machine` documentation. |


<br>

[volume]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/volume/)|
---|
A volume can be associated to containers or storage pools. <br><br> * A container can have many volumes and containers are mapped to volumes the [mount]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/mount/) link on a container. <br> * A storage pool owns many volues. The volume is only available to containers deployed on hostst that are part of the storage pool. When a volume is being created, you do not directly associate it to a storage pool. You will only need to specify a driver and during allocation, Rancher will resolve it to a storage pool. |

