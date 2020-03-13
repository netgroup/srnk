Segment Routing (SR) is a form of source routing. The SR architecture works by including a list of _segments_ in the packet headers. A segment can represent a _topological_ instruction (e.g. a node to be crossed) or a _service_ instruction (e.g. an operation to be executed on the packet). 

The Segment Routing architecture can be implemented using MPLS or IPv6 as data plane. We focus on the IPv6 implementation, called _SRv6_, in which the _segments_ are identified by IPv6 addresses. SRNK (SR-Proxy Native Kernel) is a SR proxy which acts as relay mechanism in order to support SRv6 unaware VNFs (see Figure 1)

<!--- <img src="https://raw.githubusercontent.com/netgroup/sr-proxy/master/docs/srv6_processing.png" width="400"> --->
![srv6_processing.png](<./srv6_processing.png>)

### Scientific papers, technical reports, IETF drafts, Slides

- A. Mayer, S. Salsano, P.L. Ventre, A. Abdelsalam, L. Chiaraviglio, C. Filsfils, "[An Efficient Linux Kernel Implementation of Service Function Chaining for legacy VNFs based on IPv6 Segment Routing](https://arxiv.org/abs/1901.00936)", submitted paper under review 

### SRNK (SR-Proxy Native Kernel) source code

- [SRNK kernel implementation](https://github.com/netgroup/srnk-kernel) is the kernel space implementation (starting from 4.14.0)
- [SRNK iproute2 tool implementation](https://github.com/netgroup/srnk-iproute2) is the implementation of the enhancements to iproute2 tool (starting from iproute2-ss171112)

### The Developers' Team

- Andrea Mayer
- Stefano Salsano
- Pier Luigi Ventre
- Ahmed Abdelsalam
