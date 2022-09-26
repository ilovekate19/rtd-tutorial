TERM
====

.. list-table:: Title
   :widths: 25 50
   :header-rows: 1

   * - Term
     - Description
   * - CSP
     - **Communications Service Provider** offers telecommunications services or some combination of information and media services, content, entertainment and application services over networks, leveraging the network infrastructure as a rich, functional platform
   * - CPE
     - In telecommunications, a **customer-premises equipment** or **customer-provided equipment** (CPE).CPE generally refers to devices such as telephones, routers, network switches, residential gateways (RG), set-top boxes, fixed mobile convergence products, home networking adapters and Internet access gateways that enable consumers to access providers' communication services and distribute them in a residence or enterprise with a local area network (LAN).
   * - DSL
     - A **domain-specific language (DSL)** is a computer language specialized to a particular application domain. This is in contrast to a **general-purpose language (GPL)**, which is broadly applicable across domains. 
   * - ZTP
     - **Zero-touch provisioning (ZTP)** is a method of setting up devices that automatically configures the device using a switch feature. ZTP helps IT teams quickly deploy network devices in a large-scale environment, eliminating most of the manual labor involved with adding them to a network.
   * - single pane of glass
     - A **single pane of glass** is a management console that presents data from multiple sources in a unified display.
   * - `TOSCA <https://cloudify.co/what-is-tosca/>`_
     - **Topology and Orchestration Specification for Cloud Applications (TOSCA)** represents a standard created by the industry group OASIS. OASIS is a nonprofit consortium that is engaged in the development of open standards supported by most vendors and major players in the cloud world as well as the telecom market. TOSCA (sometimes dubbed ‘TOSCA Cloud’) is known as one of the fastest growing standards in OASIS and has numerous use cases and implementations that have already been announced. The idea behind the TOSCA standard is to render improvements in the deployment, termination, and any other management function of cloud applications. By defining service templates consisting of different components and the relationships between these different parts, TOSCA helps configure applications and their underlying infrastructure as well as enable moving applications in the cloud in a very unique way. Also, all required orchestration policies and resources can be defined using templates dedicated for that purpose. The TOSCA standard has the main goal of answering the need for automation, portability, and interoperability along with the management challenges of complex cloud applications. 
   * - Intuitive
     - (chiefly of computer software) easy to use and understand.
   * - haveged
     - The haveged project is an attempt to provide an easy-to-use, unpredictable random number generator based upon an adaptation of the HAVEGE algorithm. Haveged was created to remedy low-entropy conditions in the Linux random device that can occur under some workloads, especially on headless servers.
   * - Patroni
     - A Template for PostgreSQL HA with ZooKeeper, etcd or Consul
   * - Tenant
     - A tenant is a logical entity that contains a group of Cloudify resources such as blueprints, deployments, executions, plugins and secrets.
   * - Blueprint
     - A blueprint is a model of the application’s topology and its operations implementation.Cloudify Composer allows to display/edit the blueprint in two complementary ways: Topology view - visual representation of the blueprint, Source view - blueprint’s source code
   * - Plugin
     - Cloudify Plugins are Python packages that do the work of communicating with external systems. Primarily - Infrastructure Plugins and Configuration Plugins. **Blueprints** use the Cloudify DSL to model an application. The model, or node_templates section, describes a topology which includes: * Node Templates * Relationships between node templates. **Workflows** actualize the topology by defining the order of operations that will be performed. For example, the built-in Install Workflow calls, among other things, the create, configure, and start operations defined for a particular node type. **Plugins** contain the Python code that each workflow operation calls.
