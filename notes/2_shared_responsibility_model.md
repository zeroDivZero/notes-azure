# SHARED RESPONSIBILITY MODEL

With traditional data center, user responsible for maintaining physical space, security, and hardware. Plus software, patching and updating systems.

With cloud, responsibilities shared between provider and consumer. Provider: physical security, power, cooling, and network connectivity. Consumer: data stored (not visible to provider) and access security.

Other responsibilities depend on situation. E.g., with cloud database, provider responsible for maintaining actual database, consumer responsible for ingested data. But if deploying virtual machine with database, consumer responsible for both database and data.

Shared responsibility model tied to cloud service types: infrastructure as a service (**IaaS**), platform as a service (**PaaS**), and software as a service (**SaaS**). IaaS places most responsibility on consumer, with provider responsible for physical infrastructure. SaaS places most of responsibility with provider. PaaS is middle ground.

![Shared Resonsibility](/assets/shared-responsibility.svg)

## Summary

Consumer always responsible for:

* Data stored in cloud
* Devices allowed to connect to cloud
* Accounts and identities of people, services, and devices within org

Provider always responsible for:

* Physical data center
* Physical network
* Physical hosts

Service model determines responsibility for:

* Operating systems
* Network controls
* Applications
* Identity and infrastructure
