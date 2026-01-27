--> Notes to be placed here

# Questions

## **Introduction & Cloud Computing**

- How do cloud providers balance the trade-off between building massive data centers (economies of scale) versus distributing smaller ones (latency/redundancy)?
- You mentioned the shuffle phase creates O(N²) flows—can you explain why this squared relationship is fundamental to MapReduce rather than something that could be optimized away?

## **Infrastructure - Network Topology**

- You show that oversubscription is cheaper than full bisection bandwidth—what oversubscription ratios do real data centers typically use, and how do they decide on this number?
- For fat-tree topologies, how do routing protocols actually ensure traffic is spread across all available paths rather than concentrating on a few?
- When Facebook builds custom switches, how much cost savings do they actually achieve versus buying from traditional vendors?


## **Infrastructure - NIC Hardware**

- You showed network speeds grew 50x while CPU performance didn't keep pace. Beyond SmartNICs, are there workloads where this mismatch is still a fundamental bottleneck?
- For the FPGA SmartNICs: what percentage of network processing can realistically be offloaded? What still requires CPU involvement?
- You mentioned "CPU-less applications"—can you give concrete examples of what these look like in production?

## **Network Management - SDN**

- In traditional networks, distributed control has some advantages like fault tolerance. How does SDN handle controller failures without losing these benefits?
- You mentioned P4 lets you configure how switches process packets. What are practical examples of packet processing that data centers need beyond what OpenFlow's fixed tables provide?
- What's the overhead of the centralized control plane? How quickly can SDN controllers react to network failures compared to distributed protocols?

## **Network Stack - Congestion Control**

- DCTCP requires ECN support from switches. What happens when you have mixed switch vendors or older hardware that doesn't support ECN reliably?
- With pFabric, how do switches actually know the remaining flow size? Does this require maintaining per-flow state at every switch?
- pFabric uses very small buffers (10 packets)—doesn't this cause problems with bursty traffic, or do data center traffic patterns really allow this?
- You showed dramatic improvements, but what are the deployment challenges? Why isn't pFabric universally deployed if it's so much better?

## **General/Cross-cutting**

- You emphasized the "holistic approach" and cross-layer optimization. Can you give an example where optimizing one layer actually made another layer's performance worse?
- How much of this is applicable outside hyperscale data centers? What works for a company running 100-1000 servers versus Microsoft's scale?
- What's the biggest open problem in data center networking right now that you think will be important in the next 5-10 years?

Thesea re the ways to consider the remaining system requirements that we have indeed have listed


The datacenter as a computer: an introduction to the desin of warehouse scale machines

http://aka.ms/paolo