# AVAILABILITY

Also known as *uptime*. Are resources available when needed. High availability focuses on maximum availability, regardless of disruptions or events.

**SLA (Service Level Agreement)**: Formal agreement between provider and customer on guaranteed level of service. In Azure, represented as **%**, denoting availability. Higher percent more costly (no downtime maintenance, duplications). May receive credit if not met. 99%, 99.9% are common SLAs.

Architect solution around availability.

Common issues:

* **Network outage**
* **Application failure** - often software bug; provider generally provides tools, testing environments; can roll out incrementally
* **System outage** - computer running system becomes unavailable (server on-premise, or VM in cloud)
* **Power outage**
* **Reliant system problem** - app depends on system not in cloud or by different provider, such as external database