# Bee-bots-3.0

**About:**
A swarm robotics project that aims to explore swarm intelligence and coordination using biologically-inspired algorithms. The idea is to simulate shape recovery behaviour in a swarm after obstacle interaction. The implementation is divided into:

1. Shape Formation: The bots form the input shape in a decentralised way. 

2. Formation Control: After forming the shape, the robots reach a destination while maintaining the shape and navigating through obstacles. Depending on the relative size of the obstacle in comparison with the swarm, the obstacle is either completely avoided while keeping the shape intact or a part of the formation is broken and reformed later to move past the obstacle.

* Obstacle Avoidance: The wall-following algorithm is used to avoid obstacles that are comparable in size with the formation. The formation, as a whole, avoids obstacles. 
* Disturbance and Reformation: When the obstacle is small, a part of the shape is broken and only the bots directly affected by the obstacle avoid it. After being distorted, these bots then follow a control law to rejoin the shape and maintain it until the destination is reached.    

Additionally, performance of different shapes against parameters like average distortion in shape, time taken to reach the final coordinates, etc. can be studied to find the optimal shape which can find application in search and rescue operations.
 
**Phase 1: (Ideation)**
 * Go through existing research areas and explore swarm behaviours to arrive at a novel research statement
 * Familiarisation with ARGoS and Buzz

**Phase 2: (Simulation)**
 Simulate the swarm behaviour on Argos

**Phase 3:(Hardware implementation)**
 Implement the algorithm on hardware 

**The Team:**
* Karthik S [https://github.com/karthiks1701]
* Aditya R  [https://github.com/adityaravichander]
* Akshaya C S [https://github.com/AkshayaCSubramanian]
* Visweswaran B [https://github.com/Vichu-31101]
* PM Venkata Nagarjun [https://github.com/Arjun191]

