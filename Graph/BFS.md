# Breadth First Search


 It uses Queue Data Structure.
 
 ## Algorithm :
 
 
     1. Push the Source Node in the Queue.
     2. Whenever a Node is pushed in a Queue, mark it as visited with the help of an Marked Array.
     3. Repeat 4 and 5 while Queue is not Empty.
     4. Pop the Front node from the Queue after RESERVING it in a particular variable.
     5. Traverse all its(Reserved Node) adjacent Unvisited node and push to the Queue, keeping in mind Step 2.



### We can determine the Parents and Level of each node conditional to the Source Node :

      i. Parent of Adjacent Node = Reserved Node.
     ii. Level of an Adjacent Node = Reserved Node's Level + 1. Lavel of Source Node is always = 0.
