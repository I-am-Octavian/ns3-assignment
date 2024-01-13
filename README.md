## Problem Statement

Create N number of nodes and set them in a topology. Create a remote
host and place it such that it aligns symmetrically with all nodes. Establish
Uplink TCP communication between remote host and all other nodes.
Nodes will be sending data to the remote host. Set the positions of nodes
using the `MobilityHelper` Class. Simulate the whole scenario for 50
seconds. Implement this for `TcpNewReno` and `TcpCubic` and generate
Log Files. Log files should contain the data of congestion window,
throughput etc.,
1. Trace Congestion Window of each node and plot them using gnuplot
or any other tool.
2. Use `FlowMonitor` to show the stats like Tx Packets, Tx Bytes, Rx
Packets, Rx Bytes, Throughput, Delay, Packet Loss Rate.
3. Trace the Instantaneous Throughput of each node and plot them
4. Discuss on throughput of each node, if the throughput varies why?
5. Implement this setup for different RTT’s and observe how
TcpNewReno and TcpCubic performs
6. Write your observations and differentiate between TcpNewReno and
TcpCubic
