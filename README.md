# DynamicRoutingProtocal
Comparative Analysis of Dynamic Routing  Protocol using Packet Tracer 7.3.1 with Dynamic  BW

# Abstract
In a computer network, the transmission of data from source to destination is based on the routing protocol which selects 
the best routes between any two nodes. Different types of routing protocols are applied to specific network environment. Three typical 
types of routing protocol are chosen as the simulation samples: RIP, OSPF and EIGRP. RIP (Routing Information Protocol) is one of 
the oldest routing protocols still in service. Hop count is the metric that RIP uses and the hop limit, limits the network size that RIP can 
support. OSPF (Open Shortest Path First) is the most widely used IGP (Interior Gateway Protocol) large enterprise networks. OSPF is 
based on the Shortest Path First (SPF) algorithm which is used to calculate the shortest path to each node. EIGRP Enhanced Interior 
Gateway Routing Protocol) is Cisco's proprietary routing protocol based on Diffusing Update Algorithm. EIGRP has the fastest router 
convergence among the three protocols. In this research paper we are going to study the effect of BW, Delay, communication mode and 
configuration scenario and also analyze the performance of IGP based RIP,OSPF and EIGRP routing protocol using CISCO 
proprietary simulator tool CISCO packet tracer 7.3.1 with dynamic BW.

# Keyword 
IGP routing protocol, RIPv2, OSPF, EIGRP, IPv4, CISCO packet tracer,Dynamic routing Protocal.

#Introduction
Routing protocols are based on routing algorithms, which
rely on various metrics to find the best path to transmit data
across networks. Metrics include cost, bandwidth, maximum
transmission unit (MTU), packet delay, and hop count.
Routing protocols utilize a routing table to store the results of
these metrics. Based whether the routing is within an
Autonomous System (AS) or between ASs, there are two
types of routing protocols: Interior Gateway Protocols (IGP)
and Exterior Gateway Protocol (EGP). RIP, EIGRP, and
OSPF are three commonly used IGPs. A typical EGP is the
Border Gateway Protocol (BGP).
Routing is the process of selecting paths in a network. In
packet switching networks, routing directs traffic forwarding
of logically addressed packets through intermediate nodes
from their source to their ultimate destination. Routing
protocols are designed to select and determine the best path
to each router in the network. Routers should learn the next
hop to send the packets. Forwarding data should be efficient
and effective. Consequently, the routing decision of a
protocol is very important for network performance.
Among many routing protocols, RIP, EIGRP, and OSPF
have been most widely used. In this paper, we use Packet
tracer Modeler to simulate performance of the RIP, EIGRP,
and OSPF TCP/IP Internet routing protocols and compare
about configuration scenario, Bandwidth effect MTU,HOPs,
Administrative distance and metrics Value etc.
In this paper, we compare performance of RIP, EIGRP, and
OSPF using Packet tracer simulator 7.3.1.