Segment Routing (SR) is a form of source routing. The SR architecture works by including a list of _segments_ in the packet headers. A segment can represent a _topological_ instruction (e.g. a node to be crossed) or a _service_ instruction (e.g. an operation to be executed on the packet). 

The Segment Routing architecture can be implemented using MPLS or IPv6 as data plane. We focus on the IPv6 implementation, called _SRv6_, in which the _segments_ are identified by IPv6 addresses. SRNK (SR-Proxy Native Kernel) is a SR proxy which acts as relay mechanism in order to support SRv6 unaware VNFs (see Figure 1)

<img src="https://raw.githubusercontent.com/netgroup/srv6-proxy/master/docs/srv6_processing.png" width="400">

### Scientific papers, technical reports, IETF drafts, Slides

- A. Mayer, S. Salsano, P.L. Ventre, A. Abdelsalam, L. Chiaraviglio, C. Filsfils, "[An Efficient Linux Kernel Implementation of Service Function Chaining for legacy VNFs based on IPv6 Segment Routing](https://arxiv.org/abs/1901.00936)", submitted to 

### SRNK (SR-Proxy Native Kernel)

- [SR Proxy Linux](https://github.com/repo/sr-proxy-linux) is the...
- [SR Proxy iproute](https://github.com/repo/sr-proxy-linux) is a...

### The Team

- Stefano Salsano
- Andrea Mayer
- Ahmed Abdelsalam
- Pier Luigi Ventre
