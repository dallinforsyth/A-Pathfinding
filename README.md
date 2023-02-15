# A* Pathfinding 
 - This was built with python aswell as pygame & PriorityQueue
 - The first step was calculating the path the program would use, with the basic F (total cost of the trip), G (distance from the start node), and H (estimated distance of the total trip to the end node) values. This was achievable.
- Next was establishing the relationship between the current node and those next to it. The current node would look at its neighbors in a plus formation and see which node had the lowest cost value. Once determined which path would cost the least, that is the way it moves.
- The two distance metrics in machine learning that I considered were the Manhattan and Euclidean. Manhattan distance did not work well with diagonal lines, therefore the obvious choice for me was Euclidean distance.

> MANHATTAN:
<img src="https://user-images.githubusercontent.com/122250064/219146183-67e8aae3-0a76-4ce8-a0a9-cc9a00bb2011.png" width="500" height="500">


> EUCLIDEAN:
<img src="https://user-images.githubusercontent.com/122250064/219146195-b8676592-43d3-45f7-909a-1a8874ee392a.png" width="500" height="500">


- Then setting up an algorithm that will execute the code until it finds the end node, using all previous knowledge of neighbors and least cost to move.
- Once the pathfinder finds the final node, it will count backwards to see who had the most cost-effective path, charting the most cost-efficient path.



https://user-images.githubusercontent.com/122250064/219143200-c0c93bbe-1224-48fa-af12-d7af6f30768a.mov

