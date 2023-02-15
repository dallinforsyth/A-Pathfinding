# A* Pathfinding 
 - built in python using the pygame and PriorityQueue modules
 - The first step was calculating the path the program would use, with the basic F (total cost of the trip), G (distance from the start node), and H (estimated distance of the total trip to the end node) values. This was achievable.
- Next was establishing the relationship between the current node and those next to it. The current node would look at its neighbors in a plus formation and see which node had the lowest cost value. Once determined which path would cost the least, that is the way it moves.
- The two distance metrics in machine learning that I considered were the Manhattan and Euclidean. Manhattan distance did not work well with diagonal lines, therefore the obvious choice for me was Euclidean distance.

> EUCLIDEAN:
<img src="https://user-images.githubusercontent.com/122250064/219146195-b8676592-43d3-45f7-909a-1a8874ee392a.png" width="500" height="500">


- Then setting up an algorithm that will execute the code until it finds the end node, using all previous knowledge of neighbors and least cost to move.
- Once the pathfinder finds the final node, it will count backwards to see who had the most cost-effective path, charting the most cost-efficient path.



https://user-images.githubusercontent.com/122250064/219143200-c0c93bbe-1224-48fa-af12-d7af6f30768a.mov

## Running the program
- Once you have cloned this feel free to open in your choice of code editor app
- Run it in your code editor app
- Your first right click will always place the start node, second will place your end node, finally it will place your barriers. 
- If at anypoint you would like to remove a node placed. Use your left click, and you may place it again with a right click.
- Then if you are satisfied with your placements, press spacebar to run the program.
- To reset the program, you may press C to clear and do this all over again
