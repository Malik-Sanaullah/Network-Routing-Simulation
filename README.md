# Network-Routing-Simulation
Simulate a large-scale internet router network where link weights (latency) change dynamically in real-time. Multiple threads continuously execute a modified Dijkstra’s or A* algorithm to update routing tables, while other threads concurrently update edge weights without deadlocking the entire network graph.
