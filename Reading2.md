# CECS 327 Reading Assignment 2: Architectures
# Tyler Huynh

1. A three-tiered client-server architecture is one where the application server actually needs to access a database server through a series of queries before being able to respond to the requesting client.
2. Vertical distribution involves separating different layers or types of tasks within a single system while horizontal distribution entails replicating or distributing the same type of tasks across multiple independent systems to handle scalability and load balancing.
3. A solution could be the use of CDNs to cache content closer to the client and reducing the data it needs to travel.
4. The problem with this organization is that when taking a look at a request-reply performance at process $P_{1}$ there is an overall increase in response time since $P_{1}$ is directly influenced by the time it takes to process each $P_{i}$.
5. One important disadvantage of routing messages in a structured overlay network according to its topology is the rigidity, which can make it challenging to adapt to dynamic changes in network conditions.
6. The probability that they are also neighbors would be 2c / n-1.
7. 
	1. Normal nodes should have low-latency access to super peers.
	2. Super peers should be evenly distributed across the overlay network.
	3. There should be a predefined portion of super peers relative to the total number of nodes in the overlay network.
	4. Each super peer should not need to serve more than a fixed number of normal nodes
8. An example of a self-managing system where the analysis component is completely distributed or even hidden could be a home automation system like the google nest thermostat or phillips hue light bulbs.
9. The maximum download capacity of the BitTorrent client is $B_{out}$ since the download speed is capped by the upload bandwidth.
10. An example of feedback control systems in cars are antilock braking systems to prevent the wheel from locking up during braking.