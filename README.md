### A* Pathfinding 
 - Using pyton and multipul data structures like pygame and PriorityQueue I built this system.
 - First step was caluctlating the path the program would use. With the basic F (total cost of trip), G (distace from start node), and H (Estimated distance... Guess distance) values. This was achievable. 
 - Next was esablishing the relationship between currnet node, and those next to it. The current node would look at its neighbors in a plus formation and see which node had the lowest value to move towards(Whichever consumed the least gas). 
 - Insted of using the treditional Manhattan distance I decided to use Euclidean distance which can move diagonally with more ease
MANHATTAN:
![Screenshot 2023-02-15 at 2 25 36 PM](https://user-images.githubusercontent.com/122250064/219146183-67e8aae3-0a76-4ce8-a0a9-cc9a00bb2011.png)


      EUCLIDEAN:
![Screenshot 2023-02-15 at 2 25 51 PM](https://user-images.githubusercontent.com/122250064/219146195-b8676592-43d3-45f7-909a-1a8874ee392a.png)

- Then setting up setting up an algorithm that will exacute the code. Until it finds the end node, using all previuos knoledge of neighbors and lest cost to move.
- once the pathfinder finds the final note. It will count backwards to see who had the most cost effective path, carting the most cost efficant path. 


https://user-images.githubusercontent.com/122250064/219143200-c0c93bbe-1224-48fa-af12-d7af6f30768a.mov

