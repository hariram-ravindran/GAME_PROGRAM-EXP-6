# GAME_PROGRAM-EXP-6
## Implement the AI random movement.

## Name : Hari Ram R
## Reg No : 212224240050


# Aim:
Implement the AI random movement.

# Algorithm:
Step:01 Create a Character Blueprint.

Step:02 Create a Blackboard.

Step:03 Open the Behavior Tree editor.

Step:04 Create Behavior Tree nodes for the following,
 "Selector" node: Controls the execution of child nodes.
 "Service" node: Monitors and updates values in the Blackboard.
 "Sequence" node: Executes child nodes in sequential order.
 "Random" decorator: Randomly selects a child node to execute.
 "Move To" task: Moves the AI character to a specified location.

Step:05 Set up the Blackboard with vector key and bool keys and save it.

Step:06 Set up the AI character Blueprint with the help of AI controller component.

Step:07 Set the AI controller and behavior treeiIn the Possess node, select the AI Character Blueprint you created and drag off the AICharacter reference and search for “Use Blackboard”

Step:08 Set up the NavMesh and boundaries, we can adjust the size and position to cover the desired play area.
 
# Output:

![Screenshot 2025-05-15 133109](https://github.com/user-attachments/assets/8cc1b432-1809-4fb2-b82c-842d16b2f651)


![image](https://github.com/user-attachments/assets/aac9fada-353e-4369-a7a1-8037059117b9)



![image](https://github.com/user-attachments/assets/0017652a-93f4-4168-b375-6389bb48b189)

# Result:
Thus, the AI concept to the actor for a random movement is implemented.
